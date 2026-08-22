# Copper (copper)

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

Copper is a CRM platform built natively for Google Workspace, designed to help teams cultivate enduring client relationships through purposeful collaboration. Copper offers a RESTful Developer API providing programmatic access to People, Companies, Leads, Opportunities, Projects, Tasks, Activities, Webhooks, and related resources for CRM integration and automation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Activities
- Companies
- Contact Relationship Management
- Contacts
- CRM
- Customer Relationship Management
- Google Workspace
- Leads
- Opportunities
- People
- Projects
- Sales
- Tasks

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-30

## APIs

### Copper Developer API

The Copper Developer API is a RESTful JSON API providing programmatic access to Copper CRM resources including people, companies, leads, opportunities, projects, tasks, activities, and webhooks. The API uses token-based authentication with three required headers (X-PW-AccessToken, X-PW-Application, X-PW-UserEmail) and supports full CRUD operations, search, bulk actions, and lead conversion. Rate limits are 180 requests per minute and 3 requests per second for bulk operations.

- **Human URL:** [https://developer.copper.com/](https://developer.copper.com/)
- **Base URL:** `https://api.copper.com/developer_api/v1`

#### Tags

- Activities
- Companies
- CRM
- Leads
- Opportunities
- People
- Projects
- REST
- Tasks
- Webhooks

#### Properties

- [Documentation](https://developer.copper.com/)
- [Authentication](https://developer.copper.com/introduction/requests.html)
- [Getting Started](https://developer.copper.com/introduction/quick-start.html)
- [O Auth](https://developer.copper.com/introduction/oauth-quickstart.html)
- [Webhooks](https://developer.copper.com/webhooks/general/list-of-webhook-events.html)
- [Postman Collection](https://developer.copper.com/introduction/postman-collection.html) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [People](https://developer.copper.com/people/)
- [Companies](https://developer.copper.com/companies/)
- [Leads](https://developer.copper.com/leads/)
- [Opportunities](https://developer.copper.com/opportunities/)
- [Projects](https://developer.copper.com/projects/)
- [Tasks](https://developer.copper.com/tasks/)
- [Activities](https://developer.copper.com/activities/)
- [Custom Fields](https://developer.copper.com/custom-fields/)
- [Tags](https://developer.copper.com/tags/)
- [OpenAPI](openapi/copper-developer-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/copper-developer-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/copper-developer-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/copper-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Rules](rules/copper-developer-api-rules.yml)
- [JSON-LD](json-ld/copper-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/copper-vocabulary.yml)
- [Capabilities](capabilities/copper-developer-api-capabilities.yml)

## Common Properties

- [GitHub Organization](https://github.com/ProsperWorks)
- [Website](https://www.copper.com)
- [Developer Portal](https://developer.copper.com/)
- [Documentation](https://developer.copper.com/)
- [Authentication](https://developer.copper.com/introduction/requests.html)
- [Getting Started](https://developer.copper.com/introduction/quick-start.html)
- [Rate Limits](https://developer.copper.com/introduction/requests.html)
- [Errors](https://developer.copper.com/introduction/responses.html)
- [Pricing](https://www.copper.com/pricing)
- [Blog](https://www.copper.com/blog)
- [Privacy Policy](https://www.copper.com/privacy-policy)
- [Terms of Service](https://www.copper.com/terms-of-service)
- [Status Page](https://status.copper.com/)
- [Twitter](https://twitter.com/copperinc)
- [LinkedIn](https://www.linkedin.com/company/copperinc/)
- [YouTube](https://www.youtube.com/c/CopperCRM)
- [Features](undefined)
- [Integrations](https://www.copper.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
