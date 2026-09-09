# Finding: inconsistent on-page/referenced split across tags

Date: 2026-09-09
Found during: spec review, before any skill or eval existed.

**The problem:**
Two categories (sexual violence, self-harm) split into paired tags —
on-page-X and referenced-X — so the output can record which one
applied. Five other categories (graphic-violence, child-harm,
animal-harm, pregnancy-loss, explicit-sex) have the identical
on-page-vs-backstory distinction written into their "does not qualify"
line, but only one tag name each. The distinction exists in the
definition; it has no field to land in on output.

**Why it happened:**
The first two tags were written as pairs from the start. The pattern
wasn't checked against the other nine until asked directly whether
review sites could flag any of them — at which point it became clear
review-site ambiguity (on-page vs. referenced) applies to all eleven,
not just the two that were split.

**Why it matters:**
A single `graphic-violence` tag can't distinguish a torture scene from
one sentence of backstory. If the tool's purpose is telling a reader
what they'll actually encounter on the page, collapsing that
distinction defeats part of the purpose for 5 of 11 categories.

**Two ways to close it, not yet decided:**
1. Split all five into on-page/referenced pairs, matching the existing
   two. Consistent, but doubles the tag count for five categories.
2. State a rule: violence/harm/loss categories intentionally don't
   distinguish on-page from referenced, because presence alone is the
   signal that matters for those. Keep sexual-violence and self-harm
   split because the intensity gap between "happened on page" and
   "happened off page" is larger for those two.

Leaning toward option 2, but the reasoning needs to survive an actual
example before it's real — testing against the first five books read
in Project 2 will show whether it holds.