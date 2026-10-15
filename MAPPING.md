# Mapping and Migration Record

This document records PDF, Markdown, GitBook, application, and image migration mappings.
Published image naming is defined exclusively in [STYLE.md](./STYLE.md).

## Image migration status (2026-10-15)

All images have been merged into the root `IMG/` folder. The per-chapter `images/`
directories have been removed.

| Item | Status |
|---|---|
| Total images in `IMG/` | 783, all flat, no duplicate filenames |
| Markdown image references | 825, all verified to resolve |
| Conflict images | 76, flattened into `IMG/` with a `_<Seq>` suffix |
| Formal rename per STYLE.md | **Pending** |

### Conflict images: `_<Seq>` suffix is a dedup placeholder

The 76 images that previously shared filenames across chapters were moved into `IMG/`
with a `_<Seq>` suffix assigned by original path order (e.g. `icon-delete_01.png`,
`icon-delete_02.png`, `icon-delete_03.png`). The suffix only guarantees uniqueness;
it does **not** carry the sequence semantics defined in STYLE.md.

When the formal rename is performed, these files will be renamed to their
`<Category>_<Page>_<Component>...` names and the `_<Seq>` suffix will be dropped or
replaced by a meaningful State/Seq.

### Original locations of the 76 conflict images

| Filename | Copies | Original chapter paths (path order = Seq order) |
|---|---:|---|
| `icon-delete.png` | 3 | `Account/RolePrivMgm`, `Notification/ConditionalTrigger`, `Options/Options` |
| `icon-list.png` | 4 | `Centralized/TaskScherMgm`, `Monitor/DeviceInfo`, `Options/Options`, `Report/SoftwareReportMgm` |
| `icon-expand.png` | 3 | `Account/RolePrivMgm`, `Monitor/SystemOverview`, `Report/SoftwareReportMgm` |
| `icon-edit.png` | 2 | `Notification/ConditionalTrigger`, `Options/Options` |
| `icon-account-info.png` | 2 | `Account/AccountMgm`, `Begin` |
| `icon-account.png` | 2 | `Account/AccountMgm`, `Account/RolePrivMgm` |
| `icon-centralized.png` | 5 | `Centralized/BIOSFlashMgm`, `Centralized/MetadataMgm`, `Centralized/SecurityMgm`, `Centralized/SWDispMgm`, `Centralized/TaskScherMgm` |
| `icon-home.png` | 5 | `Monitor/OOBMgmt`, `Monitor/StorageOverview`, `Monitor/SystemOverview`, `Monitor/VMHostInfo`, `Monitor/VMOverview` |
| `icon-expand-block.png` | 4 | `Monitor/HWSensor`, `Monitor/Redfish`, `Monitor/Utilization`, `Monitor/VMHostInfo` |
| `icon-minimize-block.png` | 4 | `Monitor/HWSensor`, `Monitor/Redfish`, `Monitor/Utilization`, `Monitor/VMHostInfo` |
| `icon-zoom-in.png` | 3 | `Monitor/GPUInfo`, `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-zoom-out.png` | 3 | `Monitor/GPUInfo`, `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-zoom-reset.png` | 3 | `Monitor/GPUInfo`, `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-notification.png` | 3 | `Notification/ConditionalTrigger`, `Notification/Subscription`, `Options/Options` |
| `icon-deployment.png` | 2 | `Deployment/AgentlessMgm`, `Deployment/AgentMgm` |
| `icon-options.png` | 2 | `Deployment/AgentMgm`, `Options/Options` |
| `icon-online.png` | 2 | `Monitor/DeviceInfo`, `Monitor/VMHostInfo` |
| `icon-power.png` | 2 | `Monitor/DeviceInfo`, `Monitor/Redfish` |
| `icon-tag.png` | 2 | `Monitor/DeviceInfo`, `Monitor/Redfish` |
| `icon-gear.png` | 2 | `Monitor/GPUInfo`, `Monitor/VMHostInfo` |
| `icon-chart-download.png` | 2 | `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-chart-menu.png` | 2 | `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-expand-all.png` | 2 | `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-minimize-all.png` | 2 | `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-tab-current.png` | 2 | `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-tab-history.png` | 2 | `Monitor/HWSensor`, `Monitor/Utilization` |
| `icon-detail.png` | 2 | `Monitor/Redfish`, `Monitor/StorageOverview` |
| `icon-report.png` | 2 | `Report/HardwareReportMgm`, `Report/SoftwareReportMgm` |
| `icon-search-mode.png` | 2 | `Report/HardwareReportMgm`, `Report/SoftwareReportMgm` |

Note: 24 of the 29 groups were byte-identical copies (pure duplicates); 5 groups
(`icon-delete`, `icon-list`, `icon-expand`, `icon-edit`, `icon-account-info`) have
different content. The identical copies can be deduplicated during the formal rename.

## Pending: formal rename per STYLE.md

1. Build a source image -> Markdown reference list.
2. Derive Category and Page from `SUMMARY.md` and the Markdown filename.
3. Rename all 783 images to `<Category>_<Page>_<Component>[_<State>][_<Seq>].png`.
4. Deduplicate the 24 identical-content groups (keep one, update references).
5. Upload renamed assets to the image repository, update Markdown to CDN URLs, and verify rendering.
6. Confirm the merged image directory has no duplicate filenames before using PicGo.