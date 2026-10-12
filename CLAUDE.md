# JCSC / GCSC brand and design system

Follow the JCSC/GCSC design system for new JCSC/GCSC-branded material (documents, slides, reports, dashboards, web pages, charts, emails and social posts): https://claude.ai/artifact/7WLkiGdajoq8iRWuW2K7uB

- It is a claude.ai artifact. Read it with the Artifact tool, starting with `project/README.md`, and read the relevant sections (Writing style, Information classification, Presentations, Cyber Shield, Decisions) before producing output.
- If you can't open it, follow the rules below and say that you couldn't open the design system.

## Scope

- If a repository already has its own design system, theme or style guide, follow that instead and don't restyle existing work.
- If it's unclear which applies, ask before making visual changes.

## Key rules

- **Names:** give JCSC and GCSC equal prominence unless told otherwise. Write "Jersey Cyber Security Centre (JCSC)" and "Guernsey Cyber Security Centre (GCSC)" in full the first time, then the initials. Write "JCSC", never "the JCSC". Never use "CERT.JE" or "CERT JE". "Channel Islands Cyber Shield" (cicybershield.com) is run by both centres and is "Cyber Shield" after first use. It has no logo of its own.
- **Colours:**
  - Primary: Dark Blue #011350 and Electric Mint #0FF2DB.
  - Secondary: Vibrant Blue #213DCF, Electric Yellow #E8FF75 and Light Grey #EBEBE3.
  - Never set mint, yellow or light grey text on white or light grey.
  - Don't use the logo files' mint (#00DDC5) in new material.
- **Type:** Red Hat Text Bold for titles, Red Hat Text Regular for body text (Google Fonts). Don't use Red Hat Display.
- **Logos and icons:** use only the supplied files from the design system. Never redraw or recolour them. Use the combined JCSC | GCSC lockup when both centres appear.
- **Writing (JCSC House Style Guide):**
  - British English.
  - Dates and times: "27 March 2026", "4pm", "4.15pm", "1pm to 3pm".
  - Numbers: one to nine in words, 10 and above in numerals, commas in thousands (1,000), the % symbol, "more than" rather than "over".
  - Introduce bulleted lists with a colon.
  - Write "cyber security" as two words.
  - Use italics, not bold, for emphasis.
- **Information classification:**
  - Label shared material with FIRST TLP 2.0: TLP:RED, TLP:AMBER+STRICT, TLP:AMBER, TLP:GREEN or TLP:CLEAR.
  - Write labels in capitals with no spaces, as coloured text on black, 12pt or larger, in the header and footer of every page.
  - Exception: the PowerPoint templates and the Word report template keep their own TLP labels as designed.
- **Accessibility:** text must have at least 4.5:1 contrast with its background. Never use colour as the only signal; for example, pair alert colours with a word such as "High".

## This repository

Reports, dashboards and charts produced by this metrics platform are JCSC/GCSC material, so the rules above apply to them. That includes the TLP label on every report page and the house style for dates, times and numbers.

## Local reference files

Some reference files for this project are kept outside the repository, on the shared development server, and must never be published.

- **Location:** the folder named by the `CSIRT_METRICS_LOCAL_DIR` environment variable. If it isn't set, use `/srv/csirt-metrics-local/`. If neither exists (for example in a cloud session), the files aren't available. Say so, and don't try to recreate them.
- **Reading:** you may read and analyse these files when working on the local machine.
- **Never publish:**
  - Never copy, move or export these files, or extracts from them, into this repository.
  - Never quote their contents or values in commit messages, pull request descriptions, GitHub comments, issues, artifacts or any other published or shared place.
  - Never upload them anywhere else.
- **Tests and examples:** anything committed (tests, fixtures, examples, documentation) must use invented values, never real ones from these files.
- **If a task needs something from these files in the repository,** stop and ask first.
