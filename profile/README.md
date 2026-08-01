# Ambedkar Reading Circle - GitHub Organization Profile

## Objective

Create the special GitHub repository `.github` for the GitHub organization.

This repository is **not** an application. It provides the organization's public landing page, shared community files, issue templates, contribution guidelines, and other organization-wide configuration.

GitHub automatically renders `profile/README.md` as the organization's homepage.

The goal is to make the organization look professional, welcoming, and community-driven.

---

# GitHub Connection Plan

## Repository Details

- **Organization:** ambedkar-reading-circle
- **Repository:** .github
- **URL:** https://github.com/ambedkar-reading-circle/.github
- **Visibility:** Private (initially)

## Setup Steps

### 1. Initialize Git

```bash
git init
```

### 2. Create Required Directory Structure

```bash
mkdir profile
```

Move existing files into structure:

- `banner.png` → `profile/banner.png`
- `new.md` → `profile/README.md`

### 3. Create Initial Commit

```bash
git add .
git commit -m "Initial commit: organization profile setup"
```

### 4. Add Remote and Push

```bash
git branch -M main
git remote add origin https://github.com/ambedkar-reading-circle/.github.git
git push -u origin main
```

## Files to Push

| File | Destination | Status |
|------|-------------|--------|
| banner.png | profile/banner.png | ✅ Ready |
| new.md | profile/README.md | ✅ Ready |
| CONTRIBUTING.md | CONTRIBUTING.md | ⏳ To be created |
| CODE_OF_CONDUCT.md | CODE_OF_CONDUCT.md | ⏳ To be created |
| SECURITY.md | SECURITY.md | ⏳ To be created |
| PULL_REQUEST_TEMPLATE.md | PULL_REQUEST_TEMPLATE.md | ⏳ To be created |
| ISSUE_TEMPLATE/ | ISSUE_TEMPLATE/ | ⏳ To be created |

## Next Steps After Initial Push

1. Verify README renders correctly on GitHub
2. Confirm banner displays properly
3. Add remaining template files (CONTRIBUTING.md, CODE_OF_CONDUCT.md, etc.)
4. Set up issue templates
5. Configure repository settings (branch protection, etc.)

---

# Repository Structure

.github/
├── profile/
│   ├── README.md
│   └── banner.png (placeholder)
│
├── PULL_REQUEST_TEMPLATE.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── LICENSE
└── FUNDING.yml (placeholder)

---

# Organization

Name

Ambedkar Reading Circle

Description

Building open source software, educational resources, civic technology, research, and digital public goods.

---

# Organization Philosophy

Ambedkar Reading Circle is an open community.

We build software, educational resources, workshops, research projects, games, and digital public goods inspired by the ideas of Dr. B. R. Ambedkar.

The tone should feel

- welcoming
- optimistic
- collaborative
- community-first
- technically competent
- not corporate
- not activist-heavy
- not overly academic

---

# README Layout

The README should use GitHub-flavored Markdown.

Sections should be clean with generous spacing.

Use emoji sparingly.

---

## Header

Large title

# Ambedkar Reading Circle

Below it:

> Building open source software, educational resources, civic technology, research, and digital public goods.

---

## Banner

Display banner image

profile/banner.png

centered

100% width

**Note:** Banner image has been added as `banner.png`.

---

## About

Short paragraph.

Suggested content:

We are an open community of readers, educators, researchers, designers, developers, facilitators, and volunteers building projects inspired by the ideas of Dr. B. R. Ambedkar.

We believe knowledge should be accessible, collaborative, and open.

---

## We do

Bullet list

- Organize reading circles
- Create community websites
- Develop Civic technology
- Create digital public goods
- Conduct Interactive workshops
- Do Research
- Create Games
- Visualizations

---

## Current Projects

**Note:** Not all projects are populated yet. We will add more projects soon.

Use a markdown table.

Columns

Project

Description

Status

Repository

Website

Initially populate

### ARC Bengaluru

Description

Official website for the Bengaluru chapter of Ambedkar Reading Circle.

Status

🚧 In Progress

Repository

arc-bengaluru

Website

Coming Soon

---

### Dramas of Discrimination

Description

Interactive workshop toolkit based on Augusto Boal's Theatre of the Oppressed.

Status

🚧 In Progress

Repository

dramas-of-discrimination

Website

Coming Soon

---

Status

Planning

---

## Contributing

Explain that everyone can contribute.

Mention

- documentation
- code
- design
- research
- translations
- facilitation
- testing

Encourage opening Issues and Pull Requests.

**Note:** Detailed contribution guidelines are not yet available. We will add them soon.

---

## Community Values

Short bullet list.

Examples

- Learn together
- Build in the open
- Respect every contributor
- Document our work
- Prioritize accessibility
- Share knowledge freely

---

## Repository Map

Table

Repository

Purpose

Initially

.github

Organization profile

arc-bengaluru

Website

dramas-of-discrimination

Workshop toolkit

---

## Tech Stack

Mention that projects may use

- TypeScript
- React
- Next.js
- Markdown
- Node.js

This section is intentionally short.

---

## Get Involved

Invite

Developers

Designers

Educators

Researchers

Readers

Volunteers

Workshop facilitators

---

## License

All MIT

---

# CONTRIBUTING.md

Include

Project philosophy

How to contribute

Code style

Opening issues

Submitting PRs

Code review expectations

Community behaviour

---

# CODE_OF_CONDUCT.md

Use the Contributor Covenant v2.1.

---

# SECURITY.md

Simple template.

Explain how to privately report security vulnerabilities.

---

# PULL_REQUEST_TEMPLATE.md

Checklist

- Documentation updated
- Tests run
- Screenshots added if UI changed
- Linked issue
- Ready for review

---

# Issue Templates

Bug Report

Fields

- Description
- Steps
- Expected behaviour
- Screenshots
- Environment

---

Feature Request

Fields

- Problem
- Proposed solution
- Alternatives
- Additional context

---

Workshop Proposal

Fields

- Workshop title
- Audience
- Objectives
- Duration
- Materials
- Facilitators

---

# README Style Guide

Prefer

simple language

short paragraphs

tables

bullet lists

avoid walls of text

---

# Visual Style

Inspired by

GitHub organization pages such as

- Tattle
- Kubernetes
- React
- OpenStreetMap

But should feel more community-oriented and educational.

Avoid excessive badges.

Avoid animated GIFs.

Avoid clutter.

---

# Markdown Quality

Produce high-quality GitHub Markdown.

Use tables where appropriate.

Use relative image paths.

Avoid HTML unless necessary.

Ensure the README renders well in both dark and light themes.
