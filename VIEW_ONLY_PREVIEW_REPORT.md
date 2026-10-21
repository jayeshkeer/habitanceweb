# Habitance — quick view-only preview

## What this version is

The new narrative is available at `/quick-preview` inside the existing Habitance project. The previous approved homepage at `/` is unchanged, so the two versions can be compared. This is a **read-only design and content preview**, not a deployment of the product or a live lead-generation page.

Navigation and expandable questions work. No forms, booking endpoints, customer contact, society data connections or live product workflows were added. The published website has not been changed.

## Section-by-section changes

| Section | What changed |
| --- | --- |
| A — Hook | Shifted the opening from committee workload to dependence on individual memory. One primary CTA leads to a real discovery page. The connected-history artwork is a conceptual text illustration, not a product screenshot. |
| B — Personal recognition | Replaced the feature-heavy task presentation with three familiar moments: a decision without its reasoning, a next step dependent on reminders, and a handover that requires reconstructing history. The language respects committed volunteers. |
| C — Reframing | Added “Good people need a better system.” This makes the separation of context, responsibility and follow-through the problem—not the competence of committee members. |
| D — New possibility | Introduced Habitance Operating System (HOS) as an operational-continuity approach. A restrained sequence connects context, responsibility, decision, follow-through and history. The committee retains authority and legal responsibilities. |
| E — Tangible outcome | Used a short memory-versus-continuity comparison. Retained the handover idea and member benefit, without fabricated interfaces, performance promises or perfection claims. |
| F — Discovery | Moved detailed explanations off the landing page into four substantive, linked read-only guides. No customer quotes, adoption figures or placeholder social-proof strip were added to this version. |
| G — Invitation | Ends with “See what your society could operate like.” Its CTA navigates to Discover HOS, not a simulated booking form. The preview boundary is visible in the header, footer and relevant product explanations. |

## Final hero

**Headline**

> Your society shouldn't depend on someone remembering everything.

**Supporting copy**

> Decisions, responsibilities and follow-ups deserve a shared system—not one person holding everything together.

**Personal-benefit line**

> More continuity for your society. More room for your life.

The direct memory-dependence headline was chosen over the change-of-personnel question because it explains the broader problem immediately. Handover then becomes a concrete consequence later in the story.

## CTA labels and destinations

| Label | Destination | Purpose |
| --- | --- | --- |
| Discover a better way | `/quick-preview/discover-hos` | Primary hero CTA |
| Explore the idea | `#explore-hos` | Header scroll navigation to the discovery links |
| See the difference | `#recognition` | Optional scroll cue below the hero |
| Discover HOS | `/quick-preview/discover-hos` | Final primary CTA and discovery navigation |
| Back to the overview | `/quick-preview` | Header link on each deeper page |
| Continue exploring | Next page in the four-page sequence | Keeps discovery moving without dead ends |

The four discovery rows and footer links lead to the substantive pages below. No CTA claims to create a booking, send a message or connect society data.

## Deeper pages created

| Page | Route | Content |
| --- | --- | --- |
| Discover HOS | `/quick-preview/discover-hos` | Difference between storing records and connecting society operations; systems that support people; key boundaries. |
| How HOS Works | `/quick-preview/how-hos-works` | A maintenance-renewal example connecting context, responsibility, decisions, execution and retained history. |
| Governance & Visibility | `/quick-preview/governance-visibility` | Evidence, recorded reasoning, role-appropriate visibility, member permissions and retained committee authority. |
| Explore the Platform | `/quick-preview/explore-platform` | Intended role of the Daily System Report, Decision Engine, society records, operational follow-through and member visibility. Explicitly not a live product demonstration or confirmation of feature availability. |

Each guide has topic-specific explanations, two expandable questions and working next/back/footer navigation. The navigation sequence connects all four guides and returns to the overview.

## What was preserved

The actual supplied Habitance logos, dark/light treatments, terracotta logo detail, warm off-white/navy palette, editorial typography, existing focus styles and reduced-motion behavior are retained. The previous homepage and its local-only selectors remain intact. Existing authentication, server health, database schema, stored-lead implementation and paused email/WhatsApp settings were not changed or exercised with visitor data.

Preview-specific initial HTML includes its own title, description, readable content and `noindex, nofollow` metadata. Existing homepage HTML remains unchanged. No production canonical URL was guessed.

## Verification

- TypeScript check and production build passed.
- **28 unit tests passed** across four test files, including the original validation/platform tests and seven new preview tests.
- Diff whitespace checks passed.
- The original homepage, all five preview routes and the existing health endpoint returned HTTP 200 on the public preview origin.
- Desktop (1280px), tablet (768px) and phone (390px) renders were inspected. The phone first viewport includes the hook, support and primary CTA; the full phone narrative and platform guide were rendered as well.
- Browser checks verified the primary CTA, all four page transitions, expandable questions and return navigation. No runtime errors were captured during those transitions; images loaded and no horizontal overflow was detected at the browser's checked viewport.
- The preview contained no form/input controls or data-submission calls. No test leads or society records were created.
- Independent read-only review found no material narrative, routing, claims or preservation defects. Its missing-report finding is resolved by this handoff document.

## Not verified or activated

This version does not demonstrate real HOS interfaces, bank/government actions, AI execution, permissions enforcement, legal compliance or feature availability. Those require actual product evidence. No booking, WhatsApp, email, analytics configuration or production publication was performed. Production-host behavior, search indexing and real-device/network performance were not tested.

## Decisions for a later phase

The only next design decision is whether to make this narrative the default homepage. Actual screenshots and verified product capabilities are needed before presenting deeper pages as a live platform demonstration. Booking/contact settings, privacy copy and production launch remain a separate approved phase. Habitance remains standalone; no Avensis positioning was introduced.
