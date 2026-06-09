# MotherhoodTruth Redesign Notes

## Project goal

Modernize **The Truth About Motherhood** into a fast, SEO-friendly, AI-readable editorial WordPress theme while preserving the site's 20-year content archive and brand authority.

## Repositioned brand strategy

The site is not becoming another generic motherhood, midlife, or wellness blog. The new strategic position is:

> Life Perspective Through Mom Goggles 2.0

The opportunity is to claim the full motherhood spectrum after the baby/toddler years: teens, college, adult children, launching kids, midlife identity, perimenopause, ADHD, Gen X wellness, cultural identity, political discourse, travel with older kids, and spicy opinion content.

## Core blue-ocean pillars

Focus on these proprietary/underserved pillars only:

1. **Launching Pad Mom / Training Wheels Parenting**  
   Letting go without letting down. This replaces sad/passive “empty nest” language with a stronger, ownable life-stage identity.

2. **Perimenopause + Motherhood**  
   The conversation nobody is having: hormones, rage, exhaustion, identity, parenting teens, marriage, and health while still mothering.

3. **ADHD Moms**  
   ADHD in women, ADHD moms raising ADHD kids, systems, shame, chaos, humor, and survival from an authentic lived-experience voice.

4. **Latina Mom Cultural Identity / Spicy Latina Trad Wife**  
   Culture, traditional values, modern motherhood, political awareness, identity, family, faith/values where relevant, and unapologetic representation.

5. **Gen X Mom Wellness**  
   Fitness, health, strength, mobility, perimenopause exercise, family fitness, and getting visible/healthy again in midlife.

6. **Throat Punch Thursday / Spicy Takes Sunday**  
   Signature opinion series for viral commentary, political hot takes, cultural criticism, and humorous truth-telling.

## Brand voice

- Authentic
- Irreverent
- Vulnerable
- Smart
- Opinionated but not reckless
- Funny, sharp, and human
- Strong enough to cut through sanitized parenting content

## Visual direction

- Premium editorial publication with personal-author warmth
- Centered masthead using the existing logo as a strong publication identity
- White background with soft editorial color fields
- Logo cyan: `#00ECFF`
- Soft Tiffany support color: `#81D8D0`
- Warm blush/sand supporting tones
- Large readable typography
- Full-width, fluid layouts that dynamically adjust by viewport
- Image-led landing pages and article pages
- Spacious layouts with strong visual rhythm
- Modern cards, but not boxy widget clutter
- Mobile-first
- No page-builder dependency
- No Soledad or Avada dependency

## Layout rule

The site should feel full-width on both landing pages and post pages.

Use fluid sections that can expand across large screens, but constrain long-form reading text for readability.

Recommended pattern:

- Outer page sections: full-width or near full-width
- Inner content container: fluid using `width: min(100% - clamp(24px, 5vw, 96px), 1440px)`
- Article body copy: readable measure around `720px–820px`
- Featured images: wide/full editorial treatment
- Related/author/newsletter modules: full-width section treatments below article body
- Avoid traditional sidebars inside the primary reading column
- Header should read as a centered publication masthead: utility row, centered logo, centered navigation

## Recommended content architecture

Primary navigation should support the blue-ocean strategy, not generic blog categories.

Recommended nav labels:

- Training Wheels
- Launching Pad Life
- Perimenopause
- ADHD Moms
- Spicy Latina
- Gen X Wellness
- Travel
- Throat Punch

## Homepage sections

1. Utility row with tagline/social/search/subscribe
2. Centered logo masthead
3. Centered primary navigation
4. Hero brand statement: Life Perspective Through Mom Goggles 2.0
5. Featured story
6. Blue Ocean pillar cards
7. Signature series strip
8. Latest stories
9. From 20 Years of Truth archive section
10. Author introduction
11. Newsletter signup
12. Footer navigation

## Single article priorities

- Full-width editorial article header
- Large wide featured image
- Category badge tied to pillar/series
- Article title
- Author metadata
- Published and updated dates
- Reading time estimate
- Quiet text-level sharing, no visible share counters
- Author authority box below article
- Related posts below article
- Newsletter CTA below article
- Popular posts/discovery modules below article, not as a dominant reading sidebar
- Dynamic responsive layout that adapts from wide desktop to mobile without squeezing the article body

## Signature series

- Training Wheels Tuesday
- Throat Punch Thursday
- Wisdom Wednesday
- Launching Pad Life
- Gen X Mom Gets Fit Friday
- Freedom Phase Friend-Finding
- Spicy Takes Sunday

## SEO / AI optimization priorities

- Semantic HTML
- Clean heading hierarchy
- Article schema-ready structure
- Breadcrumb-ready structure
- Strong author signals
- Internal links to topic hubs
- Related posts
- Fast mobile loading
- Lazy-loaded images
- No shortcode dependency
- Pillar landing pages for blue-ocean topics
- Strong internal linking from old evergreen posts into new pillar hubs
