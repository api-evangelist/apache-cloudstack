# Apache CloudStack (apache-cloudstack)
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
