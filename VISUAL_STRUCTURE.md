# LinuxDive Visual Structure

## Homepage Flow

```
┌─────────────────────────────────────────────┐
│                                             │
│         HERO SECTION (Full width)           │
│  ┌─────────────────────────────────────┐   │
│  │  Linux Beyond the Terminal          │   │
│  │  ────────────────────────────────   │   │
│  │  Stories about how Linux is         │   │
│  │  quietly reshaping...               │   │
│  └─────────────────────────────────────┘   │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│     PRIMARY FEATURED ARTICLE (Large)        │
│  ┌────────────────┬─────────────────────┐   │
│  │   Featured     │  Title              │   │
│  │   Image        │  Jan 25, 2026       │   │
│  │   (1:1)        │  By Neil Cass       │   │
│  │                │                     │   │
│  │                │  Excerpt...         │   │
│  │                │                     │   │
│  │                │  [Read article →]   │   │
│  └────────────────┴─────────────────────┘   │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  SECTION PREVIEW: LINUX & SOCIETY          │
│  "How Linux shapes policy, education..."    │
│  ┌──────────┬──────────┬──────────┐        │
│  │Article 1 │Article 2 │Article 3 │ ...    │
│  │[Image]   │[Image]   │[Image]   │        │
│  │Title...  │Title...  │Title...  │        │
│  │Jan 21    │Jan 15    │Jan 10    │        │
│  └──────────┴──────────┴──────────┘        │
│  [View all articles →]                     │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  SECTION PREVIEW: LINUX AT WORK             │
│  "Business, infrastructure, professional..."│
│  ┌──────────┬──────────┬──────────┐        │
│  │Article 1 │Article 2 │Article 3 │ ...    │
│  │[Image]   │[Image]   │[Image]   │        │
│  │Title...  │Title...  │Title...  │        │
│  │Jan 21    │Jan 15    │Jan 10    │        │
│  └──────────┴──────────┴──────────┘        │
│  [View all articles →]                     │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  SECTION PREVIEW: LINUX CULTURE             │
│  "Community, philosophy, learning..."       │
│  ┌──────────┬──────────┬──────────┐        │
│  │Article 1 │Article 2 │Article 3 │ ...    │
│  │[Image]   │[Image]   │[Image]   │        │
│  │Title...  │Title...  │Title...  │        │
│  │Jan 21    │Jan 15    │Jan 10    │        │
│  └──────────┴──────────┴──────────┘        │
│  [View all articles →]                     │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  SECTION PREVIEW: EVERYDAY LINUX            │
│  "Gaming, hardware, personal computing..."  │
│  ┌──────────┬──────────┬──────────┐        │
│  │Article 1 │Article 2 │Article 3 │ ...    │
│  │[Image]   │[Image]   │[Image]   │        │
│  │Title...  │Title...  │Title...  │        │
│  │Jan 21    │Jan 15    │Jan 10    │        │
│  └──────────┴──────────┴──────────┘        │
│  [View all articles →]                     │
│                                             │
└─────────────────────────────────────────────┘
```

## Section Landing Page Flow

```
┌─────────────────────────────────────────────┐
│  LinuxDive | Home | Society | Work | ...    │
├─────────────────────────────────────────────┤
│                                             │
│  SECTION INTRO                              │
│  ┌─────────────────────────────────────┐   │
│  │ Linux & Society                     │   │
│  │ ─────────────────────────────────── │   │
│  │ How Linux shapes policy,            │   │
│  │ education, finance, and public      │   │
│  │ institutions.                       │   │
│  │                                     │   │
│  │ Linux isn't just software — it's    │   │
│  │ infrastructure. This section        │   │
│  │ explores...                         │   │
│  └─────────────────────────────────────┘   │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  ARTICLE GRID (3+ columns on desktop)       │
│  ┌──────────┬──────────┬──────────┐        │
│  │Article   │Article   │Article   │        │
│  │[Image]   │[Image]   │[Image]   │        │
│  │Title     │Title     │Title     │        │
│  │Jan 21    │Jan 15    │Jan 10    │        │
│  │Excerpt.. │Excerpt.. │Excerpt.. │        │
│  │[Read →]  │[Read →]  │[Read →]  │        │
│  ├──────────┼──────────┼──────────┤        │
│  │Article   │Article   │Article   │        │
│  │...       │...       │...       │        │
│  └──────────┴──────────┴──────────┘        │
│                                             │
└─────────────────────────────────────────────┘
```

## Individual Article Page Flow

```
┌─────────────────────────────────────────────┐
│  LinuxDive | Home | Society | Work | ...    │
├─────────────────────────────────────────────┤
│                                             │
│  ARTICLE HEADER                             │
│  ┌─────────────────────────────────────┐   │
│  │                                     │   │
│  │         [Featured Image]            │   │
│  │                                     │   │
│  └─────────────────────────────────────┘   │
│                                             │
│  The Raspberry Pi Outgrew Its Original      │
│  Promise                                    │
│                                             │
│  January 21, 2026 | By Neil Cass            │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  ARTICLE CONTENT                            │
│  ┌─────────────────────────────────────┐   │
│  │ The Raspberry Pi was introduced     │   │
│  │ with a simple idea: a small,        │   │
│  │ affordable computer that could      │   │
│  │ bring real computing back into      │   │
│  │ education.                          │   │
│  │                                     │   │
│  │ ## Where the Raspberry Pi Helped   │   │
│  │                                     │   │
│  │ The Raspberry Pi did have a         │   │
│  │ positive impact in education,       │   │
│  │ particularly in wealthier           │   │
│  │ countries...                        │   │
│  │                                     │   │
│  │ [More content...]                   │   │
│  │                                     │   │
│  └─────────────────────────────────────┘   │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│  ARTICLE TAGS                               │
│  [hardware] [raspberry-pi] [education]      │
│  [linux]                                    │
│                                             │
└─────────────────────────────────────────────┘
```

## Navigation Structure

```
┌─────────────────────────────────────────────┐
│                                             │
│         [LinuxDive] Home  Society  Work     │
│                            Culture Everyday │
│                                             │
└─────────────────────────────────────────────┘
                      │
        ┌─────────────┼──────────────────┐
        │             │                  │
        ▼             ▼                  ▼
   [Homepage]   [Section Pages]   [Articles]
        │             │                  │
        ├─Hero        ├─Society          ├─Featured
        ├─Featured    ├─Work             ├─Content
        ├─Sections    ├─Culture          └─Tags
        └─Preview     └─Everyday
         Cards
```

## Content Organization

```
CONTENT HIERARCHY

LinuxDive/
├── Society
│   ├── Landing Page (/society/)
│   │   ├── Intro + Description
│   │   └── All society articles in grid
│   │
│   └── Articles
│       ├── The Raspberry Pi Outgrew...
│       └── [Future government/policy pieces]
│
├── Work
│   ├── Landing Page (/work/)
│   │   ├── Intro + Description
│   │   └── All work articles in grid
│   │
│   └── Articles
│       └── [Future enterprise/business pieces]
│
├── Culture
│   ├── Landing Page (/culture/)
│   │   ├── Intro + Description
│   │   └── All culture articles in grid
│   │
│   └── Articles
│       ├── Stop Obsessing Over Your First Distro
│       ├── There's Nothing Wrong With Distro Hopping
│       └── [Future community/philosophy pieces]
│
└── Everyday
    ├── Landing Page (/everyday/)
    │   ├── Intro + Description
    │   └── All everyday articles in grid
    │
    └── Articles
        ├── When Games Started Working...
        └── [Future gaming/hardware pieces]
```

## Responsive Behavior

### Desktop (1200px+)
- Hero: 3.5rem title, centered, full width
- Featured: 2-column layout (image left, content right)
- Article cards: 3-column grid
- Navigation: Horizontal menu

### Tablet (768px - 1199px)
- Hero: 2.5rem title
- Featured: Single column (image top)
- Article cards: 2-column grid or single
- Navigation: Hamburger menu available

### Mobile (< 768px)
- Hero: 1.8rem title
- Featured: Single column, stacked
- Article cards: Single column
- Navigation: Hamburger menu (full screen overlay)

## Color & Style

- **Background:** White (#ffffff)
- **Text:** Dark gray (#1a1a1a)
- **Secondary text:** Medium gray (#666666)
- **Accent:** Blue (#0066cc)
- **Borders:** Light gray (#e0e0e0)
- **Font:** System fonts (San Francisco, Segoe UI, etc.)

All responsive with smooth transitions and hover states.
