---
doc_type: legacy-stub
last-verified: 2026-06-17
owner: netstack-platform
---

# netbox — repository memory (legacy)

Maintenance-only StackStorm pack for NetBox REST actions (device details, journal
entries, status updates) consumed by wifinity_network_automation workflows.

## Replacement

- Temporal activities: `netauto-workflows/activities/netbox/` (get device record,
  config, context, journal entry, automation status)
- Inventory UI and plugins: **wif-netbox** → `AGENTS.md`
- Hub: `netauto-dev-netstack/docs/netstack/migration-state.md`
