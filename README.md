# Antigravity Pro Skills

A set of ready-to-use **Agent Skills** for [Google Antigravity](https://antigravity.google) that turn the agent into a senior designer, full-stack developer, UI/UX specialist and defensive security reviewer, and keep its answers short, direct and token-efficient.

| | |
|---|---|
| **Developed By** | Netfie Technology |
| **Official Website** | https://netfie.com |
| **License** | MIT |
| **Format** | Agent Skills (`SKILL.md`) |
| **Skills Included** | 3 |

---

## Table of Contents

1. [Overview](#overview)
2. [Skills at a Glance](#skills-at-a-glance)
3. [Skill 1: all-in-one-master](#skill-1-all-in-one-master)
4. [Skill 2: ui-ux-pro-max](#skill-2-ui-ux-pro-max)
5. [Skill 3: direct-efficient](#skill-3-direct-efficient)
6. [Using the Skills Together](#using-the-skills-together)
7. [Repository Structure](#repository-structure)
8. [Installation](#installation)
9. [Usage](#usage)
10. [Example Prompts](#example-prompts)
11. [Customizing](#customizing)
12. [Troubleshooting](#troubleshooting)
13. [FAQ](#faq)
14. [Notes and Limits](#notes-and-limits)
15. [Contributing](#contributing)
16. [License](#license)
17. [About](#about)

---

## Overview

Agent Skills are folders containing a `SKILL.md` file. The file has a short YAML header (`name` and `description`) and a Markdown body with instructions. Antigravity reads the description and loads the full skill when your request matches it.

This pack gives you three skills that work well alone and even better together:

- **What to know:** `all-in-one-master` supplies broad expert knowledge across design, development and security.
- **How to design:** `ui-ux-pro-max` supplies deep, rule-based UI/UX craft and removes the generic "AI look" from interfaces.
- **How to answer:** `direct-efficient` controls the agent's working style so replies are short, targeted and low on wasted tokens.

---

## Skills at a Glance

| Skill | Purpose | Best for | Triggers on |
|---|---|---|---|
| `all-in-one-master` | Senior designer + full-stack engineer + defensive security reviewer | Building and reviewing complete products | Design, UI/UX, frontend, Laravel/PHP, API, admin panel, CMS, news portal, Flutter/Android, Bangla typography, responsiveness, security |
| `ui-ux-pro-max` | Senior-level UI/UX design and front-end build guidance with strict anti-generic rules | Screens, dashboards, design systems, responsive and mobile UI | Designing, reviewing or building any interface |
| `direct-efficient` | Style and efficiency rules | Faster, shorter, cheaper sessions | Any task where you want blunt, token-efficient answers |

---

## Skill 1: all-in-one-master

A single skill that combines expert-level knowledge across design, development and security. It acts as a senior designer, a full-stack developer and a defensive security expert in one.

### Coverage

| Area | Details |
|---|---|
| **Graphic and creative design** | Branding, logos, Adobe Illustrator, Photoshop, Figma, Bangla calligraphy and typography, color theory, WCAG contrast, motion and micro-interactions |
| **UI/UX** | Wireframes, user flows, design systems and tokens, accessibility, mobile-first responsive design (320px to 4K) |
| **Frontend** | HTML5, CSS3, Tailwind, Bootstrap, JavaScript/TypeScript, React, Next.js, Vue, Alpine.js, Blade, Livewire, Core Web Vitals, SEO |
| **News portal and CMS** | Homepage, category and article pages, breaking ticker, ad slots, theme systems, admin dashboards, settings pages |
| **Backend and API** | Laravel, PHP 8+, Node, Python, REST and GraphQL, Sanctum, JWT and OAuth2, MySQL, PostgreSQL, Redis, payments, SMS, email, webhooks |
| **Mobile** | Flutter and Dart, Kotlin, Jetpack Compose, Material 3, Play Store release |
| **Security (defensive)** | OWASP Top 10, input validation, output escaping, CSRF, XSS, SQL injection and IDOR prevention, auth hardening, security headers, server hardening |
| **DevOps** | Git, Linux, Nginx and Apache, Docker, CI/CD, XAMPP and Laragon, cPanel and VPS |

### Roles it plays

1. **Senior designer.** Branding, layout, typography, color and interface design, including Bangla typography.
2. **Full-stack engineer.** Frontend, backend, APIs, databases and mobile apps.
3. **Defensive security reviewer.** Secure coding, hardening and vulnerability review.

### Triggers automatically on

Design, UI/UX, frontend, Laravel and PHP backend, API, admin panel, CMS, news portal, Flutter and Android, Bangla typography, mobile responsiveness and security-hardening tasks.

### Good fit for

- Building a Laravel admin panel with roles, settings and a theme system
- Creating a news portal homepage, article page and category layouts
- Writing a REST API with token authentication
- Reviewing existing code for common web vulnerabilities and fixing them
- Building Flutter screens connected to an API

---

## Skill 2: ui-ux-pro-max

Senior-level UI/UX design and front-end build guidance for any interface. Its core rule is that output must look like senior-designer work from Figma, not a generic AI template.

### Workflow the skill enforces

1. Understand the brief (users, main job of the screen, business goal, main device).
2. Define structure and information architecture before style.
3. Set design tokens (color, type, spacing, radius, elevation, motion) and use only those values.
4. Design mobile first, then scale up.
5. Design every state, not only the happy path.
6. Check accessibility and responsiveness.
7. Deliver in the format the user needs and summarize key decisions.

### Anti-slop rules

The skill bans the habits that make interfaces look machine-made:

- Purple-to-blue or purple-to-pink gradients, mesh blobs, neon glows and overused glassmorphism
- Emoji used as icons, and mixed icon styles
- Meaningless filler copy such as "Unlock the power of..."
- Fake or contradictory metrics and lorem ipsum
- Centered-everything layouts with three identical cards
- Stacked shadows, borders and gradients, and random corner radii
- Decorative blobs and floating 3D shapes with no purpose

### Coverage

| Area | Details |
|---|---|
| **Visual foundations** | 4px spacing scale, 4/8/12-column grids, type scale with fluid headings, tinted neutral palettes, contrast rules, radius and elevation systems, icon and imagery rules, motion durations and reduced-motion support |
| **Bangla and RTL typography** | Noto Sans Bengali and Hind Siliguri guidance, line-height and size adjustments, no negative tracking on Bengali, logical CSS for RTL |
| **UX principles** | One primary action per screen, progressive disclosure, feedback timing, undo over confirm, navigation depth, verb-based labels, Nielsen's heuristics as a review lens |
| **Responsive and mobile** | Mobile-first breakpoints, no horizontal scroll from 320px, touch targets of 44px and 48dp, thumb-zone placement, safe areas, `dvh`, container queries, `srcset`, and a table of how nav, tables, filters and modals change per screen size |
| **Navigation** | Top bar, sidebar, bottom tab bar, breadcrumbs, mega menu, command palette, search, skip links |
| **Components** | Buttons, inputs, selects, checkbox/radio/switch, date pickers, cards, tables, tabs, modals and drawers, toasts, tooltips, badges, pagination, avatars, progress, each with variants and states |
| **States** | Loading, empty, error, partial, success, offline, permission denied, long content and extreme values |
| **Dashboards and admin** | KPI cards, density options, chart selection rules, colorblind-safe palettes, saved views, bulk actions, role-based views, real-time data |
| **SaaS** | Onboarding checklists, settings structure, pricing and billing pages, notification centers |
| **E-commerce** | Homepage sections, product cards and pages, digital product delivery (eBooks, PDFs), cart, checkout, search and filters, reviews |
| **Marketing and landing pages** | Above-the-fold structure, problem-to-proof flow, believable social proof, performance targets |
| **Portfolios** | Identity-first layouts, outcome-focused case studies |
| **News and magazine** | Dense editorial grids, headline hierarchy, article page readability, ad slot handling |
| **Auth and forms** | Sign in, sign up, OTP, recovery, 2FA, validation rules, long-form patterns, file upload |
| **Mobile apps** | iOS and Android conventions, onboarding, lists and gestures, offline behavior, notifications |
| **Other surfaces** | Kanban boards, calendars, chat, CMS editors, maps, media and learning, high-stakes products such as healthcare, finance and legal |
| **Accessibility** | WCAG 2.2 AA, semantic HTML, keyboard operation, focus visibility, labels, target size, reduced motion, captions |
| **Dark mode and theming** | Designed dark palettes, semantic CSS variables, theme persistence, no flash on load |
| **Design system and tokens** | Ready-to-use CSS token template and naming rules |
| **Performance as UX** | LCP, INP and CLS targets, image and font strategy, skeletons, layout shift prevention |

### Deliverable formats

The skill adapts its output to the request:

- **Image-generation prompts:** structured JSON or text with role, brand rules, tokens, sections, states, quality check and a negative prompt
- **Working UI:** semantic, responsive HTML, CSS and minimal JavaScript (or React with Tailwind on request)
- **Design reviews:** prioritized findings (critical, major, minor) with location, problem and fix
- **Wireframes and flows:** screen lists, user flows and per-breakpoint layout notes
- **Developer handoff:** tokens, components, spacing, responsive rules, interaction and accessibility notes

### Final QA checklist

Before delivering, the skill checks visual consistency, responsiveness at 320 to 1440px, all states, accessibility, correct use of supplied brand assets, and realism of sample data.

---

## Skill 3: direct-efficient

A style and efficiency skill. It changes how the agent works and answers, not what it knows.

### Behavior rules

| Rule | What it means |
|---|---|
| **Blunt, direct answers** | No filler, no long introductions, no repeated summaries |
| **Targeted edits** | Changes only the needed lines instead of rewriting whole files |
| **No project-wide scans** | Does not search the entire project unless the task requires it |
| **No repeated file reads** | Reads a file once and reuses what it learned |
| **No extra files** | Does not create files you did not ask for |
| **No unnecessary plans** | Starts work when the request is clear |
| **Two-retry limit** | Stops after two failed attempts and reports the blocker |

> Note: this skill reduces wasted output and exploration. It cannot disable or bypass Antigravity's credit or usage metering, and it does not change any safety rules.

---

## Using the Skills Together

| Goal | Recommended combination |
|---|---|
| Build a full product (frontend, backend, security) | `all-in-one-master` + `direct-efficient` |
| Design or review screens and design systems | `ui-ux-pro-max` + `direct-efficient` |
| Build a polished, responsive interface backed by a real API | `all-in-one-master` + `ui-ux-pro-max` + `direct-efficient` |
| Quick fix with minimal output | `direct-efficient` only |

When `all-in-one-master` and `ui-ux-pro-max` both apply, use `ui-ux-pro-max` as the authority on visual and UX decisions and `all-in-one-master` for backend, security and DevOps decisions.

---

## Repository Structure

```
antigravity-pro-skills/
├── README.md
├── LICENSE
├── all-in-one-master/
│   └── SKILL.md
├── ui-ux-pro-max/
│   └── SKILL.md
└── direct-efficient/
    └── SKILL.md
```

---

## Installation

Antigravity auto-discovers skills from two locations.

| Scope | Path |
|---|---|
| Current project only | `<project>/.agent/skills/<skill-name>/SKILL.md` |
| All projects (global) | `~/.gemini/antigravity/skills/<skill-name>/SKILL.md` |

On Windows, `~` is `C:\Users\<your-username>`. If the same skill name exists in both places, the project version takes priority.

### Option A: Project install (macOS / Linux / Git Bash)

```bash
git clone https://github.com/netfie/antigravity-pro-skills.git
mkdir -p .agent/skills
cp -r antigravity-pro-skills/all-in-one-master .agent/skills/
cp -r antigravity-pro-skills/ui-ux-pro-max .agent/skills/
cp -r antigravity-pro-skills/direct-efficient .agent/skills/
```

### Option B: Global install

```bash
git clone https://github.com/netfie/antigravity-pro-skills.git
mkdir -p ~/.gemini/antigravity/skills
cp -r antigravity-pro-skills/all-in-one-master ~/.gemini/antigravity/skills/
cp -r antigravity-pro-skills/ui-ux-pro-max ~/.gemini/antigravity/skills/
cp -r antigravity-pro-skills/direct-efficient ~/.gemini/antigravity/skills/
```

### Option C: Windows (PowerShell)

```powershell
git clone https://github.com/netfie/antigravity-pro-skills.git
New-Item -ItemType Directory -Force "$env:USERPROFILE\.gemini\antigravity\skills"
Copy-Item -Recurse antigravity-pro-skills\all-in-one-master "$env:USERPROFILE\.gemini\antigravity\skills\"
Copy-Item -Recurse antigravity-pro-skills\ui-ux-pro-max "$env:USERPROFILE\.gemini\antigravity\skills\"
Copy-Item -Recurse antigravity-pro-skills\direct-efficient "$env:USERPROFILE\.gemini\antigravity\skills\"
```

### Option D: Manual

1. Download the repository as a ZIP and extract it.
2. Copy the `all-in-one-master`, `ui-ux-pro-max` and `direct-efficient` folders into one of the skills paths above.
3. Restart Antigravity or open a new chat.

### Verify the install

Open a new chat and ask: *"Which skills do you have available?"* The three skill names should appear. If not, see [Troubleshooting](#troubleshooting).

---

## Usage

Skills load automatically when your request matches their description. Write your task normally:

```
Add a Themes tab to my admin CMS with color pickers and ready-made
templates (Red & Green, Blue, Orange, Dark). Save and apply site-wide.
```

If a skill does not trigger, name it:

```
Use the all-in-one-master and direct-efficient skills.
Build a responsive news portal homepage with a breaking-news ticker.
```

Tips for better results:

- State the device priority (mobile first or desktop first).
- Provide brand colors, logo and exact copy when you have them, so they are used unchanged.
- Name your stack (Laravel, React, Flutter) so the output matches it.
- Ask for one deliverable at a time on large tasks.

---

## Example Prompts

**Design and UI/UX** (`ui-ux-pro-max`)

- "Design a mobile-responsive admin dashboard with a sidebar, KPI cards and data tables."
- "Create a book-selling store homepage with category, bestseller and testimonial sections."
- "Review this checkout page and list critical, major and minor UX problems."
- "Make a design token set and component states for a SaaS settings area."

**Full-stack and backend** (`all-in-one-master`)

- "Create a Laravel REST API with Sanctum auth for a courier tracking app."
- "Build a Flutter login screen with validation and API integration."
- "Create a Bangla news article page with proper typography."

**Security** (`all-in-one-master`)

- "Review this Laravel controller for security issues and fix them."
- "Add input validation, CSRF protection and security headers to this PHP project."

**Efficiency** (`direct-efficient`)

- "Fix only the validation bug in `OrderController.php`. Do not touch other files."
- "Rename this variable across the file. No explanation needed."

---

## Customizing

Each skill is a plain Markdown file with a short YAML header:

```markdown
---
name: all-in-one-master
description: When the agent should use this skill.
---

# Instructions the agent follows
```

- Edit `description` to change **when** the skill triggers.
- Edit the body to change **how** the agent behaves.
- Keep the folder name and the `name` field identical.
- Keep skills concise. Long skill text is sent as input each time it loads.
- For rules that must apply to every prompt, use `GEMINI.md` or `.agents/AGENTS.md` instead.
- To lock output to your stack, add a short "Stack" section to the skill (for example: Laravel 11, Blade, Tailwind, MySQL).

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Skill does not trigger | Restart Antigravity, check the folder name matches the `name` field, and confirm the file is named exactly `SKILL.md` |
| Skill not found | Check the path: `.agent/skills/<name>/SKILL.md` (singular `.agent`) |
| Agent ignores the style | Name the skill explicitly in your prompt |
| Behavior differs between projects | A project skill overrides a global one with the same name |
| UI output still looks generic | Name `ui-ux-pro-max` in the prompt and supply brand colors, copy and a reference |
| Replies are still long | Name `direct-efficient` in the prompt and state the exact scope of the change |
| Two skills seem to conflict | Say which one leads, for example: "Use ui-ux-pro-max for design decisions" |

---

## FAQ

**Do I need all three skills?**
No. Each works on its own. The combinations table above shows common pairings.

**Will `direct-efficient` lower my usage cost?**
It reduces wasted output and unnecessary file reads, which can help. It does not change Antigravity's metering.

**Can I add my own skill to this pack?**
Yes. Create a new folder with a `SKILL.md` file, then add it to the install commands and repository structure in this README.

**Does this work outside Antigravity?**
The `SKILL.md` format is a common Agent Skills format, so the files can be adapted for other tools that support it. Install paths will differ.

---

## Notes and Limits

- These skills set a role and working style. They do not give the model abilities it does not already have.
- Security guidance is **defensive** only: secure coding, hardening and vulnerability review.
- Always review generated code before deploying to production.
- Test layouts on real devices and run an accessibility check before launch.

---

## Contributing

Issues and pull requests are welcome. Please keep skills focused, concise and tested in Antigravity before submitting.

Suggested workflow:

1. Fork the repository.
2. Create a branch for your change.
3. Test the skill in a real Antigravity session.
4. Update this README if you add or change a skill.
5. Open a pull request with a short description and an example prompt.

---

## License

Released under the MIT License. See `LICENSE`.

---

## About

| | |
|---|---|
| **Developed By** | Netfie Technology |
| **Official Website** | https://netfie.com |

© Netfie Technology. All rights reserved.
