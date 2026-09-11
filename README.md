# Splunk Agent Skills

> [!WARNING]
> These skills are experimental. They are not covered by existing Splunk
> support contracts. Review [Support](SUPPORT.md) before using them.

Skills are agent-facing instructions and tools that help AI agents work with
Splunk. They may use Splunk documentation and product capabilities, but they
are not product features, product code, or replacements for built-in product
experiences.

## Skills

| Skill | Purpose |
| --- | --- |
| [`alerting-and-notable-workflows`](skills/alerting-and-notable-workflows/SKILL.md) | Give cited, advisory-only readiness guidance for Splunk alerts, scheduled-report actions, Enterprise Security finding/notable and risk workflows, delivery, ownership, escalation, and validation. |
| [`app-and-add-on-lifecycle-advisor`](skills/app-and-add-on-lifecycle-advisor/SKILL.md) | Give cited, advisory-only guidance for Splunk app and add-on packaging, compatibility, installation, upgrade, validation, migration, and removal. |
| [`custom-visualization-builder`](skills/custom-visualization-builder/SKILL.md) | Scaffold, build, package, and install a custom visualization into Splunk using the `dashboard-studio-extension` framework. |
| [`dashboard-report-alert-performance-advisor`](skills/dashboard-report-alert-performance-advisor/SKILL.md) | Assess dashboard, report, and alert latency, scheduling, timeout, concurrency, refresh, and data-source fan-out evidence without changing Splunk objects or deployments. |
| [`data-model-and-search-acceleration`](skills/data-model-and-search-acceleration/SKILL.md) | Assess Splunk data-model and report-acceleration readiness, summary health, completeness, applicability, validation, and ownership without making changes. |
| [`data-source-onboarding-advisor`](skills/data-source-onboarding-advisor/SKILL.md) | Orchestrate evidence-bound Splunk data-source intake, supported method selection, metadata and event contracts, acceptance, ownership, and exact implementation handoffs without configuring or changing a deployment. |
| [`deployment-server-and-forwarder-fleet-management`](skills/deployment-server-and-forwarder-fleet-management/SKILL.md) | Explain, plan, and diagnose Splunk Enterprise Deployment Server and Agent Management fleet behavior from public documentation and sanitized evidence without changing a deployment. |
| [`field-extraction-and-cim-mapping`](skills/field-extraction-and-cim-mapping/SKILL.md) | Author, explain, diagnose, and validate Splunk search-time field extractions and Common Information Model mappings from representative evidence without deploying configuration or changing a Splunk environment. |
| [`forwarder-and-data-ingest-doctor`](skills/forwarder-and-data-ingest-doctor/SKILL.md) | Diagnose Splunk forwarder and data-ingest paths from sanitized, read-only evidence, isolate the earliest pipeline gap, and prepare a safe next check or provider-owned handoff without changing production. |
| [`hec-setup-and-troubleshooting`](skills/hec-setup-and-troubleshooting/SKILL.md) | Set up and validate Splunk HTTP Event Collector from current public documentation, diagnose delivery failures from sanitized evidence, and prepare bounded escalation handoffs without changing production systems. |
| [`incident-diagnosis-specialist`](skills/incident-diagnosis-specialist/SKILL.md) | Diagnose post-triage multi-component Splunk incidents from privacy-reviewed packets with aligned evidence, testable hypotheses, bounded confirmation, validation, ownership, and exact specialist handoffs. |
| [`index-and-storage-management-advisor`](skills/index-and-storage-management-advisor/SKILL.md) | Design and assess Splunk indexes, retention, capacity, storage tiers, bucket lifecycle, and SmartStore without applying changes. |
| [`indexer-cluster-health-and-troubleshooting`](skills/indexer-cluster-health-and-troubleshooting/SKILL.md) | Assess Splunk indexer-cluster membership, factors, bucket and bundle state, rolling readiness, multisite behavior, and SmartStore interactions without changing a deployment. |
| [`ingestion-pipeline-design`](skills/ingestion-pipeline-design/SKILL.md) | Design implementation-ready Splunk ingestion pipelines from known source requirements without configuring, deploying, or mutating them. |
| [`knowledge-object-governance`](skills/knowledge-object-governance/SKILL.md) | Give cited public Splunk knowledge-object governance guidance and assess user-authorized inventory, ownership, permissions, naming, lifecycle, lookup, and search-head comparison evidence without changing a deployment. |
| [`license-and-capacity-planning-advisor`](skills/license-and-capacity-planning-advisor/SKILL.md) | Separate Splunk Enterprise entitlement lifecycle issues from measured license-capacity demand and produce a minimum-evidence, assumption-bounded, advisory-only plan grounded in current official Splunk documentation. |
| [`report-authoring-specialist`](skills/report-authoring-specialist/SKILL.md) | Define evidence-bounded scheduled and ad hoc Splunk report contracts, readiness findings, acceptance checks, and owner routes without creating, running, changing, scheduling, or sending reports. |
| [`search-and-dashboard-troubleshooter`](skills/search-and-dashboard-troubleshooter/SKILL.md) | Diagnose broken searches, reports, alerts, dashboards, and their dependencies from supplied evidence; isolate the first unsupported functional stage and define read-only validation and exact adjacent ownership without remediation. |
| [`search-head-cluster-health-and-troubleshooting`](skills/search-head-cluster-health-and-troubleshooting/SKILL.md) | Assess Splunk Search Head Cluster captaincy, member health, replication, search availability, KV Store, deployer phases, drift, and rolling readiness without changing a deployment. |
| [`search-performance-optimizer`](skills/search-performance-optimizer/SKILL.md) | Diagnose and improve one existing functional Splunk search from supplied SPL and runtime evidence while preserving semantics and separating query, workload, and platform concerns. |
| [`splunk-cloud-admin-copilot`](skills/splunk-cloud-admin-copilot/SKILL.md) | Read Splunk Cloud Platform ACS state, assess maintenance or restart readiness without changing it, and execute one explicitly approved IPv4 CIDR add or remove for one feature-specific IP allowlist through the documented public ACS provider. |
| [`splunk-dashboard-converter`](skills/splunk-dashboard-converter/SKILL.md) | Convert classic Splunk Simple XML dashboards (version 1) into Dashboard Studio (version 2), preserve every SPL query verbatim, and return the Studio JSON definition to the caller. |
| [`splunk-enterprise-administration-advisor`](skills/splunk-enterprise-administration-advisor/SKILL.md) | Read-only Splunk Enterprise administration advisor for routine local user, role, capability, configuration precedence, service ownership, maintenance readiness, and safe validation decisions grounded in current official Splunk documentation and sanitized supplied evidence. |
| [`splunk-health-monitoring-and-diagnostic-collection`](skills/splunk-health-monitoring-and-diagnostic-collection/SKILL.md) | Explain Splunk health-monitoring surfaces, collect the smallest useful evidence, guide privacy-aware diagnostic collection, and turn supplied observations into a bounded diagnostic packet without changing a system. |
| [`splunk-identity-saml-readiness-advisor`](skills/splunk-identity-saml-readiness-advisor/SKILL.md) | Research current public Splunk sources and use optional existing-auth read-only stack evidence to diagnose identity, SAML, LDAP, role, capability, mapping, login, and access-readiness problems without changing configuration or handling credentials. |
| [`splunk-product-question-navigator`](skills/splunk-product-question-navigator/SKILL.md) | Research current public Splunk sources to answer general product questions with citations, applicability, and explicit uncertainty or routing. |
| [`splunk-search`](skills/splunk-search/SKILL.md) | Run bounded, read-only Splunk SPL searches through `splunkctl` and return compact, evidence-backed results without exposing credentials or flooding context. |
| [`splunk-setup-page-builder`](skills/splunk-setup-page-builder/SKILL.md) | Build a certification-compliant first-run setup page for a Splunk app or add-on using the configurations REST endpoint and storage/passwords, avoiding the deprecated setup.xml mechanism. |
| [`upgrade-and-security-readiness-router`](skills/upgrade-and-security-readiness-router/SKILL.md) | Classify Splunk version-change, advisory, vulnerability, compliance, and post-change incident requests and return exact non-mutating handoffs. |
| [`upgrade-and-vulnerability-readiness-advisor`](skills/upgrade-and-vulnerability-readiness-advisor/SKILL.md) | Assess cited, evidence-labeled Splunk Enterprise and Splunk Cloud version, maintenance, and security-patch readiness without executing the change. |
| [`upgrade-planning-and-execution-readiness`](skills/upgrade-planning-and-execution-readiness/SKILL.md) | Build cited, evidence-labeled Splunk Enterprise upgrade plans and Splunk Cloud support-assisted version-change readiness plans without performing or approving an upgrade. |
| [`vulnerability-remediation-and-compliance-readiness`](skills/vulnerability-remediation-and-compliance-readiness/SKILL.md) | Assess Splunk vulnerability findings, remediation or exception evidence, compliance readiness, and documented vulnerability-management surfaces without changing a deployment or compliance state. |


Each skill is self-contained under `skills/`.

## Install and use

This repository uses the `skills/<name>/SKILL.md` layout expected by
compatible AI coding agents.

Available skill IDs:

- `alerting-and-notable-workflows`
- `app-and-add-on-lifecycle-advisor`
- `custom-visualization-builder`
- `dashboard-report-alert-performance-advisor`
- `data-model-and-search-acceleration`
- `data-source-onboarding-advisor`
- `deployment-server-and-forwarder-fleet-management`
- `field-extraction-and-cim-mapping`
- `forwarder-and-data-ingest-doctor`
- `hec-setup-and-troubleshooting`
- `incident-diagnosis-specialist`
- `index-and-storage-management-advisor`
- `indexer-cluster-health-and-troubleshooting`
- `ingestion-pipeline-design`
- `knowledge-object-governance`
- `license-and-capacity-planning-advisor`
- `report-authoring-specialist`
- `search-and-dashboard-troubleshooter`
- `search-head-cluster-health-and-troubleshooting`
- `search-performance-optimizer`
- `splunk-cloud-admin-copilot`
- `splunk-dashboard-converter`
- `splunk-enterprise-administration-advisor`
- `splunk-health-monitoring-and-diagnostic-collection`
- `splunk-identity-saml-readiness-advisor`
- `splunk-product-question-navigator`
- `splunk-search`
- `splunk-setup-page-builder`
- `upgrade-and-security-readiness-router`
- `upgrade-and-vulnerability-readiness-advisor`
- `upgrade-planning-and-execution-readiness`
- `vulnerability-remediation-and-compliance-readiness`

List the skills before installing:

```sh
npx skills add splunk/splunk-agent-skills --list
```

Run one of these commands from a project root to copy all 32 skills for the
selected agent:

```sh
npx skills add splunk/splunk-agent-skills --skill '*' --agent claude-code --copy --yes
npx skills add splunk/splunk-agent-skills --skill '*' --agent codex --copy --yes
npx skills add splunk/splunk-agent-skills --skill '*' --agent cursor --copy --yes
npx skills add splunk/splunk-agent-skills --skill '*' --agent github-copilot --copy --yes
npx skills add splunk/splunk-agent-skills --skill '*' --agent gemini-cli --copy --yes
npx skills add splunk/splunk-agent-skills --skill '*' --agent opencode --copy --yes
```

Project scope is the default. Add `--global` to install into the selected
agent's user-level skills directory instead. To copy only one skill, name it
with `--skill`:

```sh
npx skills add splunk/splunk-agent-skills --skill splunk-search --agent codex --copy --yes
```

For a manual installation, clone or download this repository and copy the
desired directory from `skills/` into the skills directory configured for the
agent. Read the selected `SKILL.md` before use; it defines the prerequisites,
workflow, and safety boundaries for that skill.

The `skills` CLI installs skill directories; it does not install external
executables. The `splunk-cloud-admin-copilot` skill requires the separately
installed `acs` CLI, preconfigured for the exact deployment and environment.
The skill never runs login or setup commands.

`splunkctl` is a separate, optional dependency for this repository and the preferred path for supported Splunk API operations. Install it from https://github.com/splunk/splunkctl when desired. The `splunk-search` skill's live SPL execution path requires `splunkctl`; SPL authoring and explanation remain available without it.

Then use the installed skill through your agent according to its normal skill
invocation workflow.

## Policies

- [Support](SUPPORT.md)
- [Security](SECURITY.md)
- [Apache License 2.0](LICENSE)
