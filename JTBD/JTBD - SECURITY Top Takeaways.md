# JTBD Analysis: SECURITY Top Takeaways - Research Sprint

## Overview
This document contains structured Jobs-to-be-Done (JTBD) extractions from the SECURITY Top takeaways - Research Sprint 02-26 document. Each instance follows the schema: Persona → Job → Workflow → Steps → Roles → Pain points.

**Note:** This document contains high-level research takeaways synthesized from multiple role-based studies. Where specific workflow steps are not explicitly stated, fields are left blank or contain only what is directly mentioned in the source text.

---

## JTBD Instance 1: Implementing Identity-First Security Guardrails

```json
{
  "persona": "Platform Engineers and Security Teams",
  "job": "Establish and maintain identity-first security foundations with centralized identity management and least-privilege access",
  "workflow": "Identity and access management implementation",
  "steps": [
    "Implement centralized identity (Entra ID/Azure AD, AWS IAM)",
    "Configure least-privilege RBAC",
    "Set up privileged-access brokers",
    "Wire preventive guardrails into organizational controls",
    "Integrate guardrails into pipelines"
  ],
  "roles": [
    "Platform Engineers",
    "Security Teams",
    "Identity and Access Management Teams"
  ],
  "pain_points": [],
  "source": {
    "file_name": "SECURITY Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Identity-first guardrails",
    "quote": "Security foundations rely on centralized identity (Entra ID/Azure AD, AWS IAM), least-privilege RBAC, and privileged-access brokers; preventive guardrails are wired into organizational controls and pipelines."
  }
}
```

---

## JTBD Instance 2: Scaling Security with Policy-as-Code

```json
{
  "persona": "Platform Engineers and Security Teams",
  "job": "Scale security programs using policy-as-code in pipelines to maintain velocity and security posture",
  "workflow": "Policy-as-code implementation",
  "steps": [
    "Implement policy-as-code in pipelines",
    "Create paved-road templates",
    "Align velocity with security posture",
    "Close ownership gaps through tagging at creation",
    "Link CMDB to security events"
  ],
  "roles": [
    "Platform Engineers",
    "Security Teams",
    "Development Teams"
  ],
  "pain_points": [
    "Need to reconcile safety with flow",
    "Policy-as-code becomes mandatory at scale"
  ],
  "source": {
    "file_name": "SECURITY Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Introduction",
    "quote": "Security programs start with identity-first guardrails (Entra ID/AWS IAM, least-privilege, privileged access) and scale with policy-as-code in pipelines. The top takeaways focus on closing ownership gaps (tagging at creation, CMDB links) and easing the 'locked door vs. hurdle' tension through paved-road templates that keep velocity and posture aligned."
  }
}
```

---

## JTBD Instance 3: Responding to Security Incidents and Regulatory Requirements

```json
{
  "persona": "Security Teams and Leadership",
  "job": "Improve security posture in response to incidents and regulatory requirements",
  "workflow": "Incident-driven security improvement",
  "steps": [
    "Respond to real security incidents",
    "Implement zero-trust resets",
    "Enforce stricter asset tracking",
    "Gain leadership attention and support",
    "Address regulatory compliance requirements"
  ],
  "roles": [
    "Security Teams",
    "Leadership",
    "Compliance Teams"
  ],
  "pain_points": [
    "Posture changes commonly follow real incidents",
    "Regulatory contexts drive stricter requirements"
  ],
  "source": {
    "file_name": "SECURITY Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Incidents & regulation",
    "quote": "Incidents & regulation drive posture change. Zero‑trust resets, stricter asset tracking, and leadership attention commonly follow real incidents and in regulated contexts."
  }
}
```

---

## JTBD Instance 4: Managing Layered Security Tools and Integration

```json
{
  "persona": "Security Teams and Platform Engineers",
  "job": "Manage and integrate multiple security tools across the security stack",
  "workflow": "Security tool management and integration",
  "steps": [],
  "roles": [
    "Security Teams",
    "Platform Engineers",
    "Security Operations"
  ],
  "pain_points": [
    "Stacks combine EDR/XDR, SIEM/SOAR, SAST/SCA, and CNAPP",
    "Integration gaps between tools",
    "Version stagnation",
    "Increased operational friction",
    "Increased audit burden",
    "Scattered visibility across tools"
  ],
  "source": {
    "file_name": "SECURITY Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Layered tools",
    "quote": "Layered tools, scattered visibility. Stacks combine EDR/XDR, SIEM/SOAR, SAST/SCA, and CNAPP; leaders cite integration gaps and version stagnation, increasing operational friction and audit burden."
  }
}
```

---

## JTBD Instance 5: Balancing Security Controls with Developer Velocity

```json
{
  "persona": "Platform Engineers and Application Developers",
  "job": "Balance strict security controls with developer productivity and flow",
  "workflow": "Security and velocity alignment",
  "steps": [
    "Implement IAM boundaries",
    "Configure network boundaries",
    "Protect against lateral movement",
    "Address developer friction from security controls",
    "Implement policy-as-code to reconcile safety with flow"
  ],
  "roles": [
    "Platform Engineers",
    "Application Developers",
    "Security Teams"
  ],
  "pain_points": [
    "Platform Engineering views strict controls as essential lateral-movement protection",
    "Developers experience same controls as hurdles",
    "Controls create 'human middleware'",
    "Locked door vs. hurdle role tension",
    "Policy-as-code becomes mandatory at scale to reconcile safety with flow"
  ],
  "source": {
    "file_name": "SECURITY Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Locked door vs. hurdle",
    "quote": "'Locked door vs. hurdle' role tension. Platform Engineering views strict (IAM) and network boundaries as essential lateral-movement protection; Developers experience the same controls as hurdles that create 'human middleware.' Policy-as-code becomes mandatory at scale to reconcile safety with flow."
  }
}
```

---

## JTBD Instance 6: Managing Resource Ownership and Provenance

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Track and manage resource ownership to avoid unknown resources and security blind spots",
  "workflow": "Resource ownership and tracking",
  "steps": [
    "Enforce tagging at resource creation",
    "Link owners in CMDB",
    "Connect CMDB to SIEM/ITSM events",
    "Identify unknown owners",
    "Perform 'scream tests' (power off resources to infer usage)"
  ],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers",
    "Security Teams"
  ],
  "pain_points": [
    "Unknown owners",
    "Weak provenance",
    "Teams power off resources to infer usage",
    "Need enforced tagging at creation",
    "Need to link owners in CMDB to SIEM/ITSM events"
  ],
  "source": {
    "file_name": "SECURITY Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Ownership gaps",
    "quote": "Ownership gaps → 'scream tests'. Unknown owners and weak provenance cause teams to power off resources to infer usage; the fix is enforced tagging at creation and linking owners in CMDB to SIEM/ITSM events."
  }
}
```

---

## Summary

This analysis extracted **6 distinct JTBD instances** from the SECURITY Top takeaways document, covering:

1. Implementing identity-first security guardrails (Entra ID/AWS IAM, least-privilege, privileged access)
2. Scaling security with policy-as-code in pipelines
3. Responding to security incidents and regulatory requirements
4. Managing layered security tools and integration challenges
5. Balancing security controls with developer velocity ("locked door vs. hurdle")
6. Managing resource ownership and provenance to avoid blind spots

**Key Themes:**
- **Identity-First Foundations**: Centralized identity management and least-privilege access as security baseline
- **Policy-as-Code**: Mandatory at scale to reconcile security with developer velocity
- **Incident-Driven Change**: Real incidents and regulation drive zero-trust resets and stricter tracking
- **Tool Integration Challenges**: Multiple security tools (EDR/XDR, SIEM/SOAR, SAST/SCA, CNAPP) create integration gaps
- **Role Tension**: Platform Engineers prioritize lateral-movement protection while Developers experience controls as friction
- **Ownership Gaps**: Unknown resources and weak provenance force "scream tests"

**Data Characteristics:**
- The source document provides synthesized research takeaways with specific security patterns
- **Steps** fields are populated where the document explicitly describes process sequences
- **Pain points** are extracted from explicitly stated tensions and challenges
- **Workflows** are inferred from the context of security implementation and management activities
- Three distinct personas are identified: Platform Engineers, Application Developers, and Security Teams (with CloudOps Managers and Leadership as additional stakeholders)

All extractions include complete source attribution with file name, section reference, and verbatim quotes for traceability, adhering to the rule of not inferring beyond what is explicitly stated in the text.