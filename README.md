# Hi, I'm mell0wx

Cybersecurity practitioner focused on **incident response, threat hunting, DFIR, cloud incident response, and supporting detection engineering**.

I build evidence-driven workflows that move from telemetry to investigation: collect the right artifacts, reconstruct timelines, test hypotheses, document findings, and turn lessons learned into reusable detections and response guidance.

## Current focus

- **Incident response & threat hunting**
- **Windows and identity investigations**
- **AWS / Cloud IR**
- **DFIR workflows and timeline reconstruction**
- **Detection engineering as a supporting capability**
- **Security automation that stays bounded, reviewable, and evidence-backed**

## Featured security work

### [cybersecurity-playbook](https://github.com/egrexsec/cybersecurity-playbook)

My primary security portfolio and investigation knowledge base.

It includes:

- investigation workflows across endpoint, identity, network, and cloud
- **15 historically live-validated Windows scenarios**
- **15 canonical Sigma rules**
- **79 positive/negative fixtures**
- threat-hunting hypotheses and validated detection content
- DFIR methods and evidence-handling workflows
- AWS CloudTrail investigation notes and case studies
- generated Splunk and Elastic queries
- sanitized validation evidence and case documentation

Start with:

- **[Flaws2.cloud Defender — AWS Cloud IR case study](https://github.com/egrexsec/cybersecurity-playbook/tree/main/case-studies/aws/flaws2-defender)**
- **[Validated PowerShell Detection Lifecycle v1](https://github.com/egrexsec/cybersecurity-playbook/tree/main/detections/packs/validated-powershell-lifecycle-v1)**
- **[Investigation portfolio](https://github.com/egrexsec/cybersecurity-playbook/tree/main/investigations)**
- **[DFIR capability library](https://github.com/egrexsec/cybersecurity-playbook/tree/main/dfir)**

### Historical Mayuri validation work

The Mayuri lab was decommissioned in October 2026 after serving as the environment for live Windows detection and purple-team validation.

The infrastructure is no longer active, but its sanitized validation evidence and technical history remain preserved in the portfolio rather than being presented as current infrastructure.

## How I approach investigations

```text
question / alert
      ↓
scope and hypotheses
      ↓
collect evidence
      ↓
build timeline
      ↓
correlate endpoint / identity / cloud activity
      ↓
determine findings and root cause
      ↓
containment / remediation guidance
      ↓
detection and visibility improvements
```

The goal is not just to produce an alert or solve a lab. It is to understand **what happened, how the evidence supports it, what remains uncertain, and what should improve afterward**.

## Cloud IR

Current AWS work includes:

- AWS CLI investigation workflows
- CloudTrail retrieval from S3
- PowerShell + `jq` analysis
- timeline construction
- IAM / STS pivots
- credential-abuse investigation
- AWS resource-policy review
- understanding when Athena becomes the better query model at scale

I am continuing to deepen cloud investigation and DFIR skills through bounded labs, public datasets, and structured case studies.

## Other engineering work

### [X32/M32 RouteView](https://github.com/egrexsec/x32-m32-routeview)

A utility that turns Behringer X32 / Midas M32 routing data into a reviewable operational view for troubleshooting and handoff.

## What I optimize for

- evidence before conclusions
- timelines and correlation over isolated alerts
- detections backed by positive and negative testing
- public artifacts that demonstrate the work without exposing sensitive details
- automation with explicit safety boundaries and truthful failure states
- documentation that another analyst can actually use

## Connect

- Website: [mell0wx.tech](https://mell0wx.tech)
- GitHub: [@egrexsec](https://github.com/egrexsec)
