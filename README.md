# MonkeyLearn

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Machine learning text analysis platform with REST APIs for sentiment analysis, keyword extraction, topic classification, and custom ML model training on text data. MonkeyLearn was acquired by Medallia in February 2022 and its capabilities are now part of the Medallia experience management platform.

## API

The MonkeyLearn REST API v3 (`https://api.monkeylearn.com/v3/`) provides two primary resource types:

- **Classifiers** (`/v3/classifiers/{model_id}/classify/`) — analyze whole texts and assign categories, sentiments, or topics
- **Extractors** (`/v3/extractors/{model_id}/extract/`) — identify and extract named entities, keywords, and other structured information from text

Authentication uses token-based headers: `Authorization: Token YOUR_API_KEY`.

Official SDKs are available for Python, Ruby, Node.js, PHP, and Java. All SDKs include built-in auto-batching (up to 200 texts per request) and automatic throttle retry handling.

## Links

- **Website:** https://monkeylearn.com/
- **Documentation:** https://monkeylearn.com/api/
- **GitHub:** https://github.com/monkeylearn
- **Blog:** https://monkeylearn.com/blog/
- **Pricing:** https://monkeylearn.com/pricing/
- **Status:** https://status.monkeylearn.com/
- **X (Twitter):** https://twitter.com/monkeylearn
- **LinkedIn:** https://www.linkedin.com/company/monkeylearn

## APIs.json

This repository contains an APIs.json 0.19 profile for MonkeyLearn maintained by [API Evangelist](https://apievangelist.com).
