# Prepnest Documentation

**Educational content platform for exam preparation**

[![Case Study](https://img.shields.io/badge/case%20study-portfolio-blue)](https://github.com/iamnortey/portfolio/blob/main/case-studies/prepnest.md)
[![Sanity Starter](https://img.shields.io/badge/starter-sanity--education-green)](https://github.com/iamnortey/sanity-education-starter)

---

## Overview

Prepnest is a structured content platform for WASSCE/BECE exam preparation, built with a schema-first approach to educational content modeling.

### The Problem

- Study materials scattered across sources
- No structured curriculum navigation
- Passive learning (static PDFs)
- Math concepts hard to visualize

### The Solution

**Structured content pipeline:** Subject → Topic → Lesson → Question

Hierarchical content organization with animated explanations and search-driven discovery.

---

## Stack

| Layer | Technology |
|-------|------------|
| CMS | Sanity |
| Mobile | React Native, Expo |
| Web | Next.js |
| Search | Typesense |
| Animation | Manim |

---

## Content Model

```
Subject
└── Topic
    └── Lesson
        └── Question
```

Schema-first design ensures consistent content structure.

---

## Documentation

| Document | Description |
|----------|-------------|
| [Architecture](./ARCHITECTURE.md) | System design |
| [Case Study](./CASE_STUDY.md) | Project overview |

---

## Open Source Component

The [sanity-education-starter](https://github.com/iamnortey/sanity-education-starter) demonstrates the schema patterns used.

---

## Metrics

| Metric | Value |
|--------|-------|
| Animation templates | 533K+ lines Python |
| Content schema | Defined |

---

## Repo Access Note

The core implementation is in **private repositories**.

This repository contains architecture and design documentation.

---

## Related

- [Portfolio](https://github.com/iamnortey/portfolio)
- [Sanity Education Starter](https://github.com/iamnortey/sanity-education-starter)
