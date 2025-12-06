Module 2 – Section Loop 
Purpose: Summarize each requested section while respecting PS2 constraints.
Inputs: normalized section list and section texts; configuration settings; flags from Intake Setup.
Outputs: a set of per‑section summaries, each tagged with its section name and metadata such as length and completeness.
Logic:
Iterate over sections in the original order.
For each section, generate a concise summary that:
Does not exceed the per‑section word limit.
Preserves the primary purpose of the section (procedures for Methods, findings for Results, etc.).
Uses terminology appropriate to the chosen audience and technical level.
Mark sections with missing or extremely short text for special handling by the Guardrails module.
