# SarvKit — Free Online Tools for Everyone

> **Website:** **[https://sarvkit.com](https://sarvkit.com/)**

**SarvKit** is a free, browser-based collection of developer utilities, PDF and OCR tools, design tools, SEO tools, resume builders, text tools, business tools and student tools. **Client-side processing. No sign-up.**

*Catalog reflects the local eight-suite inventory; this is not confirmation that changes are deployed.*

- 🌐 Visit: **<https://sarvkit.com/>**
- 📚 8 specialized "Kits" covering development, documents, writing, design, business and study
- 🔒 Every calculation runs locally in your browser — your inputs never leave your device
- ⚡ Served from Cloudflare's global edge network with HTTPS + HTTP/3

---

## All 8 SarvKit Suites

| Suite | What it does | Volume |
|---|---|---|
| 📄 **[PDFTools](https://sarvkit.com/PDFTools/)** | OCR searchable PDFs, scan to Word, redact, merge, split, compress, rotate, watermark, convert, remove password, extract data | 16 tools + 20 guides |
| 💼 **[BizKit](https://sarvkit.com/BizKit/)** | Image to Excel, receipt and business card scanners, invoice, receipt maker, ROI, break-even, profit margin, startup-cost | 14 tools + 17 guides |
| 📝 **[ResumeKit](https://sarvkit.com/ResumeKit/)** | Resume builder, cover-letter, LinkedIn summary, bullet rewriter | 5 tools + 20 guides |
| 🎓 **[StudentKit](https://sarvkit.com/StudentKit/)** | GPA, grade converter, citations, pomodoro, flashcards, typing test | 10 tools + 20 guides |
| 🔍 **[SEOKit](https://sarvkit.com/SEOKit/)** | Meta tags, OG preview, schema, robots.txt, sitemap, SERP preview | 9 tools + 21 guides |
| 🎨 **[DesignKit](https://sarvkit.com/DesignKit/)** | Graph maker (PDF/EPS/SVG charts), image resize/crop/filter, gradients, shadows, palette, clip-path, glassmorphism, easing, loaders, color scales, contrast, blobs, patterns, EXIF remover, HEIC to JPG | 24 tools + 20 guides |
| `</>` **[DevKit](https://sarvkit.com/DevKit/)** | QR code reader / JSON / Base64 / hash / regex / diff / minifier / TOML / chmod / subnet calculator / sample file generator / mock data generator / corrupt file generator | 37 tools + 21 articles |
| ✏️ **[TextKit](https://sarvkit.com/TextKit/)** | Image to text (OCR), readability, headline analyzer, slug, fancy text, text to braille, morse code, bionic reading, handwriting | 17 tools + 20 guides |

---

## Free OCR and Related Scanning Tools

| Tool | What it does |
|---|---|
| [Image to Text](https://sarvkit.com/TextKit/image-to-text/) | Extract editable text from images and scanned PDFs |
| [OCR PDF](https://sarvkit.com/PDFTools/ocr-pdf/) | Add a searchable text layer to scanned PDFs |
| [Scan to Word](https://sarvkit.com/PDFTools/scan-to-word/) | Convert scanned documents into editable Word files |
| [Redact PDF](https://sarvkit.com/PDFTools/redact-pdf/) | Find text with OCR and apply redactions to a rasterized PDF export |
| [Image to Excel](https://sarvkit.com/BizKit/image-to-excel/) | Extract scanned tables into editable rows for spreadsheet export |
| [Receipt Scanner](https://sarvkit.com/BizKit/receipt-scanner/) | Extract receipt details and amounts for review and export |
| [Business Card Scanner](https://sarvkit.com/BizKit/business-card-scanner/) | Extract contact details from business cards for review and export |
| [QR Code Reader](https://sarvkit.com/DevKit/qr-code-reader/) | Decode QR codes and barcodes from images, screenshots and PDFs locally |

Document recognition runs locally in the browser. Tesseract.js and its cores
are pinned to 7.0.0 on jsDelivr; the 21 language models use the pinned
`naptha/tessdata` commit `806cd9adc8c6e8abc11c782db1818c990576bebc`
(`4.0.0_best_int`). ZXing 3.1.5 loads on demand from pinned jsDelivr URLs
with SHA-384 integrity checks for its script and WebAssembly. jsDelivr receives
ordinary asset-request metadata, not documents. Internet access is needed for engine
startup and uncached assets; browser caches can be cleared or evicted, so offline
OCR is not guaranteed. Supporting libraries and fonts may also load from approved
CDNs. See the [OCR asset and verification guide](assets/vendor/README.md).
OCR accuracy varies with scan quality, language and layout;
review extracted text, spreadsheet cells, receipt amounts and redactions before
use. The QR reader decodes codes rather than recognizing text.

## Finding Related Tools and Guides

Start at the [main homepage](https://sarvkit.com/) or any suite homepage above.
Static navigation links connect tools, guide hubs, parent pages and all 8 suite
homepages, even with JavaScript disabled. Site search provides another route to
tools and guides when JavaScript is enabled.

The combined [sitemap](https://sarvkit.com/sitemap.xml) and generated search index cover the retained public pages. Discovery counts also include suite homepages and resume samples/templates, so they are not tool counts. Run the navigation and discovery checks after changing the inventory.

For maintenance and publishing steps, see the root
[README](README.md#sitemap-and-search-discovery).

---

## 📄 PDFTools — Free PDF Utilities

**Suite home:** **<https://sarvkit.com/PDFTools/>** · 16 tools + 20 guides

[OCR PDF](https://sarvkit.com/PDFTools/ocr-pdf/) · [Scan to Word](https://sarvkit.com/PDFTools/scan-to-word/) · [Redact PDF](https://sarvkit.com/PDFTools/redact-pdf/)

[Merge PDF](https://sarvkit.com/PDFTools/merge-pdf/) · [Split PDF](https://sarvkit.com/PDFTools/split-pdf/) · [Compress PDF](https://sarvkit.com/PDFTools/compress-pdf/) · [Rotate PDF](https://sarvkit.com/PDFTools/rotate-pdf/) · [Watermark PDF](https://sarvkit.com/PDFTools/watermark-pdf/) · [PDF to Image](https://sarvkit.com/PDFTools/pdf-to-image/) · [Image to PDF](https://sarvkit.com/PDFTools/image-to-pdf/) · [PDF Field Extractor](https://sarvkit.com/PDFTools/pdf-field-extractor/)

---

## 💼 BizKit — Small-Business Tools

**Suite home:** **<https://sarvkit.com/BizKit/>** · 14 tools + 17 guides

[Image to Excel](https://sarvkit.com/BizKit/image-to-excel/) · [Receipt Scanner](https://sarvkit.com/BizKit/receipt-scanner/) · [Business Card Scanner](https://sarvkit.com/BizKit/business-card-scanner/)

[Invoice Generator](https://sarvkit.com/BizKit/invoice-generator/) · [Invoice to Excel](https://sarvkit.com/BizKit/invoice-to-excel/) · [Receipt Maker](https://sarvkit.com/BizKit/receipt-maker/) · [ROI Calculator](https://sarvkit.com/BizKit/roi-calculator/) · [Profit Margin](https://sarvkit.com/BizKit/profit-margin-calculator/) · [Break-Even](https://sarvkit.com/BizKit/break-even-calculator/) · [Discount Calculator](https://sarvkit.com/BizKit/discount-calculator/) · [Sales Tax](https://sarvkit.com/BizKit/sales-tax-calculator/) · [Hourly Rate](https://sarvkit.com/BizKit/hourly-rate-calculator/) · [Business Name Generator](https://sarvkit.com/BizKit/business-name-generator/) · [Startup Cost Estimator](https://sarvkit.com/BizKit/startup-cost-estimator/)

---

## 📝 ResumeKit — Resume & Career Tools

**Suite home:** **<https://sarvkit.com/ResumeKit/>** · 5 tools + 20 guides

[Resume Builder](https://sarvkit.com/ResumeKit/resume-builder/) · [Cover Letter Builder](https://sarvkit.com/ResumeKit/cover-letter-builder/) · [LinkedIn Summary](https://sarvkit.com/ResumeKit/linkedin-summary/)

---

## 🎓 StudentKit — Student Tools

**Suite home:** **<https://sarvkit.com/StudentKit/>** · 10 tools + 20 guides

[GPA Calculator](https://sarvkit.com/StudentKit/gpa-calculator/) · [Citation Generator](https://sarvkit.com/StudentKit/citation-generator/) · [Pomodoro Timer](https://sarvkit.com/StudentKit/pomodoro-timer/)

---

## 🔍 SEOKit — SEO Tools

**Suite home:** **<https://sarvkit.com/SEOKit/>** · 9 tools + 21 guides

[Meta Tag Generator](https://sarvkit.com/SEOKit/meta-tag-generator/) · [Open Graph Preview](https://sarvkit.com/SEOKit/og-preview/) · [Schema Generator](https://sarvkit.com/SEOKit/schema-generator/)

---

## 🎨 DesignKit — Design Tools

**Suite home:** **<https://sarvkit.com/DesignKit/>** · 24 tools + 20 guides

[Graph Maker](https://sarvkit.com/DesignKit/graph-maker/) · [Image Resizer](https://sarvkit.com/DesignKit/image-resizer/) · [Image Cropper](https://sarvkit.com/DesignKit/image-cropper/) · [Image Filters](https://sarvkit.com/DesignKit/image-filters/) · [Color Palette Extractor](https://sarvkit.com/DesignKit/color-palette-extractor/) · [Gradient Generator](https://sarvkit.com/DesignKit/gradient-generator/) · [Box Shadow Generator](https://sarvkit.com/DesignKit/box-shadow-generator/) · [Favicon Generator](https://sarvkit.com/DesignKit/favicon-generator/) · [Screenshot Mockup](https://sarvkit.com/DesignKit/screenshot-mockup/) · [SVG to PNG](https://sarvkit.com/DesignKit/svg-to-png/) · [clip-path Generator](https://sarvkit.com/DesignKit/clip-path-generator/) · [Glassmorphism Generator](https://sarvkit.com/DesignKit/glassmorphism-generator/) · [Cubic Bézier Generator](https://sarvkit.com/DesignKit/cubic-bezier-generator/) · [CSS Loader Generator](https://sarvkit.com/DesignKit/css-loader-generator/) · [Border Radius Generator](https://sarvkit.com/DesignKit/border-radius-generator/) · [CSS Triangle Generator](https://sarvkit.com/DesignKit/css-triangle-generator/) · [Color Shades Generator](https://sarvkit.com/DesignKit/color-shades-generator/) · [Color Mixer](https://sarvkit.com/DesignKit/color-mixer/) · [Contrast Checker](https://sarvkit.com/DesignKit/contrast-checker/) · [SVG Blob Generator](https://sarvkit.com/DesignKit/svg-blob-generator/) · [SVG Pattern Generator](https://sarvkit.com/DesignKit/svg-pattern-generator/)

---

## `</>` DevKit — Developer & Converter Tools

**Suite home:** **<https://sarvkit.com/DevKit/>** · 37 tools + 21 articles

[QR Code Reader](https://sarvkit.com/DevKit/qr-code-reader/)

[Sample File Generator](https://sarvkit.com/DevKit/sample-file-generator/) · [Corrupt File Generator](https://sarvkit.com/DevKit/corrupt-file-generator/) · [Mock Data Generator](https://sarvkit.com/DevKit/mock-data-generator/) · [JSON Formatter](https://sarvkit.com/DevKit/json-formatter/) · [Base64 Encoder/Decoder](https://sarvkit.com/DevKit/base64/) · [Hash Generator](https://sarvkit.com/DevKit/hash-generator/) · [Diff Checker](https://sarvkit.com/DevKit/diff-checker/) · [Color Converter](https://sarvkit.com/DevKit/color-converter/) · [Case Converter](https://sarvkit.com/DevKit/case-converter/) · [Cron Parser](https://sarvkit.com/DevKit/cron-parser/) · [Subnet IP Enumerator](https://sarvkit.com/DevKit/subnet-ip-enumerator/) · [CSS Minifier](https://sarvkit.com/DevKit/css-minifier/) · [HTML Minifier](https://sarvkit.com/DevKit/html-minifier/) · [HTML Entities](https://sarvkit.com/DevKit/html-entities/) · [Image Compressor](https://sarvkit.com/DevKit/image-compressor/) · [Image to Base64](https://sarvkit.com/DevKit/image-to-base64/) · [JSON ↔ TOML](https://sarvkit.com/DevKit/json-toml/) · [YAML ↔ TOML](https://sarvkit.com/DevKit/yaml-toml/) · [Chmod Calculator](https://sarvkit.com/DevKit/chmod-calculator/)

---

## ✏️ TextKit — Text & Writing Tools

**Suite home:** **<https://sarvkit.com/TextKit/>** · 17 tools + 20 guides

[Image to Text (OCR)](https://sarvkit.com/TextKit/image-to-text/)

[Headline Analyzer](https://sarvkit.com/TextKit/headline-analyzer/) · [Readability Checker](https://sarvkit.com/TextKit/readability-checker/) · [Text to Slug](https://sarvkit.com/TextKit/text-to-slug/) · [Text to Braille Translator](https://sarvkit.com/TextKit/braille-translator/) · [Bionic Reading Generator](https://sarvkit.com/TextKit/bionic-reading/) · [Text to Handwriting](https://sarvkit.com/TextKit/text-to-handwriting/)

---

## About SarvKit

- **Live site:** [https://sarvkit.com](https://sarvkit.com/)
- **About:** [https://sarvkit.com/about/](https://sarvkit.com/about/)
- **Contact:** [https://sarvkit.com/contact/](https://sarvkit.com/contact/)
- **Privacy:** [https://sarvkit.com/privacy/](https://sarvkit.com/privacy/)
- **Terms:** [https://sarvkit.com/terms/](https://sarvkit.com/terms/)
- **Sitemap:** [https://sarvkit.com/sitemap.xml](https://sarvkit.com/sitemap.xml)

### Why SarvKit?

- **Browser-based tools** — document processing happens locally; supporting assets may require network downloads
- **No sign-up, no paywall, no email capture**
- **Mobile-first** responsive design across every tool
- **SEO-optimized** with structured data, OG images and canonical URLs
- **Fast** — static HTML served from Cloudflare's global edge with HTTP/3

---

© SarvKit · Built with ❤ for the open web · Visit **<https://sarvkit.com/>**
