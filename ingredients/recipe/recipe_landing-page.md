---
id: recipe_landing-page
ingredient_type: recipe
version: 1.0.0
status: approved
source_doc_id: drive://spike-recipe-cookbook
source_location: "Recipe Cookbook → Landing Page"
created_date: 2026-03-01
last_modified_date: 2026-03-01
approved_date: 2026-03-05
review_by: 2027-03-05
owner_team: content
reviewers: [tissom, kkelly]
product: [cross]
segment: [k12, hied, international, corporate]
audience: []
region: [global]
functions: [marketing]
use_cases: [landing_page]
visibility: public
channel_safety: external
tags: [recipe, landing-page]
pattern_name: "Landing Page"
composition:
  - {type: positioning_statement, count: 1, required: true, notes: "hero anchor"}
  - {type: value_proposition, count: "2-3", required: true, notes: "the three things the page promises"}
  - {type: proof_point, count: "2-3", required: true, notes: "evidence section"}
  - {type: customer_quote, count: "1-2", required: true, notes: "social proof — must be rights_status: approved"}
  - {type: statistic, count: "1-2", required: false, notes: "numeric reinforcement"}
  - {type: product_fact, count: "2-4", required: true, notes: "feature grid"}
  - {type: tone_rule, count: "2-4", required: true, notes: "language filters"}
parameters: [segment, product, audience, tone]
output_guidance: "Hero headline, 8-word subhead, three-value-prop band, evidence section with at least one quote, feature grid, single CTA. No carousels. Customer quotes must be rights_status: approved — no pending quotes, ever."
applies_to: [landing_page]
---

Lead with the positioning_statement rewritten as a one-line hero, not verbatim. Underneath, three value_propositions become the three promises of the page. The evidence section pulls a rights_status: approved customer_quote plus at least one proof_point or statistic. The feature grid is product_facts, unembellished. If the evidence is thin, fix the evidence before building the page — don't decorate.
