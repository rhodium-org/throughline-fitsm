# FitSM-1 — Requirements — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates it in
CI. The prose headings are hand-owned — everything between `tl:*` markers is injected from
the YAML items, so the published spec can never drift from the graph.

This source expresses **FitSM-1 "Requirements" (version 3.0.1)**, the normative part of the
FitSM lightweight IT service management standard: each general-requirement category and each
service management process is a `user_requirement`, and each individual FitSM-1 requirement
is a `system_requirement` that `implements` it. The FitSM-1 requirement identifier lives in
`attrs.source_ref` (e.g. `FitSM-1 PR13.4`). The throughline UIDs are this source's own and
immutable — a consumer cites an item as `fitsm:SR-0072`, never by a FitSM requirement number.

FitSM is published under the Creative Commons Attribution 4.0 International License; see
`NOTICE`.

Contains
<!-- tl:count type == 'user_requirement' -->
21
<!-- tl:end --> categories/processes and
<!-- tl:count type == 'system_requirement' -->
82
<!-- tl:end --> requirements.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — IT services can be managed through a lightweight service management system** — `intent`, status `approved`

> FitSM exists so that an organisation delivering IT services can run an effective but lightweight service management system (SMS) — a defined set of general management practices and service management processes that is practical, consistent and sufficient — rather than adopting a heavyweight framework.

**source_ref**: FitSM-1
<!-- tl:end -->

## 3. General requirements for a service management system

### GR1 Top Management Commitment & Accountability (MCA)

<!-- tl:item UR-0001 -->
**UR-0001 — Top Management Commitment & Accountability (MCA)** — `user_requirement`, status `approved`

> General SMS requirements establishing that a member of top management owns and is accountable for the service management system.

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR1
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR1.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | approved | Assign an accountable SMS owner |
| SR-0002 | system_requirement | approved | Define and communicate a service management policy |
| SR-0003 | system_requirement | approved | Conduct management reviews |
<!-- tl:end -->


### GR2 Documentation (DOC)

<!-- tl:item UR-0002 -->
**UR-0002 — Documentation (DOC)** — `user_requirement`, status `approved`

> General SMS requirements for documenting and controlling the key elements, process definitions and records of the service management system.

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR2
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR2.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0004 | system_requirement | approved | Document the key elements of the SMS |
| SR-0005 | system_requirement | approved | Document definitions of all processes |
| SR-0006 | system_requirement | approved | Document process outputs and record key activities |
| SR-0007 | system_requirement | approved | Control documented information |
<!-- tl:end -->


### GR3 Scope & Stakeholders of IT Service Management (SCS)

<!-- tl:item UR-0003 -->
**UR-0003 — Scope & Stakeholders of IT Service Management (SCS)** — `user_requirement`, status `approved`

> General SMS requirements for identifying stakeholders and defining the scope of the service management system.

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR3
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR3.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0008 | system_requirement | approved | Identify and analyse stakeholders |
| SR-0009 | system_requirement | approved | Define the scope of the SMS |
<!-- tl:end -->


### GR4 Planning IT Service Management (PLAN)

<!-- tl:item UR-0004 -->
**UR-0004 — Planning IT Service Management (PLAN)** — `user_requirement`, status `approved`

> General SMS requirements for planning the service management system and its processes (the PLAN phase).

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR4
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR4.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0010 | system_requirement | approved | Create and maintain a service management plan |
| SR-0011 | system_requirement | approved | Align process-specific plans |
<!-- tl:end -->


### GR5 Implementing IT Service Management (DO)

<!-- tl:item UR-0005 -->
**UR-0005 — Implementing IT Service Management (DO)** — `user_requirement`, status `approved`

> General SMS requirements for implementing the plan and following the defined processes in practice (the DO phase).

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR5
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR5.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0012 | system_requirement | approved | Implement the service management plan |
| SR-0013 | system_requirement | approved | Follow and enforce the defined processes |
<!-- tl:end -->


### GR6 Monitoring & Reviewing IT Service Management (CHECK)

<!-- tl:item UR-0006 -->
**UR-0006 — Monitoring & Reviewing IT Service Management (CHECK)** — `user_requirement`, status `approved`

> General SMS requirements for measuring, assessing and auditing the effectiveness of the service management system (the CHECK phase).

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR6
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR6.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0014 | system_requirement | approved | Measure effectiveness against KPIs |
| SR-0015 | system_requirement | approved | Assess or audit the SMS at planned intervals |
<!-- tl:end -->


### GR7 Continually Improving Service Management (ACT)

<!-- tl:item UR-0007 -->
**UR-0007 — Continually Improving Service Management (ACT)** — `user_requirement`, status `approved`

> General SMS requirements for correcting nonconformities and continually improving the service management system (the ACT phase).

*Derives from:* INT-0001

**source_ref**: FitSM-1 GR7
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 GR7.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0016 | system_requirement | approved | Address nonconformities and deviations |
| SR-0017 | system_requirement | approved | Subject the SMS to continual improvement |
<!-- tl:end -->


## 4. Process-specific requirements

### PR1 Service Portfolio Management (SPM)

<!-- tl:item UR-0008 -->
**UR-0008 — Service Portfolio Management (SPM)** — `user_requirement`, status `approved`

> The process that maintains the service portfolio and manages services through their lifecycle.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR1
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR1.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0018 | system_requirement | approved | Maintain a service portfolio |
| SR-0019 | system_requirement | approved | Evaluate proposals for new or changed services |
| SR-0020 | system_requirement | approved | Manage the service lifecycle |
| SR-0021 | system_requirement | approved | Identify suppliers involved in each service |
<!-- tl:end -->


### PR2 Service Level Management (SLM)

<!-- tl:item UR-0009 -->
**UR-0009 — Service Level Management (SLM)** — `user_requirement`, status `approved`

> The process that maintains the service catalogue and agrees and reviews service levels with customers and supporting parties.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR2
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR2.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0022 | system_requirement | approved | Maintain a service catalogue |
| SR-0023 | system_requirement | approved | Agree and review SLAs |
| SR-0024 | system_requirement | approved | Evaluate service performance against SLA targets |
| SR-0025 | system_requirement | approved | Agree and review UAs and OLAs |
| SR-0026 | system_requirement | approved | Evaluate supporting performance against UA/OLA targets |
<!-- tl:end -->


### PR3 Service Reporting Management (SRM)

<!-- tl:item UR-0010 -->
**UR-0010 — Service Reporting Management (SRM)** — `user_requirement`, status `approved`

> The process that identifies, specifies and produces service and process reports for their recipients.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR3
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR3.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0027 | system_requirement | approved | Identify required reports |
| SR-0028 | system_requirement | approved | Agree and specify reports |
| SR-0029 | system_requirement | approved | Produce and deliver reports |
<!-- tl:end -->


### PR4 Service Availability & Continuity Management (SACM)

<!-- tl:item UR-0011 -->
**UR-0011 — Service Availability & Continuity Management (SACM)** — `user_requirement`, status `approved`

> The process that identifies availability and continuity requirements and risks and takes measures to meet them.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR4
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR4.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0030 | system_requirement | approved | Identify availability and continuity requirements |
| SR-0031 | system_requirement | approved | Assess availability and continuity risks |
| SR-0032 | system_requirement | approved | Take measures to meet availability and continuity requirements |
| SR-0033 | system_requirement | approved | Monitor availability |
<!-- tl:end -->


### PR5 Capacity Management (CAPM)

<!-- tl:item UR-0012 -->
**UR-0012 — Capacity Management (CAPM)** — `user_requirement`, status `approved`

> The process that identifies capacity and performance requirements and plans capacity to meet them.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR5
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR5.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0034 | system_requirement | approved | Identify capacity and performance requirements |
| SR-0035 | system_requirement | approved | Identify current capacity and utilisation |
| SR-0036 | system_requirement | approved | Plan future capacity |
| SR-0037 | system_requirement | approved | Analyse performance from capacity monitoring |
<!-- tl:end -->


### PR6 Information Security Management (ISM)

<!-- tl:item UR-0013 -->
**UR-0013 — Information Security Management (ISM)** — `user_requirement`, status `approved`

> The process that identifies information security requirements and risks and implements controls to meet them.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR6
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR6.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0038 | system_requirement | approved | Identify security requirements and define policies |
| SR-0039 | system_requirement | approved | Assess information security risks |
| SR-0040 | system_requirement | approved | Implement information security controls |
| SR-0041 | system_requirement | approved | Handle security events and incidents consistently |
| SR-0042 | system_requirement | approved | Carry out access control consistently |
<!-- tl:end -->


### PR7 Customer Relationship Management (CRM)

<!-- tl:item UR-0014 -->
**UR-0014 — Customer Relationship Management (CRM)** — `user_requirement`, status `approved`

> The process that manages the relationship with service customers, including communication, reviews, complaints and satisfaction.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR7
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR7.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0043 | system_requirement | approved | Identify service customers |
| SR-0044 | system_requirement | approved | Designate a contact for each customer |
| SR-0045 | system_requirement | approved | Establish customer communication channels |
| SR-0046 | system_requirement | approved | Conduct service reviews with customers |
| SR-0047 | system_requirement | approved | Handle customer complaints consistently |
| SR-0048 | system_requirement | approved | Manage customer satisfaction |
<!-- tl:end -->


### PR8 Supplier Relationship Management (SUPPM)

<!-- tl:item UR-0015 -->
**UR-0015 — Supplier Relationship Management (SUPPM)** — `user_requirement`, status `approved`

> The process that manages the relationship with internal and external suppliers, including communication and evaluation.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR8
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR8.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0049 | system_requirement | approved | Identify suppliers |
| SR-0050 | system_requirement | approved | Designate a contact for each supplier |
| SR-0051 | system_requirement | approved | Establish supplier communication channels |
| SR-0052 | system_requirement | approved | Evaluate suppliers |
<!-- tl:end -->


### PR9 Incident & Service Request Management (ISRM)

<!-- tl:item UR-0016 -->
**UR-0016 — Incident & Service Request Management (ISRM)** — `user_requirement`, status `approved`

> The process that registers, resolves, escalates and closes incidents and service requests, including major incidents.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR9
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR9.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0053 | system_requirement | approved | Register, classify and prioritise incidents and requests |
| SR-0054 | system_requirement | approved | Resolve incidents and fulfil requests |
| SR-0055 | system_requirement | approved | Escalate incidents and requests consistently |
| SR-0056 | system_requirement | approved | Keep customers and users informed |
| SR-0057 | system_requirement | approved | Close incidents and requests consistently |
| SR-0058 | system_requirement | approved | Identify and handle major incidents |
<!-- tl:end -->


### PR10 Problem Management (PM)

<!-- tl:item UR-0017 -->
**UR-0017 — Problem Management (PM)** — `user_requirement`, status `approved`

> The process that identifies, investigates and manages problems and known errors behind recurring incidents.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR10
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR10.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0059 | system_requirement | approved | Identify and register problems |
| SR-0060 | system_requirement | approved | Investigate problems |
| SR-0061 | system_requirement | approved | Register known errors |
| SR-0062 | system_requirement | approved | Maintain known-error information |
<!-- tl:end -->


### PR11 Configuration Management (CONFM)

<!-- tl:item UR-0018 -->
**UR-0018 — Configuration Management (CONFM)** — `user_requirement`, status `approved`

> The process that defines the scope of configuration management and maintains configuration information about CIs in a CMDB.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR11
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR11.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0063 | system_requirement | approved | Define the scope of configuration management |
| SR-0064 | system_requirement | approved | Set a sufficient level of configuration detail |
| SR-0065 | system_requirement | approved | Maintain CI information in a CMDB |
| SR-0066 | system_requirement | approved | Control CIs and track changes |
| SR-0067 | system_requirement | approved | Verify CMDB information |
<!-- tl:end -->


### PR12 Change Management (CHM)

<!-- tl:item UR-0019 -->
**UR-0019 — Change Management (CHM)** — `user_requirement`, status `approved`

> The process that registers, classifies, assesses, approves and reviews changes and maintains a change schedule.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR12
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR12.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0068 | system_requirement | approved | Register and classify changes |
| SR-0069 | system_requirement | approved | Define steps for each type of change |
| SR-0070 | system_requirement | approved | Assess changes |
| SR-0071 | system_requirement | approved | Approve changes |
| SR-0072 | system_requirement | approved | Review and close changes |
| SR-0073 | system_requirement | approved | Maintain a schedule of changes |
<!-- tl:end -->


### PR13 Release & Deployment Management (RDM)

<!-- tl:item UR-0020 -->
**UR-0020 — Release & Deployment Management (RDM)** — `user_requirement`, status `approved`

> The process that defines release and deployment strategies and builds, tests, deploys and evaluates releases.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR13
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR13.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0074 | system_requirement | approved | Define release and deployment strategies |
| SR-0075 | system_requirement | approved | Define criteria for including changes in a release |
| SR-0076 | system_requirement | approved | Plan deployment with acceptance criteria |
| SR-0077 | system_requirement | approved | Build, test and evaluate releases before deployment |
| SR-0078 | system_requirement | approved | Prepare for unsuccessful deployment |
| SR-0079 | system_requirement | approved | Evaluate deployment success or failure |
<!-- tl:end -->


### PR14 Continual Service Improvement Management (CSI)

<!-- tl:item UR-0021 -->
**UR-0021 — Continual Service Improvement Management (CSI)** — `user_requirement`, status `approved`

> The process that identifies, assesses and controls the implementation of improvements to services and processes.

*Derives from:* INT-0001

**source_ref**: FitSM-1 PR14
<!-- tl:end -->

<!-- tl:table type == 'system_requirement' and attrs.get('source_ref').startswith('FitSM-1 PR14.') -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0080 | system_requirement | approved | Identify and register improvement opportunities |
| SR-0081 | system_requirement | approved | Assess improvement opportunities |
| SR-0082 | system_requirement | approved | Control the implementation of improvements |
<!-- tl:end -->

