# Encord (encord)

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
