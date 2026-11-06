# Follow the Trace, Prove the Case

*Digital Forensics in Practice* by Michael Borck.

A short book for people learning digital forensics, incident responders and analysts who need to explain what the evidence supports. The companion lab is [forensics-docker-lab](https://forensics.borck.education/).

## Structure

- `index.qmd`: preface and reading guide
- `chapters/`: eight chapters in three parts
- `appendices/`: lab map and evidence templates
- `book-design.css` / `book-design-epub.css`: house design assets
- `_quarto.yml`: HTML, PDF and EPUB configuration

## Build

```bash
quarto render
```

For the Lorekeeper pack, the engine reads the three parts and appends interactive lessons from `lorekeeper/books/follow-the-trace/`.

## Licence

Text is CC BY 4.0 International. See `LICENSE`.
