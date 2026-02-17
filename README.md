<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waven&color=0:2b5e2b,100:1a3a1a&height=150&section=header&text=HDPE%20Irrigation%20Systems&fontSize=40&fontColor=ffffff&animation=fadeIn&desc=B2B%20Product%20Design%20%26%20Information%20Architecture&descSize=16" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</p>

---

## 📌 Overview

Designed and developed a responsive B2B manufacturing website for an HDPE drip & sprinkler irrigation brand.

The platform communicates:

- Industrial reliability
- Structured technical depth
- Product range clarity
- Brand credibility

**Primary audience:**
- Distributors & Dealers
- Institutional Buyers
- Technical Evaluators
- Procurement Teams

This is a fully frontend, inquiry-driven website built with **Next.js** and **TypeScript**, styled with **Tailwind CSS**.

---

## 🎯 Problem Statement

Industrial manufacturing websites often struggle with:

- Dense technical documentation
- Poor content hierarchy
- Long-scroll specification overload
- Weak visual identity
- Low product discoverability

Users evaluating irrigation systems require:
- Quick product understanding
- Structured access to specifications
- Clear comparison ability
- Trust reinforcement

The challenge was to design a system that organizes complex product information without reducing technical depth.

---

## 🧠 Design Goals

1. Improve information hierarchy
2. Reduce cognitive overload
3. Elevate industrial brand perception
4. Maintain structured technical documentation
5. Support inquiry-based B2B conversion

---

## 🗂 Information Architecture

The product catalog follows a hierarchical structure:

```
Category Level (Drip / Sprinkler / Fittings)
    ↓
Product Family Level
    ↓
Variant Level
    ↓
Specification Module
    ↓
Application Context
```

Technical information was modularized instead of stacked vertically. This improves scan efficiency and reduces evaluation fatigue.

---

## 🧩 UX Strategy

### 1️⃣ Modular Technical Layout

Product detail pages use tab-based segmentation:

- **Overview** – Product summary and key benefits
- **Components** – Technical breakdown
- **Specifications** – Detailed technical data
- **Applications** – Suitable use cases
- **Resources** – Technical documents and manuals

**Rationale:** Preserves engineering depth while improving scannability. Separates high-level information from detailed specifications, supporting multiple user intents.

---

### 2️⃣ Industrial Brand Elevation

The design system emphasizes:

- Generous white space
- Strong typographic hierarchy
- Controlled color usage
- Structured visual rhythm

The objective was to increase perceived manufacturing precision through visual discipline.

---

### 3️⃣ Inquiry Without Disruption

Conversion design includes:

- Clear CTA hierarchy
- Persistent WhatsApp access
- Minimal inquiry form

This respects B2B research behavior — users explore first, inquire later.

---

## 🎨 Visual System

### Color Palette
- **Primary Green** – Agriculture association
- **Deep Accent Green** – CTA emphasis
- **Neutral Base** – Professional industrial tone

Color usage is restrained to maintain authority and avoid visual noise.

### Typography
- **Serif accents** – Product authority
- **Clean sans-serif** – Technical readability
- **Strong contrast** – Clear hierarchy between headings and data tables

### Implementation
```tsx
// Tailwind configuration for consistent spacing
module.exports = {
  theme: {
    extend: {
      spacing: { /* Consistent modular scale */ },
      colors: { /* Industrial palette */ }
    }
  }
}
```

---

## ✨ Interaction Design

Micro-interactions are intentionally subtle:

- Button elevation on hover
- Smooth tab transitions
- Controlled hover scaling (1.02x)
- Lightweight fade-in animations

Performance was prioritized over decorative motion.

---

## 📱 Responsiveness

The website is fully responsive across screen sizes. However, due to the depth of technical data and structured tab layouts, the experience is optimized for desktop-first evaluation.

Mobile responsiveness ensures accessibility, but full mobile-first interaction optimization remains an area for future refinement. This tradeoff was intentional to preserve specification clarity.

---

## 🛡 Trust & Brand Positioning

Trust is reinforced through:

- Structured content hierarchy
- Certification highlights
- Industrial tone of voice
- Clean spacing discipline
- Non-aggressive conversion design

---

## 🛠 Technology Stack

```tsx
// pages/index.tsx - Built with Next.js + TypeScript
import { ProductGrid } from '@/components/ProductGrid'
import type { Product } from '@/types'

export default function Home() {
  return (
    <div className="container mx-auto px-4">
      <ProductGrid products={productData} />
    </div>
  )
}
```

| Technology | Application |
|------------|-------------|
| **Next.js** | Server-side rendering, file-based routing, image optimization |
| **TypeScript** | Type safety and improved developer experience |
| **Tailwind CSS** | Utility-first styling with consistent design tokens |
| **Figma** | UI design and prototyping |
| **Vercel** | Deployment and hosting |

---

## 📊 What This Project Demonstrates

- Information architecture design for complex product catalogs
- Structuring heavy technical documentation for accessibility
- Industrial UI system development
- B2B UX strategy implementation
- Performance-aware frontend execution
- Balancing technical depth with usability

---

## 🧩 Tools Used

- **Figma** – UI System & Prototyping
- **Next.js** – Frontend Framework
- **TypeScript** – Type Safety
- **Tailwind CSS** – Styling
---

## 💡 Key Takeaway

This project demonstrates the ability to translate technically dense industrial products into a structured digital experience that improves usability, discoverability, and brand perception without compromising engineering credibility.

---

## 📬 Contact

<div align="center">
  
**Project Inquiries:** [harshch002@gmail.com](mailto:harshch002@gmail.com)  
**Portfolio:** [Portfolio](https://beamish-hotteok-7f7e29.netlify.app/)  
**GitHub:** [@grim7012](https://github.com/grim7012)

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:2b5e2b,100:1a3a1a&height=80&section=footer&text=HDPE%20Irrigation%20Systems&fontSize=16&fontColor=ffffff" />

</div>
