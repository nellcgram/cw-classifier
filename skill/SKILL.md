---
name: content-warning-classifier
description: Use when the user asks what potentially distressing content
  a specific book contains, or asks for content warnings, triggers, or
  heat level for a named title. Do not use for book recommendations, plot
  summaries, or reviews.
---

## Tag vocabulary
Use only tags defined in tag-symmetry.md

## Confidence markers

- Confirmed - Confirmed in book
- Reported - Not confirmed it exists but reported in other source
- Not found - Sources were checked; not found in book or reported
- Cannot determine - The dinstinction needs the text

## Procedure
Name the title and author, apply the tag list, assign a confidence marker per tag, state what settled each one.
- Format:
Title, Author.
Tags: comma-separated (confidence marker)
What settled each tag:

## Output format

Wuthering Heights, Emily Bronte

Output format — write it out as a filled example, not a description. A model follows a sample more reliably than a spec of a sample.