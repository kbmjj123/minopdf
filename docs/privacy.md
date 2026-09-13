# Privacy Notes

MinoPDF is designed to make file-processing behavior clear.

## Browser-First Where Feasible

Many MinoPDF workflows are designed to run locally in the browser. Depending on the tool, processing may use browser APIs, PDF.js, WebAssembly, and Web Workers.

When a tool processes files locally, the file is handled on your device rather than uploaded for server-side conversion.

## Check Each Tool Page

Processing behavior can differ by tool and may change as capabilities evolve.

Before processing sensitive material:

1. Read the privacy disclosure on the relevant tool page.
2. Confirm whether the tool is browser-based or requires server-side processing.
3. Review output before sharing it.
4. Keep an untouched copy of the source file.

## Important Distinctions

- Metadata cleanup removes selected document metadata; it does not necessarily remove sensitive visible content.
- Visual masking is not automatically irreversible redaction.
- PDF permissions are not the same as encryption or true sanitization.
- Rebuilding a PDF may alter or invalidate signatures, forms, bookmarks, annotations, attachments, links, and metadata.
- OCR and text extraction can make mistakes, especially with scans, complex layouts, custom fonts, and low-quality images.

## Sensitive Documents

Use caution with documents containing personal, financial, legal, health, client, employee, or confidential information.

MinoPDF does not make absolute security, deletion, anonymization, or accuracy guarantees.
