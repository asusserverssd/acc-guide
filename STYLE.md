# Documentation Asset Style Guide

This document is the single source of truth for published image naming. Mapping and
migration records belong in [MAPPING.md](./MAPPING.md).

## Image filename convention

```text
<Category>_<Page>_<Component>[_<State>][_<Seq>].png
```

All fields use PascalCase, except `Seq`, which is a two-digit number.

| Field | Required | Rule | Example |
|---|---:|---|---|
| `Category` | Yes | Exact enclosing `##` heading from `SUMMARY.md` | `Account` |
| `Page` | Yes | Exact Markdown basename without `.md` | `RolePrivMgm` |
| `Component` | Yes | Controlled UI component name | `CreateRoleModal` |
| `State` | No | Controlled data, operation, or control state | `Error` |
| `Seq` | No | Last-resort uniqueness suffix: `01`, `02`, ... | `02` |

Examples:

```text
Begin_Introduction_Overview.png
Monitor_SystemOverview_ExpandIcon.png
Monitor_SystemOverview_DeviceDetailPanel.png
Account_RolePrivMgm_RoleTable.png
Account_RolePrivMgm_CreateRoleModal.png
Options_ACL_RuleTable_Filtered.png
Options_ACL_CreateRuleModal_Error.png
Report_SWInventoryReport_SearchModeButton.png
```

## Component convention

Use a single controlled component identifier:

```text
[Action][Entity][UIType]
```

`Action` and `Entity` are optional when omitting either still makes the component clear.
`UIType` is required and must be the final word.

| Pattern | Examples |
|---|---|
| `[Entity][UIType]` | `RoleTable`, `DeviceList`, `UtilizationChart` |
| `[Action][Entity][UIType]` | `CreateRoleModal`, `EditProfileForm`, `ExportReportButton` |
| `[Action][UIType]` | `DeleteIcon`, `ExpandButton`, `RefreshMenu` |
| `[Context][UIType]` | `HistoryTab`, `DetailPanel`, `HelpTooltip` |

Do not duplicate concepts already covered by `Category` or `Page`. For example, use
`Account_RolePrivMgm_RoleTable.png`, not
`Account_RolePrivMgm_RolePrivilegeManagementTable.png`.

## Controlled vocabulary

### Actions

Use the following action names. Do not substitute synonyms.

| Intent | Term | Do not use |
|---|---|---|
| Create a record | `Create` | `Add`, `New` |
| Change a record | `Edit` | `Modify` |
| Delete a record | `Delete` | `Remove` |
| Persist changes | `Save` | `Submit`, `Apply` |
| Search records | `Search` | `Find`, `Lookup` |
| Filter records | `Filter` | `Refine` |
| Expand content | `Expand` | `Open` |
| Collapse content | `Collapse` | `Close` |
| Download a file | `Download` | `Export` |
| Export data | `Export` | `Download` |
| Upload a file | `Upload` | `Import` |
| Import data | `Import` | `Upload` |
| Refresh data | `Refresh` | `Reload` |
| Scan resources | `Scan` | — |
| Deploy software or agents | `Deploy` | — |
| Update software or firmware | `Update` | `Upgrade` |
| Confirm an operation | `Confirm` | `Accept` |
| Cancel an operation | `Cancel` | — |

### Entities

Use the product's existing terminology from `SUMMARY.md`, page headings, or the UI. Prefer
these canonical names when applicable:

```text
Account  Role  Privilege  User
Device   Host  VM         Storage  POD  BMC  GPU
Rule     Policy  Profile  Configuration  Threshold
Software Hardware Firmware BIOS Package
Task     Taskset Report   Inventory EventLog
Trigger  Subscription Service
Detail   History SearchMode Filter
```

An entity should contain no more than two concepts, such as `DeviceDetail` or `SearchMode`.
Preserve established uppercase abbreviations, including `ACL`, `BMC`, `BIOS`, `GPU`, `OOB`,
`SMTP`, `SSH`, `SW`, and `VM`.

### UI types

Every `Component` must end with exactly one of these UI types:

| UI type | Use for |
|---|---|
| `Overview` | Landing, summary, or dashboard view |
| `Page` | Complete functional page |
| `Table` | Tabular data |
| `List` | List of items |
| `Tree` | Hierarchical tree |
| `Form` | Data-entry or configuration form |
| `Modal` | Modal dialog |
| `Panel` | Information, filter, or side panel |
| `Card` | Independent information card |
| `Tab` | A named tab |
| `Button` | Clickable action button |
| `Menu` | Action, context, or overflow menu |
| `Dropdown` | Dropdown control |
| `Icon` | Standalone UI icon |
| `Chart` | Data visualization |
| `Tooltip` | Hover help message |
| `Toast` | Transient operation result |
| `Alert` | Persistent warning or message |
| `Popover` | Click-triggered floating information |
| `Progress` | Progress indicator |
| `Pagination` | Pagination control |
| `EmptyState` | No-data or initial state |
| `Spinner` | Loading indicator |

Use `Modal`, not `Dialog`, `Popup`, or `Window`; use `Table`, not `Grid` or `DataTable`;
and use `List`, not `Listing` or `Items`.

### States

Use a state only when the screenshot differs because of a data, operation, or control state:

```text
Empty  Loading  Filtered  Selected  Disabled  Success  Error  Warning
```

Examples:

```text
Options_ACL_RuleTable_Empty.png
Options_ACL_RuleTable_Filtered.png
Account_RolePrivMgm_CreateRoleModal_Error.png
Report_SWInventoryReport_ExportReportButton_Disabled.png
```

Use a distinct component rather than a state where the UI element itself changes. For example,
use `CurrentTab` and `HistoryTab`, not `DataTab_Current` and `DataTab_History`.

### Sequence

Use `Seq` only after confirming that a semantic `Component` or `State` cannot distinguish the
images. It is the final uniqueness safeguard, not an operation-step label.

```text
Options_ACL_CreateRuleModal_01.png
Options_ACL_CreateRuleModal_02.png
```

Never use `1`, `v2`, `new`, or `final`. Do not renumber an already published sequence because
released jsDelivr URLs must remain stable.

## Length and prohibited names

- Limit the filename without its extension to 100 characters.
- Prefer one to three semantic terms before the UI type.
- Do not use generic component names: `Image`, `Screenshot`, `Screen`, `New`, `Final`, or
  `Misc`.
- Before introducing a new action, entity, UI type, or state, add it to this document and use
  the same name consistently thereafter.
