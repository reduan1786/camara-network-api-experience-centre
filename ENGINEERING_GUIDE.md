# Engineering Guide

Project Atlas

Public Product:

CAMARA Network API Experience Centre

---

# Vision

Build a production-quality Experience Centre that demonstrates how CAMARA Network APIs solve real-world business problems.

This is not an API catalogue.

It is an interactive solution showcase.

---

# Engineering Principles

## Build once.

Reuse everywhere.

Every reusable component should be generic enough to power multiple solutions.

---

## Content over code.

Business information belongs in content.

Components render content.

---

## Composition over duplication.

If similar components appear twice,
they probably belong in a shared component.

---

## Business-first.

Every page answers:

What problem exists?

How do CAMARA APIs solve it?

How do I implement it?

---

# Architecture

Repository

docs/

assets/

web/

Application

src/

app/

components/

content/

features/

hooks/

lib/

styles/

types/

---

# Feature-first Architecture

Business capabilities live inside:

features/

Examples:

home/

solutions/

api-explorer/

industries/

resources/

playground/

Reusable UI belongs in:

components/

---

# Content-first Architecture

Every business object should eventually become structured content.

Examples:

APIs

Solutions

Industries

Service Families

Resources

Roadmap

This allows the Experience Centre to grow without rewriting React components.

---

# Naming Conventions

Components

PascalCase

Example:

SolutionCard.tsx

ServiceFamilyCard.tsx

Files

camel-case

Example:

service-families.ts

api-catalog.ts

---

# Folder Responsibilities

app/

Routing

components/

Reusable UI

content/

Business content

features/

Business functionality

lib/

Utilities

types/

TypeScript models

styles/

Global styling

---

# UI Philosophy

Inspired by:

Apple

Stripe

Vercel

Linear

Characteristics:

- generous spacing
- subtle gradients
- premium typography
- restrained motion
- clean hierarchy

---

# Motion

Animations should:

guide attention

reinforce hierarchy

never slow users down

---

# Accessibility

Minimum AA contrast.

Keyboard navigation.

Semantic HTML.

ARIA where appropriate.

Accessible animations.

---

# Performance

Prefer Server Components.

Lazy-load heavy components.

Optimize images.

Avoid unnecessary client-side rendering.

---

# Testing Philosophy

Every feature should be:

Buildable

Reviewable

Deployable

Testing will include:

Component testing

Accessibility checks

Responsive testing

Manual scenario validation

---

# Deployment

GitHub

↓

Vercel Preview

↓

Production

Every commit should be deployable.

---

# Long-term Goal

The Experience Centre should become a reusable platform.

Adding a new CAMARA API should primarily involve adding content rather than writing new application logic.

---

# Engineering Motto

Design for today's demos.

Architect for tomorrow's platform.
