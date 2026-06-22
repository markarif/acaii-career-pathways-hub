# Africa AI Career Pathways Hub
### Powered by ACAII-ACTS AI Institute

> Free AI career guidance for Kenya and East Africa — scholarships, grants, mentorship, training, and direct human support, all in one place.

---

## What This Is

The Africa AI Career Pathways Hub is a free, open-access web platform that connects aspiring AI practitioners, researchers, entrepreneurs, and innovators in Kenya — and across East Africa — with the opportunities they need to enter and grow in the field of Artificial Intelligence.

Built and operated by the **ACAII-ACTS AI Institute** (Africa Centre for Advanced Innovation Initiatives — AI and Technology for Society), the Hub is funded through development partnerships and is completely free to use. There are no fees, no subscriptions, and no barriers.

The platform is part of a broader Tech for Good initiative, submitted for the **2026 Zendesk Tech for Good Impact Awards**, under the impact area of *Creating Career Pathways into Tech*.

---

## The Problem It Solves

Across Africa, thousands of talented individuals — nurses, teachers, farmers, engineers, and students — have ideas that AI could bring to life. Most of them never act on those ideas, not because they lack ability, but because they have no idea where to start. They do not know which scholarships exist, which grants are open, how to find a mentor, or how to write a competitive application.

The Hub closes that gap. It puts all of this in one place, adds a human support layer, and makes sure that no promising person is turned away for want of information.

---

## Features

* **Opportunity Database** — Scholarships, innovation grants, mentorship programmes, free training courses, and tech job listings, all tagged by type, deadline, eligibility, and location.

* **Live Search and Filtering** — Search by keyword or filter by category (scholarships, grants, mentorship, training) to find the right opportunity instantly.

* **AI-Assisted Matching** — The platform uses Zendesk's AI Resolution Platform to instantly surface the most relevant opportunities based on a user's background and interests.

* **Human Backup** — Every query that the AI cannot resolve is escalated to a real person on the ACAII-ACTS AI Institute team, with a guaranteed 24-hour response on weekdays.

* **Support Request Form** — Users submit a short profile describing their background and what they are looking for. The team responds with a personalised match and application guidance.

* **WhatsApp Access** — A floating WhatsApp button means users can reach the Hub from any phone, without needing to be on a desktop or know the URL.

* **Success Stories** — Real accounts of people who found funding, mentorship, or training through the network, to show what is possible.

* **FAQ Section** — Covers eligibility, cost, response times, geographic scope, non-technical applicants, and more, reducing the volume of repeated queries.

* **Fully Responsive** — Works on mobile, tablet, and desktop. Designed with East African internet conditions in mind.

---

## Who It Serves

The Hub is designed for people who are currently excluded from AI career conversations — not people who already know where to look.

**Primary users:**

1. Students and graduates from low-income backgrounds looking for scholarships or funded training in AI
2. Early-career professionals wanting to transition into the AI sector
3. Community innovators with a problem and a solution but no idea how to fund or build it
4. Researchers seeking mentorship, co-investigators, or publishing support
5. Health workers, educators, and farmers interested in applying AI to their sector

**Secondary users:**

1. Programme managers at ACAII-ACTS AI Institute and partner organisations, who use the Hub to receive and route inbound queries
2. Funders and evaluators reviewing ACAII-ACTS AI Institute's reach and pipeline

---

## Opportunities Currently Listed

| Opportunity | Type | Funder | Eligibility |
|---|---|---|---|
| AI4D Innovation Scaling Challenge | Grant (up to $75K) | ACAII-ACTS AI Institute | Pan-African |
| UK-Kenya AI Challenge Fund | Challenge Fund | FCDO / ACAII-ACTS AI Institute | Kenya |
| AI4D SRAIS Mentorship Programme | Mentorship + Research Grant | ACAII-ACTS AI Institute | East Africa |
| AI4D Scholarship Programme | Full Scholarship (Masters/PhD) | ACAII-ACTS AI Institute | Pan-African |
| Responsible AI for Development — Free Course | Online Training | ACAII-ACTS AI Institute LMS | Open to All |
| AMR AI Innovation Hub | Grant + Mentorship | ACAII-ACTS AI Institute | Health Sector |

---

## How to Deploy

The Hub is a single self-contained HTML file with no external dependencies, no build step, and no server required.

**Option 1 — GitHub Pages (recommended)**

1. Fork or clone this repository
2. Go to your repository settings on GitHub
3. Under Pages, set the source to the main branch and root folder
4. GitHub will publish the site at `https://your-username.github.io/repository-name/`
5. Share the published URL with your audience

**Option 2 — Open locally**

Download `ACAII_Career_Pathways_Hub.html` and open it directly in any modern web browser. No installation needed.

**Option 3 — Any static host**

Upload the HTML file to Netlify, Vercel, Cloudflare Pages, or any other static hosting service. It will work without any configuration.

---

## Technology

| Layer | Tool |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (no frameworks) |
| Support & AI Matching | Zendesk AI-powered Resolution Platform |
| Hosting | GitHub Pages |
| WhatsApp Integration | WhatsApp Business API |
| Analytics | Zendesk Explore (built-in) |

The deliberate decision to use no JavaScript frameworks keeps the file lightweight, fast to load on slow connections, and easy for any developer to read and modify without specialised knowledge.

---

## Zendesk Integration

This Hub is built to sit on top of Zendesk's AI-powered Resolution Platform, which handles:

* **AI Agent** — Reads each incoming query and instantly returns the most relevant opportunities, articles, and next steps. Handles the majority of common questions without human involvement.

* **Ticketing** — Every support request submitted through the form creates a Zendesk ticket, assigned to the relevant team member based on query type.

* **Knowledge Base (Zendesk Guide)** — All FAQs, opportunity descriptions, eligibility guides, and application tips are published as Zendesk Help Centre articles, searchable and kept current.

* **Omnichannel** — WhatsApp, web form, and email queries all land in the same Zendesk inbox, so no query falls through the cracks.

* **Reporting (Zendesk Explore)** — The team tracks query volume, response times, satisfaction scores, and which opportunities generate the most interest — producing the impact data that funders expect.

---

## About ACAII-ACTS AI Institute

The Africa Centre for Advanced Innovation Initiatives — AI and Technology for Society (ACAII-ACTS AI Institute) is a nonprofit organisation headquartered in Nairobi, Kenya. Our mission is to support African innovators in building and scaling AI-powered solutions to the continent's most pressing challenges.

We run innovation grants, mentorship programmes, research scholarships, and a growing Community of Practice connecting AI practitioners across Kenya and East Africa. Our funded innovators work in health, agriculture, education, climate adaptation, financial inclusion, and antimicrobial resistance.

**Partner and funder network:** FCDO, AI4D Africa, GIZ, Smart Africa, the African Union, and the Zendesk Foundation.

---

## Contributing

We welcome contributions from developers, content writers, and programme staff.

**To add or update an opportunity listing:**

Open `ACAII_Career_Pathways_Hub.html`, find the `<!-- OPPORTUNITIES -->` section, and copy an existing opportunity card. Update the name, organisation, description, tags, deadline, and button text. Submit a pull request with a brief description of the opportunity added.

**To report an issue or suggest an improvement:**

Open a GitHub Issue with as much detail as possible. Please include what you were trying to do, what happened instead, and which browser or device you were using.

**To translate the Hub into Swahili or another language:**

Contact us directly — we would love to hear from you.

---

## Contact

**ACAII-ACTS AI Institute**
Nairobi, Kenya

* Website: [acaii.org](https://acaii.org)
* Email: info@acaii.org
* WhatsApp Support: Available via the Hub

---

## Licence

This project is open source under the [MIT Licence](LICENSE). You are free to use, adapt, and redistribute it, provided you retain the attribution to ACAII-ACTS AI Institute.

---

*The Africa AI Career Pathways Hub is part of ACAII-ACTS AI Institute's 2026 Tech for Good application to the Zendesk Foundation Impact Awards, under the impact area of Creating Career Pathways into Tech.*
