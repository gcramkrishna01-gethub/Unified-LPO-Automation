# Unified LPO Automation Platform

An all-in-one, browser-based tool that automates **Local Purchase Order (LPO)** processing and sales-order stamping for major UAE retail vendors — in a single page, with no installation and no backend. Everything runs locally in your browser, so your documents never leave your computer.

## Supported vendors

ADCOOP (Abu Dhabi Coop) · Carrefour · Delivery Hero · GMG · Grandiose · LULU · NESTO · Sharjah Coop (SHJ) · Spinneys · Union Coop

## What it does

- **Reads LPO PDFs** — drag and drop a vendor's purchase order and the tool parses it automatically.
- **Stamps sales orders** — applies the correct sales-order stamp/format for the selected vendor.
- **Handles Excel & CSV** — imports and exports tabular data for price matching and order details.
- **Generates clean output** — produces stamped, ready-to-send PDFs you can download or print.
- **Vendor-aware** — each retailer's layout and rules are handled in one unified interface.

## How to use

1. Open `index_unified_LPO.html` in any modern browser (Chrome, Edge, or Firefox).
2. Select the vendor you're processing.
3. Drag and drop the LPO PDF (and Excel/CSV if required).
4. Review the stamped output and download or print it.

> Live version (if GitHub Pages is enabled): rename the file to `index.html` and your page will be served at `https://<your-username>.github.io/<repo-name>/`.

## Built with

The tool is a single self-contained HTML file using client-side libraries loaded from CDN:

- [PDF.js](https://mozilla.github.io/pdf.js/) — reading and rendering PDFs
- [pdf-lib](https://pdf-lib.js.org/) — editing and stamping PDFs
- [SheetJS (xlsx)](https://sheetjs.com/) — Excel/CSV import and export
- [JSZip](https://stuk.github.io/jszip/) — packaging output files

## Privacy

All processing happens entirely in the browser. No files are uploaded to any server.

## License

All rights reserved.
