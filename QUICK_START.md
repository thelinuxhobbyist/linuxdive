# LinuxDive Quick Start Guide

## Creating a New Article

### 1. Create the file in the right section

```bash
# For a Society piece (government, education, institutional impact)
hugo new society/your-article-title.md

# For Work (business, enterprise, infrastructure)
hugo new work/your-article-title.md

# For Culture (community, philosophy, learning)
hugo new culture/your-article-title.md

# For Everyday (gaming, hardware, personal computing)
hugo new everyday/your-article-title.md
```

### 2. Fill in the frontmatter

```markdown
---
title: "Your Compelling Article Title"
date: 2026-02-05
draft: false
author: "Your Name"
featured_image: "https://cdn.linuxdive.com/image.webp"
featured: false  # Set to true to feature on homepage
tags: ["tag1", "tag2", "tag3"]
---
```

### 3. Write your article

Each section has its own expected structure (guides are in the archetypes). Follow the opening → main argument → conclusion flow.

### 4. Preview locally

```bash
hugo server -D
# Visit http://localhost:1313/
```

### 5. Publish

Remove `draft: false` from frontmatter and rebuild:

```bash
hugo --minify
```

---

## Section Guide

### **Society** (`/society/`)
- Institutional impact: government, education, policy
- Real-world adoption at scale
- Linux's role in shaping public infrastructure
- **Example:** "The Raspberry Pi Outgrew Its Original Promise"

### **Work** (`/work/`)
- Business cases and enterprise use
- Professional workflows and infrastructure
- Linux in startups, corporations, and industry
- *Currently empty — ready for your content*

### **Culture** (`/culture/`)
- Community philosophy and values
- Mindsets about open source
- How people learn and explore Linux
- **Examples:** "Stop Obsessing Over Your First Linux Distro", "There's Nothing Wrong With Distro Hopping"

### **Everyday** (`/everyday/`)
- Personal computing and gaming
- Hardware projects and DIY
- How Linux fits into regular people's lives
- **Example:** "When Games Started Working, Linux Got New Users"

---

## Featured Articles

To feature an article on the homepage:
1. Add `featured: true` to the article's frontmatter
2. Rebuild
3. The newest featured article will appear in the "Primary Featured" section

Only one featured article shows at a time (newest first).

---

## Navigation

The header shows:
```
LinuxDive | Home | Society | Work | Culture | Everyday
```

Each section link goes to that section's landing page.

---

## Tags

Use tags for cross-cutting themes:
- `linux` (appears on almost everything)
- `education`, `gaming`, `government`, `business`, `hardware`
- `opinion`, `analysis`, `news`, `culture`
- `beginners`, `enterprise`, `open-source`

Tags appear on individual article pages and can be used for filtering/discovery.

---

## Updating the Homepage

The homepage automatically pulls:
1. **Featured article** (marked with `featured: true`)
2. **Section preview cards** (up to 3 latest articles from each section)

No manual updating needed — just publish articles and the homepage reflects them.

---

## Deployment

Once you're ready to go live:

```bash
# Build the production site
hugo --minify

# The output goes to /public/
# Deploy this directory to your hosting
```

The `public/` directory contains the complete static site ready for any host.

---

## File Locations

```
/content/
  society/       ← Government, education, institutional stories
  work/          ← Business, enterprise, infrastructure
  culture/       ← Community, philosophy, learning
  everyday/      ← Gaming, hardware, personal computing
  pages/         ← Static pages (about, contact, etc.)
  posts/         ← Legacy (old posts — mostly unused now)

/layouts/
  index.html     ← Homepage (magazine layout)
  society/       ← Section pages
  work/
  culture/
  everyday/

/static/css/style.css  ← All styling
/archetypes/           ← Templates for new articles
```

---

## Common Tasks

### Add author info to an article
```markdown
author: "Neil Cass"
```

### Add a featured image
```markdown
featured_image: "https://cdn.linuxdive.com/image.webp"
```

### Feature on homepage
```markdown
featured: true
```

### Add multiple tags
```markdown
tags: ["linux", "gaming", "personal-computing", "culture"]
```

### Draft an article (won't appear until published)
```markdown
draft: true
```

### Update section description
Edit the section's `_index.md` file:
- `/content/society/_index.md`
- `/content/work/_index.md`
- `/content/culture/_index.md`
- `/content/everyday/_index.md`

---

## Tips for Writing

- **Strong headlines** — This is a magazine, not a tutorial blog
- **Opinion and analysis** — Don't be afraid to take a position
- **Real examples** — Ground your arguments in actual stories
- **Conversational tone** — Smart and approachable, not formal
- **Links to context** — Tag-based discovery helps readers explore related pieces
- **Section matters** — Choose the right section; it frames the article

---

## Need Help?

- **Site building:** Run `hugo` to rebuild
- **Local preview:** Run `hugo server -D`
- **Check syntax:** Run `hugo --check` for errors
- **See all pages:** 53 pages generate (4 section landing pages + articles + legacy content)

Your Hugo version: 0.152.2
