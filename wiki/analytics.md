---
title: "Analytics"
type: dashboard
tags: [meta]
updated: 2026-04-15
---

# Analytics

Visual analytics powered by the [Charts View](https://github.com/caronchen/obsidian-chartsview-plugin) Obsidian plugin.

## Page Distribution by Type

<!-- CUSTOMIZE: Update these numbers as your wiki grows. -->
<!-- The LLM can update this page during lint operations. -->

```chartsview
type: pie
options:
  legend:
    display: true
    position: right
data:
  - label: Concepts
    value: 7
  - label: Entities
    value: 1
  - label: Summaries
    value: 4
  - label: Syntheses
    value: 1
```

## Confidence Distribution

```chartsview
type: bar
options:
  legend:
    display: false
  indexAxis: y
data:
  - label: High
    value: 3
    backgroundColor: "#4caf50"
  - label: Medium
    value: 5
    backgroundColor: "#ff9800"
  - label: Low
    value: 0
    backgroundColor: "#f44336"
```

## Top Tags

```chartsview
type: wordcloud
options:
  maxRotation: 0
  minRotation: 0
data:
  - tag: c2c
    value: 13
  - tag: foundational
    value: 5
  - tag: itinerary
    value: 4
  - tag: pacing
    value: 3
  - tag: seasonality
    value: 3
  - tag: planning
    value: 1
  - tag: logistics
    value: 1
  - tag: trail
    value: 1
  - tag: governance
    value: 2
  - tag: accessibility
    value: 2
  - tag: economy
    value: 2
  - tag: well-established
    value: 2
  - tag: emerging
    value: 1
```
