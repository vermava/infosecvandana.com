# infosecvandana.com IA Restructure Plan

## Site Strategy Summary

The current site already has strong content depth, but the navigation exposes too many peer-level choices and makes the experience feel archival before it feels authoritative. The right move is not to remove content, but to change how it is surfaced.

Recommended strategy:

- Reduce the global navigation to 5 executive-level headings only.
- Use each top-level heading as a curated hub page, not a raw archive.
- Keep existing section archives intact in phase 1 to avoid risky content moves.
- Use homepage storytelling and proof signals to guide visitors toward the right action.
- Make the site feel like an executive platform first, and a deep content archive second.

Brand position the structure should reinforce:

**Global cybersecurity speaker, AI/AppSec leader, educator, advisor, and community builder.**

---

## New Top Navigation

Top-level navigation should contain only these 5 items:

1. Speaking & Appearances
2. Learning & Resources
3. Leadership & Impact
4. Media & Stories
5. Achievements & Credentials

Recommended utility CTA in header:

- `Work With Vandana`

Recommended contact routing under that CTA:

- Speaking inquiries
- Training/workshop requests
- Advisory/board opportunities
- Media/podcast requests

---

## Full Content Mapping

### 1. Speaking & Appearances

Purpose: establish authority, visibility, and speaking credibility.

Map these sections here:

- Keynotes & Locknotes
- Conference Talks
- Webinars
- Panel Discussion
- Podcasts

Current Hugo sources:

- `content/keynotes/`
- `content/talks/`
- `content/webinars/`
- `content/paneldiscussion/`
- `content/podcasts/`

### 2. Learning & Resources

Purpose: showcase practical expertise, teaching, and educational value.

Map these sections here:

- Blogs
- Trainings
- Reports Created
- Breaking Into InfoSec
- OWASP Projects Spotlight Series

Current Hugo sources:

- `content/blogs/`
- `content/trainings/`
- `content/reports/`
- `content/breakingintoinfosec/`
- `content/owaspspotlightseries/`

### 3. Leadership & Impact

Purpose: position Vandana as a leader, advisor, and ecosystem builder.

Map these sections here:

- Advisory Board
- Community Leadership
- Awards Judge or Jury

Current Hugo sources:

- `content/advisoryboard/`
- `content/communityleadership/`
- `content/judge/`

### 4. Media & Stories

Purpose: humanize the brand while keeping trust and editorial authority high.

Map these sections here:

- Featured
- A Day in the Life of an Entrepreneur
- A Day in the Life of a CISO

Current Hugo sources:

- `content/featured/`
- `content/leaderspeak/`
- `content/ciso/`

### 5. Achievements & Credentials

Purpose: provide proof, recognition, and formal credibility.

Map these sections here:

- Awards
- Certifications
- Books Authored or Contributed

Current Hugo sources:

- `content/awards/`
- `content/certifications/`
- `content/Books/`

---

## Revised Navigation Labels

Use these exact labels:

- `Speaking & Appearances`
- `Learning & Resources`
- `Leadership & Impact`
- `Media & Stories`
- `Achievements & Credentials`

Recommended sublabels on landing pages:

- Speaking & Appearances: `Talks, keynotes, webinars, panels, podcasts`
- Learning & Resources: `Writing, training, reports, and educational series`
- Leadership & Impact: `Boards, community work, and industry stewardship`
- Media & Stories: `Press, interviews, and career stories`
- Achievements & Credentials: `Awards, certifications, and books`

---

## Sitemap

Recommended sitemap structure:

```text
/
|-- /speaking/
|   |-- /keynotes/
|   |-- /talks/
|   |-- /webinars/
|   |-- /paneldiscussion/
|   `-- /podcasts/
|
|-- /resources/
|   |-- /blogs/
|   |-- /trainings/
|   |-- /reports/
|   |-- /breakingintoinfosec/
|   `-- /owaspspotlightseries/
|
|-- /leadership/
|   |-- /advisoryboard/
|   |-- /communityleadership/
|   `-- /judge/
|
|-- /media/
|   |-- /featured/
|   |-- /leaderspeak/
|   `-- /ciso/
|
|-- /credentials/
|   |-- /awards/
|   |-- /certifications/
|   `-- /books/
|
`-- /contact/
```

Important note for implementation:

- In phase 1, keep existing archive URLs live as they are.
- Add the new hub pages at `/speaking/`, `/resources/`, `/leadership/`, `/media/`, and `/credentials/`.
- Link from each hub to the existing archive sections.
- Only change underlying archive URLs later if there is a strong SEO or content-model reason.

---

## Homepage UX Structure

### Recommended Homepage Section Order

1. Hero
2. Trust strip
3. Executive overview
4. Signature focus areas
5. Speaking & Appearances highlights
6. Learning & Resources highlights
7. Leadership & Impact highlights
8. Media & Stories highlights
9. Achievements & Credentials snapshot
10. Opportunity CTA band
11. Footer

### Why this order works

- It establishes brand position first.
- It brings proof near the top.
- It avoids making visitors hunt through long archival lists.
- It gives different visitor types a clear next path.

### Homepage Wireframe in Text

```text
[Header]
Logo/Name | 5 top-level nav items | Work With Vandana

[Hero]
Headline:
Global Cybersecurity Speaker, AI/AppSec Leader, Educator, Advisor, and Community Builder

Support copy:
Vandana Verma helps security teams, engineering leaders, and global communities navigate application security, AI security, secure development, and modern cyber leadership.

Primary CTAs:
- Invite Vandana to Speak
- Book a Training
- Explore Leadership Work

Secondary trust line:
Speaker, trainer, advisor, author, and community leader across global security platforms

[Trust Strip]
Selected logos / institutions / proof points
Examples:
Black Hat | RSA Conference | OWASP | AppSec Village | Women in Tech | etc.

[Executive Overview]
Short bio block with headshot
3 capability pillars:
- Speaking
- Education
- Leadership

[Signature Focus Areas]
Cards:
- AI Security
- Application Security
- Secure AI-Native Development
- Security Leadership & Community

[Speaking & Appearances]
Featured highlights carousel or 3-4 cards
Links to:
- Keynotes & Locknotes
- Conference Talks
- Webinars
- Panels
- Podcasts

[Learning & Resources]
3-column highlights:
- Latest writing
- Training programs
- Educational series and reports

[Leadership & Impact]
Cards for:
- Advisory roles
- Community leadership
- Judge / jury contributions

[Media & Stories]
Featured press + story-led content
Links to:
- Featured
- Day in the Life of an Entrepreneur
- Day in the Life of a CISO

[Achievements & Credentials]
Compact proof block:
- Awards
- Certifications
- Books

[Opportunity CTA Band]
Need a speaker, trainer, advisor, or media guest?
- Speaking inquiry
- Training request
- Advisory / board inquiry
- Media request

[Footer]
Explore | Opportunities | Selected Resources | Social
```

---

## Navigation UX Recommendation

### Top Nav

Use a simple 5-item nav. Do not expose all child archives in the global header.

Recommended desktop pattern:

- 5 top-level items only
- One CTA button on the right: `Work With Vandana`

Recommended mobile pattern:

- Hamburger
- 5 top-level items
- CTA pinned at the bottom of the menu

### Dropdown or Mega-Menu Suggestion

Recommended approach: **no mega-menu**.

Reason:

- The brand should feel premium and executive, not portal-like.
- The current content is best handled through landing pages with curated card groups.
- Mega-menus are unnecessary unless the site becomes product-scale or multi-audience.

Optional compromise:

- Add a small desktop hover panel only for `Speaking & Appearances` and `Learning & Resources`.
- Keep it to 4-5 links max.
- On mobile, do not use nested hover behavior; use simple stacked links.

---

## Footer Structure

Use a concise 4-column footer:

### Column 1: Explore

- Speaking & Appearances
- Learning & Resources
- Leadership & Impact
- Media & Stories
- Achievements & Credentials

### Column 2: Opportunities

- Invite Vandana to Speak
- Book a Training
- Advisory / Board Inquiry
- Media / Podcast Inquiry

### Column 3: Featured Links

- Selected Talks
- Latest Blog Posts
- Community Leadership
- Awards & Certifications

### Column 4: Connect

- LinkedIn
- YouTube
- X / Twitter
- Instagram

Optional footer note:

- Short one-line positioning statement

Example:

`Cybersecurity leader focused on AI security, AppSec, secure development, and community impact.`

---

## Internal Linking Recommendations

Use internal linking deliberately, not automatically.

Recommended rules:

1. Every child archive page should link back to its top-level hub.
2. Every single content page should show:
   - parent section
   - related hub
   - 2-3 related resources where relevant
3. Blog posts about AI/AppSec should link to relevant talks, webinars, or trainings.
4. Media features should link to awards, leadership, or speaker pages where relevant.
5. Advisory, judge, and community pages should cross-link to credentials and featured media.

Recommended reusable labels:

- `Explore More Speaking`
- `Related Learning Resources`
- `Leadership Highlights`
- `Media Coverage`
- `Credentials & Recognition`

---

## CTA Architecture

Create one clean contact page with segmented inquiry options:

- `/contact/`

Recommended CTA labels:

- `Invite Vandana to Speak`
- `Book a Training or Workshop`
- `Discuss Advisory or Board Opportunities`
- `Request a Media or Podcast Interview`

Recommended CTA placement:

- Hero
- Bottom of each top-level hub page
- Footer
- Contextual CTA on archive pages

Recommended inquiry routing fields:

- Inquiry type
- Organization
- Event / company
- Topic of interest
- Timeline
- Budget range or format

---

## Recommended URL Structure / Slugs

Use short, clean hub URLs:

- `/speaking/`
- `/resources/`
- `/leadership/`
- `/media/`
- `/credentials/`
- `/contact/`

Keep current archive section URLs for phase 1:

- `/keynotes/`
- `/talks/`
- `/webinars/`
- `/paneldiscussion/`
- `/podcasts/`
- `/blogs/`
- `/trainings/`
- `/reports/`
- `/breakingintoinfosec/`
- `/owaspspotlightseries/`
- `/advisoryboard/`
- `/communityleadership/`
- `/judge/`
- `/featured/`
- `/leaderspeak/`
- `/ciso/`
- `/awards/`
- `/certifications/`
- `/books/`

If phase 2 normalization is desired, use cleaner long-term aliases:

- `/speaking/keynotes/`
- `/speaking/talks/`
- `/speaking/webinars/`
- `/speaking/panels/`
- `/speaking/podcasts/`
- `/resources/blogs/`
- `/resources/trainings/`
- `/resources/reports/`
- `/resources/breaking-into-infosec/`
- `/resources/owasp-project-spotlight-series/`
- `/leadership/advisory-board/`
- `/leadership/community/`
- `/leadership/judge-jury/`
- `/media/featured/`
- `/media/entrepreneur-story/`
- `/media/ciso-story/`
- `/credentials/awards/`
- `/credentials/certifications/`
- `/credentials/books/`

---

## SEO-Friendly Titles and Meta Descriptions

### Home

Title:
`Vandana Verma | Global Cybersecurity Speaker, AI/AppSec Leader, Educator, Advisor`

Meta description:
`Official website of Vandana Verma: global cybersecurity speaker, AI and application security leader, trainer, advisor, author, and community builder.`

### Speaking & Appearances

Title:
`Speaking & Appearances | Vandana Verma`

Meta description:
`Explore keynotes, conference talks, webinars, panel discussions, and podcast appearances by Vandana Verma across global cybersecurity events.`

### Learning & Resources

Title:
`Learning & Resources | Vandana Verma`

Meta description:
`Browse cybersecurity blogs, trainings, reports, career resources, and OWASP educational series by Vandana Verma.`

### Leadership & Impact

Title:
`Leadership & Impact | Vandana Verma`

Meta description:
`See Vandana Verma’s advisory roles, community leadership, and industry contributions across cybersecurity and OWASP initiatives.`

### Media & Stories

Title:
`Media & Stories | Vandana Verma`

Meta description:
`Read featured interviews, press coverage, and story-led content including leadership journeys and career perspectives from Vandana Verma.`

### Achievements & Credentials

Title:
`Achievements & Credentials | Vandana Verma`

Meta description:
`Explore awards, certifications, and books authored or contributed to by Vandana Verma across cybersecurity and technology leadership.`

### Contact

Title:
`Work With Vandana | Speaking, Training, Advisory, Media`

Meta description:
`Invite Vandana Verma to speak, deliver training, support advisory initiatives, or participate in media and podcast opportunities.`

---

## Reusable Section Intro Copy

### Speaking & Appearances

`A curated view of Vandana Verma’s public speaking across keynotes, conference sessions, webinars, panels, and podcast conversations.`

### Learning & Resources

`Practical writing, training, reports, and educational resources for security leaders, builders, and aspiring practitioners.`

### Leadership & Impact

`Leadership, advisory, governance, and community-building work shaping the cybersecurity ecosystem beyond the stage.`

### Media & Stories

`A mix of featured coverage, interviews, and personal leadership stories that add context to the work behind the profile.`

### Achievements & Credentials

`Recognition, certifications, and authored contributions that reinforce depth, trust, and long-term industry impact.`

---

## Hugo Implementation Strategy

The site is already Hugo-based and currently uses a flat `menu.main` in `config.toml`. The theme renders that menu directly from:

- `themes/personal-web/layouts/partials/sidebar/menu.html`

This is important because the current theme does **not** implement nested navigation. That means the easiest maintainable solution is:

### Recommended Phase 1 Implementation

1. Replace the existing flat multi-item menu with only 5 top-level items.
2. Create 5 hub pages:
   - `/speaking/`
   - `/resources/`
   - `/leadership/`
   - `/media/`
   - `/credentials/`
3. Keep all current content folders exactly where they are.
4. On each hub page, show curated cards that link to the existing archive sections.
5. Add a simple `/contact/` page with segmented inquiry CTAs.

This avoids:

- moving hundreds of content files
- changing many existing URLs at once
- creating redirect debt immediately
- fighting the current theme architecture

### Recommended Phase 2

Only if needed later:

- normalize archive URLs into nested hub-based paths
- introduce aliases for old archive locations
- unify repeated list templates into a common archive template
- add breadcrumbs and related-content modules

---

## Recommended Hugo Content / Folder Structure

### Practical phase 1 structure

```text
content/
|-- _index.md
|-- speaking.md
|-- resources.md
|-- leadership.md
|-- media.md
|-- credentials.md
|-- contact.md
|
|-- keynotes/
|-- talks/
|-- webinars/
|-- paneldiscussion/
|-- podcasts/
|
|-- blogs/
|-- trainings/
|-- reports/
|-- breakingintoinfosec/
|-- owaspspotlightseries/
|
|-- advisoryboard/
|-- communityleadership/
|-- judge/
|
|-- featured/
|-- leaderspeak/
|-- ciso/
|
|-- awards/
|-- certifications/
`-- Books/
```

Why this is the best short-term structure:

- It introduces the new IA without breaking the archive model.
- It keeps the current section templates usable.
- It minimizes changes to file paths and internal references.

### Optional phase 2 structure

Only if you want a cleaner long-term content model:

```text
content/
|-- speaking/
|   |-- _index.md
|   |-- keynotes/
|   |-- talks/
|   |-- webinars/
|   |-- panels/
|   `-- podcasts/
|-- resources/
|   |-- _index.md
|   |-- blogs/
|   |-- trainings/
|   |-- reports/
|   |-- breaking-into-infosec/
|   `-- owasp-project-spotlight-series/
|-- leadership/
|   |-- _index.md
|   |-- advisory-board/
|   |-- community/
|   `-- judge-jury/
|-- media/
|   |-- _index.md
|   |-- featured/
|   |-- entrepreneur-story/
|   `-- ciso-story/
`-- credentials/
    |-- _index.md
    |-- awards/
    |-- certifications/
    `-- books/
```

---

## Sample Hugo Navigation Config

Replace the current long `menu.main` with this simplified version:

```toml
[[menu.main]]
  identifier = "speaking"
  name = "Speaking & Appearances"
  url = "/speaking/"
  weight = 10

[[menu.main]]
  identifier = "resources"
  name = "Learning & Resources"
  url = "/resources/"
  weight = 20

[[menu.main]]
  identifier = "leadership"
  name = "Leadership & Impact"
  url = "/leadership/"
  weight = 30

[[menu.main]]
  identifier = "media"
  name = "Media & Stories"
  url = "/media/"
  weight = 40

[[menu.main]]
  identifier = "credentials"
  name = "Achievements & Credentials"
  url = "/credentials/"
  weight = 50
```

Optional CTA treatment:

- Keep `Work With Vandana` outside the menu as a styled button.

---

## Sample Hub Page Frontmatter

Example: `content/speaking.md`

```yaml
---
title: "Speaking & Appearances"
description: "Keynotes, talks, webinars, panel discussions, and podcast appearances by Vandana Verma."
url: "/speaking/"
layout: "hub"
hub_sections:
  - title: "Keynotes & Locknotes"
    url: "/keynotes/"
    description: "Signature keynote and locknote appearances."
  - title: "Conference Talks"
    url: "/talks/"
    description: "Conference sessions from global cybersecurity events."
  - title: "Webinars"
    url: "/webinars/"
    description: "Virtual sessions, live learning, and expert discussions."
  - title: "Panel Discussion"
    url: "/paneldiscussion/"
    description: "Panels on security leadership, hiring, community, and emerging risks."
  - title: "Podcasts"
    url: "/podcasts/"
    description: "Long-form conversations and expert interviews."
cta:
  title: "Invite Vandana to Speak"
  url: "/contact/"
---
```

---

## Sample Hub Template Idea

Suggested new template:

- `layouts/_default/hub.html`

Simple rendering pattern:

```go-html-template
{{ partial "header" . }}
<h1>{{ .Title }}</h1>
<p>{{ .Content }}</p>

<div class="hub-grid">
  {{ range .Params.hub_sections }}
    <article class="hub-card">
      <h2><a href="{{ .url }}">{{ .title }}</a></h2>
      <p>{{ .description }}</p>
    </article>
  {{ end }}
</div>

{{ with .Params.cta }}
  <p><a href="{{ .url }}">{{ .title }}</a></p>
{{ end }}

{{ partial "footer" . }}
```

This gives you a clean reusable hub pattern without changing existing archive layouts.

---

## Content Migration Plan

### Phase 1: IA without URL churn

1. Create 5 hub pages.
2. Replace current menu with the 5 new items.
3. Update the homepage to feature the 5 hubs.
4. Add contextual CTAs.
5. Add internal links from archive pages back to hub pages.

### Phase 2: UX polish

1. Add a compact trust strip on the homepage.
2. Standardize section intros across archives.
3. Improve metadata and descriptions on hub pages.
4. Add related-links blocks on singles and archives.
5. Add a proper contact / inquiry page.

### Phase 3: Optional structural cleanup

1. Normalize case issues such as `Books` vs lowercase URLs.
2. Consolidate repeated list templates where possible.
3. Add aliases if archive URLs are renamed.
4. Review canonical tags and redirect behavior after any slug changes.

---

## Migration Checklist

### IA and Navigation

- [ ] Replace current menu with 5 top-level headings only
- [ ] Add `Work With Vandana` CTA to header
- [ ] Create `/speaking/` hub
- [ ] Create `/resources/` hub
- [ ] Create `/leadership/` hub
- [ ] Create `/media/` hub
- [ ] Create `/credentials/` hub
- [ ] Create `/contact/` page

### Homepage

- [ ] Rewrite hero to reflect executive positioning
- [ ] Add trust / proof strip
- [ ] Add curated sections for each hub
- [ ] Add focused CTA band
- [ ] Reduce raw archive exposure on homepage

### Archive and Internal Links

- [ ] Add “back to hub” links on archive pages
- [ ] Add related-resource links on single pages
- [ ] Cross-link media, leadership, speaking, and credential pages

### SEO

- [ ] Update page titles
- [ ] Update meta descriptions
- [ ] Ensure canonical URLs stay stable
- [ ] Add aliases if URLs are changed later

### Technical Cleanup

- [ ] Decide whether phase 1 will keep current archive folders untouched
- [ ] Add reusable `hub` layout
- [ ] Consider consolidating repeated list templates later
- [ ] Normalize naming and slug casing over time

---

## Final Recommendation

The best version of this site is not a larger menu. It is a smaller, stronger front door with clearer pathways.

For this codebase specifically, the smartest move is:

- keep the archives
- simplify the nav
- introduce 5 curated hub pages
- sharpen the homepage narrative
- add one clear contact path for opportunities

That gets you a premium executive experience quickly, without a risky rebuild.
