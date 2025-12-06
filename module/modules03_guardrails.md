Module 3 – Guardrails 
Purpose: Enforce non‑hallucination and consistency rules.
Inputs: raw section summaries from the Section Loop; original section texts; flags about missing or short sections.
Outputs: corrected and approved section summaries; warnings for sections that cannot be fully summarized; notes about consistency adjustments.
Logic:
Check that each summary only contains information that appears in the source text; remove or rephrase content that goes beyond the paper.
Ensure terminology and definitions are consistent across all section summaries.
If a section is missing or clearly too short, replace any attempted content with a clear warning that the source text does not provide enough information.
