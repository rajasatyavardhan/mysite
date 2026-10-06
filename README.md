# Telodynamic V2

Development branch for the Telodynamic website redesign.

## Architecture
- Home: concise cinematic introduction and capability gateways
- Services: telemanipulators, hot cells, hot-cell windows, interactive explainers
- Products: filterable product catalogue
- About: company positioning and Inspect → Diagnose → Engineer → Service → Verify process
- Contact: maintenance / failure / custom-solution enquiry flow

## Development notes
- Existing `CNAME` is intentionally preserved for the eventual upstream merge.
- Temporary external imagery is marked in the UI and must be replaced with approved Telodynamic equipment photography before production sign-off.
- No unverified certifications, customer counts, years, technical specifications or regulatory claims are included.
- The existing Telodynamic Formspree endpoint is retained on the Contact page.

## Finalisation checklist
1. Replace all placeholder imagery with client-approved assets.
2. Verify service/product wording and approved company/founder information with Pavan.
3. Test Formspree delivery and mobile layouts.
4. Run Lighthouse accessibility/performance checks.
5. Review SEO metadata, social preview image and legal pages if required.
6. Open a PR back to `Telodynamic/mysite` only after client review.
