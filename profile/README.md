<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="mark-dark.svg">
    <img alt="abc-cluster" src="mark-light.svg" width="220">
  </picture>
</p>

# abc-cluster

**African Bioinformatics Computing** — open, sovereign computing for research.
A cluster designed to be your research assistant, so you can focus on the science.

abc-cluster is built on HashiCorp Nomad, MinIO and Nextflow. Data residency is a
property of the architecture, not a policy document: your data stays on
infrastructure your institution controls.

**Status:** the *seedling* tier is in closed beta for BMRI research groups at
Stellenbosch University. Website and docs: <https://abc-cluster.cloud>

## Repositories

| Repository | What it is |
|---|---|
| [abc-cluster-cli](https://github.com/abc-cluster/abc-cluster-cli) | The `abc` command-line tool: jobs, Nextflow pipelines, data movement, apps |
| [nf-nomad](https://github.com/abc-cluster/nf-nomad) | HashiCorp Nomad executor plugin for Nextflow |
| [abc-auth-svc](https://github.com/abc-cluster/abc-auth-svc) | Auth and access service for the seedling tier |
| [abc-nodes](https://github.com/abc-cluster/abc-nodes) | Nomad, Consul, Vault, Boundary and Caddy configuration for cluster nodes |
| [abc-node-probe](https://github.com/abc-cluster/abc-node-probe) | Read-only readiness check for a node joining a cluster |
| [abc-print-svc](https://github.com/abc-cluster/abc-print-svc) | Document compilation and compliance verification for thesis-style documents |
| [nomad-driver-singularity](https://github.com/abc-cluster/nomad-driver-singularity) | Nomad task driver for Singularity containers |
| [abc-dev](https://github.com/abc-cluster/abc-dev) | Docker Compose development environment |
| [brims](https://github.com/abc-cluster/brims) | Bio-medical Research Information Management System |

## Get started

Install the CLI and read the docs: <https://abc-cluster.cloud>
