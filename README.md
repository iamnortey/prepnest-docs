# Prepnest

> Educational content platform for WASSCE/BECE exam preparation.

[![Case Study](https://img.shields.io/badge/case%20study-read-blue)](https://github.com/iamnortey/portfolio/blob/main/case-studies/prepnest.md)
[![Sanity Starter](https://img.shields.io/badge/starter-sanity--education-green)](https://github.com/iamnortey/sanity-education-starter)
[![Portfolio](https://img.shields.io/badge/portfolio-iamnortey-green)](https://github.com/iamnortey/portfolio)

---

## What It Does

Prepnest is a structured content platform for exam preparation, built with a schema-first approach to educational content modeling.

**Content pipeline:** Subject → Topic → Lesson → Question

Hierarchical content organization with animated explanations and search-driven discovery.

---

## The Problem

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

## Content Model

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

## Open Source Component

The [sanity-education-starter](https://github.com/iamnortey/sanity-education-starter) demonstrates the schema patterns used in Prepnest — available as a standalone starter for any educational content project.

---

## Access

The core implementation is in **private repositories**. This repository contains architecture and design documentation.

---

## Related

- [Sanity Education Starter](https://github.com/iamnortey/sanity-education-starter) — open-source schema
- [Portfolio](https://github.com/iamnortey/portfolio) — all case studies and architecture samples
- [Case Study](https://github.com/iamnortey/portfolio/blob/main/case-studies/prepnest.md) — full project deep-dive
