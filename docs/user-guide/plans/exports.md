---
sidebar_position: 9
description: Discover export options for a plan
---

# Exports

You can export the structure of a plan in the following formats:
- **PDF**
- **DOCX**
- **JSON**
- **XML**

:::info
- `JSON` file is produced according to [RDA](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard) or [RAiD](https://metadata.raid.org/en/v1.6.3/core/core.html#contents) specifications
- File formats `PDF`, `DOCX`, `JSON` exports are done by [file transformer services](optional-services/file-transformers.md)
- You can use the export feature if current plan status has this action. More details can be found [here](admin-guide/system-configuration/plan-statuses.md)
:::

![Export a plan](/images/plans/exports/plan-export.png)
*Export a plan*

:::tip

- `Export` the button can be used both internally in the form and externally in [`Μy Plans`](user-guide/plans/my-plans.md) and [`Plan Overview`](user-guide/plans/plan-overview.md)
- Export is also available for the [Public Plans](user-guide/plans/my-plans.md#public-plans)

:::

## See Also

- [Deposit a Plan](user-guide/plans/deposit-a-plan.md) — publish to a repository and receive a permanent DOI
- [File Transformer Services](optional-services/file-transformers.md) — learn about supported formats and how to add custom transformers
