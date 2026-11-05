# Fernwood Studio Kit

A minimal Jekyll template used for Fernwood Labs team microsites.

## Contents

| Path | Purpose |
| --- | --- |
| `index.md` | Landing page. |
| `engagements/index.md` | Engagement index. It renders every document in the `_engagements` collection. |
| `_engagements/` | One Markdown document per engagement. |
| `_data/navigation.yml` | Top navigation. |
| `_layouts/` | `default` and `engagement` layouts. |
| `assets/main.css` | Base stylesheet. |

## Engagement document format

```yaml
---
title: "Engagement title"
client: "Client name"
year: 2024
role: "Lead"   # Lead or Contributor
slug: "engagement-slug"
---
```

Keep the body short: the problem, what the studio did, and the outcome.

## Studio convention

Engagement detail belongs in the `_engagements` collection and is rendered by
`engagements/index.md`. The landing page is the profile page.
