# KK直播 (KK Live)

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

KK直播 (KK Live) is a Chinese mobile-first video livestreaming and social entertainment platform operated by 杭州米络文化传播有限公司 (Hangzhou Melot Culture Communication Co., Ltd.), part of 米络星集团 (Melot Group) of Hangzhou. Founded in 2012, it pairs talent and performance streaming with interactive social features — virtual gifting, bullet comments (弹幕), multi-person live connections, PK mini-games and karaoke rooms. The company reports 100,000+ independent streamers, 600+ partner talent agencies and 150 million registered users.

Melot Group operates three business lines — entertainment livestreaming, online education and video service solutions — under the KK, 棒直播 and 米乐 brands.

- Website: https://www.kktv5.com
- Backed by: Qiming Venture Partners (启明创投), Sequoia China, CMC Capital, Shanda Capital

## API surface

KK Live is a business-to-consumer product. As of the 2026-07-19 enrichment pass it publishes **no public developer portal, API documentation, SDKs, CLI, or machine-readable API specifications**. `/.well-known/*` and `/llms.txt` on `www.kktv5.com` return HTTP 200 with an HTML soft-404 body, so no discovery documents are actually published. The group's RTC developer platform domain (`mlrtc.com`) has no DNS delegation, and `melotgroup.com` serves a expired free-tier placeholder.

## Artifacts

- `security/kktv5-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture
- `llms/kktv5-llms.txt` — generated agent-facing company summary
