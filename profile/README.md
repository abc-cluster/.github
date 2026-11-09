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

## Get started

Install the CLI and read the docs: <https://abc-cluster.cloud>
