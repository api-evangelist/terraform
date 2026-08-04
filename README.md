# Terraform (terraform)

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
