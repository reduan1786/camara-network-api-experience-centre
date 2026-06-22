# Contributing to the CAMARA Network API Experience Centre

Thank you for contributing to the CAMARA Network API Experience Centre.

Our goal is to build the premier interactive showcase for CAMARA Network APIs that is clean, maintainable, scalable and enjoyable to use.

---

# Project Philosophy

This project values:

- Simplicity
- Consistency
- Accessibility
- Maintainability
- Business-first storytelling
- High-quality developer experience

Every contribution should improve at least one of these areas.

---

# Before You Begin

Please read:

- PROJECT_BRIEF.md
- ARCHITECTURE.md
- DESIGN_SYSTEM.md
- ENGINEERING_GUIDE.md

These documents describe how the project is structured and the principles behind implementation decisions.

---

# Development Workflow

Every feature follows the same lifecycle.

1. Plan
2. Design
3. Implement
4. Review
5. Test
6. Deploy

Features should be small enough to review independently.

---

# Branch Naming

Examples:

feature/homepage

feature/api-explorer

feature/passwordless-login

fix/navigation

docs/design-system

---

# Commit Messages

We follow Conventional Commits.

Examples:

feat(home): add hero section

feat(api): add API catalogue

fix(nav): correct mobile navigation

docs: update architecture guide

style: improve spacing

refactor: simplify service family component

---

# Pull Requests

Each Pull Request should contain:

- Clear description
- Screenshots (if UI changes)
- Acceptance criteria
- Testing notes

Small pull requests are preferred over large ones.

---

# Code Style

- TypeScript only
- Functional React components
- Reusable components
- No duplicated logic
- Prefer composition over inheritance

---

# UI Principles

Every interface should be:

- Accessible
- Responsive
- Fast
- Consistent

Avoid unnecessary animations.

Motion should reinforce understanding rather than distract.

---

# Content Principles

The Experience Centre is content-driven.

Business content should never be hardcoded into components.

Instead, content belongs in:

/src/content

Components should render content rather than contain it.

---

# Design Philosophy

Business users should immediately understand:

- the problem
- the solution
- the business value

Developers should immediately understand:

- the APIs
- the workflow
- the implementation

The Experience Centre should bridge both audiences.

---

# Questions to Ask Before Every Change

Does this improve clarity?

Is this reusable?

Can this become content instead of code?

Does this support future CAMARA APIs?

Would another developer understand this in six months?

If the answer is "no", reconsider the implementation.

---

# Thank You

Every contribution helps build a better experience for the CAMARA community.
