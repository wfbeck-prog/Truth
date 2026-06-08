# MotherhoodTruth Redesign Notes

## Project goal

Modernize **The Truth About Motherhood** into a fast, SEO-friendly, AI-readable editorial WordPress theme while preserving the site's 20-year content archive and brand authority.

## Brand direction

The site began as a mommy blog and is evolving into a modern platform for motherhood, midlife, perimenopause, women's health, family, travel, and opinion.

Working positioning:

> Honest motherhood, midlife, and everything we were never told.

## Visual direction

- Premium editorial magazine with personal-author warmth
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

## Recommended content pillars

- Perimenopause
- Midlife Motherhood
- Motherhood
- Health & Wellness
- Family Life
- Travel
- Opinion

## Homepage sections

1. Sticky navigation
2. Logo / brand header
3. Hero feature area
4. Brand statement highlighting 20 years of truth
5. Start Here / pillar cards
6. Midlife Shift feature section
7. Latest Stories
8. From 20 Years of Truth archive section
9. Author introduction
10. Newsletter signup
11. Instagram/social section
12. Footer navigation

## Single article priorities

- Full-width editorial article header
- Large wide featured image
- Category badge
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
