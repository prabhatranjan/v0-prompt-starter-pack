# GTM Landing Page App (v0)

**Use when:** You want v0 to build a complete landing page web app for a new product or feature.

## Prompt
You are v0. Build a production-ready **GTM landing page web app** for {{product_name}}.

**Inputs**
- Target persona: {{persona}}
- Core problem: {{pain_points}}
- Primary outcome: {{desired_outcome}}
- Proof assets (logos, metrics, testimonials): {{proof}}
- Primary CTA: {{cta}}
- Brand tone: {{brand_voice}}

**App requirements**
1. **Pages**
   - `/` Landing page
   - `/pricing` Pricing table with FAQ
   - `/case-studies` 2–3 case study cards
2. **Core sections on `/`**
   - Hero with headline, subhead, CTA
   - Benefits (3–5 cards)
   - Social proof (logos + 2 testimonials)
   - Feature grid (4–6)
   - How it works (3 steps)
   - FAQ (5 questions)
   - Final CTA band
3. **Components**
   - Reusable `SectionHeader`, `FeatureCard`, `TestimonialCard`, `PricingCard`
   - Use a cohesive design system (spacing, typography, colors)
4. **Data model (mock data)**
   - Provide structured mock content in a `data` file (arrays of features, testimonials, FAQs, pricing tiers)
5. **UX details**
   - Sticky top nav with active section anchors
   - Responsive layout (mobile → desktop)
   - Accessible headings and buttons

**Output format**
- Generate the full app UI with working navigation.
- Include placeholder copy that can be swapped for real inputs.
- Keep text concise and conversion-focused.
