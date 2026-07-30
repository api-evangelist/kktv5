# KK直播 (KK Live)

KK直播 (KK Live) is a Chinese mobile-first video livestreaming and social entertainment platform operated by 杭州米络文化传播有限公司 (Hangzhou Melot Culture Communication Co., Ltd.), part of 米络星集团 (Melot Group) of Hangzhou. Founded in 2012, it pairs talent and performance streaming with interactive social features — virtual gifting, bullet comments (弹幕), multi-person live connections, PK mini-games and karaoke rooms. The company reports 100,000+ independent streamers, 600+ partner talent agencies and 150 million registered users.

Melot Group operates three business lines — entertainment livestreaming, online education and video service solutions — under the KK, 棒直播 and 米乐 brands.

- Website: https://www.kktv5.com
- Backed by: Qiming Venture Partners (启明创投), Sequoia China, CMC Capital, Shanda Capital

## API surface

KK Live is a business-to-consumer product. As of the 2026-07-19 enrichment pass it publishes **no public developer portal, API documentation, SDKs, CLI, or machine-readable API specifications**. `/.well-known/*` and `/llms.txt` on `www.kktv5.com` return HTTP 200 with an HTML soft-404 body, so no discovery documents are actually published. The group's RTC developer platform domain (`mlrtc.com`) has no DNS delegation, and `melotgroup.com` serves a expired free-tier placeholder.

## Artifacts

- `security/kktv5-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture
- `llms/kktv5-llms.txt` — generated agent-facing company summary
