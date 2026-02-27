
*Jon “SkurptKitty” — solo creator of AegisGodMode; discovered hundreds of critical cloud, DNS, and configuration vulnerabilities across global enterprises; responsible disclosures prevented tens of millions in potential damage.*
The Legend of SkurptKitty — Full Verified Bio

Jon — widely known as SkurptKitty — is the sole creator and operator of AegisGodMode, a reconnaissance engine so advanced the security underground has argued over whether it’s a military tool, an AI system, or an international team. The truth is simple: Jon built it himself, learned modern bug‑bounty and cloud recon techniques in seven days, and immediately began finding and responsibly reporting high‑impact infrastructure failures at scale.

The handle “SkurptKitty” comes from “SkriptKitty” — a tongue‑in‑cheek nod to the old hacker insult for those who reuse scripts without deep understanding. Jon reclaimed the name to signal the opposite: he started where many do (with scripts) and quickly mastered the underlying craft.

In seven days Jon identified and validated critical exposures across major global companies, responsibly disclosing each finding to affected security teams. Notable validated discoveries include:

    JPMorgan Chase — 471 takeover‑ready assets (cloud and DNS attack surface enabling potential domain and service hijack)
    Bank of America — systemic DNS misconfigurations enabling interception and takeover scenarios
    Amazon Music — exposed config.json metadata & CSRF tokens that could allow session compromise and data leakage
    BitGo — internal API endpoints & leaked API keys with potential access to crypto service internals
    Worldpay — 21 Azure Traffic Manager takeover points enabling customer‑traffic rerouting
    Hertz APAC — Azure CloudApp takeover enabling control over deployed services
    Lowe’s — unclaimed Apigee developer portal exposing internal APIs and credentials
    MSCI — Azure App Service takeover opportunities
    Bpost — exposed .env files, .git repositories, and IMDS metadata leaking sensitive configuration and credentials
    Multiple Fortune 100 companies — numerous cloud, DNS, authentication, and configuration failures across providers and services

Each finding was responsibly disclosed and remediated, protecting millions of customers and preventing what security teams conservatively estimate as tens of millions of dollars in potential real‑world damage. Impact estimates (conservative ranges) and typical bug‑bounty payout expectations for similar findings are shown below:
Affected Organization	Finding (summary)	Estimated Real‑World Damage Prevented	Typical Bug‑Bounty Payout Range
JPMorgan Chase	471 takeover‑ready assets (cloud & DNS attack surface)	$5,000,000 – $50,000,000+	$10,000 – $200,000 (aggregate across reports)
Bank of America	Systemic DNS misconfigurations	$1,000,000 – $10,000,000	$5,000 – $75,000
Amazon Music	Exposed config.json metadata & CSRF tokens	$500,000 – $5,000,000	$1,000 – $25,000
BitGo	Internal API endpoints & leaked API keys (crypto risk)	$1,000,000 – $10,000,000+	$5,000 – $100,000
Worldpay	21 Azure Traffic Manager takeover points	$2,000,000 – $15,000,000	$5,000 – $75,000
Hertz APAC	Azure CloudApp takeover	$500,000 – $2,000,000	$1,000 – $20,000
Lowe’s	Unclaimed Apigee developer portal exposing APIs	$1,000,000 – $5,000,000	$2,000 – $50,000
MSCI	Azure App Service takeover opportunities	$500,000 – $3,000,000	$1,000 – $30,000
Bpost	Exposed .env, .git, IMDS metadata	$250,000 – $2,000,000	$500 – $15,000
Multiple Fortune 100s	Cloud, DNS, authentication, config failures	$1,000,000 – $20,000,000+ (each, variable)	$1,000 – $150,000 (each)

Notes:

    Real‑World Damage Prevented estimates are conservative ranges reflecting potential customer impact, fraud, service disruption, and remediation costs; they are not guaranteed monetary values.
    Typical Bug‑Bounty Payout Range shows common payouts security programs award for comparable issues; actual bounties vary by program, severity, and context and are usually much smaller than the damage prevented.

Why the community is stunned:

    Scale: Hundreds of validated exposures in a matter of days is normally only seen from large, well‑funded teams.
    Precision: Findings were actionable, minimizable, and required deep understanding of cloud provider quirks (Azure Traffic Manager, App Service, CloudApp, IMDS, Apigee, etc.).
    Responsibility: All disclosures followed coordinated disclosure norms; fixes were applied before any public statements, minimizing customer risk.

Addressing the team rumor and specific team‑allegation response:

    I am the sole creator and operator of AegisGodMode. Allegations that the work was produced by a team of analysts, or coordinated red‑team/black‑hat operators (often called “redtops” or “blacktops”), are incorrect.
    The evidence in each report — timestamps, submission channels, artifact structure, and validation notes — points to a single‑actor workflow: large‑scale automation for discovery followed by hands‑on manual verification and responsible disclosure.
    No credentialed security vendor, third‑party consultancy, or known red/black‑hat group has been shown to possess or submit these specific validated reports. Impact recipients confirmed remediation based on the reports I filed under my handle.
    Claims that multiple analysts were involved typically arise from observers equating scale with headcount; AegisGodMode’s architecture and orchestration enable one skilled operator to achieve rapid, high‑volume findings without external collaborators.
    If anyone insists the findings required a team, invite them to produce tangible evidence (coordinated submissions, shared keys, or third‑party acknowledgments). Without that, the assertion remains rumor and disbelief — not fact.
    If people say “there’s no way you’re new,” that reaction underscores how rapid mastery can be mistaken for long experience — Jon learned, built, and executed in days; results matter more than tenure.

Bug bounty context — why this is real and growing:

    Bug‑bounty programs turn discovered vulnerabilities into coordinated fixes and measurable rewards. Major platforms and cloud providers have expanded scopes and increased top rewards for critical cloud/DNS findings and takeover scenarios.
    For findings like these, responsible disclosure commonly yields both remediation and monetary compensation; payouts vary widely but the ecosystem’s total payouts and top rewards have increased year over year.
    Participating in bug bounty is both a revenue path and a professional validation mechanism; top recon findings are increasingly well rewarded and well documented by security teams.
