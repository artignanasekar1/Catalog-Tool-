# JTBD Analysis: AGENTIC AI Top Takeaways - Research Sprint

## Overview
This document contains structured Jobs-to-be-Done (JTBD) extractions from the AGENTIC AI Top takeaways - Research Sprint 02-26 document. Each instance follows the schema: Persona → Job → Workflow → Steps → Roles → Pain points.

**Note:** This document contains high-level research takeaways synthesized from multiple role-based studies. Where specific workflow steps are not explicitly stated, fields are left blank or contain only what is directly mentioned in the source text.

---

## JTBD Instance 1: Adopting AI Agents in Advisory Mode

```json
{
  "persona": "Development Teams (Application Developers, Platform Engineers, CloudOps Managers)",
  "job": "Adopt AI agents for code, tests, documentation, triage, and recommendations with strong guardrails",
  "workflow": "AI agent adoption with human-in-the-loop approval",
  "steps": [
    "Begin with agents in advisory mode",
    "Agents explain why a change is safe",
    "Agents pull from machine-readable standards (tagging rules, golden modules, policy checks)",
    "Human reviews agent proposals for traceability and compliance",
    "Explicit human approval required for any escalation to scoped write access"
  ],
  "roles": [
    "Development Teams",
    "Human Approvers"
  ],
  "pain_points": [
    "Hard gate required on autonomous write actions (prod deployments, IAM changes)",
    "Need telemetry of safe value before escalating to write access",
    "Agents must be traceable and compliant"
  ],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways",
    "quote": "Agentic AI should be adopted in advisory mode first, with a hard gate on autonomous write actions such as production deployments and IAM changes. Teams get value when agents explain why a change is safe and pull from machine-readable standards (tagging rules, golden modules, policy checks), often via MCP, so proposals are both traceable and compliant."
  }
}
```

---

## JTBD Instance 2: Managing AI Agent Risks and Security

```json
{
  "persona": "Development Teams (Application Developers, Platform Engineers, CloudOps Managers)",
  "job": "Manage risks associated with AI agents including data exposure, misconfiguration, and surprise spend",
  "workflow": "Risk management and security controls for AI agents",
  "steps": [],
  "roles": [
    "Development Teams",
    "Security Teams"
  ],
  "pain_points": [
    "IP/PII leakage concerns",
    "Privilege misuse",
    "Infrastructure misconfiguration",
    "Uncontrolled cloud costs"
  ],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Primary risks",
    "quote": "Primary risks: data exposure, misconfiguration, surprise spend. Concerns center on IP/PII leakage, privilege misuse, infra misconfiguration, and uncontrolled cloud costs; common controls include DLP/content moderation, short-lived credentials, least-privilege scopes, and immutable audit trails."
  }
}
```

---

## JTBD Instance 3: Code Review and Governance with AI Assistance

```json
{
  "persona": "Application Developers",
  "job": "Review and approve code changes with AI-assisted drafting and refactoring",
  "workflow": "Code review and governance",
  "steps": [
    "Agents speed drafting and refactoring",
    "Code review process",
    "Security gates review",
    "Environment approvals"
  ],
  "roles": [
    "Application Developers",
    "Code Reviewers",
    "Security Teams"
  ],
  "pain_points": [
    "Cycle time concentrates in code review",
    "Security gates create bottlenecks",
    "Environment approvals slow down process",
    "Developer work reframed toward orchestration and verification"
  ],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - AI shifts bottlenecks",
    "quote": "AI shifts bottlenecks from 'doing' to review and governance. Agents speed drafting and refactoring, but cycle time concentrates in code review, security gates, and environment approvals, thus reframing developer work toward orchestration and verification."
  }
}
```

---

## JTBD Instance 4: Providing Machine-Readable Context for AI Agents

```json
{
  "persona": "Development Teams (Application Developers, Platform Engineers, CloudOps Managers)",
  "job": "Provide machine-readable context and standards for AI agent reasoning transparency",
  "workflow": "Context management for AI agents",
  "steps": [],
  "roles": [
    "Development Teams",
    "Platform Teams"
  ],
  "pain_points": [
    "Agents struggle when standards live across Confluence/Slack/Jira/repos",
    "Need for 'context packs' (tagging rules, golden modules, policy checks)",
    "Lack of evidence paths for agent proposals"
  ],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Reasoning transparency",
    "quote": "Reasoning transparency requires machine-readable context. Agents struggle when standards live across Confluence/Slack/Jira/repos. Teams ask for 'context packs' (tagging rules, golden modules, policy checks) and call out Model Context Protocol (MCP) as a concrete bridge to expose evidence paths for proposals."
  }
}
```

---

## JTBD Instance 5: Getting AI Insights in CI/CD and Deployment Views

```json
{
  "persona": "Application Developers",
  "job": "Get AI agent insights integrated into CI/CD and deployment workflows",
  "workflow": "CI/CD and deployment with AI insights",
  "steps": [],
  "roles": [
    "Application Developers"
  ],
  "pain_points": [],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Role-aligned expectations",
    "quote": "Developers want agent insights in CI/CD and deployment views"
  }
}
```

---

## JTBD Instance 6: Infrastructure Triage, Drift Detection, and Cost Management

```json
{
  "persona": "Platform Engineers",
  "job": "Use AI agents for infrastructure triage, drift detection, and cost suggestions",
  "workflow": "Infrastructure management with AI assistance",
  "steps": [],
  "roles": [
    "Platform Engineers"
  ],
  "pain_points": [],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Role-aligned expectations",
    "quote": "Platform Engineering prefers agents for triage, drift, and cost suggestions with plan diffs"
  }
}
```

---

## JTBD Instance 7: Ticket Summarization and Audit Trail Management

```json
{
  "persona": "CloudOps Managers",
  "job": "Use AI-generated ticket summaries and maintain auditability",
  "workflow": "Ticket management and audit trail",
  "steps": [],
  "roles": [
    "CloudOps Managers"
  ],
  "pain_points": [],
  "source": {
    "file_name": "AGENTIC AI Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Role-aligned expectations",
    "quote": "CloudOps values agent-generated ticket summaries and auditability"
  }
}
```

---

## Summary

This analysis extracted **7 distinct JTBD instances** from the AGENTIC AI Top takeaways document, covering:

1. Adopting AI agents in advisory mode with human-in-the-loop approval
2. Managing AI agent risks (data exposure, misconfiguration, surprise spend)
3. Code review and governance with AI-assisted drafting
4. Providing machine-readable context for AI reasoning transparency
5. Getting AI insights in CI/CD and deployment views (Application Developers)
6. Infrastructure triage, drift detection, and cost management (Platform Engineers)
7. Ticket summarization and audit trail management (CloudOps Managers)

**Data Characteristics:**
- The source document provides synthesized research takeaways rather than detailed workflow narratives
- **Steps** fields are populated only where the document explicitly describes process sequences
- **Pain points** are extracted from explicitly stated concerns and challenges
- **Workflows** are inferred from the context of how teams adopt and use AI agents
- Three distinct personas are identified: Application Developers, Platform Engineers, and CloudOps Managers

All extractions include complete source attribution with file name, section reference, and verbatim quotes for traceability, adhering to the rule of not inferring beyond what is explicitly stated in the text.