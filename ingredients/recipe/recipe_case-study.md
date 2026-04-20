---
id: recipe_case-study
ingredient_type: recipe
version: 1.0.0
status: approved
source_doc_id: drive://spike-recipe-cookbook
source_location: "Recipe Cookbook → Case Study"
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
use_cases: [case_study]
visibility: public
channel_safety: external
tags: [recipe, case-study]
pattern_name: "Customer Case Study"
composition:
  - {type: customer_quote, count: "2-3", required: true, notes: "all must be rights_status: approved"}
  - {type: pain_point, count: "1-2", required: true, notes: "the before state"}
  - {type: product_fact, count: "2-4", required: true, notes: "what the customer deployed"}
  - {type: proof_point, count: "1-2", required: true, notes: "what changed"}
  - {type: statistic, count: "1-3", required: true, notes: "measured outcomes"}
  - {type: tone_rule, count: "2-4", required: true, notes: "language filters"}
parameters: [segment, product, audience]
output_guidance: "500–800 words. Before / Change / After structure. Name the specific customer — organization, location, size. Numbers must come from statistics with valid_to in the future. No 'transformation,' no 'journey.' Pending or revoked quotes are disqualifying."
applies_to: [case_study]
---

Open with the customer — name, location, scale. Describe the specific pain_point they faced. Name what they deployed (product_facts). Quote them (approved only). Close with the measured outcomes from statistics that are still valid. If any quote is not rights_status: approved, the case study does not ship.
