# Speechmatics (speechmatics)

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

Speechmatics is an enterprise-grade speech intelligence platform headquartered in Cambridge, UK, delivering highly accurate speech-to-text APIs that support 55+ languages with both batch and real-time transcription modes. The platform provides REST APIs for asynchronous batch transcription job management and WebSocket APIs for low-latency streaming real-time transcription, along with speaker diarization, speaker identification, custom vocabulary, sentiment analysis, translation, and topic detection. Speechmatics also offers a Text-to-Speech API, an early-access Voice Agent API, and a Management API for programmatic account and API key administration. Flexible deployment options include cloud SaaS, containerized on-premises, Kubernetes, and virtual appliance installations.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/speechmatics/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=speechmatics-api-evangelist&utm_content=repo

---

## Tags

- Speech Recognition
- Speech-to-Text
- Transcription
- Real-Time Transcription
- Batch Transcription
- Speaker Diarization
- Text-to-Speech
- Voice AI
- NLP
- Audio Processing
- WebSocket
- REST

---

## APIs

| API | Description |
|-----|-------------|
| Batch Transcription API | REST API for submitting audio files for asynchronous batch transcription with 55+ languages, diarization, translation, and custom vocabulary. |
| Realtime Transcription API | WebSocket API for low-latency real-time streaming transcription with speaker diarization and partial/final transcript events. |
| Management API | REST API for programmatic management of projects, API keys, usage tracking, and account administration. |
| Text-to-Speech API | REST API for converting text to natural-sounding speech with multiple voice options. |

---

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/speechmatics-plans-pricing.yml](plans/speechmatics-plans-pricing.yml) |
| Rate Limits | [rate-limits/speechmatics-rate-limits.yml](rate-limits/speechmatics-rate-limits.yml) |
| FinOps | [finops/speechmatics-finops.yml](finops/speechmatics-finops.yml) |

**Pricing summary:**
- **Free:** 2,400 minutes/month speech-to-text, 1M characters/month TTS, 2 concurrent real-time sessions
- **Pro:** $0.005/min batch, $0.0067/min real-time (~$0.24/hr); 50 concurrent sessions; 20% auto-discount above 500 hrs/month
- **Enterprise:** Custom pricing, no rate limits, on-premises and multi-region options, dedicated support
- **Startup Program:** $50,000+ in credits for qualifying early-stage companies

---

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-12 |
| Modified | 2026-06-12 |

---

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.speechmatics.com/ |
| Documentation | https://docs.speechmatics.com/ |
| GitHub Organization | https://github.com/speechmatics |
| LinkedIn | https://www.linkedin.com/company/speechmatics |
| X / Twitter | https://x.com/Speechmatics |
| Blog | https://www.speechmatics.com/company/articles-and-news/articles |
| Pricing | https://www.speechmatics.com/pricing |
| Status Page | https://status.speechmatics.com/ |
| Portal | https://portal.speechmatics.com/ |
| Discord | https://discord.gg/speechmatics |

---

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
