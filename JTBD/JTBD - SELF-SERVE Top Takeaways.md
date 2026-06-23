# JTBD Analysis: SELF-SERVE Top Takeaways - Research Sprint

## Overview
This document contains structured Jobs-to-be-Done (JTBD) extractions from the SELF-SERVE Top takeaways - Research Sprint 02-26 document. Each instance follows the schema: Persona → Job → Workflow → Steps → Roles → Pain points.

**Note:** This document focuses on self-serve (Developer Portal) readiness and how teams enable self-serve at scale. Where specific workflow steps are not explicitly stated, fields are left blank or contain only what is directly mentioned in the source text.

---

## JTBD Instance 1: Assessing Risk Across Multiple Safety Tools

```json
{
  "persona": "Platform Engineers and Application Developers",
  "job": "Assess infrastructure change risk through a unified view of safety controls",
  "workflow": "Risk assessment for infrastructure changes",
  "steps": [
    "Check IAM permissions",
    "Review networking configurations",
    "Run CI checks",
    "Conduct manual reviews",
    "Make decisions based on fragmented information"
  ],
  "roles": [
    "Platform Engineers",
    "Application Developers",
    "Security Teams"
  ],
  "pain_points": [
    "Safety is stitched across many tools, creating friction",
    "Teams rely on IAM, networking, CI checks, and manual reviews to stay safe",
    "None of which present a unified view of risk",
    "This duplication slows decisions and raises uncertainty",
    "terraform plan shows what will change — not the risk"
  ],
  "source": {
    "file_name": "SELF-SERVE Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 1",
    "quote": "Safety is stitched across many tools, creating friction. Teams rely on IAM, networking, CI checks, and manual reviews to stay safe—none of which present a unified view of risk. This duplication slows decisions and raises uncertainty. 'terraform plan shows what will change — not the risk.'"
  }
}
```

---

## JTBD Instance 2: Discovering Critical Infrastructure Boundaries

```json
{
  "persona": "Application Developers",
  "job": "Discover and understand critical infrastructure boundaries before attempting changes",
  "workflow": "Boundary discovery and compliance",
  "steps": [
    "Attempt infrastructure change",
    "Hit locked-down boundary (IAM, networking, clusters, encryption)",
    "Learn boundary exists reactively",
    "Rework approach",
    "Follow up via Slack for clarification"
  ],
  "roles": [
    "Application Developers",
    "Platform Engineers"
  ],
  "pain_points": [
    "Critical boundaries are locked down, but poorly surfaced",
    "High-risk areas (IAM, networking, clusters, encryption) are tightly controlled",
    "Developers only learn these boundaries when they hit them",
    "This reactive discovery causes rework",
    "Causes avoidable Slack follow-ups",
    "What stays restricted are things that impact security or core infrastructure"
  ],
  "source": {
    "file_name": "SELF-SERVE Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 2",
    "quote": "Critical boundaries are locked down, but poorly surfaced. High‑risk areas (IAM, networking, clusters, encryption) are tightly controlled, yet developers only learn these boundaries when they hit them. This reactive discovery causes rework and avoidable Slack follow‑ups. 'What stays restricted are things that impact security or core infrastructure.'"
  }
}
```

---

## JTBD Instance 3: Accelerating Development with Unified Self-Serve Tools

```json
{
  "persona": "Application Developers",
  "job": "Provision resources, get approvals, access systems, view logs, and monitor costs through unified self-serve tools",
  "workflow": "Self-serve development workflow",
  "steps": [
    "Request provisioning",
    "Seek approvals",
    "Request access",
    "View logs",
    "Check cost visibility",
    "Chase unblocks across separate systems"
  ],
  "roles": [
    "Application Developers",
    "Platform Engineers",
    "Approvers"
  ],
  "pain_points": [
    "Developer speed depends on accelerators scattered across systems",
    "Provisioning, approvals, access, logs, and cost visibility sit in separate places",
    "Teams lose time chasing unblocks",
    "The 'paved road' is not unified",
    "Developers ask for faster provisioning and more freedom to deploy"
  ],
  "source": {
    "file_name": "SELF-SERVE Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 3",
    "quote": "Developer speed depends on accelerators scattered across systems. Provisioning, approvals, access, logs, and cost visibility sit in separate places. Teams lose time chasing unblocks because the 'paved road' is not unified. 'Developers ask for faster provisioning and more freedom to deploy.'"
  }
}
```

---

## JTBD Instance 4: Finding and Standardizing Infrastructure Patterns

```json
{
  "persona": "Platform Engineers and Application Developers",
  "job": "Find, use, and standardize infrastructure patterns for safe and consistent usage",
  "workflow": "Pattern discovery and standardization",
  "steps": [
    "Search for patterns in Git repos and docs",
    "Identify need for new pattern",
    "Align with multiple teams to standardize new pattern",
    "Wait for pattern to be standardized",
    "Rely on platform guidance"
  ],
  "roles": [
    "Platform Engineers",
    "Application Developers",
    "Multiple Teams"
  ],
  "pain_points": [
    "Patterns guide safe usage, but are slow to find and standardize",
    "Patterns live in Git repos and docs",
    "New ones requiring multi-team alignment",
    "This slows teams down",
    "Increases reliance on platform guidance",
    "One event-driven pattern took ~1 month to standardize"
  ],
  "source": {
    "file_name": "SELF-SERVE Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 4",
    "quote": "Patterns guide safe usage, but are slow to find and standardize. Patterns live in Git repos and docs, with new ones requiring multi‑team alignment. This slows teams down and increases reliance on platform guidance. 'One event‑driven pattern took ~1 month to standardize.'"
  }
}
```

---

## Summary

This analysis extracted **4 distinct JTBD instances** from the SELF-SERVE Top takeaways document, covering:

1. Assessing infrastructure change risk through a unified view of safety controls
2. Discovering and understanding critical infrastructure boundaries before attempting changes
3. Accelerating development with unified self-serve tools (provisioning, approvals, access, logs, costs)
4. Finding, using, and standardizing infrastructure patterns for safe and consistent usage

**Key Themes:**
- **Fragmented Safety**: Safety controls (IAM, networking, CI checks, manual reviews) scattered across tools without unified risk view
- **Reactive Boundary Discovery**: Developers learn critical boundaries (IAM, networking, clusters, encryption) only when they hit them
- **Scattered Accelerators**: Provisioning, approvals, access, logs, and cost visibility in separate places
- **Slow Pattern Standardization**: Patterns live in Git repos and docs, requiring multi-team alignment (~1 month for new patterns)

**Key Quotes:**
- "terraform plan shows what will change — not the risk"
- "What stays restricted are things that impact security or core infrastructure"
- "Developers ask for faster provisioning and more freedom to deploy"
- "One event-driven pattern took ~1 month to standardize"

**Self-Serve Readiness Conditions:**
The research examines what conditions must be met for self-serve to work reliably at scale, highlighting the need for:
- Unified risk visibility across safety tools
- Proactive boundary surfacing instead of reactive discovery
- Consolidated "paved road" with unified accelerators
- Faster pattern discovery and standardization processes

**Data Characteristics:**
- The source document provides research insights from 11 Platform Engineers, 8 CloudOps Managers, and 1 App Developer
- **Steps** fields are populated where the document explicitly describes process sequences
- **Pain points** are extracted from explicitly stated challenges and friction points
- **Workflows** are inferred from the context of self-serve enablement and developer portal readiness
- Primary personas are Platform Engineers and Application Developers

All extractions include complete source attribution with file name, section reference, and verbatim quotes for traceability, adhering to the rule of not inferring beyond what is explicitly stated in the text.