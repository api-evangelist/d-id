# D-ID (d-id)

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

D-ID is an AI-powered platform for generating talking-head videos and interactive digital human experiences. Developers can access REST APIs to produce pre-rendered talking avatar videos from still photos and text scripts, run real-time AI agent streaming sessions over WebRTC, translate videos into 100+ languages with voice cloning and lip-sync, and build custom digital humans backed by LLMs and RAG knowledge bases. D-ID has generated over 150 million videos and supports parallel processing of tens of thousands of simultaneous API requests.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/d-id/refs/heads/main/apis.yml

**Naftiko Fleet:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=d-id-api-evangelist&utm_content=repo

---

## Tags

`AI Video` `Digital Humans` `Talking Head` `Avatar` `Generative AI` `Video Generation` `Real-Time Streaming` `Text to Video` `Video Translation` `Voice Cloning`

---

## APIs

| API | Description | Docs |
|-----|-------------|------|
| D-ID Videos API | Generate AI talking-head videos from images with text or audio scripts across multiple avatar versions | [Reference](https://docs.d-id.com/reference/createtalk) |
| D-ID Agents API | Create real-time interactive AI agents combining digital avatar streaming with LLMs and knowledge bases | [Reference](https://docs.d-id.com/reference/agents) |
| D-ID Translations API | Translate videos into 100+ languages with voice cloning and lip-sync | [Reference](https://docs.d-id.com/reference/translations) |

---

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Pricing Plans | [plans/d-id-plans-pricing.yml](plans/d-id-plans-pricing.yml) |
| Rate Limits | [rate-limits/d-id-rate-limits.yml](rate-limits/d-id-rate-limits.yml) |
| FinOps | [finops/d-id-finops.yml](finops/d-id-finops.yml) |

**Pricing model:** Freemium subscription with shared API + Studio video minute quota. Plans: Trial (free, 14 days), Lite ($5.90/mo, 10 min), Pro ($48/mo, 30 min), Advanced ($299/mo, 65 min), Enterprise (custom).

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.d-id.com |
| Documentation | https://docs.d-id.com |
| API Reference | https://docs.d-id.com/reference/get-started |
| GitHub Organization | https://github.com/de-id |
| LinkedIn | https://www.linkedin.com/company/deidentification |
| X / Twitter | https://twitter.com/D_ID_ |
| Blog | https://www.d-id.com/blog |
| API Blog | https://www.d-id.com/blog/category/api/ |
| Pricing | https://www.d-id.com/pricing/api/ |
| Status Page | https://status.d-id.com |

---

## Maintainers

**Kin Lane** — kin@apievangelist.com
