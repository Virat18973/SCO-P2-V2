Sinter Burden Control v30 — Dry/Wet Composition Add-on

This package preserves the existing dashboard structure and adds exactly one new analysis page:

Dry & Wet Composition
- Dry-basis burden composition and % burden
- Dry-basis raw-material cost and % cost
- Wet / as-received burden composition and % burden
- Wet / as-received procurement cost and % cost
- Moisture % shown on the wet table
- O&M shown as a separate cost row
- TOTAL rows on both tables
- Same material sequence as the active optimized recipe
- BF_Returns and any other material present in the active optimizer dataframe are shown automatically

No existing page, optimizer workflow, manual burden logic, or dashboard page was structurally redesigned.

Run:
streamlit run app.py

Dependencies are listed in requirements.txt.
