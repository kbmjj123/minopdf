# Tool Limitations

PDF files vary widely in structure. Results may differ based on the document, browser, device, and selected options.

## Text-Based vs Scanned PDFs

Text extraction tools work best with PDFs that contain selectable text.

Scanned PDFs often contain page images only. They normally require OCR before text can be extracted, searched, or converted into editable formats.

## Layout and Structure

Plain-text and Markdown export may not fully preserve:

- Multi-column reading order
- Tables
- Footnotes and sidebars
- Floating text
- Complex typography
- Embedded images
- Exact spacing and page design
- Custom font encodings

## PDF Rebuilding

Tools that merge, extract, resize, rotate, flatten, or otherwise generate a new PDF can affect:

- Metadata
- Bookmarks
- Hyperlinks
- Form fields
- Annotations
- Attachments
- Optional content layers
- Permissions
- Digital signatures

Always verify the downloaded result before relying on it.

## Image Rendering

Rendering PDF pages to PNG, JPG, or WebP creates a page image. It is different from extracting the original embedded image objects from a PDF.

A rendered image may include text, vector graphics, page backgrounds, and visible layout. It may not preserve the original dimensions or compression of images embedded in the source PDF.

## Device Limits

Browser-based processing uses your device memory and CPU.

Large files, many pages, high DPI rendering, large archives, or multiple files can take longer or fail on lower-memory devices. Closing unused tabs or processing files in smaller batches may help.
