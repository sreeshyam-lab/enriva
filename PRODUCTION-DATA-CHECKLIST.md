# Enriva Global — Data needed to go live

`Enriva-Global-Landing.html` is a polished **preview** with realistic placeholder content. Below is exactly what to replace before publishing. Items marked **⚠ legal** must be accurate — they are claims to regulators and buyers.

---

## 1. Certifications & compliance ⚠ legal
The badge strip is the page's #1 trust driver. Each badge must be true and ideally backed by a document.

| Badge shown | What's needed | Notes |
|---|---|---|
| APEDA Registered | RCMC / registration number | Confirm the product category is covered |
| FSSAI | License number | Only if applicable to your processing |
| ISO 9001 | Certificate + issuing body | Remove if not yet certified |
| IEC · ICEGATE | Importer-Exporter Code | Standard for any Indian exporter |
| Phytosanitary | Confirm you can obtain per shipment | Issued by Plant Quarantine, per consignment |
| SGS Lab-Tested | Lab name + a sample report PDF | Could be SGS or any NABL-accredited lab |

➡ **Remove any badge you cannot substantiate.** A fake cert is worse than a missing one. Supply PDFs for any "Download report" links.

## 2. Product specifications
Confirm the real, lab-verified figures (currently illustrative):
- NPK values — Powdered (3.5·1.5·1.5) and Cake (3.0·1.0·1.0)
- Moisture %, shelf life, odour claim
- **HS code** — shown as `3101 00 99`; confirm with your CHA/customs broker
- Packaging — confirm 25kg / 50kg PP bags (and any other options)
- A **datasheet / TDS PDF** to link from the "Download datasheet" buttons

## 3. Export & logistics terms
Verify each figure with your freight forwarder:
- **MOQ** (shown 1×20ft FCL ≈ 28 MT)
- **Container loadability** (shown up to 28 MT / 20ft) — depends on bag density
- **Incoterms** — FOB Cochin / CIF GCC; confirm which you offer
- **Lead time** (shown 2–3 weeks after PO)
- **Payment terms** (shown TT / LC, advance + balance on B/L)
- Document set you actually provide (Phyto, CoO, lab report, packing list, invoice, B/L)

## 4. Social proof — replace the demo content ⚠
- **Testimonial** is currently invented. Replace with a real buyer quote + attribution (with permission), or remove the section.
- **Ports / countries served** (UAE Jebel Ali, Saudi Dammam, Qatar Hamad, Oman Sohar) — list only markets you've actually shipped to, or reword to "We ship to" as a capability.
- Optional but powerful: number of containers/MT exported to date, years in operation, client logos.

## 5. Contact details
- Confirm **WhatsApp / phone**: currently `+91 80899 23923` (used in 4 places + the form submit + floating button).
- Confirm **email**: `info@enrivaglobal.com`.
- The quote form currently opens **WhatsApp pre-filled**. For a real inbox/CRM instead, we'd wire it to a form backend (Formspree, Google Forms, or your own endpoint) — decide which.

## 6. Imagery
- Current photos are your real farm shots (good — keep using real, not stock).
- For best quality/performance, supply: 1 strong **hero image** (landscape, ~1600px), 2 farm/process images, and ideally **product close-ups** (powder + cake bags) which the page could use in the grades section.

## 7. Arabic translation review ⚠
- The EN/AR toggle uses Modern Standard Arabic written for this draft. **Have a native Arabic speaker proofread** the hero, CTAs, FAQ and form before launch — especially the phone-number direction and any technical terms.

## 8. Technical / hosting (developer tasks)
- **Compile Tailwind to a static CSS file** (currently loaded via CDN). Fixes page-speed and the Subresource-Integrity security warning; required for a fast production page.
- Add a **favicon** and confirm the `<title>` / meta description / OpenGraph image once hosted on the real domain.
- Set up the **domain + HTTPS hosting** (the `.planning` exclusion in the repo suggests a static deploy is already in place).
- Optional: privacy note / terms link in the footer, and analytics (e.g. GA4 or Plausible) to measure quote-form conversions.

---

### Fastest path to launch
1. Send me: real **cert numbers/PDFs**, confirmed **specs + HS code**, confirmed **export terms**, real **WhatsApp/email**, and one **real testimonial** (or say "remove it").
2. Decide form destination: **WhatsApp (current)** or a **form backend/CRM**.
3. I'll drop in the real data, compile the CSS for production, add the datasheet PDF link, and hand you a deploy-ready build.
