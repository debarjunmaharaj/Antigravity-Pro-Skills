# Antigravity Pro Skills

A pair of ready-to-use **Agent Skills** for [Google Antigravity](https://antigravity.google) that turn the agent into a senior designer, full-stack developer and defensive security reviewer, and keep its answers short, direct and token-efficient.

| | |
|---|---|
| **Developed By** | Netfie Technology |
| **Official Website** | https://netfie.com |
| **License** | MIT |
| **Format** | Agent Skills (`SKILL.md`) |

---

## Skills Included

### 1. `all-in-one-master`
A single skill that combines expert-level knowledge across design, development and security.

| Area | Coverage |
|---|---|
| Graphic and creative design | Branding, logos, Illustrator, Photoshop, Figma, Bangla calligraphy and typography, color theory, WCAG contrast, motion and micro-interactions |
| UI/UX | Wireframes, user flows, design systems and tokens, accessibility, mobile-first responsive design (320px to 4K) |
| Frontend | HTML5, CSS3, Tailwind, Bootstrap, JavaScript/TypeScript, React, Next.js, Vue, Alpine.js, Blade, Livewire, Core Web Vitals, SEO |
| News portal and CMS | Homepage, category and article pages, breaking ticker, ad slots, theme systems, admin dashboards, settings pages |
| Backend and API | Laravel, PHP 8+, Node, Python, REST/GraphQL, Sanctum/JWT/OAuth2, MySQL/PostgreSQL/Redis, payments, SMS, email, webhooks |
| Mobile | Flutter/Dart, Kotlin, Jetpack Compose, Material 3, Play Store release |
| Security (defensive) | OWASP Top 10, input validation, output escaping, CSRF/XSS/SQLi/IDOR prevention, auth hardening, security headers, server hardening |
| DevOps | Git, Linux, Nginx/Apache, Docker, CI/CD, XAMPP/Laragon, cPanel/VPS |

**Triggers automatically** on design, UI/UX, frontend, Laravel/PHP, API, admin panel, CMS, news portal, Flutter/Android, Bangla typography, responsiveness and security tasks.

### 2. `direct-efficient`
A style and efficiency skill.

- Blunt, direct answers with no filler
- Targeted edits instead of full rewrites
- No project-wide scans, repeated file reads, extra files or unnecessary plans
- Stops after two failed retries and reports the blocker

> Note: this skill reduces wasted output and exploration. It cannot disable or bypass Antigravity's credit or usage metering, and it does not change any safety rules.

---

## Repository Structure

```
antigravity-pro-skills/
├── README.md
├── LICENSE
├── all-in-one-master/
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
cp -r antigravity-pro-skills/direct-efficient .agent/skills/
```

### Option B: Global install

```bash
git clone https://github.com/netfie/antigravity-pro-skills.git
mkdir -p ~/.gemini/antigravity/skills
cp -r antigravity-pro-skills/all-in-one-master ~/.gemini/antigravity/skills/
cp -r antigravity-pro-skills/direct-efficient ~/.gemini/antigravity/skills/
```

### Option C: Windows (PowerShell)

```powershell
git clone https://github.com/netfie/antigravity-pro-skills.git
New-Item -ItemType Directory -Force "$env:USERPROFILE\.gemini\antigravity\skills"
Copy-Item -Recurse antigravity-pro-skills\all-in-one-master "$env:USERPROFILE\.gemini\antigravity\skills\"
Copy-Item -Recurse antigravity-pro-skills\direct-efficient "$env:USERPROFILE\.gemini\antigravity\skills\"
```

### Option D: Manual

1. Download the repository as a ZIP and extract it.
2. Copy the `all-in-one-master` and `direct-efficient` folders into one of the skills paths above.
3. Restart Antigravity or open a new chat.

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

### Example prompts

- "Design a mobile-responsive admin dashboard with a sidebar, stats cards and data tables."
- "Create a Laravel REST API with Sanctum auth for a courier tracking app."
- "Build a Flutter login screen with validation and API integration."
- "Review this Laravel controller for security issues and fix them."
- "Create a Bangla news article page with proper typography."

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
- Keep skills concise. Long skill text is sent as input each time it loads.
- For rules that must apply to every prompt, use `GEMINI.md` or `.agents/AGENTS.md` instead.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Skill does not trigger | Restart Antigravity, check the folder name matches the `name` field, and confirm the file is named exactly `SKILL.md` |
| Skill not found | Check the path: `.agent/skills/<name>/SKILL.md` (singular `.agent`) |
| Agent ignores the style | Name the skill explicitly in your prompt |
| Behavior differs between projects | A project skill overrides a global one with the same name |

---

## Notes

- These skills set a role and working style. They do not give the model abilities it does not already have.
- Security guidance is **defensive** only: secure coding, hardening and vulnerability review.
- Always review generated code before deploying to production.

---

## Contributing

Issues and pull requests are welcome. Please keep skills focused, concise and tested in Antigravity before submitting.

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
