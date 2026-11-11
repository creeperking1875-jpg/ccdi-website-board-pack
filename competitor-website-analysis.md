# Philippine diagnostic websites: content and conversion audit

**Checked:** 11 November 2026 UTC / 12 November 2026 Philippine time  
**Scope:** CCDI plus seven Philippine reference brands, with Guadalupe recorded as an evidence gap.  
**Purpose:** Decide what CCDI should shorten, preserve or move, using current first-party pages rather than assumptions about competitors.

## Bottom line

CCDI is not uniformly shorter than its competitors. Its homepage carries substantially less extracted text than Clinica Prime and Health Screen, but more than MyHealth and the text layer of Hi-Precision. It is shorter than The Medical City's hospital homepage, although that is a much broader business. Singapore Diagnostics changes position depending on whether repeated carousel text is counted; Healthway's count is also affected by repeated text. None of these comparisons establishes which site converts better.

The strongest editing case is **less repetition and a shorter first screen**, not removing the useful service explanations. CCDI already has very short collapsed service summaries. Keep the walk-in/corporate distinction, hours, location, phone access and meaningful service details. Shorten repeated positioning, simplify the booking introduction, and replace the explicit clinic-photo placeholder with appropriate photography when available.

## 1. Method and limits

### What was checked

- Public homepages, service entry points, employer/corporate pages and contact/booking entry points where identified.
- First-party pages were fetched and then inspected in a rendered desktop browser. Homepage screenshots were inspected for visual structure, photography and proof placement.
- CCDI's first service accordion was opened to distinguish collapsed copy from optional detail. No personal data was entered, no inquiry submitted and no appointment booked.
- Public package pages were sampled for price visibility. This is not a complete price or product audit.
- The Medical City here means its main hospital/network website. It is a reference for presentation, not a like-for-like single-location laboratory competitor.

### How the counts work

The tables report **rendered text-layer tokens**, not total visual words or editorial prose alone. The counting rule is whitespace-separated tokens containing at least one letter or number. Counts include headings, button labels, navigation, footer, cookie notices and calendar numbers present in the captured page state. They exclude words drawn inside images, image alternative text, closed content that is not rendered, inaccessible embedded content and later form steps.

Pages were scrolled to activate lazy sections before capture. Carousels, animations, rotating search prompts and asynchronous content can still change the count. These are dated snapshots, not permanent site specifications.

The homepage table also shows a **unique-line check**: trim each text line, collapse whitespace and count only its first exact occurrence. This helps expose carousel inflation. It also removes legitimate repeated labels and contact details, so it is a sensitivity check, not a corrected "true" word count. No manual image-word count was added, because doing so for only some sites would create a second inconsistency.

**Do not interpret the smallest count as the best site.** A photo-led page can have a tiny text layer while showing many words in graphics. A multi-branch directory or long testimonial collection has a different job from a local clinic landing page. No conversion analytics, task-completion tests, mobile audit or accessibility audit were run.

## 2. Homepage copy volume

| Site | Rendered tokens | Unique-line check | What the comparison supports |
| --- | ---: | ---: | --- |
| [CCDI](https://ccdilab.com/) | 585 | 544 | Mid-range within this sample; services and employer workflow share the homepage. |
| [Hi-Precision](https://www.hi-precision.com.ph/) | 93 | 93 | CCDI has much more text-layer copy. Hi-Precision is heavily image-led, so this is not a complete visible-word comparison. |
| [Clinica Prime](https://clinicaprime.com.ph/) | 1,795 | 1,719 | CCDI is substantially leaner in extracted text. Branch information and long testimonials account for much of Prime's volume. |
| [Singapore Diagnostics, corporate homepage](https://singaporediagnostics.com/) | 772 | 484 | Raw extraction makes CCDI look shorter; removing repeated lines reverses that result. Treat them as similar-order text volume, not a clean CCDI win. |
| [Health Screen](https://healthscreendiagnostic.com/) | 1,010 | 836 | CCDI is leaner by both measures. Health Screen combines patient information, branches, awards, franchise promotion and repeated FAQ labels. |
| [MyHealth](https://www.myhealth.ph/) | 234 | 219 | CCDI is wordier in extracted text. MyHealth uses a short hero, service titles, a product teaser and visual partner proof. |
| [Healthway](https://www.healthwaymedicalnetwork.com.ph/) | 478 | 401 | CCDI is wordier in this snapshot. Rotating testimonials and image-based offers limit precision. |
| [The Medical City](https://www.themedicalcity.com/) | 805 | 780 | CCDI is leaner in extracted text; hospital/network scope makes the comparison less direct. |

Singapore Diagnostics also has a separate [patient homepage](https://singaporediagnostics.com/patient-site/), captured at **1,083 tokens**. It includes packages, branch selection, a callback/request form and a long review collection. The corporate homepage alone does not represent its patient journey.

### What this means for "too wordy"

- **Supported:** CCDI has less extracted homepage copy than Clinica Prime and Health Screen.
- **Also supported:** MyHealth demonstrates that a broad service menu can be presented with much less homepage text. CCDI's first screen has a longer audience-specific explanation than MyHealth's hero.
- **Not supported:** "CCDI is shorter than the other labs," "more words are why people do not book," or "the shortest competitor is the best model."
- **Still a design judgment:** CCDI can feel wordy because the same facts recur, even when its total count is moderate. Hero length, line wrapping, whitespace and the tall placeholder all affect the first impression.

## 3. Key-page measurements and source index

Each number below is for the **whole page**, including its shared navigation/footer and default visible state. Comparing a service search screen with a detailed service catalog is not comparing equivalent content. A dash means no separate equivalent page was measured, not that the business lacks that service.

| Site / page purpose | Tokens | First-party URL | Interpretation |
| --- | ---: | --- | --- |
| CCDI services | 74 | [Homepage services section](https://ccdilab.com/#services) | Section only, not a separate page; includes headings, summaries and labels. |
| CCDI benefits | 115 | [Why CCDI section](https://ccdilab.com/#why-ccdi) | Section only; rendered benefit-carousel text. |
| CCDI audience workflow | 88 | [How it works section](https://ccdilab.com/#how-it-works) | Section only; walk-in and employer paths together. |
| CCDI location/contact | 276 | [Location](https://ccdilab.com/location) | Practical visit information plus shared footer. |
| CCDI corporate-call entry | 369 | [Book](https://ccdilab.com/book) | Includes calendar labels/numbers and shared footer, not just explanatory prose. |
| Hi-Precision services | 200 | [Our services](https://www.hi-precision.com.ph/our-services) | Category/service list and action shortcuts. |
| Hi-Precision corporate | 191 | [Corporate service](https://www.hi-precision.com.ph/corpservice) | Portal links, short explanation, sales inquiry and service list. |
| Hi-Precision contact | 117 | [Contact us](https://www.hi-precision.com.ph/contact-us) | Form-led page. |
| Clinica Prime services | 158 | [Services](https://clinicaprime.com.ph/clinica-prime-services/) | Search/filter entry screen, not the full catalog. |
| Clinica Prime corporate | 442 | [Corporate service](https://clinicaprime.com.ph/corporate-service/) | Employer service descriptions, proof claim, benefits and inquiry form. |
| Clinica Prime contact destination | 619 | [About/contact](https://clinicaprime.com.ph/about-us/#about-us-form) | About content and values precede the contact form within the same page. |
| Clinica Prime packages | 180 | [Packages](https://clinicaprime.com.ph/packages/) | Default executive-panel tab; other tabs/details not counted as an expanded catalog. |
| Singapore Diagnostics contact | 168 | [Contact](https://singaporediagnostics.com/contact/) | Shared corporate inquiry and branch access. |
| Singapore Diagnostics patient entry | 1,083 | [Patient site](https://singaporediagnostics.com/patient-site/) | Separate patient journey; includes reviews and request fields. |
| Health Screen lab/diagnostic services | 433 | [Services](https://healthscreendiagnostic.com/laboratory-and-diagnostic-test/) | Test/service descriptions and lists. |
| Health Screen contact | 331 | [Contact](https://healthscreendiagnostic.com/contact/) | Message form and multiple branch details. |
| Health Screen packages | 877 | [Packages](https://healthscreendiagnostic.com/packages/) | Long inclusion lists; necessary detail rather than just marketing prose. |
| MyHealth laboratory | 111 | [Laboratory and diagnostics](https://www.myhealth.ph/services/laboratory) | Short service explanation. |
| MyHealth employer/on-site | 111 | [On-site medical services](https://www.myhealth.ph/services/onsite-medical) | Short explanation, three service headings and sales email. |
| MyHealth contact | 212 | [Contact/branch locator](https://www.myhealth.ph/contact) | Multiple branches rather than a single-location visit page. |
| MyHealth packages | 408 | [Products](https://www.myhealth.ph/products) | Six package summaries in the captured listing. |
| Healthway corporate | 299 | [Corporate health solutions](https://www.healthwaymedicalnetwork.com.ph/find-care/corporate-health-solutions/) | Clinic-management scope, scale claims, program list and contact route. |
| Healthway contact | 331 | [Contact us](https://www.healthwaymedicalnetwork.com.ph/contact-us/) | Contact information and engagement options. |
| The Medical City services | 831 | [Our services](https://www.themedicalcity.com/our-services) | Extensive hospital service taxonomy; not equivalent to four local lab cards. |
| The Medical City contact | 368 | [Contact us](https://www.themedicalcity.com/contact-us) | Hospital contact page. |

**Excluded measurement:** Healthway's older [diagnostic and imaging URL](https://healthwaymedicalnetwork.com.ph/service-categories/diagnostic-and-imaging-services/) returned a substantial service listing through the page fetch, but the live browser showed "This page doesn't seem to exist." Its error-page count is excluded. This is conflicting retrieval evidence, not proof that Healthway has no diagnostic services. Navigate from its current site before relying on that older link.

## 4. Content, CTAs and booking paths

### CCDI

**Observed structure:** audience-specific hero; three trust/tenure labels; graphic photo placeholder; four service cards; benefit carousel; employer-proof strip; separate walk-in and employer steps; final contact prompt and footer.

**Observed actions:** phone link in navigation and hero; "Visit Us - Hours & Location"; "For HR Teams" scrolling to the employer workflow; corporate-call link in navigation and workflow. Services remain on the homepage rather than requiring a separate catalog page.

**Booking entry:** the corporate page explains who the call is for, asks for employee-count range, then shows a calendar. It is not an individual medical appointment scheduler. The entry headline says 15 minutes while the calendar label says 15-20 minutes. Date/time availability and final submission were not tested, so a visible calendar is not proof that a usable slot exists.

**Copy finding:** the four collapsed service summaries are only **8, 7, 5 and 7 tokens**, respectively. The first opened detail adds an **11-token** sentence about turnaround and report delivery, taking the whole services section from 74 to 85 tokens in that state. A blanket instruction to shorten every service card would target material that is already concise. The benefit section contains more explanation, but much of it answers practical questions.

**Editing opportunity:** "same standards, same staff, same turnaround" appears in both the services introduction and benefits introduction. Hours, turnaround and audience positioning recur across the hero, benefits, process and footer. Some repetition is useful at decision points; identical positioning does not need to be repeated everywhere.

### Hi-Precision

The homepage prioritizes visual banners and shortcuts. Its text layer is very small, but graphics carry visible labels that the count misses. Corporate Service is directly accessible in the navigation, so describing it as unreachable or requiring three clicks would be inaccurate.

The [corporate page](https://www.hi-precision.com.ph/corpservice) combines existing-client results/billing portals with a new-client inquiry. The inquiry says a sales specialist will get in touch and asks for company name/number, contact person, designation, email and message. This is a callback-style corporate path, not a verified live-slot booking flow. Its [services page](https://www.hi-precision.com.ph/our-services) separates home service, doctor and HMO tasks from service categories.

**Lesson for CCDI:** concise task shortcuts can replace some general explanation. Do not copy image-only information merely to lower the text count.

### Clinica Prime

The homepage offers doctor search, service browsing and package discovery before lengthy branch and testimonial content. The corporate page has its own workplace-wellness positioning, service explanations and a tailored-services inquiry form. It asks for company, phone, contact person, designation and email, with a message field. No live corporate time-slot picker was observed on that page.

Its service entry is search/filter-led. Its package page lists public peso amounts for the default executive panels. This directly contradicts a blanket claim that all comparable clinics hide their prices.

**Lesson for CCDI:** keep a dedicated employer route and useful service descriptions, but do not copy the homepage's long testimonial inventory merely because a larger clinic uses it.

### Singapore Diagnostics

There are distinct corporate and patient sites. The corporate homepage presents quality/team/network messaging, three service categories, branch access and an inquiry form. Its contact form asks for name, email, phone, company, service type and message. The quality messaging is repeated by the hero carousel, inflating raw extraction.

The patient site promotes home-service calling, packages, branches and "Request for a call back." Its request form includes lab tests, branch, date and time. Date/time fields alone do not prove a confirmed appointment or live inventory; no request was submitted.

**Lesson for CCDI:** separate audience journeys can reduce the amount each visitor needs to read, but adding a second site is not necessary for a single clinic. Clear sections or a focused employer page may be enough.

### Health Screen

The homepage is content-heavy: service and location introductions, benefit statements, awards, franchise promotion, articles, gallery and repeated FAQ questions. It is not simply a short lab brochure. Its "Book your diagnostic test today" section instructs visitors to select a branch and call its listed number. The contact page also offers a message form.

The package page gives long test-inclusion lists without a numeric fee in the captured text. That is useful evidence for **inclusions without public prices**, not evidence that fees are absent everywhere on the site or in images.

**Lesson for CCDI:** a separate inclusion catalog can preserve needed information while keeping the homepage lean. Franchise and awards content belongs only where it serves the audience.

### MyHealth

The homepage uses a brief hero and "Call Now," then mostly service titles, a featured-package teaser, partner imagery, a locator and trust/tenure statements. The laboratory page explains the service in two paragraphs. The employer/on-site page is short, lists annual checkups, vaccination and phlebotomy, and directs inquiries to a sales email.

The products listing is more descriptive than the homepage and gives package summaries. No numeric price was present in the captured listing; individual detail screens were not audited. The branch locator includes Cebu. Old claims about broken corporate pages or schedulers should not be carried over to this current site without a fresh test.

**Lesson for CCDI:** move depth to the destination page while letting the homepage act as a clear menu. This is the strongest low-copy comparator in the sample that does not depend entirely on image lettering.

### Healthway

The homepage combines service navigation, visual offers, patient testimonials and news. Current navigation includes Corporate Health Solutions and several scheduling/portal routes. It should not be described as phone-only.

The [executive health check-up scheduler](https://www.healthwaymedicalnetwork.com.ph/find-care/executive-health-check-up-scheduler/) explicitly says visitors can choose a date and time, but appointments are confirmed upon availability. It describes facility follow-up and a processing cut-off. Only the entry instructions were inspected, not a completed booking.

The corporate page emphasizes clinic management, claimed scale and programs rather than a long employer inquiry form. Phone/email remain available. The older diagnostic-listing URL produced conflicting fetch/browser results, so its price-list request cannot be treated as a fully verified current path.

**Lesson for CCDI:** name the kind of booking honestly. A requested appointment, a confirmed clinical slot and a corporate discovery call are different products.

### The Medical City

The hospital/network homepage uses a photographic campaign hero, doctor/service/HMO actions, locations, institutional proof and news. The services page is an extensive hospital taxonomy. Its JCI-related proof is a claim displayed by the site, not independently verified in this audit. A booking action is visible in the header; its completion path and corporate-specific equivalent were not audited.

**Lesson for CCDI:** clear service categories and proof placement are useful references. A hospital's content breadth and institutional claims are not appropriate targets for a small laboratory's word count or positioning.

### Guadalupe Cebu Medical & Diagnostic

Searches found directory/map references, but no first-party website was confidently identified for this exact business. No content count, booking verdict, accreditation claim or photo judgment is assigned. Do not substitute another clinic in Guadalupe or a directory page as its website. A verified official URL would allow this gap to be filled.

## 5. Price visibility, proof and images

| Site | Price visibility in the inspected sample | Proof placement and visual treatment |
| --- | --- | --- |
| CCDI | No numeric fee in the inspected home/location/call-entry text. Corporate copy describes a quote on the call. | Accreditation/tenure claims near the hero; employer proof lower down. Hero explicitly says a clinic photo is coming soon. The graphic is not a clinic photograph or independent accreditation verification. |
| Hi-Precision | No numeric fee in inspected home/services/corporate/contact text. An online-store link exists, but store inventory/prices were not audited. | Quality/proficiency certification strip visible on the short homepage; photographic hero and graphic task shortcuts. Some words are embedded in images. |
| Clinica Prime | Public amounts visible on the default executive-package tab; corporate pricing remains inquiry-led in the inspected page. | Photographic family hero; branch information, patient testimonials and wellness-partner section; corporate page displays a company-count proof claim. |
| Singapore Diagnostics | No numeric fee in the captured corporate/contact/patient-entry text. Image-based package prices and package detail pages were not comprehensively checked. | Lab-person imagery and quality claims in corporate hero; patient site uses a claimed annual patient-volume signal and reviews. |
| Health Screen | No numeric fee in captured package-page text; inclusion lists are public. | Photographic branch/campaign slides, benefit cards and prominent awards/milestones. Awards are not interchangeable with laboratory licensure or accreditation. |
| MyHealth | No numeric fee in captured products listing; detail screens not checked. | Photographic care hero, illustrated service cards, HMO/insurance logos and tenure/patient-volume claims below. Logos represent the site's assertion, not a verified coverage promise. |
| Healthway | No reliable site-wide price verdict. The old diagnostic route's price-list request was not consistently reachable. | Image-led offers, patient testimony, news and corporate scale claims; consent overlay can obscure the first screen. |
| The Medical City | No numeric fee in inspected home/services/contact text; package/booking pricing outside scope. | Photographic care hero and institutional recognition imagery near the top; locations, JCI-related proof and news further down. |

Photography was assessed as **photographic imagery versus an explicit placeholder**, not authenticated as original photography. A clinician or patient in a hero image is not proof that the person works at or attended that branch. Likewise, displayed accreditation, quality and client-count claims were not checked against regulators, certification registries or contracts. No employer/client identities are reproduced here.

## 6. Recommended CCDI edits, in order

| Priority | Change | Why | Preserve |
| --- | --- | --- | --- |
| 1 | Shorten the first screen to one clear location/service statement and one supporting sentence. | The current headline wraps over many lines and repeats the audience split in the paragraph. This can feel dense even on a mid-length page. | Equal access for walk-ins and employer inquiries, plus visible phone and hours/location actions. |
| 2 | Remove repeated positioning before cutting service substance. | Identical standards/staff/turnaround wording appears in two introductions; benefits/process sections repeat practical facts. | One useful explanation of each benefit and a practical walk-in workflow. |
| 3 | Replace the clinic-photo placeholder when appropriate photography is ready. | Every other inspected homepage uses photographic imagery. CCDI visibly labels its image as unfinished. This is a separate issue from word count. | Honest representation. Do not pass stock imagery off as the actual clinic. |
| 4 | Simplify the corporate-call introduction and make duration consistent. | The entry repeats eligibility, purpose and pricing discussion before the calendar; headline and calendar duration differ. | Who should book, what the call covers, walk-in alternative, privacy/consent and direct-contact fallback. |
| 5 | Keep concise service summaries and optional detail. | Current collapsed summaries are already only 5-8 tokens. The sampled expansion adds useful report/turnaround information. | Service distinctions and facts patients/HR need to choose the next step. |
| 6 | Use a focused employer destination if the homepage remains busy. | Combining two audiences creates repeated explanation; competitors often put deeper employer content elsewhere. | A visible employer entry from the homepage. Do not hide it in a portal meant for existing clients. |
| 7 | Check every operational/quality promise before retaining or strengthening it. | Turnaround, scope, availability and compliance language can become promises. This audit verifies their presence, not operational accuracy. | Accurate, supportable claims and wording that distinguishes laboratory services from other care. |

These are editing proposals, not approved production changes. There is no evidence here that public pricing must be added or that a confirmed appointment scheduler is required for CCDI's walk-in services.

### Proposed test, not a claim of improvement

Create one shorter variant rather than repeatedly trimming without a baseline:

1. Keep the existing service summaries and optional details.
2. Cut duplicated introductory copy and shorten the hero.
3. Use one primary next step for each audience, with phone available throughout.
4. Check that someone can quickly answer: "Can I walk in?", "Where and when?", "Do they offer my test?" and "How does my company inquire?"
5. Compare qualified calls, location/directions actions, corporate-call starts and completed inquiries. Review patient questions for missing information. Do not optimize only for fewer words or more button clicks.

## 7. Remaining uncertainty and refresh rules

- Desktop only. Test mobile wrapping, tap targets, cookie overlays, sticky buttons and accordions separately before publishing a redesign.
- No final booking, form delivery, callback response or actual slot availability was tested. Visible interfaces are not end-to-end verification.
- Counts vary with carousels, dynamic prompts, reviews, consent state and loaded content. Repeat the method on the same pages after a revision.
- Image lettering was not counted. This particularly limits Hi-Precision and campaign-led pages.
- Corporate page functions vary: clinic management, individual exam requests, existing-client portals and sales calls should not be scored as the same task.
- Guadalupe's official URL remains unresolved. The Medical City corporate-specific booking path, Hi-Precision store, competitor package detail screens and regulatory claims remain outside the verified sample.
- Healthway's older service URL needs a current navigation-based replacement before it is used as evidence of a working service or price-list funnel.

**Decision supported by this audit:** keep CCDI's useful detail, make the first screen easier to scan, and remove repetition. The evidence supports neither defending every current sentence nor cutting content simply because competitors appear simpler.
