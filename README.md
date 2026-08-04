# Encord (encord)

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

Encord is a computer vision data labeling and model evaluation platform that provides tools and APIs for managing datasets, annotation tasks, labels, and quality workflows at scale. The platform supports multimodal data including images, video, audio, DICOM, point clouds, and text. Encord exposes a REST API and a Python SDK for programmatically managing projects, datasets, ontologies, storage, and automated labeling workflows. Encord is trusted by AI teams in healthcare, autonomous systems, and other industries to accelerate model development by streamlining data curation, annotation, and evaluation pipelines.

APIs.json: https://raw.githubusercontent.com/api-evangelist/encord/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=encord-api-evangelist&utm_content=repo

## Tags

- Computer Vision
- Data Labeling
- Annotation
- Machine Learning
- Model Evaluation
- Dataset Management
- Artificial Intelligence
- Image Annotation
- Video Annotation
- DICOM
- Active Learning
- Quality Assurance

## APIs

### Encord Annotate API

REST API and Python SDK for programmatically managing annotation projects, datasets, ontologies, labels, and workflows within the Encord Annotate platform. Supports creating and retrieving projects and datasets, importing and exporting labels, managing automated labeling agents, integrating cloud storage, and orchestrating annotation workflows.

- Documentation: https://docs.encord.com/
- Base URL: https://api.encord.com/public
- Python SDK: https://pypi.org/project/encord/
- GitHub Client: https://github.com/encord-team/encord-client-python

### Encord Active API

API for the Encord Active module providing model evaluation, data curation, and active learning capabilities. Allows importing model predictions, computing quality metrics (mAP, mAR, F1), running embedding-based similarity search, and surfacing the most valuable data for labeling.

- Documentation: https://docs.encord.com/sdk-documentation/api-active/sdk-active-collections
- Product Page: https://encord.com/active/
- GitHub: https://github.com/encord-team/encord-active

## Plans, Rate Limits, and FinOps

| Resource | File |
|---|---|
| Plans and Pricing | [plans/encord-plans-pricing.yml](plans/encord-plans-pricing.yml) |
| Rate Limits | [rate-limits/encord-rate-limits.yml](rate-limits/encord-rate-limits.yml) |
| FinOps | [finops/encord-finops.yml](finops/encord-finops.yml) |

Encord offers three tiers: a free Starter plan, a quote-based Team plan, and custom Enterprise agreements. Rate limits are not publicly disclosed; Enterprise customers negotiate throughput as part of their contract. Authentication uses SSH private key or service account credentials, with separate UK (api.encord.com) and US (api.us.encord.com) region endpoints.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Property | URL |
|---|---|
| Website | https://encord.com/ |
| Documentation | https://docs.encord.com/ |
| GitHub Organization | https://github.com/encord-team |
| LinkedIn | https://www.linkedin.com/company/encord-team |
| X (Twitter) | https://x.com/encord_team |
| Blog | https://encord.com/blog/ |
| Pricing | https://encord.com/pricing/ |
| Status Page | https://status.encord.com/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
