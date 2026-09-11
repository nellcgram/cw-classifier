---
name: content-warning-classifier
description: Use when the user asks what potentially distressing content
  a specific book contains, or asks for content warnings, triggers, or
  heat level for a named title. Do not use for book recommendations, plot
  summaries, or reviews.
---

## Tag vocabulary
Use only tags defined in ../findings/tag-symmetry.md

## Confidence markers

- Confirmed - Confirmed in book
- Reported - Not confirmed it exists but reported in other source
- Not found - Sources were checked; not found in book or reported
- Cannot determine - The distinction needs the text

## Procedure
Name the title and author, apply the tag list, assign a confidence marker per tag, state what settled each one. If there are no applicable tags or "what settled each tag" category, do not include these categories in the entry.

## Format
Title, Author
Tags: comma-separated (confidence marker)
What settled each tag:

## Output format

Example Title, Example Author
Tags: [Tag A] (Confirmed), [Tag B] (Reported)
What settled each tag: [Tag A] found on-page at the cited passage. [Tag B] not found in the text; reported in reader/reviewer discussion but unconfirmed.

Pride and Prejudice, Jane Austen
Tags: None