# GLHIGA Website — Georgia Life & Health Insurance Guaranty Association

Complete 8-page responsive website. Every page is fully self-contained: all images,
logos, and PDF documents are embedded directly in the HTML. No assets folder is
required for the pages to work.

---

## What's in this zip

### `/website` — the deployable site (use this one)
The 8 pages, cross-linked by real filenames. Upload this folder's contents to your
web host and `index.html` becomes the homepage.

| File | Page | Intended URL |
|------|------|--------------|
| `index.html` | Homepage | `/` |
| `about-us.html` | About Us | `/about-us` |
| `faqs.html` | Frequently Asked Questions | `/faqs` |
| `receiverships.html` | Receiverships | `/receiverships` |
| `additional-information.html` | Additional Information | `/additional-information` |
| `insurance-companies.html` | For Insurance Companies | `/insurance-companies` |
| `links.html` | Links | `/links` |
| `contact-us.html` | Contact Us | `/contact-us` |

### `/standalone-pages` — portable copies
The same 8 pages, but linked to each other by standalone filenames. Handy for
emailing or double-click viewing without a server. Keep the 8 files together so
the navigation between them works.

### `/source-assets` — original image files
The original logo, icons, and photos. The pages do NOT need these (everything is
embedded), but they're included in case you want to edit or reuse the artwork.

---

## Site features

- **Responsive** — full nav on desktop, hamburger menu below 1040px.
- **Fonts** — Montserrat, loaded from Google Fonts (the only external request).
  Falls back to a system sans-serif if offline.
- **Embedded PDFs** — the Georgia Guaranty Association Act and the GLHIGA Plan of
  Operation download directly from the pages (About Us, Additional Information, FAQs).
- **Receiverships** — 58 companies; 55 link to their NOLHGA detail pages.
- **Links page** — dropdown of all 52 guaranty associations (URLs from NOLHGA).
- **FAQs** — 29 questions in 6 collapsible sections, plus the coverage limits table.

---

## Known placeholders / to-do

These links have no destination yet:

1. **Georgia Insurers Insolvency Pool** — "click here" in the FAQ answer
   *"What types of insurance policies and contracts are NOT covered?"* (`href="#"`).
2. **Privacy Policy** and **Terms and Conditions** — footer links on every page
   (`#privacy`, `#terms`). No pages built yet.

Also worth confirming: the coverage limits table sub-bar reads
**"July 1, 2012 – Current"** (per the supplied design), while the rest of the site
references the July 1, 2020 amendments.
