---
sidebar_position: 4
description: Discover everything about the deposit services
---

# Deposit Services

The `Deposit Services` are independent third party services responsible to provide a place to store and validate data objects *(in our case [plans](user-guide/plans/index.md))*. They are used as a source of trust and provide a unique key / signature *(called **DOIs** or **D**ata **O**bject **I**dentifiers)* for every data entity deposited to them.

These are the currently services implemented and integrated.

| Service | Supported Version(s) | Docker Image | Notes |
|---|---|---|---|
| [Zenodo](https://zenodo.org/) | InvenioRDM v12.0 | [repository-deposit-zenodo](https://hub.docker.com/r/opencdmp/repository-deposit-zenodo) | OAuth 2.0 or personal access token |
| [DSpace](https://dspace.org/) | 8.x | [repository-deposit-dspace](https://hub.docker.com/r/opencdmp/repository-deposit-dspace) | Username/password authentication |
| [CKAN](https://ckan.org/) | 2.11.4 | [repository-deposit-ckan](https://hub.docker.com/r/opencdmp/repository-deposit-ckan) | Access token authentication |
| [Dataverse](https://dataverse.org/) | 6.9 | [repository-deposit-dataverse](https://hub.docker.com/r/opencdmp/repository-deposit-dataverse) | Access token authentication |
| [Fedora](https://fedorarepository.org/) | 6.x | [repository-deposit-fedora](https://hub.docker.com/r/opencdmp/repository-deposit-fedora) | Username/password authentication |

:::note
You can create your own deposit source. More details [here](developers/plugins/deposit.md).
:::

---

## See Also

- [Deposit Service Configuration](/getting-started/configuration/backend/deposit.md) - Environment variable reference for deploying deposit services