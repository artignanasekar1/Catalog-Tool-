# JTBD Analysis: ONBOARDING Top Takeaways - Research Sprint

## Overview
This document contains structured Jobs-to-be-Done (JTBD) extractions from the ONBOARDING Top takeaways - Research Sprint 02-26 document. Each instance follows the schema: Persona → Job → Workflow → Steps → Roles → Pain points.

**Note:** This document focuses on Terraform onboarding for infrastructure management tools. Where specific workflow steps are not explicitly stated, fields are left blank or contain only what is directly mentioned in the source text.

---

## JTBD Instance 1: Getting Productive with Terraform Safely

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Get productive with Terraform quickly without causing damage to infrastructure",
  "workflow": "Terraform onboarding and adoption",
  "steps": [
    "Use terraform plan as primary 'safe sandbox'",
    "Review plan output to understand what will happen",
    "Gain confidence before applying changes",
    "Apply changes"
  ],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers",
    "New Terraform Users"
  ],
  "pain_points": [
    "Terraform enables speed but lacks visibility into impact",
    "Creates fear due to lack of clarity",
    "Engineers want to understand what will happen",
    "Need to understand how things connect",
    "Need to avoid breaking something"
  ],
  "source": {
    "file_name": "ONBOARDING Top takeaways - Research Sprint 02-26",
    "section": "Context",
    "quote": "Across interviews, onboarding success was defined simply: help new users get productive fast—without causing damage. Terraform enables speed, but it lacks visibility into impact, which creates fear. The gap is clarity: engineers want to understand what will happen, how things connect, and how to avoid breaking something."
  }
}
```

---

## JTBD Instance 2: Building Trust Through Terraform Plan

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Build trust and confidence in infrastructure changes using terraform plan",
  "workflow": "Change validation and confidence building",
  "steps": [
    "Run terraform plan",
    "Review plan output",
    "Gain confidence from plan preview",
    "Apply changes with confidence"
  ],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers"
  ],
  "pain_points": [],
  "source": {
    "file_name": "ONBOARDING Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 1",
    "quote": "Instant clarity builds trust—and Terraform partially delivers it. Teams rely on terraform plan as their primary 'safe sandbox,' and it gives them confidence before applying changes. This is Terraform's strongest onboarding asset."
  }
}
```

---

## JTBD Instance 3: Understanding Resource Relationships and Dependencies

```json
{
  "persona": "Platform Engineers and CloudOps Managers (New and Experienced)",
  "job": "Form a mental model of how infrastructure resources relate and understand blast radius of changes",
  "workflow": "Infrastructure understanding and mental model formation",
  "steps": [],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers",
    "New Engineers",
    "Experienced Engineers"
  ],
  "pain_points": [
    "New and experienced engineers struggle to form a mental model of how resources relate",
    "Especially difficult in legacy codebases",
    "Without visual maps or blast-radius indicators, onboarding feels like guessing",
    "Lack of visual understanding slows onboarding",
    "Lack of visual understanding increases risk"
  ],
  "source": {
    "file_name": "ONBOARDING Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 2",
    "quote": "Lack of visual understanding slows onboarding and increases risk. New and experienced engineers struggle to form a mental model of how resources relate, especially in legacy codebases. Without visual maps or blast‑radius indicators, onboarding feels like guessing."
  }
}
```

---

## JTBD Instance 4: Using AI for Terraform Code Scaffolding and Pattern Recognition

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Accelerate Terraform setup and reduce cognitive load using AI assistance",
  "workflow": "AI-assisted Terraform development",
  "steps": [
    "Use external AI tools for scaffolding",
    "Use external AI tools for pattern recognition",
    "Maintain human control over changes"
  ],
  "roles": [
    "Platform Engineers",
    "CloudOps Managers"
  ],
  "pain_points": [
    "AI helps with code but Terraform doesn't leverage AI for onboarding",
    "Engineers already use external AI tools",
    "Terraform provides little built-in AI support",
    "Teams want AI to accelerate setup and reduce cognitive load—without removing human control"
  ],
  "source": {
    "file_name": "ONBOARDING Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 3",
    "quote": "AI helps with code but Terraform doesn't leverage AI for onboarding. Engineers already use external AI tools for scaffolding and pattern recognition but Terraform provides little built‑in support. Teams want AI to accelerate setup and reduce cognitive load—without removing human control."
  }
}
```

---

## JTBD Instance 5: Adapting Onboarding to Company Maturity and Constraints

```json
{
  "persona": "Platform Engineers and CloudOps Managers",
  "job": "Follow onboarding paths that match company size, maturity, and constraints",
  "workflow": "Context-appropriate onboarding",
  "steps": [],
  "roles": [
    "Platform Engineers (Large Organizations)",
    "Platform Engineers (Small Teams)",
    "CloudOps Managers"
  ],
  "pain_points": [
    "One-size-fits-all guidance doesn't work",
    "Large organizations prioritize governance and security clarity",
    "Smaller teams prioritize speed and 'no-docs' simplicity",
    "Terraform onboarding does not yet adapt to company maturity or constraints",
    "Different companies need fundamentally different onboarding paths"
  ],
  "source": {
    "file_name": "ONBOARDING Top takeaways - Research Sprint 02-26",
    "section": "Top takeaways - Point 4",
    "quote": "Different companies need fundamentally different onboarding paths. One-size-fits-all guidance doesn't work: large organizations prioritize governance and security clarity; smaller teams prioritize speed and 'no‑docs' simplicity. Terraform onboarding does not yet adapt to company maturity or constraints."
  }
}
```

---

## Summary

This analysis extracted **5 distinct JTBD instances** from the ONBOARDING Top takeaways document, covering:

1. Getting productive with Terraform quickly without causing infrastructure damage
2. Building trust and confidence through terraform plan as a "safe sandbox"
3. Understanding resource relationships and dependencies (mental model formation)
4. Using AI for Terraform code scaffolding and pattern recognition
5. Adapting onboarding to company maturity and constraints

**Key Themes:**
- **Speed vs. Safety**: Terraform enables speed but lacks visibility into impact, creating fear
- **Terraform Plan as Trust Builder**: Primary "safe sandbox" that gives confidence before applying changes
- **Visual Understanding Gap**: Engineers struggle to form mental models without visual maps or blast-radius indicators
- **AI Assistance Gap**: Engineers use external AI tools but Terraform provides little built-in support
- **One-Size-Fits-All Problem**: Large organizations need governance/security clarity; small teams need speed/simplicity

**Onboarding Success Definition:**
"Help new users get productive fast—without causing damage"

**Company-Specific Needs:**
- **Large Organizations**: Prioritize governance and security clarity
- **Smaller Teams**: Prioritize speed and "no-docs" simplicity

**Data Characteristics:**
- The source document provides research insights from 11 Platform Engineers and 8 CloudOps Managers
- **Steps** fields are populated where the document explicitly describes process sequences
- **Pain points** are extracted from explicitly stated challenges and gaps
- **Workflows** are inferred from the context of Terraform onboarding and adoption activities
- Primary personas are Platform Engineers and CloudOps Managers at various experience levels and company sizes

All extractions include complete source attribution with file name, section reference, and verbatim quotes for traceability, adhering to the rule of not inferring beyond what is explicitly stated in the text.