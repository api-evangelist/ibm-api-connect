# IBM API Connect (ibm-api-connect)

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

IBM API Connect is a comprehensive end-to-end API management solution that enables organizations to create, secure, manage, share, monetize, and analyze APIs across clouds. It provides an API gateway, developer portal, and lifecycle management capabilities.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ibm-api-connect/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - API Management, API Gateway, Developer Portal, IBM

## Timestamps

- **Created:** 2026-03-16 
- **Modified:** 2026-10-10 

## APIs

### IBM API Connect Platform - Cloud Management API
Cloud-scoped operations for managing the IBM API Connect cloud configuration: user registries, provider organizations, availability zones, registered clients and cloud settings. Calls require a bearer token issued to a member of the admin organization. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{platform-api-endpoint}/api`


#### Tags:

 - Administration, API Management, Cloud, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

### IBM API Connect Platform - Provider API
Provider-organization operations covering the API lifecycle: draft APIs and products, catalogs, spaces, staging and publishing, consumer organizations, apps and subscriptions. Formerly listed here as the Management API. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{platform-api-endpoint}/api`


#### Tags:

 - Administration, API Management, Lifecycle, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

### IBM API Connect Platform - Consumer API
Consumer-organization operations used by application developers: profile, apps, credentials and subscriptions to published products. Calls require the X-IBM-Consumer-Context header naming the provider organization and catalog. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{consumer-api-endpoint}/consumer-api`


#### Tags:

 - Consumer, Developer Portal, REST API, Subscription

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

### IBM API Connect Analytics API
Retrieves API event data stored in API Connect Analytics, dashboard data, and the filter parameters supported at cloud, provider organization, catalog and space scope. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{platform-api-endpoint}/analytics`


#### Tags:

 - Analytics, API Management, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=ui-analytics-rest-api)

### IBM API Connect Consumer Analytics API
Returns consumer-organization and per-app analytics dashboard data for application developers. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{consumer-api-endpoint}/consumer-analytics`


#### Tags:

 - Analytics, Consumer, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=ui-analytics-rest-api)

### IBM API Connect Engagement API
Manages engagement configuration and rules evaluated against API Connect Analytics data for a provider organization. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)


#### Tags:

 - Analytics, Alerting, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

### API Connect Portal Admin API
Administers the content of a catalog's developer portal: the APIs, products and related content it exposes. OpenAPI 3.0, version 1.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)


#### Tags:

 - Administration, Developer Portal, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

### IBM API Connect Discovery API
Processes API call records collected from gateways and proxies to discover APIs that are not yet managed in API Connect. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{discovery-endpoint}/discovery`


#### Tags:

 - API Discovery, Governance, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

### IBM API Connect Governance API
Validates API definitions against governance rulesets at cloud and provider organization scope. OpenAPI 3.0, version 2.0.0.

**Human URL:** [https://apic-api.apiconnect.ibmcloud.com/v12/](https://apic-api.apiconnect.ibmcloud.com/v12/)

**Base URL:** `https://{governance-endpoint}/governance`


#### Tags:

 - Governance, Linting, REST API

#### Properties

- [Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Documentation](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=cli-managing-platform-rest-api-keys)

## Common Properties

- [Website](https://www.ibm.com/products/api-connect)
- [Documentation](https://www.ibm.com/docs/en/api-connect/)
- [Getting Started](https://www.ibm.com/docs/en/api-connect/cloud/12.1.1_saas?topic=overview-getting-started)
- [API Reference](https://apic-api.apiconnect.ibmcloud.com/v12/)
- [Authentication](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=reference-api-connect-rest-apis)
- [Support](https://www.ibm.com/mysupport)
- [Pricing](https://www.ibm.com/products/api-connect/pricing)
- [Blog](https://developer.ibm.com/blogs/)
- [Change Log](https://www.ibm.com/docs/en/api-connect/cloud/12.1.1_saas?topic=aceaso-whats-new-in-api-connect-enterprise-as-service)
- [GitHub Organization](https://github.com/ibm-apiconnect)
- [Community](https://community.ibm.com/community/user/integration/communities/community-home?CommunityKey=2106cca0-a9f9-45c6-9b28-01a28f39ce47)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/ibm-api-connect)
- [YouTube](https://www.youtube.com/@IBMTechnology)
- [Terms of Service](https://www.ibm.com/support/customer/csol/terms/)
- [Privacy Policy](https://www.ibm.com/privacy)
- [Status](https://cloud.ibm.com/status)
- [Rules](rules/ibm-api-connect-rules.yml)
- [MCP Server](https://github.com/ibm-apiconnect/apic-mcp-server)
- [API Connect Flow Pilot (agent skills and MCP servers)](https://www.ibm.com/docs/en/api-connect/software/12.1.1?topic=studio-api-connect-flow-pilot-api-development)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
