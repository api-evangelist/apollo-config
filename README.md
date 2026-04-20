# Apollo Config (apollo-config)
Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. Originally developed by Ctrip, now maintained by the apolloconfig community under Apache 2.0 license.

**URL:** [https://www.apolloconfig.com/](https://www.apolloconfig.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache 2.0, Configuration Management, Ctrip, Distributed Systems, Java, Microservices, Open Source, Real-Time Configuration

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Apollo Config
Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. The Open API provides programmatic access to app management, namespace management, configuration publishing, and release management including gray releases.

**Human URL:** [https://www.apolloconfig.com/](https://www.apolloconfig.com/)

#### Tags:

 - Apache 2.0, Configuration Management, Distributed Systems, Java, Microservices, Open Source, Real-Time Configuration

#### Properties

- [Documentation](https://www.apolloconfig.com/#/en/portal/apollo-open-api-platform)
- [OpenAPI](openapi/apollo-open-api.yml)
- [JSONSchema](json-schema/apollo-open-api-app-schema.json)
- [JSONSchema](json-schema/apollo-open-api-cluster-schema.json)
- [JSONSchema](json-schema/apollo-open-api-namespace-schema.json)
- [JSONSchema](json-schema/apollo-open-api-item-schema.json)
- [JSONSchema](json-schema/apollo-open-api-release-schema.json)

## Common Properties

- [Documentation](https://www.apolloconfig.com/#/en/)
- [GettingStarted](https://www.apolloconfig.com/#/en/deployment/quick-start)
- [GitHubRepository](https://github.com/apolloconfig/apollo)
- [GitHubOrganization](https://github.com/apolloconfig)
- [ReleaseNotes](https://github.com/apolloconfig/apollo/releases)
- [Support](https://github.com/apolloconfig/apollo/issues)
- [Java SDK](https://github.com/apolloconfig/apollo-java)
- [.NET SDK](https://github.com/apolloconfig/apollo.net)
- [Go SDK](https://github.com/apolloconfig/agollo)
- [Java Demo](https://github.com/apolloconfig/apollo-demo-java)
- [Use Cases](https://github.com/apolloconfig/apollo-use-cases)

## Features

| Name | Description |
|------|-------------|
| Centralized Configuration Management | Centralize configuration for all microservices in one place with real-time push updates. |
| Real-Time Configuration Updates | Push configuration changes to all clients instantly without application restarts. |
| Multi-Environment Support | Manage configurations across DEV, FAT, UAT, and PRO environments independently. |
| Versioning and History | Track configuration changes with full version history and rollback capability. |
| Gray Release Support | Gradually roll out configuration changes to a subset of instances. |
| Namespace Management | Organize configurations into namespaces supporting properties, JSON, YAML, XML, and text formats. |
| Cluster Management | Manage configuration at the cluster level for multi-cluster deployments. |
| Open API | REST API for programmatic configuration management and automation. |
| Kubernetes Operator | Kubernetes Operator for automated Apollo deployment in container environments. |
| Helm Chart Deployment | Official Helm chart for Kubernetes deployments. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservice Configuration | Manage centralized configuration for distributed microservice architectures. |
| Multi-Environment Configuration | Maintain separate configurations for development, testing, staging, and production. |
| Dynamic Configuration Updates | Update application configuration at runtime without redeployment. |
| Configuration Audit | Track who changed what configuration and when with full audit trail. |
| Kubernetes Configuration Management | Manage configuration for containerized applications deployed on Kubernetes. |

## Integrations

| Name | Description |
|------|-------------|
| Java | Official Java client library via apollo-java SDK. |
| .NET | Official .NET client library via apollo.net SDK. |
| Go | Go client library via agollo SDK. |
| Kubernetes | Apollo Operator and Helm chart for Kubernetes deployment. |
| Spring Boot | Spring Boot integration via Java SDK for auto-configuration refresh. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apollo Config Open API](openapi/apollo-open-api.yml)

### JSON Schema

- [App Schema](json-schema/apollo-open-api-app-schema.json)
- [Cluster Schema](json-schema/apollo-open-api-cluster-schema.json)
- [Namespace Schema](json-schema/apollo-open-api-namespace-schema.json)
- [Item Schema](json-schema/apollo-open-api-item-schema.json)
- [Release Schema](json-schema/apollo-open-api-release-schema.json)

### JSON Structure

- [App Structure](json-structure/apollo-open-api-app-structure.json)
- [Cluster Structure](json-structure/apollo-open-api-cluster-structure.json)
- [Namespace Structure](json-structure/apollo-open-api-namespace-structure.json)
- [Item Structure](json-structure/apollo-open-api-item-structure.json)
- [Release Structure](json-structure/apollo-open-api-release-structure.json)

### JSON-LD

- [Apollo Config Open API Context](json-ld/apollo-config-open-api-context.jsonld)

### Examples

- [App Example](examples/apollo-open-api-app-example.json)
- [Cluster Example](examples/apollo-open-api-cluster-example.json)
- [Namespace Example](examples/apollo-open-api-namespace-example.json)
- [Item Example](examples/apollo-open-api-item-example.json)
- [Release Example](examples/apollo-open-api-release-example.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
