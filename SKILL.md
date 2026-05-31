---
name: sre-systems-researcher
user-invocable: true
description: >
  Skill for structured research in site reliability engineering and systems engineering.
  Use when you need to analyze operational risk, recommend resilient designs, or create evidence-based engineering reports.
---

# SRE & Systems Engineering Researcher

## Purpose

This skill guides a researcher through an operations-led, systems engineering research workflow. It helps clarify goals, gather and evaluate evidence, identify reliability and architectural tradeoffs, and deliver practical recommendations.

## Workflow

1. Clarify the objective
   - Ask what the desired outcome is: whitepaper, incident analysis, architecture review, tooling recommendation, or organizational guidance.
   - Identify the audience: operators, engineering leadership, architects, or cross-functional stakeholders.
   - Confirm the system scope: service, platform, pipeline, site, or enterprise architecture.

2. Discover and frame the problem
   - Define key reliability attributes: availability, latency, capacity, security, maintainability, and observability.
   - Identify failure modes, dependencies, and operational risks.
   - Separate assumptions, constraints, and current known issues from the requirements.

3. Gather evidence and compare options
   - Collect relevant source material: SRE best practices, systems engineering patterns, incident reports, standards, and metrics.
   - Evaluate each option by operational impact, complexity, cost, and feasibility.
   - Highlight how choices affect reliability, resilience, and systems behavior under load or failure.

4. Synthesize findings
   - Summarize the core insights with clear reasoning.
   - Translate technical analysis into actionable recommendations.
   - Prioritize improvements by risk reduction, cost, and implementation effort.

5. Validate and finalize
   - Check that recommendations are grounded in evidence and aligned to the stated objective.
   - Ensure the output includes explicit assumptions, tradeoffs, and next steps.
   - If needed, propose follow-up review questions or validation experiments.

## Decision Points

- If the scope is unclear, ask the user for the target audience, system boundaries, and success criteria.
- If the request is about a specific incident or outage, treat it as an incident analysis and focus on root cause, remediation, and systemic prevention.
- If the request is about architecture or design, emphasize reliability patterns, dependency management, and operational observability.
- If the request is about tooling or process, compare how it supports SRE workflows and systems engineering lifecycle goals.

## Quality Criteria

- The analysis is operations-first and anchored in concrete system behavior.
- Recommendations are actionable, prioritized, and tied to reliability outcomes.
- Tradeoffs are explicit and documented.
- Sources, assumptions, and limitations are clearly stated.
- The final output matches the requested format and audience.

## Example Prompts

- "Analyze the reliability risks of deploying a stateful service across multiple cloud regions and recommend a resilient systems design."
- "Compare SRE incident response practices with traditional systems engineering review cycles for a mixed on-prem/cloud service."
- "Create a research brief on how to measure and improve operational readiness for a high-throughput distributed data pipeline."
