# Koyeb

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Koyeb is a developer-friendly serverless platform for deploying applications, Postgres databases, GPU workloads and isolated code-execution sandboxes across a global edge network. The Koyeb REST API is a Swagger 2.0 contract generated from protobuf services by grpc-gateway — 126 paths, 177 operations and 422 schemas, all under /v1 on https://app.koyeb.com — covering apps, services, deployments, regional deployments, instances, secrets, volumes, snapshots, domains, organizations, quotas, budgets and usage. Authentication is a single organization-wide bearer token with no scopes; the platform is also driven by a first-party Go CLI, JavaScript/Python/Go SDKs, Terraform and Pulumi providers, an MCP server, and sixteen published Agent Skills. Koyeb entered into a definitive agreement with Mistral AI in February 2026.

**Areas:** Cloud Platform · Deployment · Platform-as-a-Service · Serverless · Serverless GPU · AI Infrastructure · Containers · Developer Tools · Compute · Hosting · PostgreSQL · Sandbox

## Koyeb on APIs.io

Everything profiled for Koyeb is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/koyeb/](https://apis.io/providers/koyeb/)** — or go straight to one of the APIs or properties below.

### APIs (44)

- [Koyeb Activity API](https://apis.io/apis/koyeb/koyeb-activity-api/) — The activity API from Koyeb — 3 operation(s) for activity.
- [Koyeb Apps API](https://apis.io/apis/koyeb/koyeb-apps-api/) — The Apps API from Koyeb — 5 operation(s) for apps.
- [Koyeb Archives API](https://apis.io/apis/koyeb/koyeb-archives-api/) — The Archives API from Koyeb — 1 operation(s) for archives.
- [Koyeb Billing API](https://apis.io/apis/koyeb/koyeb-billing-api/) — The billing API from Koyeb — 3 operation(s) for billing.
- [Koyeb CatalogDatacenters API](https://apis.io/apis/koyeb/koyeb-catalogdatacenters-api/) — The CatalogDatacenters API from Koyeb — 1 operation(s) for catalogdatacenters.
- [Koyeb CatalogInstances API](https://apis.io/apis/koyeb/koyeb-cataloginstances-api/) — The CatalogInstances API from Koyeb — 2 operation(s) for cataloginstances.
- [Koyeb CatalogInstanceUsage API](https://apis.io/apis/koyeb/koyeb-cataloginstanceusage-api/) — The CatalogInstanceUsage API from Koyeb — 1 operation(s) for cataloginstanceusage.
- [Koyeb CatalogRegions API](https://apis.io/apis/koyeb/koyeb-catalogregions-api/) — The CatalogRegions API from Koyeb — 2 operation(s) for catalogregions.
- [Koyeb Compose API](https://apis.io/apis/koyeb/koyeb-compose-api/) — The Compose API from Koyeb — 1 operation(s) for compose.
- [Koyeb Coupons API](https://apis.io/apis/koyeb/koyeb-coupons-api/) — The Coupons API from Koyeb — 1 operation(s) for coupons.
- [Koyeb Credentials API](https://apis.io/apis/koyeb/koyeb-credentials-api/) — The Credentials API from Koyeb — 2 operation(s) for credentials.
- [Koyeb Deployments API](https://apis.io/apis/koyeb/koyeb-deployments-api/) — The Deployments API from Koyeb — 5 operation(s) for deployments.
- [Koyeb DockerHelper API](https://apis.io/apis/koyeb/koyeb-dockerhelper-api/) — The DockerHelper API from Koyeb — 1 operation(s) for dockerhelper.
- [Koyeb Domains API](https://apis.io/apis/koyeb/koyeb-domains-api/) — The Domains API from Koyeb — 3 operation(s) for domains.
- [Koyeb Instances API](https://apis.io/apis/koyeb/koyeb-instances-api/) — The Instances API from Koyeb — 4 operation(s) for instances.
- [Koyeb Intercom API](https://apis.io/apis/koyeb/koyeb-intercom-api/) — The Intercom API from Koyeb — 1 operation(s) for intercom.
- [Koyeb Invite API](https://apis.io/apis/koyeb/koyeb-invite-api/) — The invite API from Koyeb — 1 operation(s) for invite.
- [Koyeb Logs API](https://apis.io/apis/koyeb/koyeb-logs-api/) — The Logs API from Koyeb — 2 operation(s) for logs.
- [Koyeb Metrics API](https://apis.io/apis/koyeb/koyeb-metrics-api/) — The Metrics API from Koyeb — 1 operation(s) for metrics.
- [Koyeb Organization API](https://apis.io/apis/koyeb/koyeb-organization-api/) — The organization API from Koyeb — 12 operation(s) for organization.
- [Koyeb OrganizationConfirmations API](https://apis.io/apis/koyeb/koyeb-organizationconfirmations-api/) — The OrganizationConfirmations API from Koyeb — 1 operation(s) for organizationconfirmations.
- [Koyeb PersistentVolumes API](https://apis.io/apis/koyeb/koyeb-persistentvolumes-api/) — The PersistentVolumes API from Koyeb — 3 operation(s) for persistentvolumes.
- [Koyeb Profile API](https://apis.io/apis/koyeb/koyeb-profile-api/) — The Profile API from Koyeb — 17 operation(s) for profile.
- [Koyeb Projects API](https://apis.io/apis/koyeb/koyeb-projects-api/) — The Projects API from Koyeb — 2 operation(s) for projects.
- [Koyeb Provisioning API](https://apis.io/apis/koyeb/koyeb-provisioning-api/) — The Provisioning API from Koyeb — 2 operation(s) for provisioning.
- [Koyeb Quotas API](https://apis.io/apis/koyeb/koyeb-quotas-api/) — The Quotas API from Koyeb — 1 operation(s) for quotas.
- [Koyeb RegionalDeployments API](https://apis.io/apis/koyeb/koyeb-regionaldeployments-api/) — The RegionalDeployments API from Koyeb — 3 operation(s) for regionaldeployments.
- [Koyeb Repositories API](https://apis.io/apis/koyeb/koyeb-repositories-api/) — The Repositories API from Koyeb — 3 operation(s) for repositories.
- [Koyeb Search API](https://apis.io/apis/koyeb/koyeb-search-api/) — The Search API from Koyeb — 1 operation(s) for search.
- [Koyeb Secrets API](https://apis.io/apis/koyeb/koyeb-secrets-api/) — The Secrets API from Koyeb — 3 operation(s) for secrets.
- [Koyeb Services API](https://apis.io/apis/koyeb/koyeb-services-api/) — The Services API from Koyeb — 8 operation(s) for services.
- [Koyeb Sessions API](https://apis.io/apis/koyeb/koyeb-sessions-api/) — The Sessions API from Koyeb — 4 operation(s) for sessions.
- [Koyeb Snapshots API](https://apis.io/apis/koyeb/koyeb-snapshots-api/) — The Snapshots API from Koyeb — 2 operation(s) for snapshots.
- [Koyeb SSO API](https://apis.io/apis/koyeb/koyeb-sso-api/) — The sso API from Koyeb — 2 operation(s) for sso.
- [Koyeb Subscriptions API](https://apis.io/apis/koyeb/koyeb-subscriptions-api/) — The Subscriptions API from Koyeb — 1 operation(s) for subscriptions.
- [Koyeb Summary API](https://apis.io/apis/koyeb/koyeb-summary-api/) — The Summary API from Koyeb — 1 operation(s) for summary.
- [Koyeb Usages API](https://apis.io/apis/koyeb/koyeb-usages-api/) — The Usages API from Koyeb — 2 operation(s) for usages.
- [Koyeb Users API](https://apis.io/apis/koyeb/koyeb-users-api/) — The Users API from Koyeb — 2 operation(s) for users.
- [Koyeb Instance Snapshots API](https://apis.io/apis/koyeb/koyeb-instancesnapshots-api/) — The InstanceSnapshots API from Koyeb — 3 operation(s) for instancesnapshots.
- [Koyeb Test API](https://apis.io/apis/koyeb/koyeb-test-api/) — The Test API from Koyeb — 2 operation(s) for test.
- [Koyeb Organization Invitations API](https://apis.io/apis/koyeb/koyeb-organization-invitations-api/) — The Organization Invitations API from Koyeb — 3 operation(s) for organization invitations.
- [Koyeb Organization Members API](https://apis.io/apis/koyeb/koyeb-organization-members-api/) — The Organization Members API from Koyeb — 2 operation(s) for organization members.
- [Koyeb Organization Quotas API](https://apis.io/apis/koyeb/koyeb-organization-quotas-api/) — The Organization Quotas API from Koyeb — 1 operation(s) for organization quotas.
- [Koyeb Payment Methods API](https://apis.io/apis/koyeb/koyeb-payment-methods-api/) — The Payment Methods API from Koyeb — 3 operation(s) for payment methods.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [koyebApi](https://apis.io/servers/koyeb/koyebapi/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Koyeb Agentic Access](https://apis.io/agentic-access/koyeb/koyeb-agentic-access/)

#### Collections (43)

Postman and Open Collection request collections.

- [Koyeb Rest API](https://apis.io/collections/koyeb/open-koyeb/)
- [Koyeb Rest activity API](https://apis.io/collections/koyeb/open-koyeb-activity-api/)
- [Koyeb Rest activity Apps API](https://apis.io/collections/koyeb/open-koyeb-apps-api/)
- [Koyeb Rest activity Archives API](https://apis.io/collections/koyeb/open-koyeb-archives-api/)
- [Koyeb Rest activity billing API](https://apis.io/collections/koyeb/open-koyeb-billing-api/)
- [Koyeb Rest activity CatalogDatacenters API](https://apis.io/collections/koyeb/open-koyeb-catalogdatacenters-api/)
- [Koyeb Rest activity CatalogInstances API](https://apis.io/collections/koyeb/open-koyeb-cataloginstances-api/)
- [Koyeb Rest activity CatalogInstanceUsage API](https://apis.io/collections/koyeb/open-koyeb-cataloginstanceusage-api/)
- [Koyeb Rest activity CatalogRegions API](https://apis.io/collections/koyeb/open-koyeb-catalogregions-api/)
- [Koyeb Rest activity Compose API](https://apis.io/collections/koyeb/open-koyeb-compose-api/)
- [Koyeb Rest activity Coupons API](https://apis.io/collections/koyeb/open-koyeb-coupons-api/)
- [Koyeb Rest activity Credentials API](https://apis.io/collections/koyeb/open-koyeb-credentials-api/)
- [Koyeb Rest activity Deployments API](https://apis.io/collections/koyeb/open-koyeb-deployments-api/)
- [Koyeb Rest activity DockerHelper API](https://apis.io/collections/koyeb/open-koyeb-dockerhelper-api/)
- [Koyeb Rest activity Domains API](https://apis.io/collections/koyeb/open-koyeb-domains-api/)
- [Koyeb Rest activity Instances API](https://apis.io/collections/koyeb/open-koyeb-instances-api/)
- [Koyeb Rest activity Intercom API](https://apis.io/collections/koyeb/open-koyeb-intercom-api/)
- [Koyeb Rest activity invite API](https://apis.io/collections/koyeb/open-koyeb-invite-api/)
- [Koyeb Rest activity Logs API](https://apis.io/collections/koyeb/open-koyeb-logs-api/)
- [Koyeb Rest activity Metrics API](https://apis.io/collections/koyeb/open-koyeb-metrics-api/)
- [Koyeb Rest activity organization API](https://apis.io/collections/koyeb/open-koyeb-organization-api/)
- [Koyeb Rest activity OrganizationConfirmations API](https://apis.io/collections/koyeb/open-koyeb-organizationconfirmations-api/)
- [Koyeb Rest activity OrganizationInvitations API](https://apis.io/collections/koyeb/open-koyeb-organizationinvitations-api/)
- [Koyeb Rest activity OrganizationMembers API](https://apis.io/collections/koyeb/open-koyeb-organizationmembers-api/)
- [Koyeb Rest activity OrganizationQuotas API](https://apis.io/collections/koyeb/open-koyeb-organizationquotas-api/)
- …and 18 more published on APIs.io

#### Overlays (42)

OpenAPI overlays, including conversational phrasing for each operation.

- [Koyeb Activity Api Overlay](https://apis.io/overlays/koyeb/koyeb-activity-api-overlay/)
- [Koyeb Apps Api Overlay](https://apis.io/overlays/koyeb/koyeb-apps-api-overlay/)
- [Koyeb Archives Api Overlay](https://apis.io/overlays/koyeb/koyeb-archives-api-overlay/)
- [Koyeb Billing Api Overlay](https://apis.io/overlays/koyeb/koyeb-billing-api-overlay/)
- [Koyeb Catalogdatacenters Api Overlay](https://apis.io/overlays/koyeb/koyeb-catalogdatacenters-api-overlay/)
- [Koyeb Cataloginstances Api Overlay](https://apis.io/overlays/koyeb/koyeb-cataloginstances-api-overlay/)
- [Koyeb Cataloginstanceusage Api Overlay](https://apis.io/overlays/koyeb/koyeb-cataloginstanceusage-api-overlay/)
- [Koyeb Catalogregions Api Overlay](https://apis.io/overlays/koyeb/koyeb-catalogregions-api-overlay/)
- [Koyeb Compose Api Overlay](https://apis.io/overlays/koyeb/koyeb-compose-api-overlay/)
- [Koyeb Coupons Api Overlay](https://apis.io/overlays/koyeb/koyeb-coupons-api-overlay/)
- [Koyeb Credentials Api Overlay](https://apis.io/overlays/koyeb/koyeb-credentials-api-overlay/)
- [Koyeb Deployments Api Overlay](https://apis.io/overlays/koyeb/koyeb-deployments-api-overlay/)
- [Koyeb Dockerhelper Api Overlay](https://apis.io/overlays/koyeb/koyeb-dockerhelper-api-overlay/)
- [Koyeb Domains Api Overlay](https://apis.io/overlays/koyeb/koyeb-domains-api-overlay/)
- [Koyeb Instances Api Overlay](https://apis.io/overlays/koyeb/koyeb-instances-api-overlay/)
- [Koyeb Intercom Api Overlay](https://apis.io/overlays/koyeb/koyeb-intercom-api-overlay/)
- [Koyeb Invite Api Overlay](https://apis.io/overlays/koyeb/koyeb-invite-api-overlay/)
- [Koyeb Logs Api Overlay](https://apis.io/overlays/koyeb/koyeb-logs-api-overlay/)
- [Koyeb Metrics Api Overlay](https://apis.io/overlays/koyeb/koyeb-metrics-api-overlay/)
- [Koyeb Organization Api Overlay](https://apis.io/overlays/koyeb/koyeb-organization-api-overlay/)
- [Koyeb Organizationconfirmations Api Overlay](https://apis.io/overlays/koyeb/koyeb-organizationconfirmations-api-overlay/)
- [Koyeb Organizationinvitations Api Overlay](https://apis.io/overlays/koyeb/koyeb-organizationinvitations-api-overlay/)
- [Koyeb Organizationmembers Api Overlay](https://apis.io/overlays/koyeb/koyeb-organizationmembers-api-overlay/)
- [Koyeb Organizationquotas Api Overlay](https://apis.io/overlays/koyeb/koyeb-organizationquotas-api-overlay/)
- [Koyeb Paymentmethods Api Overlay](https://apis.io/overlays/koyeb/koyeb-paymentmethods-api-overlay/)
- …and 17 more published on APIs.io

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Koyeb Authentication](https://apis.io/security/koyeb/koyeb-authentication/)
- [Koyeb Domain Security](https://apis.io/security/koyeb/koyeb-domain-security/)
- [Koyeb Trust Center](https://apis.io/security/koyeb/koyeb-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Koyeb Plans Pricing](https://apis.io/plans/koyeb/koyeb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Koyeb Rate Limits](https://apis.io/rate-limits/koyeb/koyeb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Koyeb Finops](https://apis.io/finops/koyeb/koyeb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.koyeb.com)
- [Documentation](https://www.koyeb.com/docs)
- [Getting started](https://www.koyeb.com/docs/deploy)
- [API reference](https://www.koyeb.com/docs/reference/api)
- [Pricing](https://www.koyeb.com/pricing)
- [Sign up](https://app.koyeb.com/auth/signup)
- [Support](https://slack.koyeb.com/)
- [Blog](https://www.koyeb.com/feed.xml)
- [Compliance](https://trust.koyeb.com/)
- [Terms of service](https://www.koyeb.com/docs/legal/terms)
- [GitHub](https://github.com/koyeb)
- [Status](https://status.koyeb.com/)

## API Evangelist rating

**Kin Score 62.0** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 47.0 |
| Contract governance | 18.2 |
| Operational transparency | 52.6 |
| Developer ergonomics | 81.0 |
| Access clarity | 67.1 |

**Agent readiness 42.0** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | mostly |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/koyeb/](https://apis.io/providers/koyeb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Koyeb: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/koyeb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
