---
id: recipe_launch-email
ingredient_type: recipe
version: 1.0.0
status: approved
source_doc_id: drive://spike-recipe-cookbook
source_location: "Recipe Cookbook → Launch Email"
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
use_cases: [email]
visibility: public
channel_safety: external
tags: [recipe, email, launch]
pattern_name: "Launch Email"
composition:
  - {type: persona, count: 1, required: true, notes: "addressee"}
  - {type: product_fact, count: "1-2", required: true, notes: "what shipped"}
  - {type: value_proposition, count: 1, required: true, notes: "so-what for this persona"}
  - {type: pain_point, count: "0-1", required: false, notes: "optional reminder of the why"}
  - {type: tone_rule, count: "2-3", required: true, notes: "language filters"}
parameters: [segment, product, audience, tone]
output_guidance: "150–250 words. Subject line under 60 characters. First line names the specific change — don't bury it. One clear action. No exclamations. No 'we're excited to announce.'"
applies_to: [email]
---

Open with the specific product_fact that shipped — not a greeting, not a windup. Follow with the value_proposition framed for the persona's actual day. One paragraph, two at most. Close with one action. If the email needs three paragraphs, the product_fact isn't concrete enough — go back and narrow it.
