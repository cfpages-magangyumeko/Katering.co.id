# Topical Authority — Katering.co.id

## Role and boundary

Katering.co.id is an Indonesian catering-commerce and buyer-education property. Its useful editorial role is to help households, event organizers, offices, schools, institutions, and procurement teams translate a meal requirement into a safe, suitable, verifiable catering brief and purchase. The existing site already sells daily, boxed, buffet, gubukan, tumpeng/liwetan, wedding, aqiqah, Ramadan, child, diet, vegetarian, and institutional formats.

This authority plan covers catering decisions, menu systems, quantities, procurement, food safety, allergen communication, halal assurance, production, logistics, service, and post-event control. Existing commercial routes remain the owners of direct quote, package, availability, and order intent. Editorial pages must not claim that Katering.co.id operates in a location, holds a certification, employs a named expert, achieved a result, or offers a current price unless current business evidence supports it.

No article in this plan is a city, province, or region name swap. A location page is justified only by verified local operations and materially distinct logistics, supply, regulation, or case evidence.

## Evidence audited

- Canonical-repository check on 2026-07-23: `cfpages-magangyumeko/Katering.co.id`, branch `main`, HEAD `37fb190c48d40a6ee0a3f3c68e4cf57e61aeb6c0`, is the plausible deployed source. It contains the live site's 660-page static WordPress export, canonical-rewrite workflow, and the same navigation, titles, and contact details observed at `https://katering.co.id/`.
- Duplicate candidate: `Tim-SEO-PT-LAN-Magang/katering.co.id`, branch `main`, HEAD `509f39947d00fbc61a8a3b296c0f7f58ea95866d`, last pushed in 2023. It contains only 19 HTML files versus 660 in the newer repository. Cloudflare Pages binding should still be checked before any code deployment; this documentation commit does not change the live site.
- Tracked source: 1,570 files, including 660 HTML pages and 8 XML sitemap-related files.
- `sitemap-complete.xml`: 660 page URLs. The conventional child maps contain 26 page entries and 489 post entries, but `/berita` occurs in both, leaving 514 unique child-map URLs. The complete sitemap adds 146 archive/pagination surfaces that are absent from those child maps.
- Existing route inventory: homepage; 24 first-level service/about/contact routes; 488 root-level `catering-<location>.html` pages; and 147 author, category, and news archive/pagination HTML files.
- Existing first-level commercial topics: halal, healthy, diet, vegetarian, daily, lunch, weekly, baby/MPASI, children, school, office, ration/tiffin, rice box, snack box, buffet, gubukan, tumpeng/liwetan, birthday, wedding, aqiqah, sahur, and Lebaran.
- Sitemap infrastructure includes two index-like files, three post sitemaps, one page sitemap, a 660-URL complete sitemap, and a 500-entry video sitemap. The live value and uniqueness of the video entries require manual verification.
- Sampled homepage and first-level pages show strong commercial claims such as “100% dijamin halal,” weight-loss implications, low-price claims, broad nationwide delivery language, and testimonials. Those are claims to verify, not evidence to repeat in editorial content.
- No repository-local `AGENTS.md`, topical-authority plan, article catalog, or documentation index existed before this audit.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Commercial homepage and navigation hub; broad quality, price, chef, hygiene, reach, and testimonial claims | expand | Homepage remains service hub; `KAT-01` owns neutral buyer education | Verify operating entity, actual fulfillment model, chefs, testimonials, service area, price freshness, and hygiene evidence |
| `/halal/` | Commercial halal page with an absolute guarantee in its title | manual review | `/halal/` owns offer/certificate disclosure; `KAT-09` owns neutral halal education | Verify certificate number, product and facility scope, validity, suppliers, process, and current BPJPH rules before any guarantee |
| `/sehat/`, `/diet/`, `/vegetarian/` | Commercial special-menu pages; “healthy” and weight-loss language can become health claims | manual review | Existing routes own the offers; `KAT-08` and `KAT-10` own risk-aware education | Registered dietitian review where health outcomes or therapeutic suitability are discussed; verify recipes, nutrition data, and cross-contact controls |
| `/bayi/`, `/anak/`, `/sekolah/` | Vulnerable-audience menu offers, including MPASI | manual review | Existing routes own the offers; `KAT-10` owns life-stage education | Pediatric/dietitian and food-safety review; verify texture, age suitability, allergens, holding, and institutional requirements |
| `/harian/`, `/makan-siang/`, `/mingguan/`, `/rantangan/`, `/kantor/` | Recurring meal services with overlapping duration, audience, and delivery intent | keep | Commercial routes retain transactional intent; `KAT-14` owns recurring-program design | Redraw copy and canonicals after query/lead review; confirm each route has a distinct offer and fulfillment workflow |
| `/nasi-kotak/`, `/snack-box/`, `/prasmanan/`, `/gubukan/`, `/tumpeng-liwetan/` | Service-format pages; some overlap around event feeding | keep | Existing route owns quote intent; `KAT-03` and `KAT-13` own menu/format decisions | Verify package contents, equipment, staffing, minimum order, time limits, and current prices |
| `/ulang-tahun/`, `/pernikahan/`, `/aqiqah/`, `/sahur/`, `/lebaran/` | Occasion pages; religious and ceremonial claims require care | keep | Existing routes own packages; `KAT-15` owns planning education | Verify religious guidance with qualified reviewer, actual packages, deadlines, slaughter/supplier evidence, and seasonal capacity |
| `/catering-*.html` (488 URLs) | Large location-swapped set with visibly repeated commercial structure and some questionable place-name combinations | manual review | Keep only URLs backed by real serviceability and unique local evidence; otherwise consolidate to an appropriate service-area owner | For every URL verify demand, fulfillment radius, local partner, address/coverage, unique logistics, leads/backlinks, indexation, and content uniqueness before keep/redirect/noindex |
| `/author/syamsul-alam/page/*`, `/category/catering/page/*`, `/berita/page/*` (147 HTML files in total) | Thin archive and pagination surfaces that duplicate discovery paths | noindex | Main articles, service hubs, and a single useful news index own discovery | Verify index status, inbound links, pagination canonicals, and whether any archive has independent user value |
| `sitemap.xml`, `sitemap_index.xml`, `sitemap-complete.xml`, child sitemaps | Two identical index files, a broader complete sitemap, and duplicate `/berita` entries make indexation monitoring noisy | canonicalize | One maintained sitemap index should own discovery | Verify which file is submitted in Search Console and served in `robots.txt`; reconcile the 514 unique child-map URLs with the 660-URL complete map before changing submissions |
| `video-sitemap.xml` (500 entries) | Very high video count relative to visible unique editorial assets | manual review | Only pages with accessible, page-specific video should remain | Validate each video URL, thumbnail, title, embed, playback, and page relevance against current search requirements |

The highest risks are not missing volume. They are unverified safety/health/halal assertions, unclear fulfillment evidence behind 488 location pages, overlapping recurring-service routes, thin archives, and a static export that can make stale claims difficult to govern.

## Coverage matrix

| Completeness lens | Topic owner(s) | Coverage decision |
|---|---|---|
| Definition, vocabulary, taxonomy, history | `KAT-01`, `KAT-03`, `KAT-13` | Cover catering models, Indonesian service terms, menu structure, and service-format evolution |
| Anatomy, components, materials, mechanisms | `KAT-03`, `KAT-07`, `KAT-11`, `KAT-12`, `KAT-13` | Treat ingredients, kitchen flow, packaging, heat/cold control, and service equipment as connected systems |
| Measurement and calculations | `KAT-04`, `KAT-05`, `KAT-12` | Portions, yield, buffers, price composition, holding and delivery timing |
| Need recognition and briefing | `KAT-01`, `KAT-02` | Decide when catering is appropriate and convert a situation into a usable brief |
| Survey, requirements, comparison, selection | `KAT-02`, `KAT-06`, `KAT-13` | Guest constraints, vendor evidence, tasting, and format decisions |
| Budget, procurement, contracts | `KAT-05`, `KAT-06` | Quote normalization, scope gaps, payment, cancellation, evidence, and acceptance |
| Preparation, production, commissioning | `KAT-11`, `KAT-12`, `KAT-13` | Procurement, batch control, dispatch, setup, service checks, and handover |
| Use and operation | `KAT-13`, `KAT-14`, `KAT-15` | Event service, recurring programs, and occasion-specific operations |
| Inspection, troubleshooting, repair/recovery | `KAT-07`, `KAT-12`, `KAT-16` | Stop conditions, late delivery, temperature/packaging defects, complaints, recall, and recovery |
| Upgrade, replacement, decommissioning | `KAT-14`, `KAT-16` | Program review, vendor change, leftover disposition, and waste improvement |
| Stakeholders | all topics | Buyer, household, event organizer, procurement, kitchen operator, service crew, institution, vulnerable consumer, and guest paths |
| Site type and scale | `KAT-02`, `KAT-04`, `KAT-13`, `KAT-14` | Home, venue, office, school, institution, small meeting, and large event without place-name doorway pages |
| Geography and climate | `KAT-07`, `KAT-12` | Indonesia's heat, humidity, rain, traffic, power, and last-mile realities; location articles require real local evidence |
| New setup versus existing program | `KAT-02`, `KAT-14` | New event/program design versus audit and correction of an existing service |
| DIY versus professional | `KAT-01`, `KAT-07`, `KAT-13` | Safe self-planning versus tasks requiring caterer, trained food handler, dietitian, laboratory, or authority |
| Quality levels | `KAT-05`, `KAT-06`, `KAT-13` | Economical, standard, premium, temporary, and institutional needs without equating price with safety |
| Safety and health | `KAT-07`, `KAT-08`, `KAT-10`, `KAT-12` | Strongest evidence gate; no diagnosis or unsupported suitability/health claims |
| Standards and regulation | `KAT-07`, `KAT-08`, `KAT-09`, `KAT-10` | Recheck current Indonesian primary sources at publication; separate ready-to-eat catering from packaged-food rules |
| Environmental impact | `KAT-11`, `KAT-12`, `KAT-16` | Procurement, packaging, portions, leftovers, measurement, and truthful waste reduction |
| Evidence quality and myths | `KAT-06`, `KAT-07`, `KAT-08`, `KAT-09`, `KAT-10` | Certificates, records, measurements, expert review, and explicit limits replace slogans |
| Search formats | all topics | Hubs, decision tables, calculators, checklists, diagrams, workflows, evidence templates, and genuine case studies only |
| News/trends | N/A | No standing news topic: short-lived food trends are not maintainable authority assets unless they materially change procurement, law, or operations |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KAT-01 | Dasar dan model layanan katering | Understand what type of catering service fits the job and when catering is not the best option | Catering versus restaurant delivery and meal prep; full-service versus drop-off; one-off versus subscription; central kitchen versus partner network; service vocabulary; buyer responsibilities | Service-model diagram, glossary, decision tree, sourced explanation | Neutral education only; package availability and ordering remain on `/` and first-level commercial routes | 6 |
| KAT-02 | Discovery, requirement, and catering brief | Turn guest, venue, timing, and risk constraints into a complete vendor brief | Guest profile; schedule; venue access; utilities; dietary data; service level; rain/power contingencies; approval chain; change control | Downloadable brief, venue-survey checklist, responsibility matrix, timeline | Does not calculate portions (`KAT-04`), evaluate vendors (`KAT-06`), or sell an event package (commercial routes) | 6 |
| KAT-03 | Menu architecture and Indonesian food systems | Build a balanced, operationally feasible menu rather than a random dish list | Meal components; flavor/texture/color balance; Nusantara diversity; menu rotation; ingredient seasonality; production compatibility; menu naming; beverage and snack roles | Menu matrix, sensory map, sample structures clearly labeled as examples, culinary expert review | Does not prescribe therapeutic diets (`KAT-10`), calculate quantities (`KAT-04`), or quote packages (`/nasi-kotak/`, `/prasmanan/`, other routes) | 6 |
| KAT-04 | Portions, yield, and quantity planning | Calculate a defensible order quantity and buffer for a defined service format | Edible portion; raw-to-cooked yield; guest mix; attendance uncertainty; buffet refill; box counts; beverage/ice; crew/vendor meals; waste-sensitive buffers | Calculator specification, worked examples, yield table with sourced assumptions, reconciliation sheet | Does not set selling prices (`KAT-05`) or decide menu composition (`KAT-03`) | 6 |
| KAT-05 | Budget, quote, and contract economics | Compare total catering cost and negotiate a clear, fair commercial scope | Cost components; per-person versus package pricing; tax/service/transport/equipment; minimums; overtime; deposits; cancellation; change orders; payment milestones; hidden exclusions | Quote-normalization table, total-cost worksheet, contract checklist, accountant/legal review where needed | Does not rank vendor quality (`KAT-06`) or publish current Katering.co.id prices (commercial routes) | 6 |
| KAT-06 | Vendor due diligence and quality evidence | Verify that a caterer can safely and reliably deliver the promised scope | Legal identity; service area; kitchen evidence; SLHS/certificates; halal scope; references; tasting; capacity; staffing; contingency; subcontractors; red flags; acceptance evidence | Evidence-request checklist, tasting scorecard, comparison matrix, source-verification links | Does not guarantee a vendor or replace authority inspection; Katering.co.id offer proof belongs on its commercial/about routes | 6 |
| KAT-07 | Food safety, hygiene, and incident prevention | Recognize critical controls, unsafe shortcuts, and stop/escalate conditions across the catering chain | Biological/chemical/physical hazards; hand hygiene; cross-contamination; time-temperature control; water/ice; cleaning/sanitizing; pests; illness; samples/records; recall/escalation | Process-flow diagram, hazard-control table, checklists, current Kemenkes/BPOM sources, food-safety expert review | General education, not certification or incident diagnosis; allergens are owned by `KAT-08` and verified operator claims by commercial routes | 6 |
| KAT-08 | Allergens, intolerances, and cross-contact communication | Collect, communicate, and verify special-food risk information without promising zero risk | Allergen versus intolerance; ingredient declarations; hidden ingredients; shared equipment; segregation; labels; guest communication; emergency boundary; packaged versus ready-to-eat rules | Allergen matrix, communication card, process map, BPOM primary sources, dietitian/food-safety review | Does not diagnose allergy, promise allergen-free food, or design therapeutic menus (`KAT-10`) | 6 |
| KAT-09 | Halal assurance for catering | Evaluate halal evidence as an end-to-end ingredient and process system | Certificate verification; scope and validity; ingredients; slaughter/meat suppliers; kitchen/equipment; storage; transport; subcontractors; audit trail; claims and deadlines | BPJPH links, certificate-check workflow, supply-chain diagram, qualified halal reviewer | Does not issue religious rulings or claim Katering.co.id is certified; actual offer/certificate disclosure belongs on `/halal/` | 6 |
| KAT-10 | Nutrition, dietary patterns, and life-stage menus | Ask better questions about nutrition and suitability while knowing when professional review is required | “Healthy” claim limits; diet and vegetarian patterns; nutrient balance; sodium/sugar/fat; child/school needs; baby/MPASI stop conditions; older adults; medical diets; nutrition information | Dietitian-reviewed decision tables, claim checklist, current Kemenkes/BPOM sources, explicit referral points | No diagnosis, weight-loss promise, infant feeding prescription, or disease-treatment menu; commercial offers remain on `/sehat/`, `/diet/`, `/vegetarian/`, `/bayi/`, `/anak/`, `/sekolah/` | 6 |
| KAT-11 | Kitchen production, sourcing, and quality control | Understand how purchasing and batch production affect consistency, safety, and capacity | Approved suppliers; receiving; storage; FIFO/FEFO; recipe specification; batch scaling; prep sequence; change control; tasting/retention records; equipment capacity; staff handoff | Kitchen-flow diagram, batch sheet, receiving checklist, original process evidence, culinary/food-safety review | Not a DIY certification manual; dispatch/transport is owned by `KAT-12` and quoteable capacity by commercial routes | 6 |
| KAT-12 | Packaging, holding, dispatch, and delivery | Specify packaging and a delivery plan that protects food and service readiness | Package-food compatibility; seals and labels; hot/cold holding; loading; route buffers; rain/traffic; handover; missing/damaged items; remote-site limitations; reusable packaging | Packaging decision table, dispatch checklist, timeline, temperature-record template, field measurements | Does not choose service format (`KAT-13`) or claim a universal safe holding duration without validated product/process evidence (`KAT-07`) | 6 |
| KAT-13 | Service formats, equipment, setup, and guest flow | Select and operate box, buffet, gubukan, plated, tumpeng/liwetan, or hybrid service coherently | Format comparison; table/queue layout; replenishment; serving ware; fuel/electric needs; accessibility; signage; staff roles; setup/strike; weather and venue constraints | Floor-flow diagrams, equipment checklist, decision matrix, genuine venue case only | Does not design dishes (`KAT-03`) or publish package prices/availability (existing format routes) | 6 |
| KAT-14 | Recurring office, school, household, and institutional catering | Design, monitor, and improve a repeat meal program | Subscription cadence; menu cycle; attendance/order cutoff; service-level agreement; delivery windows; feedback; absence/holiday handling; billing; vendor transition; school/institution safeguards | SLA template, menu-cycle calendar, KPI dashboard, feedback form, procurement review | Does not prescribe nutrition (`KAT-10`) or duplicate transactional pages `/harian/`, `/kantor/`, `/sekolah/`, `/mingguan/`, `/rantangan/` | 6 |
| KAT-15 | Social, religious, and seasonal occasion planning | Plan food service around the real sequence and meaning of an occasion | Wedding run sheet; birthday guest mix; aqiqah scope and religious review; tumpeng/liwetan presentation; Ramadan meal timing; Lebaran volume; gifts/take-home packs; family approvals | Occasion-specific timelines, question lists, qualified religious/cultural review, genuine case evidence | Does not issue religious rulings or sell packages; commercial intent belongs on `/pernikahan/`, `/ulang-tahun/`, `/aqiqah/`, `/sahur/`, `/lebaran/`, `/tumpeng-liwetan/` | 6 |
| KAT-16 | Handover, complaints, leftovers, waste, and improvement | Close a catering job safely, resolve failures fairly, and improve the next order | Acceptance check; shortage/late/damage triage; complaint evidence; food-safety escalation; refund/remedy records; leftover decision; donation constraints; waste measurement; post-event review | Handover checklist, incident tree, complaint evidence template, waste log, current food-safety guidance | Does not promise legal entitlement, diagnose foodborne illness, or recommend unsafe leftover reuse; contract rights belong to `KAT-05` and hazards to `KAT-07` | 6 |

## Related-domain opportunities

- `WeddingEvent.co.id` may independently cover the full event-production viewpoint and link conceptually to catering run sheets; overlap across domains is permitted and is not cannibalization.
- `Franchisee.id` and `Franchisor.id` may independently discuss catering-business systems or franchise due diligence from their own network perspectives.
- `Jemaah.id` may independently cover community-meal governance, Ramadan service, or aqiqah from a faith/community perspective, with qualified religious review.
- Katering.co.id should not use cross-domain links as a fabricated network or ranking scheme. Link only when the destination materially completes the reader's task and ownership/editorial independence is transparent where relevant.

## Consolidation plan

1. Establish one canonical sitemap index and reconcile it with Search Console before changing any sitemap file.
2. Export performance, indexation, backlinks, leads, and actual fulfillment evidence for all 488 location URLs. Keep and materially rewrite only real service-area pages with unique operational evidence; do not create more location variants.
3. Review the 147 archive/pagination files. Prefer `noindex,follow` or removal from sitemaps where they add no independent value, while preserving crawl paths through hubs.
4. Separate overlapping recurring-service routes by intent: cadence (`/harian/`, `/mingguan/`), container/service (`/rantangan/`), audience (`/kantor/`, `/sekolah/`), and meal window (`/makan-siang/`). Merge or canonicalize only after query and lead evidence.
5. Audit every health, diet, child, baby, halal, hygiene, price, service-area, capacity, testimonial, and certification claim. Remove or qualify unsupported claims before using those pages as authority evidence.
6. Validate `video-sitemap.xml` against genuinely embedded, indexable, page-specific videos. Do not treat repeated thumbnails or boilerplate video metadata as 500 editorial assets.
7. Preserve useful existing commercial URLs. New informational articles should occupy distinct slugs and link to a commercial route only when a buyer is ready for the next step.

## Internal-link architecture

- `/` links to the central `KAT-01` buyer guide and all verified commercial formats; the buyer guide returns readers to the correct commercial route only after explaining the decision.
- Each topic hub links to all six children. Every child links back to its hub and to two or three task-adjacent pages named in `ARTICLE_CATALOG.md`.
- Requirement flow: `KAT-01` → `KAT-02` → `KAT-04` → `KAT-05` → `KAT-06`.
- Safety flow: `KAT-07` ↔ `KAT-08` ↔ `KAT-09` ↔ `KAT-10`; every high-risk menu or logistics page links to the relevant stop conditions.
- Delivery flow: `KAT-11` → `KAT-12` → `KAT-13` → `KAT-16`.
- Program flow: `KAT-03` + `KAT-10` → `KAT-14`; occasion flow: `KAT-02` + `KAT-13` → `KAT-15`.
- Diagnostic pages link to prevention, immediate containment, evidence collection, and the appropriate professional/authority escalation. They must not funnel an active safety incident straight into a sales CTA.
- Do not add identical “related article” blocks site-wide. Links should reflect the decision, risk, or lifecycle transition on the specific page.

## Evidence and editorial standards

- Recheck law and guidance on the publication date. As of this audit, primary starting points include [PP 86/2019 on Food Safety, as amended by PP 1/2026](https://peraturan.bpk.go.id/Details/129230/ppno-86-tahun-2019), [Permenkes 2/2023 on environmental health implementation](https://jdih.kemkes.go.id/pdfjs/web/viewer.html?file=https%3A%2F%2Fjdih.kemkes.go.id%2Fstorage%2Fdocuments%2Fpdfs%2F2023permenkes002.pdf), and the [Kemenkes ready-to-eat hygiene/SLHS registry](https://tpm.kemkes.go.id/rbi/web).
- Use [BPOM's current labeling and allergen guidance](https://rumahsiripo.pom.go.id/peraturan/label/contoh-label-pangan-olahan/) where packaged-food rules are applicable. Explicitly distinguish retail packaged food from ready-to-eat catering; do not transfer a rule between scopes without checking.
- Verify halal process, certificate scope, and timelines through [BPJPH's certification service](https://bpjph.halal.go.id/read/sertifikasi-halal) and current BPJPH regulations. A logo, supplier assertion, or pork-free recipe is not by itself proof of end-to-end certification.
- Nutrition, “healthy,” weight, infant/child, allergy, medical-diet, and foodborne-illness content requires qualified professional review. State stop conditions and referral paths; do not diagnose or guarantee outcomes.
- Food-safety procedures require current primary guidance, product/process-specific limits, and trained operator review. Never invent a universal holding time, temperature, shelf life, or sanitizing concentration.
- Prices, capacities, service areas, certificates, package contents, testimonials, and case outcomes require dated first-party records. Examples must be labeled hypothetical unless supported by real documentation and consent.
- Use original kitchen/venue photographs only with consent and captions explaining what the image proves. Do not use decorative imagery as evidence of hygiene, capacity, or compliance.
- For calculations, expose assumptions, units, buffer logic, and rounding. Encourage post-event reconciliation so future estimates improve.
- Indonesian should be direct, practical, and buyer-centered. Avoid unsupported superlatives, fear-driven food-safety copy, and interchangeable AI summaries.

## First bounded publication cluster

Publish 12 P0 assets in Wave 1:

1. `KAT01-01` central catering-selection guide.
2. `KAT02-01` complete catering brief.
3. `KAT03-01` balanced menu architecture.
4. `KAT04-01` portion and buffer calculation.
5. `KAT05-01` total-cost quote comparison.
6. `KAT06-01` vendor evidence checklist.
7. `KAT07-01` catering-chain hazard map.
8. `KAT08-01` allergen-information workflow.
9. `KAT09-01` halal certificate verification.
10. `KAT12-01` packaging decision guide.
11. `KAT13-01` service-format comparison.
12. `KAT16-01` delivery handover checklist.

This cluster follows one real purchase from definition to brief, menu, quantity, cost, verification, safety, packaging, service, and acceptance. It also creates evidence templates that can expose unsupported claims on existing pages before more content is published.

Monitor: indexation and sitemap discovery; impressions and clicks by distinct intent; brief/checklist completion; assisted clicks to the correct commercial route; qualified inquiries with complete requirements; lead response and conversion; post-event complaint/shortage rate where business data exists; and same-domain query overlap. Ranking alone is not the success condition.

## Definition of done

- All 16 parent topics have six distinct, validated briefs: 96 articles in total.
- Every title, ID, and slug is unique; every slug is checked against all 660 existing HTML routes and proposed routes.
- Each brief has one primary intent, a concrete coverage promise, an explicit owner for excluded intent, evidence requirements, and valid related IDs.
- The 12-asset first wave is edited and reviewed before later waves are commissioned.
- High-risk articles pass the required food-safety, dietitian, halal, religious, legal, or regulatory review before publication.
- Existing location, archive, sitemap, video, and commercial-claim risks have evidence-led decisions; “manual review” is not treated as permission to mass-delete or redirect.
- Internal links form usable decision and lifecycle paths; no article is orphaned.
- Search visibility is connected to qualified inquiries, fulfillment, conversion, and collected revenue where applicable.
