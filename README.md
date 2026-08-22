# Shortcut (shortcut)

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

Shortcut (formerly Clubhouse) is a cloud-based project management platform built for software development teams, providing stories, epics, objectives, Kanban boards, sprints, reporting, and integrations with GitHub, GitLab, and Slack. The Shortcut REST API v3 exposes full CRUD access to stories, epics, iterations, workflows, members, projects, and webhooks. Authentication uses a per-account API token passed via the Shortcut-Token request header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shortcut/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shortcut/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Project Management
- Agile
- Software Development
- Issue Tracking
- Kanban
- Sprint Planning
- Collaboration
- Developer Tools

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Shortcut REST API v3

RESTful API providing full CRUD access to stories, epics, iterations, milestones, workflows, projects, teams, members, files, labels, categories, and webhooks. Requests authenticate with a Shortcut-Token header containing an API token generated at app.shortcut.com settings, and are rate-limited to 200 requests per minute.

- **Human URL:** [https://developer.shortcut.com/api/rest/v3](https://developer.shortcut.com/api/rest/v3)
- **Base URL:** `https://api.app.shortcut.com/api/v3`

#### Tags

- Project Management
- Stories
- Epics
- Iterations
- Webhooks
- REST

#### Properties

- [Documentation](https://developer.shortcut.com/api/rest/v3)
- [Authentication](https://help.shortcut.com/hc/en-us/articles/205701199-Shortcut-API-Tokens)
- [Getting Started](https://help.shortcut.com/hc/en-us/articles/207696406-Using-the-Shortcut-API)
- [A P I  Cookbook](https://github.com/useshortcut/api-cookbook)
- [Java Script  S D K](https://www.npmjs.com/package/@useshortcut/client)
- [Postman Collection](collections/shortcut.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shortcut.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/shortcutsoftware)
- [Website](https://www.shortcut.com)
- [Documentation](https://developer.shortcut.com)
- [Pricing](https://www.shortcut.com/pricing)
- [Sign Up](https://app.shortcut.com/signup)
- [Support](https://help.shortcut.com)
- [Blog](https://shortcut.com/blog)
- [Git Hub](https://github.com/useshortcut)
- [Status Page](https://status.shortcut.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
