# Habitance OS — view-only narrative preview

## Current direction and low-risk interpretation

The user requests a quick **view-only version** of the attached desire/differentiation/conversion brief. Implement it inside the existing Habitance project at `/quick-preview`, retaining the current approved homepage at `/`. This makes the new positioning easy to review without replacing the prior design or changing the published website. Do not publish or enable integrations.

The preview tells one story: societies should not depend on someone remembering everything. The landing page creates recognition, curiosity, reframing, desire and product discovery; the deeper pages explain the intended HOS approach. Avoid a conventional SaaS brochure, screenshots, dashboards, excessive feature grids, metrics, customer claims, fear or promises of perfection. Habitance remains standalone; do not introduce Avensis.

## Narrative and content

A. Hook: “Your society shouldn't depend on someone remembering everything.” Explain connected decisions, responsibilities and follow-through, with one primary CTA to Discover HOS.

B. Make the problem personal: three short familiar moments about the lost context behind a decision, reminders that depend on one person and work that stalls at handover. Respect volunteers; this is not a judgment of competence.

C. Reframe: “Good people need a better system.” Explain that committed people still struggle when context, responsibilities and follow-through are separated.

D. New possibility: name Habitance Operating System (HOS), connecting operational knowledge, ownership, records, decisions and follow-through. HOS supports people; authority and legal responsibilities stay with the committee. No automatic compliance promise.

E. Tangible outcome: a restrained memory-versus-continuity narrative, not fabricated UI. Show traceable context, visible responsibility, retained follow-through and history across personnel changes as intended outcomes.

F. Curiosity: four functional, content-rich, read-only routes under `/quick-preview`: `/discover-hos`, `/how-hos-works`, `/governance-visibility`, `/explore-platform`. Explain the concept and proposed product areas using the user's prior notes. No actual screenshots or live-capability claims can be verified, so the platform page explicitly describes an approach preview rather than pretending to expose a working product.

G. Invitation: “See what your society could operate like.” Primary CTA links to Discover HOS. No simulated booking form or success message. A view-only notice states that no details are submitted and booking/contact is not connected.

## Design evolution, not replacement

Reuse the supplied H symbol/full lockup, warm off-white, deep navy, terracotta brand detail, editorial serif headings, sans-serif support, existing button/focus treatments and continuity motif. Keep the approved site's restrained leaf-green accents rather than recoloring the brand. Use compact editorial sections rather than forcing each section to 100vh. The first viewport prioritizes headline, a short support and one CTA; the abstract connected-operations composition sits beside it on desktop and below it on phones. It is a semantic text illustration, not a product screenshot.

Brand essence: an operating-system approach that helps housing society committees keep people, decisions and follow-through connected. Human, assured, thoughtful. Motion: existing short reveal transitions only, with reduced-motion behavior preserved. No decorative effects or new stock assets. Full light-logo header and white-logo dark footer remain.

## Implementation and project structure

- `client/src/pages/Home.tsx`, `siteCopy.ts`, existing `/`: preserve unchanged as the approved prior design; existing quiz weights and lead validation remain staged.
- `client/src/content/previewCopy.ts`: one editable source for all new preview copy, route declarations and detail-page content.
- `client/src/components/PreviewFrame.tsx`: shared branded navigation, preview notice, footer, internal links and route-change accessibility/motion helpers.
- `client/src/pages/QuickPreview.tsx`: the seven-step landing narrative using existing brand and editorial scene primitives.
- `client/src/pages/HosDiscovery.tsx`: content-rich detail-page renderer for the four read-only topics; no empty destinations.
- `client/src/preview.css`: scoped layout refinements and responsive styles, imported after the existing stylesheet.
- `client/src/App.tsx`: add five valid preview routes without removing `/`, `/404` or fallback behavior.
- `client/public/manus-routes.json`: synchronize the six content routes; exclude APIs and 404-only pages.
- `server/preview.test.ts`: view-only source, route/content and claims assertions without database writes.
- `VIEW_ONLY_PREVIEW_REPORT.md`: section changes, final hero, CTA destinations, page list, checks and explicit limitations.

The initialized Express/Vite server stays on port 3000 with existing development/production setup. React/Wouter links are local navigation only. No changes to database schema, authentication, owner notifications, email/WhatsApp settings or server intake gate. The managed database is shared; do not write test records. Keep unknown production-domain metadata omitted, label preview pages noindex, and do not pretend that browser-only metadata is production-ready SEO.

## Scope retained from the approved design

The current `/` homepage retains its six scenes, Imagine/core local selectors, member-record mock, history and visibly inactive walkthrough. Logos and consent-dependent society proof remain as before. Historical design requirements and passing checks remain tracked in `TODO.md`; the new preview provides a different narrative for review, not an approved replacement or operational deployment.

## Evidence-backed refinement — 15 October 2026

The latest user brief (`pasted_content_3.txt`) supersedes the earlier absence of authentic screenshots, not the approved hook, routes, visual identity or view-only boundary. Inspect handoff → evidence pack → catalogue, then all seven images. Use the capability matrix as the status authority; broader handoff marketing suggestions do not override the user's explicit hook or guarantee exclusions. The screenshots themselves visibly identify a standalone front-end simulation. Runtime verification in the supplied pack therefore establishes demonstrated interface/workflow behavior, not independently tested production backends, banking or IoT connectivity. No access to the actual HOS codebase is available here.

Keep `/` unchanged and refine `/quick-preview` plus its four discovery pages. Do not create more routes merely for evidence. The landing page retains recognition → reframing → connected HOS → tangible evidence → discovery → invitation. Replace only the repetitive abstract before/after section with a benefit-led Operations Cockpit figure and a short continuity bridge. Use one screenshot on the landing page; preserve the hero composition and primary CTA to Discover HOS.

Deep pages: Discover HOS explains the distinction using a concrete meeting-to-mandate example; How HOS Works follows the documented voucher preparation/verification/approval sequence with the pre-approval queue; Governance & Visibility presents the AGM record, minutes export and assigned directives; Explore the Platform connects Elevation Grid to Unit Dossier and includes a Resident Portal section. Six unique screenshots will be used. The post-approval screenshot is not necessary: it repeats the finance surface, uses the same demo identity for verification/approval and cannot establish independent signatories or real NEFT settlement. Do not market those conclusions. Preserve the original seven images privately as evidence.

Screenshot captions identify authentic HOS demo captures and synthetic values, not customers or performance. The Operations Cockpit additionally identifies simulated telemetry and configuration-dependent live inputs. Screenshots retain their full aspect ratio and are losslessly encoded as WebP to project storage. A shared accessible image viewer supports native dialog close/Escape, zoom/pan and full-image access, keeping dense screens inspectable on phones without recreating or altering product UI. No screenshot interaction executes the pictured product actions.

Copy uses verified-demo surfaces rather than continuing to claim no authentic screens are supplied. Mention minutes `.docx` export, quorum/voting records, action mandates/custodians/deadlines, voucher signatory stages, elevation-to-dossier navigation, member record/parking/ledger context and resident circular/staff/amenity views, citing matrix rows in the completion report. Avoid claims of automatic physical work completion, real money transfers, universal statutory compliance, anti-fraud guarantees, real sensor installations, privacy certification, immutable production storage or vendor integrations. Omit AI/OIE and register-ingestion pipelines (implemented, not runtime-verified), partial contract automation, planned data-residency/certifications and unsupplied Daily System Report/Decision Engine screens.

New files: `client/src/content/productEvidence.ts` holds the screenshot catalogue, safe captions, dimensions and storage paths; `client/src/components/ProductEvidence.tsx` owns responsive figures/viewer; `PRODUCT_EVIDENCE_COMPLETION_REPORT.md` owns page placements, claims/status provenance, exclusions and remaining decisions. Revise existing `previewCopy.ts`, `QuickPreview.tsx`, `HosDiscovery.tsx`, scoped `preview.css`, initial preview HTML and preview tests. Asset preparation script preserves originals in `evidence/hos-pack`, generates only selected lossless assets and does not publish private source Markdown. Server/db/auth/booking integrations remain unchanged; save with auto-publication off only.

## Production evidence correction — 15 October 2026, latest brief

This section supersedes the earlier prototype-evidence recommendations. After inspection of the 16 screenshots, manifest/comparison/gaps and current UI, the initial gap analysis was recorded in `LIVE_EVIDENCE_GAP_ANALYSIS.md` before application modifications. Only production-reported screenshots from the new pack may be used as product proof. Do not reuse the previous dark-blue localhost captures, their synthetic society, or their workflow claims.

Keep the exact hook, personal recognition, category revelation, warm editorial design, true logos and all current routes. Original `/` remains a clearly labeled design draft, not live product evidence. Refine `/quick-preview` plus existing detail pages, with one Command Center figure on landing. Explain the Society Operating System category as context, responsibilities, decisions and follow-through held together rather than another app/agency; the concept flow expresses a desired operating approach, not automatic execution of every link.

Replace current voucher/elevation/resident examples: How HOS Works presents Today's Priorities and meeting lifecycle; Governance & Visibility presents committee/office bearers and handover assessment; Explore Platform presents desktop Walkthrough and Genie Reasoning. Use seven captures: 02 Command Center, 05 Priorities, 13 Completed Meeting, 15 Committee Structure, 08 Handover, 10 Desktop Walkthrough, 14 Genie. Meeting may be reused on governance where relevant. Describe visible controls/layout/stages; do not claim working export, AI success, native mobile capability, automatic mandates, verified compliance or completed execution from still images. Counts/statuses are captured tenant states, not business outcomes. Omit unverified finance/Vault/resident/populated-topology features reported in the gaps ledger.

Privacy preparation is a deterministic data-removal operation: preserve source dimensions/layout, replace reviewed sensitive regions with plain opaque masks, never reconstruct interface text. Universal header identity/account/credits region and screen-specific confidential descriptions are removed in marketing copies; zero/empty-state or status metrics are qualified, selected nonempty confidential figures masked. Full raw production screenshots and their source documents remain in `evidence/live-pack` outside public content and excluded from Git. Only safe copies go into `client/public/hos-live`, project storage and the checkpoint. Previous public `hos-evidence` assets are removed; originals retained privately. Before/after renders go under private `review/live-refinement`, delivered as a ZIP.

Reuse `productEvidence.ts`, `ProductEvidence.tsx`, `previewCopy.ts`, `QuickPreview.tsx`, `HosDiscovery.tsx`, scoped CSS, initial preview HTML and existing tests. Add reproducible privacy redaction manifest/script, gap analysis and `LIVE_EVIDENCE_VERIFICATION_REPORT.md`. Keep screenshot zoom/pan/Escape/full-image fallback, privacy caveats in both figure and dialog, reduced-motion behavior and internal CTA navigation. No architecture changes, new product integrations, data writes or public launch. Save only with auto-publication off.

## Website strategy and adoption refinement — latest brief

Initial audit completed before application edits in `STRATEGY_INITIAL_AUDIT.md`. Public homepage inspected in actual browser: original committee-first six-scene concept, no real form/contact. Declared public routes include existing four supporting destinations, which are available in the project and reused. Direct HTTP clients received 403 for some public paths while browser same-origin requests succeeded; access restrictions are not missing-page proof. Owner supplied hello@habitance.in after audit.

Upgrade this project's root `/` into the strategic primary landing preview, reusing QuickPreview and visual primitives rather than replacing the project; preserve `/quick-preview` as equivalent compatibility entry. Retain original Home source unchanged at `/design-reference`, explicitly reference-only (old concepts are not current feature proof). Do not publish the domain; deliver review preview.

Select the original committee second-full-time-job headline for immediate buyer recognition. Category headline is revealed after the hidden problem/missing layer, not used as a universal assertion that a society has every possible resource. Nine varied chapters: committee recognition, fragmented context, missing operating layer, Society Operating System reveal, narrow captured meeting lifecycle, practical outcomes as aims, selective actual product proof, implications for committee/manager/resident, society-specific next step. Two screenshot figures on landing at a time: Meeting Governance lifecycle and selectable Command Center/Today's Priorities proof; three unique captures. No fake real-time product interaction. Local stage selection changes explanatory copy only.

Reuse four supporting routes: Discover HOS short category-in-practice depth (philosophy consolidated into Home); How HOS Works narrow five-stage meeting lifecycle and questions about downstream work; Governance roles/accountability/exceptions/continuity without duplicate meeting figure; Explore all seven selected safe captures with distinct operational question/caption, each once. Add only `/for-your-society` and `/residents` for missing purposes. Resident advocacy is footer/contextual only, not a role gate or competing primary nav item. Main nav: workflow, platform, governance; primary highlighted For Your Society.

Conversion: Discover → Experience → Assess (select actual priorities, optionally describe existing arrangements) → Plan adoption (email request to owner-provided hello@habitance.in). No assessment score, claimed diagnosis, data capture API, appointment confirmation or inactive button. Society details stay in React state in the current tab; client generates a concise editable brief, download/copy alternatives and mailto with encoded body/subject. Sending is deliberately done by visitor's own email application; recipient address visible, no response-time guarantees. Local download fallback always usable; clipboard failure uses clear error/fallback, no fabricated success. Resident can copy/download a neutral committee introduction with current review-site homepage link or open an email draft addressed by the visitor. No verified resident portal claim.

New `adoptionCopy.ts` holds public recipient, utility copy and brief generation; new `SocietyAdoption.tsx` and `ResidentAdvocacy.tsx` share existing frame and styling. `MeetingLifecycle.tsx` is a labeled educational stage selector, not replicated application UI. Existing previewCopy, QuickPreview, HosDiscovery, PreviewFrame, scoped preview.css, App route definitions, manifest and initial HTML refined; tests updated for nine chapters, correct route mapping, email URL encoding, local-only planning, screenshot limits and safe fallback paths. Preserve original source, server/auth/db/intake/evidence masks; raw evidence remains private and development fs blocked. Before/after renders retained privately; audit/final strategy report and comparison ZIP delivered. Final noindex preview metadata remains until an explicitly approved launch; no automatic publication.


## Pricing page — attached implementation brief

### Scope and implementation

Add a dedicated `/pricing` route to this existing Habitance review site. Reuse `PreviewFrame`, its supplied logo, header, footer, editorial serif/sans typography, palette and existing `/for-your-society` demo/enquiry action. Add one Pricing navigation item, the new route and route-manifest entry; preserve all existing pages and behavior. Keep the pricing page noindex as part of the current preview state.

The page order is hero/pricing philosophy, calculator immediately after its intro, payment terms, optional setup/training, Referral Advantage, value-benefit sheet, AI billing transparency, FAQs, then a final CTA. The calculator uses residential flat count for a society-wide subscription, not per-person licences. Its native numeric input and slider, term radios, referral checkbox, output, quote form and copy action recalculate only in the browser.

Centralize pricing anchors, range, discounts, fees, referral rule, Indian-currency formatting and calculation functions in `client/src/content/pricingModel.ts`. Reuse the same formula for the calculator, quote, first-year comparison and output text. Retain full intermediate precision and round displayed rupee values only. Do not extrapolate above 300 flats; show a custom-quote path instead. Subscription discounts never apply to setup or training.

Create `client/src/content/pricingCopy.ts` for all headings, disclosures, terms, assumptions and FAQs; `client/src/pages/Pricing.tsx` for calculator, value comparison, quote form and page; and `client/src/pricing.css` for responsive styles scoped under `.pricing-page`. Add route/navigation integration in `App.tsx` and `PreviewFrame.tsx`, register `/pricing` in `manus-routes.json`, and add meaningful route-specific no-JavaScript HTML through `server/previewHtml.ts` while retaining preview noindex. Extend `server/preview.test.ts` and add focused pricing-model tests.

“Get My Society Quote” collects society, flat count, contact person, phone/email and chosen term, then opens a prefilled draft to the already-approved `hello@habitance.in`; it does not submit, save or email automatically. “Copy Quote” writes a clear summary locally and reports the actual clipboard outcome. `Request a Demo` and “Experience Habitance” use the existing `/for-your-society` route. No database, lead API or external integrations are enabled.

### Commercial assumptions and limits

Use the supplied Section 7 consolidated value table for display arithmetic: digitisation ₹75,000 once; manager-cost difference ₹60,000 conservative / ₹6,00,000 high annually; helpdesk ₹1,800 / ₹18,000 annually; RFQ ₹6,200 / ₹62,000 annually; preventable loss ₹2,000 / ₹10,000 annually; and productivity ₹7,300 / ₹73,000 annually. These total ₹1,52,300 and ₹8,38,000 for the first year. At 100 flats, the canonical annual term gives ₹63,000 after 30% off, producing differences of ₹89,300 and ₹7,75,000. Clearly distinguish one-time avoided digitisation expense, cash estimates and productivity value; label every value illustrative, conditional and not measured/guaranteed. Do not double count or include AI/setup/training in totals.

The attachment separately says helpdesk ₹1,500/month (=₹18,000/year), in conflict with its final table's ₹1,800/year conservative and ₹18,000/year high assumptions. Use the final consolidated table for this review implementation, record the discrepancy for confirmation, and do not publish. Training participation/mode/travel and final AI allowance/wallet rules also remain launch confirmations; mark them as such rather than inventing details. The manager-cost case is conditional on maintaining service quality, presence, expertise and physical responsibilities; never say Genie replaces a manager. The Mumbai digitisation benchmark is one time and depends on actual scan, verification, cleanup and entry work; do not promise free physical scanning.

### Design direction

- **Design Movement:** Existing contemporary editorial institutional aesthetic; no generic SaaS pricing-card grid.
- **Core Principles:** Show value before asking for price; make the quote legible and society-level; separate assumptions from proof; be candid about commercial and integration limits.
- **Color Philosophy:** Warm cream and pale sage make a financial decision calm; deep navy adds institutional confidence; muted/accent green emphasizes selected terms and payable figures; terracotta is reserved for validation/friction.
- **Layout Paradigm:** Long editorial page with the calculator and quote in an aligned split composition, then quieter ruled sections and compact disclosures; retain generous whitespace.
- **Signature Elements:** Large serif headlines, fine section rules and a navy quote-summary panel with controlled green emphasis.
- **Interaction Philosophy:** Native label/input/fieldset/radio/checkbox/details semantics, keyboard operation and immediate local recalculation; no hidden server submission.
- **Animation:** Reuse restrained existing reveals only; obey reduced-motion behavior; never animate or conceal price changes.
- **Typography System:** Reuse Habitance's existing serif display and clean sans body; use readable aligned rupee figures.
- **Brand Essence:** A candid institutional subscription for housing societies that supports committee oversight and continuity; calm, credible, practical.
- **Brand Voice:** Direct and commercially confident without overpromising: “The subscription is for the society—not individual user licences.” / “Illustrative potential value, based on stated assumptions—not guaranteed savings.”
- **Wordmark & Logo:** Use existing supplied Habitance lockup and symbol in `PreviewFrame`; do not create a competing mark.
- **Signature Brand Color:** Deep navy `#17293A`.

### Project structure and material constraints

`client/src/content/pricingModel.ts` owns the canonical rate/quote/value mathematics; `pricingCopy.ts` owns editable copy and assumptions; `pages/Pricing.tsx` owns the interface and local state; `pricing.css` owns scoped styles. Existing route/navigation files expose the page. `server/previewHtml.ts` serves meaningful non-JavaScript preview content, with `preview.test.ts` covering route and copy boundaries; dedicated pricing-model tests cover formula edges. No dependencies are required. Preserve noindex/preview status, no backend capture, no user data persistence and no publication.


## Homepage refresh — current Command Center and Genie demonstration (21 October 2026)

Continue in the existing Habitance WebDev project. Preserve the nine-chapter homepage, all established routes, existing brand identity and the preview-only boundary. Reuse the current editorial cream/navy/sage style and place the new experience inside the existing homepage's product-evidence chapter rather than rebuilding the page or changing the CTA.

Use the owner-supplied updated Command Center screenshot as the only current HOS interface capture. Keep its supplied pixels and aspect ratio, show it with clear point-in-time / unverified-outcome qualification, and remove prior interface captures from all visible pages and publicly served project assets because the owner has said they are no longer valid. Update discovery copy and no-JavaScript HTML where references to those images or their captured states would otherwise persist.

Copy the supplied Genie HTML to a versioned project public asset and present it on the homepage in a titled, accessible, responsive sandboxed iframe with a direct-open link. The supplied implementation has no backend/API call: its spinner and result are scripted; the report body is a fixed Horizon Demo sample; operational controls alter only local presentation; and the Word download action is only an alert. Preserve useful sample interactions, but make these limits prominent inside and outside the iframe, avoid collecting real society/member information, and change placeholder actions/status labels that imply real AI, record lookups or generated document exports. Add route-manifest and noindex handling for the standalone demo asset and retain a meaningful no-JavaScript fallback. Do not connect Genie, use the database, send data, or enable publication.

Responsibilities remain in existing modules: `QuickPreview.tsx` owns homepage composition; shared copy and evidence metadata remain in `client/src/content/`; screenshot viewing remains in `ProductEvidence.tsx`; `HosDiscovery.tsx` and its shared data cover deeper pages; `previewHtml.ts` covers initial HTML; `manus-routes.json` lists user-facing pages; the isolated demo lives under `client/public/`.


### User refinement — original Genie sample and integrated Command Center composition (21 October 2026)

The pump scenario introduced during the first pass is not approved. Restore the exact original example and answer content from `/home/ubuntu/upload/habitance_genie_assistant.html` (including the Flat 15 / Sameer transfer example, sample workflow and original Genie response). Keep the page honest by labeling the content as the supplied scripted Horizon Demo example—not a live AI response or verified legal advice—and keep actual actions local-only. Do not rewrite or replace Genie’s answers. Preserve a prominent disclaimer that the legal/statutory material is illustrative, unverified and must be checked with a qualified professional.

Re-compose the existing homepage Command Center scene so the owner-supplied screenshot is visually integrated into the editorial layout as an atmospheric background/visual layer, not a standalone gallery card. Preserve the original screenshot and point-in-time caveat; retain a keyboard-accessible affordance to inspect the full capture. Use the current cream, navy and sage language, with a mobile treatment that does not obscure the page copy or make the evidence unreadable.
