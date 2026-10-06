# Telodynamic V2 — client review

Preview: https://telodynamic-client-preview.vercel.app/

Review branch: `rajasatyavardhan/mysite`, `telodynamic-v2`.

## Ready for review

- Home: concise introduction, three capability gateways and clear enquiry actions.
- Services: the existing equipment service list, accessible keyboard tabs, a conceptual hot-cell schematic and remote-handling explainer.
- Products: five product entries from the existing catalogue, category filters and product-specific enquiry links. Technical specifications remain unpublished.
- About: focused company positioning and an interactive service-discussion process without invented founder credentials or company metrics.
- Contact: verified phone, email and Formspree endpoint; enquiry preselection; accessible form labels; success/error feedback with input retained after errors.

The navy/cyan/white/steel design is retained. Stock imagery is visibly temporary and does not depict Telodynamic equipment. The hot-cell drawing is educational, not a product design or technical specification.

## QA

Five pages tested at 320, 390, 768, 1024 and 1440 px widths: no horizontal overflow, working local links/assets and one primary heading per page. Keyboard tabs, mobile menu/Escape, filters, hot-cell markers, enquiry preselection and form success/error states checked. JavaScript-disabled service content remains available. Form responses were intercepted; no test enquiry was sent to Telodynamic. Inbox delivery still requires a coordinated live test.

Page titles, descriptions, canonical URLs, social metadata, sitemap and legacy redirects reviewed. The separate preview blocks indexing and excludes CNAME. Upstream main and the fork's main were not changed.

Automated axe-core scans at phone and desktop sizes found no reported violations after fixes. Gradient and image backgrounds require manual contrast review; this is a review check, not an accessibility certification. Hero text uses a strengthened navy overlay, and temporary-image captions use an opaque navy background.

## Before live release

1. Replace temporary photos with approved equipment photography.
2. Confirm public service/product wording and the proposed process with Pavan. Add company/founder information only if supplied and approved.
3. Confirm technical data before publishing any dimensions, materials, ratings, certifications or compliance statements.
4. Coordinate a real Formspree delivery test and confirm receipt.
5. Approve the review branch before opening or merging an upstream pull request.

No upstream pull request, domain change or live-site release is part of this handoff.
