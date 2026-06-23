# JTBD Analysis: INFRASTRUCTURE FRICTIONS Top Takeaways - Research Sprint

## Overview
This document contains structured Jobs-to-be-Done (JTBD) extractions from the INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26 document. Each instance follows the schema: Persona → Job → Workflow → Steps → Roles → Pain points.

**Note:** This document focuses on common sources of infrastructure friction in modern cloud environments. Where specific workflow steps are not explicitly stated, fields are left blank or contain only what is directly mentioned in the source text.

---

## JTBD Instance 1: Operating Infrastructure Reliably at Scale

```json
{
  "persona": "Platform Engineers, CloudOps Managers, and Application Developers",
  "job": "Operate infrastructure reliably at scale with safe, predictable operations without manual work",
  "workflow": "Infrastructure operations and management",
  "steps": [
    "Connect systems manually (acting as 'human middleware')",
    "Perform manual work to maintain operations"
  ],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers",
    "Application Developers"
  ],
  "pain_points": [
    "Teams have the tools they need, but systems aren't well connected, governed, or owned",
    "Cloud maturity requires safe, predictable operations without manual work, but this remains uneven",
    "Especially problematic in Day 2, hybrid, or multi-cloud environments",
    "Engineers act as 'human middleware' who manually connect systems",
    "Slows teams down and limits scale"
  ],
  "source": {
    "file_name": "INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Introduction",
    "quote": "Teams have the tools they need, but systems aren't well connected, governed, or owned. Cloud maturity requires safe, predictable operations without manual work, but this remains uneven, especially in Day 2, hybrid, or multi-cloud environments. As a result, engineers act as 'human middleware' who manually connect systems, which slows teams down and limits scale."
  }
}
```

---

## JTBD Instance 2: Responding to Incidents with Unified Visibility

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Respond to incidents quickly with unified visibility across all systems",
  "workflow": "Incident response",
  "steps": [
    "Use many tools to view different parts of the system",
    "Manually connect the dots across tools",
    "Rely on knowledge spread across people"
  ],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers",
    "On-call Engineers"
  ],
  "pain_points": [
    "No unified view means slower incident response",
    "Teams use many tools but can't see everything in one place",
    "Each tool shows only part of the system",
    "Teams connect the dots manually",
    "Knowledge is spread across people",
    "Slower response",
    "Harder maintenance",
    "Work can stall if the right person isn't available"
  ],
  "source": {
    "file_name": "INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - No unified view",
    "quote": "No unified view means slower incident response. Teams use many tools but can't see everything in one place. Each tool shows only part of the system, teams connect the dots manually, and knowledge is spread across people. → Result: slower response, harder maintenance, and work can stall if the right person isn't available."
  }
}
```

---

## JTBD Instance 3: Implementing Governance Without Slowing Delivery

```json
{
  "persona": "Platform Engineers and Application Developers",
  "job": "Implement governance that doesn't slow down development velocity",
  "workflow": "Governance and approval workflow",
  "steps": [
    "Platform teams enforce rules",
    "Developers try to move fast",
    "Seek approvals from gatekeepers",
    "Wait for approvals to proceed"
  ],
  "roles": [
    "Platform Engineers",
    "Application Developers",
    "Gatekeepers/Approvers"
  ],
  "pain_points": [
    "Governance slows teams because it's not built into workflows",
    "Governance exists but isn't built into daily work",
    "Platform teams enforce rules, while developers try to move fast, creating friction",
    "Responsibilities sit with a few people, so approvals become bottlenecks",
    "Additional approvals required",
    "Slower delivery",
    "Reliance on a few gatekeepers"
  ],
  "source": {
    "file_name": "INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Governance slows teams",
    "quote": "Governance slows teams because it's not built into workflows. Governance exists but isn't built into daily work. Platform teams enforce rules, while developers try to move fast, creating friction. Responsibilities sit with a few people, so approvals become bottlenecks. → Result: additional approvals, slower delivery, and reliance on a few gatekeepers."
  }
}
```

---

## JTBD Instance 4: Managing Infrastructure Lifecycle and Dependencies

```json
{
  "persona": "Platform Engineers",
  "job": "Manage infrastructure lifecycle with clear ownership and visibility into dependencies",
  "workflow": "Infrastructure lifecycle management",
  "steps": [
    "Identify systems that need cleanup or updates",
    "Assess dependencies and potential impact",
    "Either avoid cleanup due to uncertainty or resort to trial and error",
    "Perform manual updates in Day 2",
    "Avoid upgrades due to unclear ownership"
  ],
  "roles": [
    "Platform Engineers",
    "Infrastructure Owners"
  ],
  "pain_points": [
    "Lifecycle debt creates fear-based operations",
    "Teams lack clear ownership and visibility into dependencies",
    "Systems become harder to change and maintain",
    "Platform engineers either avoid cleanup because they're unsure what might break",
    "Or resort to trial and error",
    "In Day 2, updates stay manual",
    "Upgrades are avoided, often due to unclear ownership",
    "Outdated systems pile up",
    "Costs rise",
    "Teams get stuck in a cycle where progress slows"
  ],
  "source": {
    "file_name": "INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Lifecycle debt",
    "quote": "Lifecycle debt creates fear-based operations. Teams lack clear ownership and visibility into dependencies, and systems become harder to change and maintain. Platform engineers either avoid cleanup because they're unsure what might break or resort to trial and error. In Day 2, updates stay manual, and upgrades are avoided, often due to unclear ownership. → Result: outdated systems pile up, costs rise, and teams get stuck in a cycle where progress slows."
  }
}
```

---

## JTBD Instance 5: Standardizing Infrastructure with Golden Paths

```json
{
  "persona": "Platform Engineers and Application Developers",
  "job": "Standardize infrastructure using reusable Golden Paths that are consistently adopted",
  "workflow": "Infrastructure standardization",
  "steps": [
    "Platform teams define reusable 'Golden Paths'",
    "App developers choose whether to use templates",
    "Some follow templates, others use manual or ad hoc setup"
  ],
  "roles": [
    "Platform Engineers",
    "Application Developers"
  ],
  "pain_points": [
    "Standardization exists, but its adoption is inconsistent",
    "Platform teams define reusable 'Golden Paths' to standardize infrastructure",
    "App developers don't always use them",
    "Some follow these templates, while others rely on manual or ad hoc setup",
    "Often due to complexity or a need for speed",
    "Teams also vary in experience and autonomy, which further limits adoption",
    "Inconsistent environments",
    "Unpredictable setup",
    "Best practices don't scale across orgs"
  ],
  "source": {
    "file_name": "INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Standardization exists",
    "quote": "Standardization exists, but its adoption is inconsistent. Platform teams define reusable 'Golden Paths' to standardize infrastructure, but app developers don't always use them. Some follow these templates, while others rely on manual or ad hoc setup, often due to complexity or a need for speed. Teams also vary in experience and autonomy, which further limits adoption. → Result: inconsistent environments, unpredictable setup, best practices don't scale across orgs."
  }
}
```

---

## JTBD Instance 6: Demonstrating Infrastructure Value and ROI

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Demonstrate the value and ROI of infrastructure investments to stakeholders",
  "workflow": "Infrastructure value communication",
  "steps": [],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers",
    "Leadership",
    "Stakeholders"
  ],
  "pain_points": [
    "The value of robust infrastructure is invisible until something breaks",
    "When everything works, the value of infrastructure investments is invisible",
    "Infrastructure becomes the center of attention mainly during incidents, audits, or cost spikes",
    "Benefits of infrastructure investments build over time",
    "ROI cycles often demand shorter-term proof",
    "Infrastructure investments are reactive",
    "Teams lack clear visibility into value"
  ],
  "source": {
    "file_name": "INFRASTRUCTURE FRICTIONS Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - The value of robust infrastructure",
    "quote": "The value of robust infrastructure is invisible until something breaks. When everything works, the value of infrastructure investments is invisible. Infrastructure becomes the center of attention mainly during incidents, audits, or cost spikes. Benefits of infrastructure investments build over time, but the ROI cycles often demand shorter-term proof. → Result: infrastructure investments are reactive, and teams lack clear visibility into value."
  }
}
```

---

## Summary

This analysis extracted **6 distinct JTBD instances** from the INFRASTRUCTURE FRICTIONS Top takeaways document, covering:

1. Operating infrastructure reliably at scale with safe, predictable operations
2. Responding to incidents quickly with unified visibility across systems
3. Implementing governance that doesn't slow down development velocity
4. Managing infrastructure lifecycle with clear ownership and dependency visibility
5. Standardizing infrastructure using Golden Paths with consistent adoption
6. Demonstrating infrastructure value and ROI to stakeholders

**Key Themes:**
- **Human Middleware**: Engineers manually connect disconnected systems, limiting scale
- **Fragmented Visibility**: No unified view across tools slows incident response
- **Governance Friction**: Rules exist but aren't built into workflows, creating bottlenecks
- **Lifecycle Debt**: Fear-based operations due to unclear ownership and dependencies
- **Inconsistent Standardization**: Golden Paths exist but adoption varies
- **Invisible Value**: Infrastructure value only visible during incidents, audits, or cost spikes

**Bottom Line:**
"Teams can build infrastructure, but without connected systems and clear ownership, they can't operate it reliably at scale."

**Data Characteristics:**
- The source document provides research insights from 30 participants across App Developer, Platform Engineer, and CloudOps roles
- **Steps** fields are populated where the document explicitly describes process sequences
- **Pain points** are extracted from explicitly stated challenges and friction points
- **Workflows** are inferred from the context of infrastructure operations and management activities
- Primary personas are Platform Engineers, CloudOps Managers, and Application Developers

All extractions include complete source attribution with file name, section reference, and verbatim quotes for traceability, adhering to the rule of not inferring beyond what is explicitly stated in the text.