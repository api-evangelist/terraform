# Terraform

HashiCorp Terraform is an open-source infrastructure-as-code tool that enables teams to define, provision, and manage cloud infrastructure using a declarative configuration language (HCL). HCP Terraform and Terraform Enterprise expose a comprehensive REST API for automating workspace management, runs, state, policies, and access control.

**Type:** Open Source  
**GitHub:** https://github.com/hashicorp/terraform  
**Developer Portal:** https://developer.hashicorp.com/terraform  
**HCP Terraform:** https://app.terraform.io  

## APIs

### HCP Terraform API
The HCP Terraform API provides programmatic access to all HCP Terraform features including workspace management, runs, state versions, policies, teams, organizations, VCS integrations, and the private module registry. Follows the JSON API specification with bearer token authentication.

- **Base URL:** `https://app.terraform.io/api/v2`
- **Authentication:** Bearer token
- **Documentation:** https://developer.hashicorp.com/terraform/cloud-docs/api-docs
- **OpenAPI Spec:** [openapi/hcp-terraform-openapi.yml](openapi/hcp-terraform-openapi.yml)

### Terraform Registry API
The Terraform Registry API enables discovery, listing, versioning, and downloading of modules from the public Terraform Registry.

- **Base URL:** `https://registry.terraform.io`
- **Authentication:** None (public)
- **Documentation:** https://developer.hashicorp.com/terraform/registry/api-docs
- **OpenAPI Spec:** [openapi/terraform-registry-openapi.yml](openapi/terraform-registry-openapi.yml)

## Artifacts

| Type | Files |
|------|-------|
| OpenAPI Specs | [openapi/](openapi/) |
| Spectral Rules | [rules/hcp-terraform-rules.yml](rules/hcp-terraform-rules.yml) |
| Capabilities | [capabilities/](capabilities/) |
| JSON Schema | [json-schema/](json-schema/) |
| JSON Structure | [json-structure/](json-structure/) |
| JSON-LD | [json-ld/terraform-context.jsonld](json-ld/terraform-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/terraform-vocabulary.yml](vocabulary/terraform-vocabulary.yml) |

## Capabilities

### Workflow Capabilities
- **[infrastructure-automation.yaml](capabilities/infrastructure-automation.yaml)** — Unified workflow for infrastructure automation: workspace management, run orchestration, state versioning, policy governance, and module discovery (16 tools)

### Shared Per-API Definitions
- **[shared/hcp-terraform.yaml](capabilities/shared/hcp-terraform.yaml)** — HCP Terraform API: organizations, workspaces, runs, state versions, teams, policies (14 tools)
- **[shared/terraform-registry.yaml](capabilities/shared/terraform-registry.yaml)** — Terraform Registry: module listing, search, versioning (4 tools)

## Tags

Infrastructure As Code, Cloud Infrastructure, DevOps, Open Source, HashiCorp, Workspaces, Runs, State Management, Policy, Modules

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
