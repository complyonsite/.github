# ComplyOnSite directory gallery: titles, captions and alt text

Five 1270 × 760 images, in gallery order. Each comes as a PNG (lossless, full colour) and a WebP (lossy, quality 88). Image 1 leads with the company and the full range of tools; images 2 to 5 cover one tool each.

## Provenance and limitations

- **The screen in every image is a real capture of a public page**, cropped and pasted at 1:1. It has not been scaled, stretched, retouched or redrawn. Only the corners are rounded. The headings, bullet points, frame and orange band are added marketing copy.
- **The data on screen is public example data, not customer results.** The RAMS example (Hollins & Reed Electrical Ltd), the waste transfer note example (Example Builders Ltd) and the RAMS review sample (Fernhollow Scaffolding Ltd) are fictional. The HAVS figures are a worked example.
- **Captures used:** `company-tools-public.png`, `rams-builder-public-example.png`, `rams-review-public-sample.png`, `waste-transfer-note-public-example.png` and `havs-calculator-example-392-points.png`, all in `output/tool-listings/captures/`. `rams-review-public-hero.png` was not used.
- **Image 1** shows the waste and exposure groups on the tools page. RAMS Builder and RAMS review are named in its text but are not in that part of the capture.
- **Image 2** shows the filled-in RAMS example under the builder, not the builder's editing steps. **Image 4** shows the filled-in example note, not the on-screen signing step. Their captions say so.
- **Image 5:** the Hours field shows a text cursor after the "1", as it was captured.
- **Facts checked against source:**
  - RAMS Builder: no account, saves in the browser, PDF built on the device (`src/pages/rams/index.tsx`).
  - Waste transfer note: phone, on-screen signing, PDF, the four UK nations, starting from EWC finder codes (`src/features/wasteTransferNote/tool.ts`, `src/features/ewc/EwcCodeFinderPage.tsx`).
  - RAMS review: three Quick reviews a day per device without an account (`QUICK_DAILY.anonymousDevice`), and it does not approve a RAMS (`ramsReview/tool.ts` on the worktree that matches `main`).
  - HAVS: the values come from the capture.
- **Not claimed:** that every tool is free, any approval or sign-off, customer numbers, endorsements or video.
- **Rebuild:** `python3 _build_gallery.py <repo root> <captures dir> <this directory>` (needs Pillow). It rewrites the images and `gallery-manifest.json`.

## 1. ComplyOnSite: construction health and safety software for UK site teams

Files: `01-complyonsite-construction-health-safety-software-tools-1270x760.png`, `01-complyonsite-construction-health-safety-software-tools-1270x760.webp`

Source capture: `output/tool-listings/captures/company-tools-public.png`

Caption: ComplyOnSite helps UK contractors, subcontractors and waste operators with site paperwork: build a RAMS, review one before work starts, fill in waste transfer and consignment notes, and estimate vibration and noise exposure. The screenshot shows part of the public tools page, with the waste and exposure tools.

Alt text: ComplyOnSite graphic headed "Construction health and safety software for UK site teams", listing Build RAMS (RAMS Builder), Review RAMS (RAMS review), Waste paperwork (transfer and consignment notes) and Exposure tools (HAVS and noise). Below is a screenshot of the ComplyOnSite tools page: a Waste group with cards for the EWC code finder, waste transfer note, hazardous waste consignment note and Defra Receipt of Waste spreadsheet checker, and a Vibration, noise and dust group with the HAVS and noise exposure calculators.

## 2. RAMS Builder: write a RAMS for your job and download the PDF

Files: `02-rams-builder-risk-assessment-method-statement-1270x760.png`, `02-rams-builder-risk-assessment-method-statement-1270x760.webp`

Source capture: `output/tool-listings/captures/rams-builder-public-example.png`

Caption: Choose the type of work, fill in the job details and work through the method statement and risk assessment, then download the RAMS as a PDF. No account is needed, and your draft is kept in your browser as you go. The screenshot is the builder's public filled-in example; the company and people in it are fictional.

Alt text: ComplyOnSite graphic headed "Build a RAMS for the job", with the points no account needed, saves as you go in this browser, and the PDF built on your device. Beside it is a screenshot of a filled-in RAMS example for an electrical job at a workshop in Stockport, with company, site, dates, person in charge and team, then the first method statement steps: set up the work area, isolate and prove dead, check permits before work.

## 3. RAMS review: points to raise, each marked on its page

Files: `03-rams-review-source-linked-points-1270x760.png`, `03-rams-review-source-linked-points-1270x760.webp`

Source capture: `output/tool-listings/captures/rams-review-public-sample.png`

Caption: Upload a RAMS PDF, yours or a subcontractor's, and get a list of points for a competent reviewer to raise. Open a point to see the words it comes from highlighted on the page. Three Quick reviews a day are free without an account; Full and Max reviews use credits. RAMS review does not approve a RAMS. The screenshot is the public sample review of an invented scaffolding RAMS.

Alt text: ComplyOnSite graphic headed "Check a RAMS for the points to raise", noting that each point links to the words on its page, that the tool does not approve the RAMS, and that three Quick reviews a day are free while Full and Max reviews use credits. Below is a screenshot of the sample review of FSL-RAMS-0042 Scaffold to the Rear Elevation: page 2 of the RAMS with two lines highlighted, and the open point "No rescue plan for the MEWP", marked Changes needed, asking for the MEWP rescue plan or Appendix C. Other points listed include Exclusion zone has no size and Tie pattern needs checking.

## 4. Waste transfer note: fill it in, sign on screen, share the PDF

Files: `04-waste-transfer-note-phone-signatures-pdf-1270x760.png`, `04-waste-transfer-note-phone-signatures-pdf-1270x760.webp`

Source capture: `output/tool-listings/captures/waste-transfer-note-public-example.png`

Caption: Fill in a non-hazardous waste transfer note on your phone, have both parties sign on screen, then share the PDF. Codes found in the EWC code finder can start the note. For England, Wales, Scotland and Northern Ireland, with a hazardous waste consignment note tool alongside. The screenshot is the public filled-in example; the names and numbers are made up.

Alt text: ComplyOnSite graphic headed "Waste transfer notes on your phone": fill in the note, both parties sign on screen, then share the PDF, for non-hazardous waste in England, Wales, Scotland and Northern Ireland. Points listed: start from codes found in the EWC code finder, a blank template to print, and hazardous waste consignment notes too. Beside it is a screenshot of a waste transfer note example marked EXAMPLE: mixed construction and demolition waste from a kitchen refit, List of Waste code 17 09 04, one 8-yard skip, with the transferor Sam Carter of Example Builders Ltd, SIC code 41202, acting as producer, and the waste hierarchy declaration.

## 5. HAVS calculator: estimate one worker's daily hand-arm vibration

Files: `05-havs-calculator-daily-vibration-exposure-1270x760.png`, `05-havs-calculator-daily-vibration-exposure-1270x760.webp`

Source capture: `output/tool-listings/captures/havs-calculator-example-392-points.png`

Caption: Add each tool a worker uses and how long it runs in their hands to estimate their daily hand-arm vibration exposure. In this example, a breaker at HSE's figure of 14 m/s² for one hour gives an HSE estimate of 392 points, with a tool data range of 98 to 648, above HSE's action level. It is an estimate to plan with, not a measurement or a promise that the work is safe. A noise exposure calculator is also available.

Alt text: ComplyOnSite graphic headed "Estimate daily hand-arm vibration", with an example of a breaker at 14 m/s² for one hour, HSE estimate 392 points with a tool data range of 98 to 648, described as an estimate to plan with, not a safe-use promise. Below is a screenshot of the HAVS calculator: tool 1 is Breaker, time in use 1 hour, HSE estimate 14 m/s². The daily exposure panel reads "Estimated above HSE's action level" and "This estimate could exceed the daily limit", with a gauge from 0 to the 400 daily limit showing HSE estimate 392 points, tool data range 98 to 648.
