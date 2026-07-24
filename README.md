

# 📁 01. thirdroom-hq ⭐

**Purpose**

The internal operating system.

Contains:

* Dashboard
* Company Brain
* Knowledge
* CRM
* Projects
* AI
* Documents

This becomes the biggest repository.

---

# 📁 02. blankspace

The client platform.

Contains

* Partner dashboard
* Partner authentication
* Billing
* Client workspace
* Client notifications

Eventually becomes the SaaS.

---

# 📁 03. thirdroom-web

Company website.

Contains

* Landing pages
* Blog
* CMS
* SEO
* Journal

---

# 📁 04. blueprint-library

This is one of the coolest repos.

Instead of code...

Store reusable Blueprint specifications.

Example

```
Healthcare

Restaurant

School

Gym

Architect

Salon

Real Estate
```

Each Blueprint contains

```
README.md

Features.md

Automation.md

SOP.md

Pricing.md

Deployment.md
```

Think of it as **open documentation for your internal team**.

---

# 📁 05. design-system

Everything visual.

Contains

```
Colors

Typography

Spacing

Buttons

Icons

Components

Animations

Tokens
```

Later it can become an npm package.

---

# 📁 06. ui-components

Reusable components.

```
Navbar

Cards

Forms

Tables

Dialogs

Modals

Charts

Buttons
```

One source of truth.

---

# 📁 07. ai-prompts

One of my favorite ideas.

Every production prompt lives here.

Example

```
Proposal Generator

Website Writer

Meeting Summary

CRM Assistant

Knowledge Extraction

Partner Analysis

Discovery Questions
```

Version-controlled.

---

# 📁 08. automations

Contains

```
n8n

Zapier

Make

Webhook

API

Scripts
```

Everything automation-related.

---

# 📁 09. docs

Internal documentation.

```
Architecture

PRDs

System Design

API

Security

Roadmaps

Meeting Notes
```

---

# 📁 10. assets

Contains

```
Logos

Icons

Fonts

Illustrations

Brand Files

Videos
```

---

# 📁 11. templates

Reusable templates.

```
Proposal

Invoice

Contract

Email

Presentation

Landing Page

Discovery Call
```

---

# 📁 12. experiments

Never build experimental ideas inside production.

Everything new goes here.

```
AI

Voice

Agents

RAG

Vision

OCR

Internal tools
```

---

# 📁 13. integrations

Separate integration layer.

```
Google

WhatsApp

Resend

Stripe

Razorpay

OpenAI

Claude

Supabase

Figma
```

---

# 📁 14. infrastructure

Contains

```
Deployment

Docker

CI/CD

Cloudflare

Vercel

Supabase

Environment configs
```

---

# 📁 15. archive

Old versions.

Never delete.

Archive.

---

# Inside every repository

Every repo should have

```
README.md

CHANGELOG.md

ROADMAP.md

CONTRIBUTING.md

LICENSE

/docs

/src
```

Even for internal repos, consistent structure helps future contributors.

---

# GitHub Projects

Don't only use repositories.

Use **GitHub Projects** for planning.

Boards like:

```
Roadmap

Backlog

In Progress

Review

Done
```

For:

* Third Room HQ
* Blankspace
* Website
* Marketing Site

---

# Discussions

Enable GitHub Discussions.

Categories:

* Ideas
* Questions
* Product Feedback
* Architecture
* Feature Requests
* Decisions

This keeps design discussions close to the code.

---

# Wiki

Every repository can have a Wiki.

Use it for:

* Setup guides
* Deployment steps
* API notes
* Troubleshooting

Avoid scattering this across random documents.

---

# Milestones

Use milestones such as:

```
HQ v1

HQ v2

Blankspace Alpha

Website v1

Client Portal Beta
```

They give everyone a shared view of progress.

---

## One thing I'd add that most startups don't

Create a repository called:

```
company-memory
```

Not code.

Just Markdown.

Structure it like this:

```
company-memory/

├── decisions/
├── meeting-notes/
├── founder-journal/
├── principles/
├── retrospectives/
├── product-philosophy/
├── customer-insights/
└── timelines/
```

Every important decision gets its own Markdown file.

Example:

```
2026-07-24-third-room-positioning.md
```

Inside:

* Decision
* Context
* Alternatives
* Why this choice
* Expected impact
* Related documents

Why? Because Git is excellent at preserving history. Years later, you can see not only **what** changed, but **how your thinking evolved** over time.

---

## A small recommendation

Since you're using AI-assisted development and no-code tools today, **don't create all these repositories immediately**.

Start with just these four:

1. **thirdroom-hq** (internal operating system)
2. **thirdroom-web** (company website)
3. **blankspace** (future partner platform)
4. **company-memory** (documentation and decisions)

Everything else can be added when there's a real need. A clean, purposeful GitHub organization scales much better than dozens of empty repositories created on day one.

