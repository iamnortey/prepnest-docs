# Prepnest

> Educational content platform for WASSCE/BECE exam preparation.

[![Case Study](https://img.shields.io/badge/case%20study-read-blue)](https://github.com/iamnortey/portfolio/blob/main/case-studies/prepnest.md)
[![Sanity Starter](https://img.shields.io/badge/starter-sanity--education-green)](https://github.com/iamnortey/sanity-education-starter)
[![Portfolio](https://img.shields.io/badge/portfolio-iamnortey-green)](https://github.com/iamnortey/portfolio)

---

## What it does

Prepnest is a structured content platform for exam preparation, built with a schema-first approach to educational content modeling.

**Content pipeline:** Subject → Topic → Lesson → Question

Hierarchical content organization with animated explanations and search-driven discovery.

---

## The problem

- Study materials scattered across sources with no structure
- No curriculum-aligned navigation
- Passive learning (static PDFs)
- Math and science concepts hard to visualize

---

## Stack

| Layer | Technology |
|-------|------------|
| **CMS** | Sanity |
| **Mobile** | React Native, Expo |
| **Web** | Next.js |
| **Search** | Typesense |
| **Animation** | Manim |

---

## Content model

```
Subject
└── Topic
    └── Lesson
        └── Question
```

Schema-first design ensures consistent content structure across all subjects and topics.

---

## Documentation

| Document | Description |
|----------|-------------|
| [Case Study](https://github.com/iamnortey/portfolio/blob/main/case-studies/prepnest.md) | Full project overview |

---

## Open source component

The [sanity-education-starter](https://github.com/iamnortey/sanity-education-starter) demonstrates the schema patterns used in Prepnest — available as a standalone starter for any educational content project.

---

## Relationship to Ghana Education Data OS

Prepnest's schema-first approach to Ghanaian curriculum content feeds into the broader **Ghana Education Data OS (GEDOS)** initiative, which builds a governed control plane for Ghana curriculum and exam intelligence. GEDOS is developed in the [`ninobyte-labs`](https://github.com/ninobyte-labs) organization (private product repos; public org profile).

---

## What's public vs private

This repository contains architecture and design documentation for the Prepnest content model. The core implementation (mobile app, Sanity studio configuration, content library) lives in private repositories.

For partnership or technical conversations, reach out via [LinkedIn](https://linkedin.com/in/inortey/).

---

## Related

- [Sanity Education Starter](https://github.com/iamnortey/sanity-education-starter) — open-source schema starter
- [`ninobyte-labs`](https://github.com/ninobyte-labs) — sibling Ninobyte org running the GEDOS work
- [Portfolio](https://github.com/iamnortey/portfolio) — all case studies and architecture samples
- [Case Study](https://github.com/iamnortey/portfolio/blob/main/case-studies/prepnest.md) — full project deep-dive
