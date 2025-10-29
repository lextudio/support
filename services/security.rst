Microsoft Security Product Line Service
=======================================

This offering is narrowly focused on helping you deploy, tune, and operationalize
the Microsoft Security product stack. It intentionally excludes general
application / supply chain security and custom software review so that we can
deliver fast, opinionated guidance where Microsoft-native capabilities matter most.

In-Scope Product Families
-------------------------
* Microsoft Defender XDR (Defender for Endpoint, Identity / Entra ID Protection,
  Office 365, Cloud Apps, Server, Cloud, and Vulnerability Management)
* Microsoft Sentinel (log source onboarding, analytics rules, automation / SOAR playbooks, workbooks)
* Microsoft Entra ID (Conditional Access, Identity Protection policies, PIM role strategy)
* Microsoft Purview (DLP policies, sensitivity labels, insider risk – high‑level configuration & rollout approach)
* Defender for Cloud / CSPM baseline policy alignment & recommendations

Core Focus Areas
----------------
* Licensing & feature alignment: matching SKU capabilities to security objectives
* Secure deployment sequencing: phased enablement plans to avoid user disruption
* Data connector & telemetry onboarding strategy (Sentinel + Defender workloads)
* Analytics & detection tuning (rule selection, noise reduction, enrichment ideas)
* Incident triage workflows (Defender portal & Sentinel integration, role delineation)
* Conditional Access & Zero Trust access posture review (gap & risk summary)
* Role Based Access (RBAC / PIM) rationalization for least privilege operations
* Automation & playbooks (Sentinel Logic Apps: containment, notification, enrichment)
* Exposure / vulnerability signal interpretation & operational cadence
* High‑level data loss protection (Purview labeling & DLP policy rollout staging)

Explicit Exclusions
-------------------
The following are out of scope for this service (may require a broader security or
application assessment engagement):
* Custom application code review or secure SDLC pipeline design
* Non-Microsoft SIEM / EDR / CASB tooling
* Deep forensics or incident response beyond triage playbook design
* Red / purple teaming execution (we can recommend, but not perform here)
* Detailed SBOM / supply chain attestations & build hardening
* Source code or dependency vulnerability remediation services

Engagement Flow
---------------
1. Scoping Call – confirm product SKUs in use, current deployment stage, target outcomes.
2. Baseline Review – gather current portal configuration exports, role assignments, key policies, data connector list.
3. Working Sessions – themed deep dives (e.g., Sentinel analytics, Conditional Access tuning, Defender attack surface reduction).
4. Prioritized Roadmap – 30/60/90 day actionable plan with impact & effort tags.
5. (Optional) Playbook & Rule Tuning Support – iterative refinement over agreed window.
6. Closeout – summary report + recommended operational metrics (coverage, alert fidelity, MTTA/MTTR tracking pointers).

Deliverables
------------
* Deployment & maturity score snapshot (qualitative + quick win table)
* Prioritized roadmap (CSV / table suitable for backlog import)
* Sentinel data connector & analytics gap matrix
* Conditional Access & Identity Protection recommendation set
* RBAC / PIM rationalization summary
* Optional: Sample Logic App / KQL rule snippets (illustrative, not full library)

Optional Add‑Ons
----------------
* Monthly advisory checkpoint (roadmap progress & new feature review)
* Targeted KQL analytics / hunting query workshop
* Incident simulation tabletop (Sentinel + Defender workflow validation)

Requesting the Service
----------------------
Contact ``support@lextudio.com`` with a short description of your current
Microsoft Security deployment state and primary objectives (e.g. "reduce alert
noise", "accelerate Sentinel onboarding", "improve Conditional Access"). We'll
respond with a scoping questionnaire and scheduling options.

Related Services
----------------
* :doc:`/services/consulting`
* :doc:`/services/training`
* :doc:`/services/patching`

Last Updated: 2025-10-22
