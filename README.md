# Terraform (terraform)

HashiCorp Terraform is an open-source infrastructure-as-code tool that enables teams to define, provision, and manage cloud infrastructure using a declarative configuration language (HCL). HCP Terraform and Terraform Enterprise expose a comprehensive REST API for automating workspace management, runs, state, policies, and access control.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Infrastructure As Code
- Cloud Infrastructure
- DevOps
- Open Source
- HashiCorp

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### HCP Terraform API

The HCP Terraform API provides programmatic access to all HCP Terraform features including workspace management, runs, state versions, policies, teams, organizations, VCS integrations, and the private module registry. The API follows the JSON API specification and uses bearer token authentication.

- **Human URL:** [https://developer.hashicorp.com/terraform/cloud-docs/api-docs](https://developer.hashicorp.com/terraform/cloud-docs/api-docs)
- **Base URL:** `https://app.terraform.io/api/v2`

#### Tags

- Infrastructure As Code
- Workspaces
- Runs
- State Management
- Policy

#### Properties

- [Documentation](https://developer.hashicorp.com/terraform/cloud-docs/api-docs)
- [Documentation](https://developer.hashicorp.com/terraform/cloud-docs/api-docs/workspaces)
- [Documentation](https://developer.hashicorp.com/terraform/cloud-docs/api-docs/run)
- [Documentation](https://developer.hashicorp.com/terraform/cloud-docs/api-docs/state-versions)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/hcp-terraform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hcp-terraform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp-terraform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/terraform-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terraform-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Terraform Registry API

The Terraform Registry API enables discovery, listing, versioning, and downloading of modules from the public Terraform Registry. It supports searching by keyword, filtering by provider and namespace, and retrieving download metrics.

- **Human URL:** [https://developer.hashicorp.com/terraform/registry/api-docs](https://developer.hashicorp.com/terraform/registry/api-docs)
- **Base URL:** `https://registry.terraform.io`

#### Tags

- Registry
- Modules
- Providers
- Discovery

#### Properties

- [Documentation](https://developer.hashicorp.com/terraform/registry/api-docs)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/terraform-registry-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hcp-terraform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp-terraform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/terraform-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terraform-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.hashicorp.com/terraform)
- [Repository](https://github.com/hashicorp/terraform)
- [Portal](https://registry.terraform.io)
- [Portal](https://app.terraform.io)
- [Changelog](https://github.com/hashicorp/terraform/blob/main/CHANGELOG.md)
- [Forum](https://discuss.hashicorp.com/c/terraform-core)
- [Repository](https://github.com/hashicorp/terraform)
- [SDK](https://github.com/hashicorp/terraform-cdk)
- [SDK](https://github.com/hashicorp/go-tfe)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
