# Apache CloudStack (apache-cloudstack)

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

Apache CloudStack is an open-source cloud computing platform developed by the Apache Software Foundation for creating, managing, and deploying infrastructure cloud services. It provides a comprehensive IaaS platform supporting multiple hypervisors (KVM, VMware vSphere, XenServer) and a rich API for programmatic cloud resource management. CloudStack is used by service providers and enterprises to build public, private, and hybrid cloud environments with virtual machine management, networking, storage, and multi-tenancy features.

**URL:** [https://cloudstack.apache.org/](https://cloudstack.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Apache, Cloud, IaaS, Infrastructure, Open Source, Virtualization

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache CloudStack API
The CloudStack API provides comprehensive REST endpoints for managing virtual machines, networks, storage volumes, accounts, domains, zones, and all cloud infrastructure resources using a query-parameter-based command dispatch pattern with HMAC-SHA1 authentication and asynchronous job support.

**Human URL:** [https://cloudstack.apache.org/api/](https://cloudstack.apache.org/api/)

#### Tags

 - Cloud, IaaS, REST, Virtual Machines

#### Properties

- [Documentation](https://cloudstack.apache.org/api/)
- [OpenAPI](openapi/apache-cloudstack-api-openapi.yaml)
- [GettingStarted](https://docs.cloudstack.apache.org/en/latest/installguide/)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/cloudstack)
- [Documentation](https://docs.cloudstack.apache.org/)
- [GettingStarted](https://docs.cloudstack.apache.org/en/latest/installguide/)
- [Support](https://cloudstack.apache.org/community/)
- [TermsOfService](https://www.apache.org/licenses/)
- [ChangeLog](https://github.com/apache/cloudstack/releases)

## Features

| Name | Description |
|------|-------------|
| Virtual Machine Management | Full VM lifecycle management including deploy, start, stop, reboot, migrate, and destroy across multiple hypervisors. |
| Multi-Hypervisor Support | Support for KVM, VMware vSphere, XenServer, and Hyper-V hypervisors within a single CloudStack deployment. |
| Network Management | Advanced networking with isolated networks, shared networks, VLANs, VPNs, and software-defined networking. |
| Storage Management | Primary and secondary storage management with volume snapshots, templates, and ISOs. |
| Multi-Tenancy | Account and domain hierarchy for isolating resources between tenants, departments, and organizations. |
| Asynchronous API | Long-running operations return async job IDs that can be polled for completion status. |
| Security Groups | Stateful firewall rules for controlling inbound and outbound traffic to virtual machines. |
| Auto Scaling | Automatic scaling of VM instances in response to load conditions using configurable policies. |
| REST API | Comprehensive query-parameter-based REST API with HMAC-SHA1 authentication for programmatic cloud management. |
| CloudStack UI | Web-based management console for administrators and users to manage cloud resources visually. |

## Use Cases

| Name | Description |
|------|-------------|
| Public Cloud Infrastructure | Build and operate public IaaS clouds for service providers offering compute, storage, and networking. |
| Private Enterprise Cloud | Deploy private clouds for enterprise organizations needing isolated, on-premises infrastructure. |
| Hybrid Cloud Orchestration | Extend on-premises CloudStack clouds to public cloud providers for burst capacity and disaster recovery. |
| Managed Service Provider Hosting | Host multi-tenant virtual server environments for managed service providers and resellers. |
| Development and Test Environments | Provision self-service development and testing environments on demand for engineering teams. |

## Integrations

| Name | Description |
|------|-------------|
| KVM | KVM hypervisor support for Linux-based compute clusters in CloudStack zones. |
| VMware vSphere | VMware vSphere integration for managing ESXi hosts and vCenter clusters via CloudStack. |
| Apache Cloudbridge | Integration with Apache Cloudbridge for hybrid cloud connectivity between CloudStack and AWS. |
| Ceph | Ceph distributed storage integration for primary storage in CloudStack deployments. |
| OpenDaylight | OpenDaylight SDN controller integration for software-defined networking in CloudStack. |
| Terraform | HashiCorp Terraform CloudStack provider for infrastructure-as-code provisioning. |
| Ansible | Ansible CloudStack modules for automating VM provisioning and cloud management tasks. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache CloudStack API](openapi/apache-cloudstack-api-openapi.yaml)

### JSON Schema

5 schema files covering VirtualMachine, Network, Volume, Zone, and AsyncJobResponse.

### JSON-LD

- [Apache CloudStack Context](json-ld/apache-cloudstack-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache CloudStack API](capabilities/shared/cloudstack-api.yaml) — 8 operations for VM lifecycle, network listing, volume listing, zone browsing, and async job polling

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache CloudStack IaaS Management](capabilities/cloudstack-iaas-management.yaml) | CloudStack API | 5 | Cloud Administrator, Cloud Tenant |

## Vocabulary

- [Apache CloudStack Vocabulary](vocabulary/apache-cloudstack-vocabulary.yaml) — Domain taxonomy mapping 8 resources, 6 actions, 1 workflow, and 2 personas for IaaS cloud management

## Rules

- [Apache CloudStack Spectral Rules](rules/apache-cloudstack-spectral-rules.yml) — 12 rules across 5 categories enforcing Apache CloudStack API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
