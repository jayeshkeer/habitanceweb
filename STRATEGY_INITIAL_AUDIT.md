# Habitance — Initial Audit and Prioritised Gaps

**Audit basis:** latest strategy brief supplied in `pasted_content_5.txt`, the parent public-site audit, the current local preview implementation, and the supplied HOS evidence/ledger summary.
**Scope:** marketing website strategy, information architecture, evidence use and conversion readiness. This is not a fresh live login, interaction, responsive, build or browser-console verification.

## Executive conclusion

Habitance has the foundations of a credible category-creation site, but the current experience is split between two different stories:

- **Public production (`www.habitance.in`):** the parent audit found an older six-scene design concept, including supplied user logos, the committee “second full-time job” headline, and an inactive walkthrough/no-mail path. It should not be treated as current product proof or as a working enquiry journey.
- **Current local implementation:** the seven-step `QuickPreview` has a stronger evidence-led narrative, privacy-safe production captures and four detail routes. Its principal weakness is not lack of material; it is repeated philosophy across pages and the absence of a genuine practical conversion destination.
- **Authoritative product evidence (`live.habitance.in` / supplied pack):** the reviewed captures show identifiable HOS surfaces and a narrow meeting-lifecycle view. They do **not** establish an end-to-end automated matter workflow, operational outcomes, compliance, or successful downstream actions.

**Recommended direction:** preserve the existing brand, components, evidence registry and routes; upgrade `/` into the main narrative preview; retain the prior concept at `/design-reference` so no reference material is lost; preserve `/quick-preview` as an alias; consolidate the category reveal into Home while retaining a purposeful, shorter Discover HOS page. Add only the two genuinely missing audience purposes—**For Your Society** and **Residents**—and do not fabricate a form, assessment score, booking, email destination or submission confirmation.

## 1. Findings by audit surface

### 1.1 Public production site — observed, not adopted as product proof

The public root currently represents an older six-scene direction rather than the latest evidence-led experience. The older concept is useful as brand/reference material, particularly its committee-specific recognition hook and user-supplied logos, but it contains illustrative/synthetic material that must not be presented as live HOS capability.

The public walkthrough/contact path is inactive and no working public mail or scheduling destination was identified. Therefore the current public site cannot honestly claim that a visitor can request a demo, submit an enquiry, receive a confirmation, or begin an assessment.

### 1.2 Current local preview — strongest reusable base

The current implementation contains:

- a seven-step `QuickPreview` story;
- shared `PreviewFrame` / `PreviewHeading` presentation components;
- reusable `ProductEvidence` entries and viewer behavior;
- four supporting routes: Discover HOS, How HOS Works, Governance & Visibility, and Explore the Platform;
- reviewed, privacy-safe evidence entries for Command Center, priorities, Operations Genie, meeting governance, structure, handover and walkthrough.

The implementation already expresses the necessary care: people retain authority; screenshots are surfaces rather than proof of every action; empty states and inaccessible areas are qualified; and the preview is view-only. The main content problem is **philosophy duplication**, not missing explanatory volume.

### 1.3 Evidence boundary

The raw pack of seven reviewed, privacy-safe assets is usable for the website. The evidence ledger and supplied metadata remain the source of capture status; this audit did not independently re-verify a production session.

The safest demonstrated visual workflow is the bounded meeting sequence:

> **Agenda Prep → In Session → Compilation → Review / Sign → Archive**

This should be described as a visible lifecycle/workspace sequence, not as proof that evidence automatically becomes a decision, approval, assignment, execution, verification and outcome. The previous localhost/synthetic society prototype and its illustrative six-scene material must not be reused as live product evidence.

## 2. What to preserve

1. **Committee-first recognition.** Retain the original headline, **“Your society committee shouldn't be a second full-time job.”** It is more concrete and empathic than a generic software headline. The category line **“Your society has everything. Except an operating system.”** is better used as the later reveal/bridge or a test variant, not as an automatic replacement.
2. **Brand and visual language.** Preserve Habitance as the standalone Society Operating System / Platform. Keep Avensis separate and never imply that Avensis is a prerequisite, service layer or upsell.
3. **Continuity motif and human authority.** Retain the concise continuity idea—people change, context should remain—while making the committee/manager the decision-maker. Do not position HOS as a ticketing-only helpdesk or as a replacement for statutory/professional judgment.
4. **The current QuickPreview story arc.** The seven sequential scenes are a useful modular base. Upgrade their order and distinctness rather than replacing the implementation wholesale.
5. **Authentic evidence.** Keep the privacy-safe Command Center capture as initial tangible proof. Reuse the reviewed registry entries for priorities, meeting, structure, handover, Genie and walkthrough with capture-specific captions and limitations.
6. **Candid caveats.** Preserve view-only status, screenshot provenance, privacy-safe framing, empty-state caveats, and the statement that visible controls do not independently verify successful actions or outcomes.
7. **Existing routes/components.** Preserve working navigation, `ProductEvidence`, shared preview framing, zoom/viewer behavior and all current supporting URLs. Avoid unrelated changes to the HOS application.

## 3. What should improve

### Home (`/`)

Make Home the complete desire-building narrative rather than a gateway to another explanation. Shape it as approximately nine varied chapters, not nine repeated text panels:

1. **Recognition:** committee responsibility should not become a second job.
2. **Hidden problem:** chats, files, people and follow-ups can fragment context.
3. **Missing layer:** records and applications alone do not preserve shared operating context.
4. **Category reveal:** Habitance is the Society Operating System.
5. **Experience:** Command Center oversight → Today’s Priorities → the bounded meeting lifecycle; explicitly illustrative where linkage is not proven.
6. **Outcomes:** clearer oversight, visible governance and continuity as supported aims, not guaranteed results.
7. **Product proof:** a small number of screenshots, beginning with Command Center, each stating exactly what it visibly establishes.
8. **Imagine the society:** committee, manager and resident implications framed as questions/possibilities, not customer claims.
9. **Next step:** transparent exploration only; no inactive booking/contact cue.

Use Home for the emotional recognition and category reveal. Link to supporting pages for depth, not for the visitor's first understanding of why the category matters.

### Supporting pages

- **Discover HOS:** shorten into a “category in practice” page. Keep the distinct explanation of Command Center, priorities, governance and handover surfaces; remove the second landing-page philosophy essay.
- **How HOS Works:** center on the narrow five-stage meeting lifecycle. Explain the relationship between priorities and meeting governance as adjacent visible surfaces, not as a proven causal handoff.
- **Governance & Visibility:** focus on authority, accountability, roles, records, follow-ups, attention signals and continuity. Distinguish visible structure from proof of permissions, completion or retained history.
- **Explore the Platform:** organize the seven existing captures by seven distinct operational questions—Command Center, Today’s Priorities, Operations Genie, Meeting Governance, Committee & Office Bearers, Handover Readiness and Daily Walkthrough. Use one capture per use case, with one specific non-claim each.

## 4. Duplication to remove

| Repeated theme | Recommended owner | Treatment elsewhere |
|---|---|---|
| “Society Operating System” category explanation | Home | Discover HOS keeps only a short bridge and concrete surface evidence. |
| People change / context remains / continuity | Home | Governance & Visibility applies it specifically to roles, records and handover. |
| Priorities, meeting stages and work progression | How HOS Works | Home previews the bounded proof; Explore labels the relevant screens. |
| Governance, authority and compliance caveats | Governance & Visibility | Home keeps one short boundary statement. |
| Screenshot provenance and human authority | Shared preview notice | Keep only capture-specific limits beside each image; avoid repeating the full disclaimer on every page. |
| Discovery-link card teasers | Navigation layer | Keep links, but do not reproduce each destination's full introduction on Home. |
| Generic evidence → approval → execution → verification → outcome chain | None until evidenced | Remove from visible claims or label it explicitly as a future walkthrough question. |

## 5. Prioritised gaps and actions

### P0 — blocks a credible release

1. **No genuine conversion destination.** Contact settings, public email and scheduler details are not supplied/verified. Resolve the owner-approved destination and test it end to end before presenting a request/demo CTA. Until then, use a read-only **download/share society brief** fallback that does not imply that a request was sent.
2. **Public root is behind the intended strategy.** Upgrade `/` to the evidence-led narrative preview. Keep the older concept available at `/design-reference`; do not silently discard it or promote its illustrative material as product proof.
3. **Evidence wording risks overclaiming.** Constrain the proof to visible surfaces and the five-stage meeting lifecycle. Do not claim automatic handoffs, assignments, execution, verification, compliance, outcomes, valid signatures or successful export from still images.
4. **Conversion language must be honest.** No pretend assessment scores, fake enquiry forms, inactive buttons, booking confirmation, “we received your request” message or implied live scheduling until a real destination is authorized and verified.

### P1 — materially improves comprehension and conviction

5. **Remove philosophy duplication.** Reassign each idea to one page using the table above; preserve contextual links so depth remains available.
6. **Make the narrative progression visible.** Pair the committee-specific recognition headline with the later category-reveal headline; sequence concrete problem → missing layer → HOS category → bounded evidence → implications.
7. **Make evidence legible and selective.** Home should use only the strongest few captures; Explore should render the seven reviewed assets once each with use-case captions and precise limitations.
8. **Clarify page purpose in navigation.** Keep the main navigation simple and make Home the primary destination. Preserve route meaning, aliases and existing shared rendering rather than adding parallel pages.
9. **Add missing audience purposes only.** Create **For Your Society** for an honest adoption conversation and **Residents** for a share/recommendation journey. Neither should compete with the committee-first primary path or force role selection before the core proposition is understood.

### P2 — verify after content/route changes

10. **Responsive and interaction checks.** Verify scroll chapters, screenshot viewer/zoom, internal links, aliases, mobile layout and animation behavior. Do not report these as complete until actually tested.
11. **Evidence and privacy QA.** Re-check every public asset for identifiers, simulated values and misleading empty states; preserve originals unchanged and use sanitized copies.
12. **Product verification backlog.** When access is available, test resident identity/unit linkage, Vault and Finance routing, seeded topology, native mobile walkthrough, live audio/video meeting behavior and any real handover/history retention. Keep blocked/unseeded/locked states distinct from product absence.

## 6. Recommended information architecture

| Route | Status | Visitor question / job |
|---|---|---|
| `/` | **Refine / primary** | Why does my society need an operating system? |
| `/quick-preview` | **Preserve alias** | Compatibility entry to the main preview. |
| `/design-reference` | **Retain reference** | What was the earlier six-scene concept? Not live product proof. |
| `/quick-preview/discover-hos` | **Refine, retain route** | What is HOS, and which visible surfaces make the category tangible? |
| `/quick-preview/how-hos-works` | **Refine, retain route** | How does the bounded meeting/operating sequence appear? |
| `/quick-preview/governance-visibility` | **Refine, retain route** | How can structure and records support accountability while authority stays human? |
| `/quick-preview/explore-platform` | **Refine, retain route** | What do the reviewed HOS screens visibly show? |
| `/for-your-society` | **Create only for distinct adoption purpose** | How can a committee explore fit and next steps for its own society? |
| `/residents` | **Create only for distinct advocacy purpose** | How can a resident understand, share or recommend HOS to the committee? |

The category explanation should be consolidated into Home, but Discover HOS remains meaningful as a shorter supporting evidence page. No additional feature, industry or campaign pages are justified by this audit.

## 7. Conversion recommendation

The intended journey remains:

> **Discover → Experience → Assess → Plan adoption**

The site can currently support **Discover** and **Experience** through the narrative and reviewed evidence. **Assess** and **Plan adoption** are incomplete because no verified society-specific intake, email or scheduler destination is available.

### Safe interim path

- Home and supporting pages use an informational “Explore for your society” link only if it lands on a real, tested page.
- `/for-your-society` explains what a genuine conversation would cover—existing arrangements, operating priorities and an implementation path—without pretending to score the society.
- Provide a **society brief download/share** as the fallback action if no enquiry destination is approved.
- State plainly that no request is submitted from the preview and that contact/scheduling is not active.

### Once an owner-approved destination exists

Replace the fallback with the simplest real enquiry or scheduling mechanism, state what happens next, test the success/error states, and only then use conversion language such as request, schedule or submit. Never add pricing, guarantees, customer outcomes or compliance commitments without approval and evidence.

## 8. Claims that remain unverified

The following must remain out of factual product claims until independently verified:

- end-to-end evidence → decision → approval → responsibility → execution → verification → outcome linkage;
- automatic transitions, assignment, execution, completion or downstream commitment creation;
- successful minutes export/download, legally valid signatures or reliable historical retrieval;
- permissions, actual committee-role assignment, complete exception detection or compliance;
- completed handover/readiness, continuity across real personnel changes or operational outcomes;
- Operations Genie answer quality, grounded reasoning or automatic action—the capture shows a reasoning state without a completed answer;
- native mobile patrol, camera capture or offline sync from the desktop walkthrough image;
- live audio/video deliberation, resident portal behavior, Vault/Finance routing or tenant topology where the ledger reports blocked, locked, isolated or unseeded status;
- any live booking, enquiry submission, email delivery, scheduling confirmation or demo request.

A zero count, stable-status banner, empty state, vacant role, 100% walkthrough card or visible control is a captured state—not proof of successful operations or compliance.

## 9. Reuse decision

**Reuse and refine:** `QuickPreview`, `previewCopy.ts`, `PreviewFrame`, `PreviewHeading`, `ProductEvidence`, shared navigation, viewer behavior, the four existing discovery routes and the seven reviewed privacy-safe evidence entries.

**Consolidate:** the category/philosophy reveal belongs primarily on Home. Discover HOS becomes a concise supporting “category in practice” page rather than a second landing page.

**Retain without promotion:** the older six-scene concept at `/design-reference`, including its brand/reference value but not its synthetic or illustrative material as live evidence.

**Create only:** `/for-your-society` and `/residents`, because they answer distinct adoption/advocacy questions absent from the current preview. Their conversion mechanics remain gated by the missing verified destination; do not create any additional pages or fake workflow.

## Final release gate

The strategy is ready to implement as a targeted refinement when the following are true:

- `/` carries the complete recognition-to-category-to-proof story;
- the old concept is preserved at `/design-reference`, and `/quick-preview` remains valid;
- each supporting route has one distinct job and materially less repeated philosophy;
- all seven evidence entries have precise visible-fact captions and non-claims;
- the Home/How HOS Works language uses only the bounded meeting lifecycle where evidence supports it;
- public contact behavior is either a real tested destination or an explicitly labeled society-brief fallback;
- no page claims a submitted request, assessment score, booking, verified outcome or automated end-to-end workflow without evidence;
- navigation, responsive behavior, interactions, asset privacy and available build checks are actually run and reported—not assumed.

## Owner-provided conversion destination — audit addendum

After the initial inspection, the owner supplied **hello@habitance.in**. The refinement can therefore implement a genuine pre-filled email request, with a downloadable/copyable society brief as an alternative. Clicking opens the visitor's email application; visitors review and send themselves. This is not a server submission or a scheduling confirmation. Recipient deliverability and email sending will not be tested by transmitting a real enquiry. This update supersedes the missing-contact recommendation above; all product-evidence limits remain unchanged.
