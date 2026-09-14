# B5D Project Instructions

## Document & Design Formatting Standards (non-negotiable)

**Minimum font size: 10 point — no exceptions.** This applies to every
deliverable created in this project: Word docs, PDFs, Google Docs, slides,
HTML pages, infographics, charts, and exports to Canva/Miro/Gamma.

Conversions of the 10pt floor by medium:
- Print / docs / PDFs / slides: 10pt minimum
- Web / HTML / infographics: 13.5px or 0.84rem minimum (at 16px root size)
- Charts and data visualizations: axis labels, legends, annotations, and
  data labels all count — they are the most common violators

This includes footnotes, captions, photo credits, chart labels, table cells,
and fine print. If content does not fit at 10pt, cut or restructure the
content — never shrink the type. Readability beats density every time.

When editing an existing file, raise any font size found below the floor to
at least the floor value.

## Google Drive Conventions

Leslie's Drive (valmontebridges@gmail.com) has two dedicated Claude folders
at the top level of My Drive:

**"Claude Downloads"** — folder ID `1sd532fR5ApWeNo--ki39IoL_jg_48RUN`
- This is Leslie's intake folder. PDFs and reports she saves (McKinsey
  pieces, NAAIC reports, etc.) land here.
- When she asks to "process" a report, "sweep downloads", or check for new
  files, search this folder (`parentId = '1sd532fR5ApWeNo--ki39IoL_jg_48RUN'`)
  and compare against existing Resources records in the Hub — process
  anything not yet recorded.
- After processing a PDF into the Hub, set the Resources record's File Link
  field to the file's Drive link (https://drive.google.com/file/d/FILE_ID/view).

**"Claude Artifacts"** — folder ID `1pDGihLhXyxeCPsWrnaLwKjFXSeLTIRr2`
- Any file Claude creates and saves to Leslie's Drive goes IN THIS FOLDER
  (pass it as the parent when creating). Never save to Drive root or other
  folders unless Leslie names a different destination.

## B5D AI Intelligence Hub (Airtable)

**The Operating Runbook is authoritative, not this file.** Read it before any
Hub work: Google Doc `19xa4zGL9tGGBfcZHT_sCnLAbMW1i7E64qLNJaKoQcUM`,
"B5D AI Intelligence Hub: Operating Runbook". It defines Procedures A-E
(capture, processing sweep, insight extraction, Friday digest, LinkedIn
drafting) and the exact select-option vocabularies in Appendix A. Where this
file and the runbook disagree, the runbook wins. If the runbook cannot be
read, proceed with the notes below and say so rather than stopping.

Base "B5D AI Intelligence Hub": `appRtBs7OyX7uPVMC`
- Resources `tblTOTgiR9AabVm9o` · Insights `tblGKAokYQ94hC4SF` ·
  Projects `tblupguFwH3YiNl0z` · LinkedIn Posts `tblceQzKft3E4g6tP` ·
  Weekly Digests `tblmG7smi5j5euJrL`
- There are **no Airtable-native automations**. Everything runs from a
  scheduled routine or a conversation. When a routine breaks, capture keeps
  working and enrichment stops silently — check routine run status first.

Field handling (runbook Appendix B):
- **Never edit** Raw Capture (`fldaKxojQ7jFiprx4`), or Leslie's Spark. They
  are the paper trail.
- **Why I Saved This** (`fldcUQJLQ2vBhcqKQ`): fill only if empty, mark it
  "(Inferred — please confirm)", and flag it. Never overwrite her words.
- **Source URL** (`fldzAye9xcAUnqlgB`) is the original online source, cleaned
  of tracking parameters. **File Link** (`fldCoNqaF88YOdpro`) is Leslie's
  archived copy, e.g. a Drive PDF. Not interchangeable — fill both when both
  exist.
- Claude owns Summary and Key Takeaway.
- Before enriching, check for an existing record with the same canonical
  Source URL. Flag duplicate pairs for Leslie; never delete one yourself.
- New Insights start at Status = "Raw". Insight names lead with source and
  substance ("MIT stat: 95% of AI pilots fail to reach production").
- Use only the select options in runbook Appendix A.
