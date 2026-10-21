# Habitance — Website Strategy and Conversion Refinement

**Review version · 15 October 2026**

[Open the refined website preview](https://8328-isy9apa9e093utj71g5ig-033c4cb2.sg2.manus.computer/)

This is a targeted refinement of the existing Habitance project, not a new project or HOS application redesign. The published `www.habitance.in` deployment has **not** been replaced. The owner-provided **hello@habitance.in** is used for a genuine visitor-controlled demonstration email, not an in-site booking.

## 1. What the audit changed

The initial audit distinguished the older public six-scene concept from the current evidence-backed preview and the supplied production screenshot pack. It found three strategic gaps: Home did not yet carry the complete category story, supporting pages repeated philosophy, and the walkthrough could not accept an enquiry.

The refinement retains the approved logos, warm editorial identity, committee-first perspective, four supporting URLs, existing evidence viewer and seven sanitized product captures. It consolidates the primary story into Home, gives supporting pages distinct jobs, and adds only two missing purposes: society-specific adoption and resident advocacy. Initial audit and priorities are recorded separately in `STRATEGY_INITIAL_AUDIT.md`, including the subsequent owner-approved email destination.

## 2. Final information architecture

| Page / route | Treatment | Distinct visitor question |
|---|---|---|
| Home `/` | Refined; reused `QuickPreview` and existing visual primitives | Why does our society need an operating system? |
| `/quick-preview` | Preserved compatibility entry to the same main narrative | Earlier review link remains usable |
| Discover HOS `/quick-preview/discover-hos` | Retained and shortened; core philosophy consolidated into Home | Where does HOS fit alongside our current arrangements? |
| How HOS Works `/quick-preview/how-hos-works` | Refined around the narrow meeting lifecycle and downstream verification questions | How does the operating sequence appear? |
| Explore the Platform `/quick-preview/explore-platform` | Refined from two examples into seven explained operating questions | What does the actual interface show? |
| Governance & Visibility `/quick-preview/governance-visibility` | Refined around roles, review, exceptions and handover | How does it support accountability while authority remains human? |
| For Your Society `/for-your-society` | Created for a missing, distinct adoption purpose | How do we start a relevant demonstration conversation? |
| Residents `/residents` | Created for advocacy; footer/contextual destination only | How can I introduce HOS constructively to our committee? |
| Earlier design `/design-reference` | Original `Home.tsx` preserved unchanged, explicitly reference-only with its own metadata | What was the earlier illustrative visual direction? |

Main navigation is limited to workflow, governance and platform depth, with **For your society** visually prioritized. Mobile uses a native disclosure menu. Residents are not an up-front role gate or competing primary journey. Existing authentication, database schema, intake gate and HOS application remain unchanged.

## 3. Selected narrative and headline rationale

> **Your society committee shouldn't be a second full-time job.**
>
> Keep decisions, responsibilities and follow-ups connected—without carrying the whole society in your head.

The original opening was retained because it immediately recognizes the buyer and the personal burden without requiring category knowledge. The proposed “Your society has everything. Except an operating system.” was evaluated as a useful category-testing direction, but not selected as the opening: it begins with abstraction and a broad assertion before the visitor recognizes their own problem. The implemented later reveal is **“Meet your Society Operating System.”** No A/B test or conversion lift is claimed.

| Chapter | Narrative job | Design treatment |
|---|---|---|
| 1. Recognition | Committee service should leave room for life | Empathetic headline, one primary action, continuity illustration—not a dashboard hero |
| 2. Hidden problem | Records exist but context and follow-ups fragment | Three familiar, non-blaming moments |
| 3. Missing layer | Committed people need more than disconnected tools | Short dark contrast chapter |
| 4. Category reveal | HOS supports an operating structure rather than merely another inbox | Context/responsibility/decision/follow-through/history motif; human-authority boundary |
| 5. Experience | Inspect one narrower, evidenced meeting lifecycle | Five explanatory stage controls and authentic Meeting Governance capture |
| 6. Outcomes | Clearer starting points, review and continuity | Editorial outcomes, framed as value to assess—not achieved results |
| 7. Product proof | Oversight and priorities have actual interface surfaces | Switch between Command Center and Today's Priorities; no product action executes |
| 8. Imagine your society | Implications for committee, manager and residents | Three concise perspectives, continuity bridge, contextual depth links |
| 9. Next step | Turn interest into a practical conversation | One society-specific action, no fake assessment or appointment |

The demonstrated visual sequence is **Agenda Prep → In-Session → Compilation → Review & Sign → Archive & Law**. These are captured stages, not independently verified successful transitions. Evidence → approval → responsibility → execution → verification → outcome is included as a **demonstration test agenda**, not a claim that every handoff already runs automatically.

## 4. Authentic screenshots and sanitization

All seven existing privacy-safe copies were reused; no new product screenshots or generated application UI were created.

| Supplied capture | Where used | What it establishes / limit |
|---|---|---|
| 02 Command Center | Home proof selector; Platform | Executive/attention/operational layout; status and zero counts are not compliance evidence |
| 05 Today's Priorities | Home selector; How HOS Works; Platform | Priorities and labelled controls; not assignment or completed execution |
| 13 Completed Meeting | Home lifecycle; How HOS Works; Platform | Named stages and download control; not successful export, valid signatures or automatic commitments |
| 15 Committee & Office Bearers | Governance; Platform | Role structure/history entry; vacant roles do not verify assignments or permissions |
| 08 Handover Readiness | Governance; Platform | Assessment categories/transition entry; not certified readiness or executed handover |
| 10 Desktop Walkthrough | Platform | Oversight perspectives and inspection layout; zero activity/100% card are not achieved results or native-mobile proof |
| 14 Operations Genie | Platform | Question interface and Reasoning state; no successful answer, accuracy or autonomous action established |

The previously reviewed opaque masks remove identifying headers, private descriptions, confidential meeting details and selected tenant counts. Source dimensions and interface layout remain intact. Originals were verified unchanged against the supplied ZIP. No reconstruction, replacement records or invented labels were drawn into product images.

A prominent **CAPTURED TENANT STATE · NOT VERIFIED OUTCOMES** notice now appears before every image and inside its enlarged viewer, alongside detailed per-capture caveats. Status values in the authentic UI therefore remain visible as captured states, not marketing success assertions.

Raw production sources stay private and excluded from the checkpoint. Obsolete prototype source files were removed from the **Git index only** and preserved locally; history was not rewritten. The internal redaction manifest was moved out of public assets, and the preparation script now writes it privately. Prior localhost/synthetic society proof is not used by the current journey.

## 5. Implemented conversion

**Discover → Experience → Assess → Plan adoption**

Visitors understand the category on Home, inspect actual interface evidence, choose relevant operating priorities, and optionally add their society name, committee role and current arrangements. These are local discussion inputs, **not a scored assessment**. They remain in the current tab and are not sent to a website API or stored in a lead database.

**Email for a tailored demonstration** opens an encoded draft addressed to **hello@habitance.in**. The draft asks the team to demonstrate a relevant matter and discuss fit, verification and an implementation path. Visitors review and send it in their own email application. No request is falsely marked received; no appointment, response deadline, activation, price or integration is promised.

Working alternatives are **Download discussion brief** and **Copy brief**, with useful feedback when clipboard access is unavailable. The recipient is visible so the downloaded text can be used in any email service. Resident advocacy separately offers a neutral committee introduction to copy/download or open in an email draft whose committee recipient the visitor chooses. It is not an adoption commitment or a claim of verified resident-portal functionality.

## 6. Checks actually performed

| Check | Result |
|---|---|
| TypeScript and production frontend/backend build | Passed |
| Unit/regression suite | **31 tests passed** across four files |
| Diff hygiene | Passed |
| Nine Home chapters, five stage selections, proof selector | Browser-tested; explanatory content updates; no pictured product action executes |
| Primary CTA and supporting routes | Real visitor browser reaches `/for-your-society`; all declared content routes HTTP 200 with meaningful initial HTML |
| Phone navigation and internal destinations | Seven main destinations inspected in 390px same-origin frames; no horizontal overflow or invalid internal links |
| Screenshot loading | All seven Platform images loaded at source width; landing and relevant detail images loaded |
| Phone viewer | Open, zoom, close, caveat visibility and returned focus passed |
| Scroll/reveals and runtime capture | All nine chapters and reveal elements reached; no captured runtime errors in exercised journey |
| Local adoption preparation | Optional inputs/priorities populate the correctly encoded owner-addressed email draft |
| Download | Browser saved discussion brief; generated file matched draft; resident download also matched introduction |
| Clipboard | Real pointer-click produced copied feedback; forced clipboard-denial test produced the download fallback |
| Privacy / no mutation | Raw evidence development path returns 403; internal audit no longer served as JSON; backend/schema/intake and original Home source unchanged; no enquiry sent |
| Metadata/fallback fixes | Preview titles/descriptions and noindex present; reference has its own title/body; generic fallback no longer leaks legacy claims; resident initial HTML uses same-site navigation |
| Visual review | Desktop, tablet and phone renders checked; before/after package includes major changes and new destinations |

Build output still reports a non-blocking large-JavaScript-chunk warning and the starter's runtime configuration script warning. No real 4G timing, assistive-technology certification or conversion experiment was performed. Email draft preparation was tested; **mail delivery, mailbox deliverability and an installed email handler were not tested by sending a message**. Mobile checks cover responsive browser layout, not native HOS.

## 7. Limits and next approval

Still unverified: successful meeting exports and valid signatures; automatic downstream commitments and verified execution; actual permission enforcement, reliable records/history across personnel changes and completed handover; Genie answer quality; resident linkage/portal behavior; isolated Vault/Finance views, populated topology, native mobile patrol/offline/camera and live audio/video. The supplied gaps ledger remains authoritative for reported capture limitations, not evidence that features are absent.

No fabricated customer evidence, savings, adoption metrics, statutory guarantees or service upsell was added. HOS remains standalone software supporting human governance; no mandatory agency arrangement is introduced.

The review preview is **noindex** and has not replaced the published domain. Before launch: approve the final story/flow, test the real recipient and visitor email handlers, confirm capability claims with product demonstrations, set production metadata/routing, and explicitly authorize publication. A server-side lead or scheduling integration can be added later if desired; it is not required for the current honest email alternative.

## 8. Before-and-after review package

`HABITANCE_STRATEGY_BEFORE_AFTER.zip` contains matched original-home and existing-narrative baseline renders against the refined main narrative, before/after Platform views, phone comparisons, and clearly labelled after-only adoption/resident pages. Full-page images may be proportionally reduced by the rendering tool; first-viewport phone/tablet images are included for legible hierarchy review. The preview's image viewer remains the best place to inspect dense product captures.

**Independent review:** A full read-only strategic/source review identified the fallback, reference metadata, private-file and evidence-qualification issues above. After corrections, a separate focused recheck found no confirmed remaining boundary defect in those items. Raw sources remain locally preserved; the forthcoming saved version removes the obsolete pack from tracked deliverables without rewriting history.
