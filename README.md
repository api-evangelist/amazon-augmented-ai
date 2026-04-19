# Amazon Augmented AI

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
