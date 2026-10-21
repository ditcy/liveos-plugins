---
name: nutrition
description: Save meals, reuse food recipes and labels, and read verified nutrition totals in Live OS.
---

Start with fresh get_context and the current nutrition skills returned by it.
Read [Nutrition workflow](references/nutrition-tracker.md) and
[Data quality](references/nutrition-data-quality.md) when needed.

Find saved products/recipes first; use user-provided label values next, then
clearly marked reasonable estimates. Do not demand labels for ordinary fruit or
already saved products. Unknown nutrition is not zero. Zero energy is only
appropriate for water and plain drinks without caloric additions.

Resolve the day from fresh account timezone context unless the user explicitly
names a historical date. Preserve the specified meal and time. Use default
portions from saved products; do not repeatedly ask settled questions.
Write authorized meals directly, retain source links, and report confirmed
storage. Do not promise a write based only on text in the conversation.

For nutrition totals call show_day_table for the requested local day and read all
pages. Distinguish just-added foods, the whole meal and the whole day. Never add
food intake to exercise expenditure and call the sum energy burned.
Offer reusable products unobtrusively when repetition or a label suggests value.
