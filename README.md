# Tawa Talent Partners — Brochure Site

> Case study: a clean, fast marketing site for a talent company, built from client-provided reference sites.
> **Code is proprietary; this repo documents the build.**

---

## Context

| | |
|---|---|
| **Client** | Tawa Talent Partners (talent/recruitment firm) |
| **Role** | Design + build |
| **Timeline** | 2026 — recent client build |

## Problem

A talent firm needed a professional brochure site to establish its presence — services, about, and contact — with the polished, editorial feel of the reference sites the client supplied ([climate17.com](https://www.climate17.com), [surgeclimatetalent.earth](https://surgeclimatetalent.earth), [alphabetedd.com](https://alphabetedd.com/)).

## Stack

| Layer | Technology |
|---|---|
| App | React 19.2, Vite 7.2, TypeScript 5.9, Tailwind CSS 3.4 |
| UI | Radix UI primitives, shadcn-style component patterns, Framer-motion-ready structure |
| Routing | React Router 7 |
| Forms | React Hook Form + Zod (contact forms) |
| Content | Embla carousels, day-picker/date primitives where needed |

## Notes

A deliberately lean build: a static SPA keeps hosting trivial and costs near zero for a brochure site, while the Radix + Tailwind component foundation means the site can grow (blog, job listings, CMS) without a rewrite when the client's needs do.

## Evidence

- **Live site:** available on request.

---

*Case study by David Aloba — [davidaloba.com](https://davidaloba.com) · [LinkedIn](https://linkedin.com/in/davidaloba)*
