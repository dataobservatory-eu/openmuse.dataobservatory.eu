---
title: Open Music Europe document template
summary: Preliminary document template
authors: [synyo]
tags: ["Templates"]
categories: []
date: '2022-10-03T12:42:00+02:00'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: white
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---


{{< slide background-image="libre_office_preview.webp" >}}
</br></br></br></br></br></br></br></br></br>

---

### Open Music Europe Document Template

- Download the template in the [docx](https://github.com/dataobservatory-eu/open_music_europe_templates/blob/main/document/Open_Music_Europe_Document.docx?raw=true) 
format.
- Check out how [it looks](https://github.com/dataobservatory-eu/open_music_europe_templates/blob/main/_book/open_music_europe_demo.docx?raw=true) after running a minimal example through bookdown/pandoc.
- Send feedback as [issue](https://github.com/dataobservatory-eu/open_music_europe_templates/issues) in the template repository, one problem, one issue at a time. (First read if somebody reported the same problem earlier!) Faster, task immediately assigned to a person.
- Alternatively, get in touch with the [Synyo](https://openmuse.dataobservatory.eu/authors/synyo/) team on [Keybase](https://keybase.io/) (task is not immediately assigned.)
- Examples: [Define Word document template titles](https://github.com/dataobservatory-eu/open_music_europe_templates/issues/1)

</br></br></br></br></br></br></br></br></br>)

---

### Experience so far

- We learned in `WP3` that using different spreadsheet applications on Word, Mac, Linux (Excel, Google, Libre) can have disastrous interoperability and many hours of manual revision of lost Eastern European characters or non-printing symbols.
- Simplification is key to working across organizations using different operational systems and workflows.
- The current preliminary delivery template is too Word-specific and complex.

---

### Considerations 

- We must comply with the [Open Policy Analysis Guidelines](https://openmuse.dataobservatory.eu/resources/opa/) and [FAIR](https://www.go-fair.org/). Both require interoperability and reusability of our files. 
- Furthermore, the EU FAIR requires findability and accessibility, so we must dissemintate our files on open repositories. You need to work in an interoperable format, or in a simple Word template that can be converted back to a simpler format.
---

### Testing

- Upload a Word file to Google Docs. 
- Use the free [Docs to Markdown](https://workspace.google.com/marketplace/app/docs_to_markdown/700168918607) and convert it to a simpler, interoperable, universal formatting. 
- The smallest common denominator is markdown for simple files, and perhaps tex for scientific publications. Do not use Word formatting that is not present in [markdown](https://www.markdownguide.org/).
- Check if the resulting [markdown](https://www.markdownguide.org/) is easily readable in any text editor. Send this `.md` file through pandoc, knitr, or any reproducible application. If it breaks, it is not simple enough.
