# MinoPDF

**Simple Tools for Better PDFs**

MinoPDF is a browser-first PDF toolkit for converting, organizing, extracting, and cleaning PDF files.

Visit the product: [minopdf.com](https://minopdf.com)

> This repository provides public product information, documentation, release notes, and feedback channels for MinoPDF.  
> The MinoPDF application source code is proprietary and is not published in this repository.

## What MinoPDF Does

MinoPDF provides practical PDF workflows for developers, technical writers, researchers, students, content creators, small teams, and privacy-conscious users.

Depending on the tool, you can process one or multiple files, preview the output, download individual files, or download grouped results as a ZIP archive.

When technically feasible, file processing runs locally in your browser. Review the privacy information on each tool page before processing sensitive files.

## Tool Categories

### Convert

Convert between PDF, images, and document-oriented formats.

- PDF to PNG, JPG, and WebP
- Image to PDF
- ZIP images to PDF
- HTML to PDF
- Markdown to PDF
- TXT to PDF
- PDF to TXT
- PDF to Markdown

### Organize

Create, arrange, and standardize PDF documents.

- Merge PDF files
- Extract PDF pages
- Reorder PDF pages
- Rotate PDF pages
- Resize PDF pages
- Normalize pages to A4 or Letter

### Extract

Retrieve reusable content and structured information from PDF documents.

- Render PDF pages as images
- Inspect PDF image counts by page
- Extract text from text-based PDFs
- Convert text-based PDFs to Markdown

### Clean

Inspect and reduce document-level PDF metadata.

- View PDF metadata
- Clean PDF metadata
- Export metadata reports

### Planned and Exploring

MinoPDF is also exploring additional browser-first document workflows:

- OCR and searchable PDF creation
- Scanned PDF cleanup
- Table extraction
- Layout analysis
- Barcode and QR code detection
- Sensitive-information detection
- PDF quality and accessibility checks

See the public [roadmap](docs/roadmap.md).

## Browser-First Processing

MinoPDF is designed around browser-first processing.

Where supported by the individual tool, files are processed locally with browser technologies such as PDF.js, WebAssembly, Web Workers, and standard browser APIs. This can reduce the need to transfer files to a remote service.

Local processing does not mean every PDF workflow is risk-free or suitable for every document. Browser compatibility, device memory, file size, encryption, embedded content, and PDF structure can affect results.

Read [Browser Processing](docs/browser-processing.md) and [Limitations](docs/limitations.md) before using MinoPDF with important documents.

## Privacy and Safety

MinoPDF aims to make file-processing behavior clear on every tool page.

- Browser-based tools process files locally when feasible.
- Any server-side processing should be disclosed before use.
- MinoPDF does not claim absolute security, complete sanitization, or 100% extraction accuracy.
- Metadata cleanup is not the same as content redaction.
- Visual masking is not necessarily irreversible redaction.
- Rebuilding a PDF can affect document metadata, forms, bookmarks, annotations, permissions, and digital signatures.

For details, see [Privacy Notes](docs/privacy.md).

## Tool Limitations

PDF is a flexible and complex format. Results can vary by file.

- Text extraction works best with text-based PDFs that contain selectable text.
- Scanned or image-only PDFs generally require OCR before text can be extracted.
- Complex multi-column layouts, tables, custom font encodings, forms, and interactive content may not transfer perfectly.
- Merging, resizing, rotating, or rebuilding a PDF can affect bookmarks, links, annotations, forms, attachments, metadata, and digital signatures.
- Always review output files before sharing, printing, submitting, or archiving them.

See [Tool Limitations](docs/limitations.md).

## Feedback and Support

Found a reproducible tool issue or want to suggest a workflow?

- Product website: [minopdf.com](https://minopdf.com)
- Bug reports and tool feedback: [Open an issue](../../issues)
- Security concerns: See [SECURITY.md](SECURITY.md)
- General support: See [SUPPORT.md](SUPPORT.md)

Please do not attach confidential or personal documents to public issues.

## Project Status

MinoPDF is actively evolving. Public documentation and tool availability may change as workflows are improved and new tools are released.

See [CHANGELOG.md](CHANGELOG.md) for notable public updates.

## Legal Notice

The MinoPDF website, product, visual identity, documentation, and related materials are proprietary unless explicitly stated otherwise.

This repository is provided for product information, public documentation, and feedback. It does not grant a license to use, copy, redistribute, self-host, or reverse engineer the MinoPDF application.

© MinoPDF. All rights reserved.
