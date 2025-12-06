Module 1 – Intake Setup
Purpose: Validate and organize user inputs.
Inputs: full paper text split into sections; list of sections to summarize; configuration settings (audience and technical level).
Outputs: a normalized representation of the section list; a record of configuration settings; flags for any missing or obviously incomplete sections.
Logic:
Check that requested sections are among Abstract, Introduction, Methods, Results, Discussion, Conclusion, References, Appendixes.
Preserve the original order of sections.
Store configuration settings so downstream modules can adapt language and detail level.
