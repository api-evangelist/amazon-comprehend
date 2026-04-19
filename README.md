# Amazon Comprehend (amazon-comprehend)
Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to uncover information in unstructured data. It provides entity recognition, sentiment analysis, key phrase extraction, language detection, topic modeling, PII detection, and custom classification capabilities for text documents at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-comprehend/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Machine Learning, Natural Language Processing, NLP, Text Analysis

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Comprehend API
The Amazon Comprehend API provides programmatic access to natural language processing capabilities including sentiment analysis, entity recognition, key phrase extraction, language detection, topic modeling, PII detection, and syntax analysis. Supports real-time and batch processing with 84 operations.

**Human URL:** [https://aws.amazon.com/comprehend/](https://aws.amazon.com/comprehend/)

#### Tags:

 - AWS, Machine Learning, Natural Language Processing, NLP, Text Analysis

#### Properties

- [Documentation](https://docs.aws.amazon.com/comprehend/latest/dg/)
- [OpenAPI](openapi/amazon-comprehend-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/comprehend/latest/APIReference/)
- [Pricing](https://aws.amazon.com/comprehend/pricing/)
- [GettingStarted](https://aws.amazon.com/comprehend/getting-started/)
- [FAQ](https://aws.amazon.com/comprehend/faqs/)
- [JSONSchema](json-schema/comprehend-entity-schema.json)
- [JSONStructure](json-structure/comprehend-entity-structure.json)
- [JSON-LD](json-ld/amazon-comprehend-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/comprehend/)
- [Documentation](https://docs.aws.amazon.com/comprehend/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/comprehend/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-comprehend)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Entity Recognition | Identify named entities such as people, places, organizations, dates, and quantities in text. |
| Sentiment Analysis | Detect positive, negative, neutral, or mixed sentiment in text documents. |
| Key Phrase Extraction | Extract key noun phrases and concepts from unstructured text. |
| Language Detection | Automatically detect the dominant language of input text from 100+ supported languages. |
| PII Detection and Redaction | Identify and optionally redact personally identifiable information from documents. |
| Topic Modeling | Discover latent topics in large collections of documents using unsupervised learning. |
| Custom Classification | Train custom document classifiers using your own labeled training data. |
| Custom Entity Recognition | Train custom entity recognizers to identify domain-specific entities in text. |
| Syntax Analysis | Analyze the syntax of text including parts of speech tagging and tokenization. |
| Flywheel | Continuously improve custom models with new training data using the Flywheel feature. |

## Use Cases

| Name | Description |
|------|-------------|
| Customer Feedback Analysis | Analyze customer reviews, support tickets, and survey responses to understand sentiment and extract actionable insights. |
| Content Moderation | Detect and filter inappropriate content, hate speech, or PII from user-generated content. |
| Document Processing | Extract entities, key information, and classifications from contracts, reports, and medical records. |
| Voice of Customer Analytics | Mine customer interactions for trends, topics, and sentiment to improve products and services. |
| Compliance and PII Redaction | Automatically detect and redact PII from documents to meet GDPR, HIPAA, and other compliance requirements. |
| Search Enhancement | Enrich search indexes with entities, key phrases, and topics to improve search relevance. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Process documents stored in S3 buckets using async batch analysis jobs. |
| Amazon SageMaker | Integrate custom Comprehend models with SageMaker for advanced ML workflows. |
| AWS Lambda | Trigger real-time Comprehend analysis from Lambda functions in event-driven architectures. |
| Amazon Kinesis | Analyze streaming text data from Kinesis Data Streams and Firehose. |
| Amazon OpenSearch | Enrich OpenSearch indexes with Comprehend-detected entities and topics for better search. |
| AWS Glue | Use Comprehend in AWS Glue ETL jobs for large-scale document processing pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Comprehend OpenAPI](openapi/amazon-comprehend-openapi.yml)

### JSON Schema

403 schema files extracted from the OpenAPI specification covering all request/response models.

### JSON Structure

403 JSON Structure files converted from JSON Schema using the json-structure.org specification.

### JSON-LD

- [Amazon Comprehend Context](json-ld/amazon-comprehend-context.jsonld) — 268 types, 216 properties

### Examples

403 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Comprehend API](capabilities/shared/comprehend.yaml) — 11 operations for NLP analysis and custom model management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Comprehend NLP Analysis](capabilities/nlp-analysis.yaml) | Amazon Comprehend API | 10 | Data Scientist, Application Developer |

## Vocabulary

- [Amazon Comprehend Vocabulary](vocabulary/amazon-comprehend-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Comprehend Spectral Rules](rules/amazon-comprehend-spectral-rules.yml) — 26 rules across 13 categories enforcing Amazon Comprehend API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
