# Hi, I'm mell0wx

Cybersecurity practitioner focused on **incident response, threat hunting, DFIR, cloud incident response, and supporting detection engineering**.

My work centers on turning telemetry into defensible investigations: scoping activity, collecting the right evidence, reconstructing timelines, testing hypotheses, documenting findings, and feeding lessons learned back into detection and response.

## Current focus

- **Incident response & threat hunting**
- **Windows and identity investigations**
- **AWS / Cloud IR**
- **DFIR workflows and timeline reconstruction**
- **Detection engineering as a supporting capability**
- **Security automation with clear validation and safety boundaries**

## Featured security work

### [cybersecurity-playbook](https://github.com/mell0wx/cybersecurity-playbook)

My primary public security portfolio and investigation knowledge base.

It includes:

- endpoint, identity, network, and cloud investigation workflows
- Sigma detections with positive and negative validation material
- threat-hunting hypotheses and detection-development work
- DFIR methods and evidence-handling workflows
- AWS CloudTrail investigation notes and case studies
- generated Splunk and Elastic queries
- sanitized validation evidence and technical documentation

Recommended starting points:

- **[Flaws2.cloud Defender — AWS Cloud IR case study](https://github.com/mell0wx/cybersecurity-playbook/tree/main/case-studies/aws/flaws2-defender)**
- **[Validated PowerShell Detection Lifecycle](https://github.com/mell0wx/cybersecurity-playbook/tree/main/detections/packs/validated-powershell-lifecycle-v1)**
- **[Investigation portfolio](https://github.com/mell0wx/cybersecurity-playbook/tree/main/investigations)**
- **[DFIR capability library](https://github.com/mell0wx/cybersecurity-playbook/tree/main/dfir)**

### Historical Mayuri validation work

Mayuri was a Windows-focused lab used for detection validation and purple-team exercises before being decommissioned.

The infrastructure is no longer active. Sanitized evidence and technical history are preserved in the cybersecurity playbook as historical validation material rather than presented as current infrastructure.

## Investigation approach

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

The goal is to understand **what happened, what the evidence supports, what remains uncertain, and what should improve afterward**.

## Cloud IR

Current AWS-focused work includes:

- AWS CLI investigation workflows
- CloudTrail retrieval and analysis
- PowerShell and `jq` workflows
- timeline construction
- IAM / STS pivots
- credential-abuse investigation
- AWS resource-policy review
- Athena-based CloudTrail analysis for larger datasets

I continue developing cloud investigation and DFIR skills through bounded labs, public datasets, and structured case studies rather than maintaining a standing cloud lab.

## Other engineering work

### [X32/M32 RouteView](https://github.com/mell0wx/x32-m32-routeview)

A browser-based utility that turns Behringer X32 / Midas M32 scene files into readable routing documentation and production handoff guides.

It reflects a broader interest in building practical tools for real operational problems outside of cybersecurity.

## Principles

- evidence before conclusions
- timelines and correlation over isolated alerts
- detections backed by positive and negative testing
- public artifacts that demonstrate work without exposing sensitive details
- automation with explicit boundaries and truthful failure states
- documentation another analyst can actually use

## Connect

- Website: [mell0wx.tech](https://mell0wx.tech)
- GitHub: [@mell0wx](https://github.com/mell0wx)
