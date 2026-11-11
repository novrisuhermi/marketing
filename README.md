# Marketing — Interactive Study Dashboards

Four interactive, single-file study dashboards for digital marketing professionals: **measurement, media buying, media planning and business messaging**. Each one turns a professional exam study guide into short lessons, hands-on labs, practice quizzes, flashcards, a cheat sheet and a glossary, and runs entirely in the browser.

| Dashboard | Open online | What it covers | File |
|---|---|---|---|
| 📊 **Marketing Science** | [novrisuhermi-marketing-science](https://novrisuhermi-marketing-science.share.connect.posit.cloud) | Goals and KPIs, hypotheses, A/B and lift tests, attribution, regression, marketing mix models, SQL | `index.html` |
| 🛒 **Media Buying** | [novrisuhermi-buying](https://novrisuhermi-buying.share.connect.posit.cloud) | Campaign setup, objectives, buying types and the ad auction, signals and audiences, creative, reporting | `buying/index.html` |
| 🗓️ **Media Planning** | [novrisuhermi-planning](https://novrisuhermi-planning.share.connect.posit.cloud) | Campaign elements, buying types, objectives, budget, audiences, placements, creative, measurement, privacy, brand safety, ad review | `planning/index.html` |
| 💬 **Business Messaging** | [novrisuhermi-messaging](https://novrisuhermi-messaging.share.connect.posit.cloud) | Messaging solutions and policies, message categories, goals and journeys, the maturity model, partners and onboarding, testing | `messaging/index.html` |

---

## ✨ What every dashboard offers

- **Learning steps** that follow the exam’s structure, each with short lessons, inline knowledge checks and a progress ring that marks a step done once every section has been opened.
- **Interactive labs** where you change the inputs and watch the results move: simulators, calculators, sorting games and decision pickers.
- **Practice:** scenario questions in the style of the exam, with shuffled answers, instant explanations and study guide page references, plus flashcards built from the glossary.
- **Reference:** a cheat sheet of the numbers, rules and frameworks worth knowing cold, and a searchable glossary.
- **Light and dark appearance:** light by default, with a switch in the navigation bar; the choice is remembered.
- **Lightweight:** one self-contained HTML file per dashboard, with no libraries, no build step and no server. It works offline.

## 📊 Marketing Science

Five steps: **Assess, Hypothesize, Recommend measurement, Perform an analysis, Make recommendations.**
Six labs: a conversion lift and A/B test simulator (including the *baseline trap*), attribution models, a marketing mix model with a 10% budget-cut game, regression, SQL joins and a query builder, and a measurement method picker.

## 🛒 Media Buying

Lessons follow the buying workflow, from activating campaigns in Ads Manager and managing assets in Business Suite to campaign objectives, auction and reservation buying, signals and data sources, audience creation, creative strategy, and reporting and measurement. Labs let you run an ad auction and explore the decisions buyers make every day.

## 🗓️ Media Planning

Lessons cover the planner’s toolkit: core campaign elements, buying types, objectives, budgets, audiences, placements, ad creative, reporting and measurement, and the guardrails of data privacy, brand safety and ad review. Labs let you plan reach and frequency and budgets.

## 💬 Business Messaging

Five steps: **Solutions and policies, Goals and journeys, Maturity model, Partners and onboarding, Measure and optimize.**
Four labs:
- **Conversation windows:** step through a WhatsApp timeline to see when the 24-hour customer service window is open, which conversation categories open and when a template is required.
- **Click-to-message funnel:** model ads that click to message from impressions to conversations, leads and purchases, with cost per result and return on ad spend.
- **Maturity check:** answer six questions to place a business on the five-phase maturity model, with focus areas and next steps.
- **Journey designer:** build a messaging journey from business outcome to entry point, in-thread experience and conversion point, and check that the pieces fit.

## 🚀 Getting started

**Use them online** with the links in the table above. There is nothing to install, and they work on phones, tablets and laptops.

**Open them locally.** Download any of the HTML files and open it in a modern browser (Chrome, Edge, Safari or Firefox). No internet connection is needed.

**Embed them in a website** such as Google Sites, a learning management system or a blog, with an iframe:

```html
<iframe src="https://novrisuhermi-messaging.share.connect.posit.cloud" width="100%" height="900"
        style="border:0;border-radius:16px" title="Business Messaging"></iframe>
```

**Link straight to a section.** Each dashboard reads the part of the address after `#`, so a link such as `index.html#practice/quiz` opens that page directly. Every dashboard has `#practice/quiz`, `#practice/cards`, `#cheatsheet` and `#glossary`, plus one address per lesson and lab (for example `#lab-window` in Business Messaging).

## 🛠️ Under the hood

- **Self-contained:** HTML, CSS and JavaScript live in one file per dashboard. The only optional external request is the Inter web font, which loads without blocking the page and falls back to the system font.
- **No libraries:** charts are hand-built SVG, and formulas are native MathML.
- **Responsive and accessible:** from phones to wide screens, with keyboard navigation, visible focus states, screen-reader labels and support for reduced motion.
- **No tracking:** progress, quiz scores and the appearance setting stay in the visitor’s own browser (local storage). The pages have no analytics.

## 🗂️ Repository structure

```
marketing/
├── index.html              # Marketing Science
├── buying/index.html       # Media Buying
├── planning/index.html     # Media Planning
├── messaging/index.html    # Business Messaging
└── README.md
```

## 👤 Author

Maintained by **Novri Suhermi**.
