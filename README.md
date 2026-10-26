# Amazon Augmented AI

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

Amazon Augmented AI (Amazon A2I) is a machine learning service that makes it easy to build the workflows required for human review of ML predictions. Amazon A2I brings human review to all developers, removing the undifferentiated heavy lifting associated with building human review systems or managing large numbers of human reviewers.

## Overview

The Amazon Augmented AI runtime API enables programmatic control over human loops — the review tasks routed to human workers when ML predictions need human judgment. It integrates with Amazon Rekognition, Textract, and custom ML workflows.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/augmented-ai/2019-11-07/APIReference/Welcome.html
- **Base URL:** https://a2i-runtime.sagemaker.us-east-1.amazonaws.com

## Features

- Human review integration for Amazon Rekognition and Amazon Textract
- Custom flow definitions for any ML use case
- Built-in worker task templates for common review tasks
- Integration with Amazon SageMaker Ground Truth for workforce management
- Private, vendor, and Amazon Mechanical Turk workforce support
- Automatic routing based on ML confidence scores
- Audit trail with evidence of human review decisions
- Scalable workforce management across thousands of reviewers
- Pre-built UI templates for image and text review tasks
- Compliance support with PII content classifiers

## Use Cases

- Review low-confidence document text extraction results
- Validate image classification predictions before deployment
- Moderate user-generated content with human reviewers
- Ensure accuracy of medical record processing
- Verify identity document data extraction results
- Build training datasets with human-verified labels

## Artifacts

### OpenAPI Specification
`openapi/amazon-augmented-ai-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all Augmented AI API paths.

### Spectral Rules
`rules/amazon-augmented-ai-spectral-rules.yml`

### Naftiko Capabilities
- `capabilities/shared/a2i-api.yaml` — Shared per-API capability definition
- `capabilities/human-review-workflow.yaml` — Workflow capability for human review

### Vocabulary
`vocabulary/amazon-augmented-ai-vocabulary.yaml`

### JSON Schemas
`json-schema/` — 12 JSON Schema files for all objects.

### JSON Structures
`json-structure/` — 12 JSON Structure files.

### JSON-LD Context
`json-ld/amazon-augmented-ai-context.jsonld`

### Examples
`examples/` — 12 example JSON files.

## Integrations

- Amazon SageMaker
- Amazon Rekognition
- Amazon Textract
- Amazon S3
- Amazon SageMaker Ground Truth
- Amazon Mechanical Turk
- AWS IAM
- Amazon CloudWatch
- AWS Lambda
- Amazon SNS

## Tags

Amazon Augmented AI, Human In The Loop, Machine Learning, AI Review, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
