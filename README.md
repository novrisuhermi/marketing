# Marketing Science — Interactive Study Dashboard

**▶ Open the dashboard: [novrisuhermi-marketing-science.share.connect.posit.cloud](https://novrisuhermi-marketing-science.share.connect.posit.cloud)**

An interactive, single-file dashboard for learning marketing science: how to turn a business goal into a measurable KPI, design experiments that prove causality, read statistical output with confidence, and turn results into recommendations that decision makers can act on.

It is organized around the five domains of the **Marketing Science Professional** exam and is built for self-study, classroom teaching and team training. Everything runs in the browser, works offline and can be embedded in any website.

---

## ✨ Highlights

- **Learn by doing.** Six labs let you run simulated lift tests, split attribution credit, cut a budget with a marketing mix model, fit regressions and write SQL.
- **Exam-style practice.** 61 scenario questions with explanations and source page references, plus flashcards.
- **Everything in one place.** Five lessons, a cheat sheet of thresholds and formulas, and an 82-term glossary.
- **Light and dark appearance.** Light by default, with a switch in the navigation bar; the choice is remembered.
- **Lightweight and portable.** One HTML file of about 290 KB (around 85 KB compressed), with no external libraries, no build step and no server.

## 🧭 The five steps

| Step | What you learn | Interactive pieces |
|---|---|---|
| **1. Assess** | SMART goals; primary and secondary KPIs; metrics across the funnel and across channels; data sources; data quality (granularity, outliers, missing data); experimental versus observational methods | SMART checker, goal-to-KPI matching, funnel explorer, data source finder, outlier lab, missing-data redistribution, randomization demo |
| **2. Hypothesize** | Who, what, where, when and why; test hypotheses with a null and an alternative; independent and dependent variables; choosing a measurement approach; p-values and R² | Hypothesis builder, variable spotter, scenario-to-approach matching, p-value explorer |
| **3. Recommend measurement** | Designing A/B, brand lift and conversion lift tests; single-cell, multi-cell and nested designs; strengths and limits of each solution; feasibility and statistical power | Brand lift calculator, audience investment case, solution comparison, method picker, power check |
| **4. Perform an analysis** | Statistical outputs versus validation metrics; five attribution models; least-squares regression and how to read its output; summary statistics; lift calculations; SQL joins and aggregates; charts; reconciling results across tools | Sorting game, attribution explorer, scatter explorer, regression output reader and predictor, summary statistics table, lift calculator, join explorer |
| **5. Make recommendations** | Synthesizing insights; reading A/B, conversion lift and brand lift results; avoiding over-attribution; the plan, test, learn, scale loop; communicating with stakeholders | Results reader, test-and-learn cycle, one insight told to three audiences |

Every step combines short lessons with inline knowledge checks, and a progress ring tracks how far you have come: a step counts as done once each of its sections has been opened.

## 🧪 Labs

| Lab | What you do |
|---|---|
| **Lift and A/B tests** | Set the audience, holdout, baseline conversion rate, true lift and budget, then run a simulated conversion lift test as often as you like and watch confidence and power. Run an A/B test, and explore the *baseline trap*, where an A/B test crowns retargeting while a lift test shows prospecting adds more sales. |
| **Attribution models** | Build a customer journey of impressions, clicks and visits, and compare first click, last touch, even credit, positional (30% and 40%) and time decay (1-day and 7-day half-life) side by side. |
| **Marketing mix model** | Read a marketing mix equation as a waterfall, then cut a budget by 10% using response curves and marginal returns, and compare your plan with the optimal one. |
| **Regression** | Change the correlation, add an outlier and show the residuals; then read a regression output table and predict sales, revenue and profit. |
| **SQL** | See exactly which rows each JOIN keeps, then build queries clause by clause (`SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `LIMIT`) and solve seven challenges. |
| **Method picker** | Answer a few questions about your goal and constraints to get the recommended measurement solution, with its KPI, thresholds and caveats. |

## 📝 Practice and reference

- **Quiz:** a quick 10, one step at a time, or all 61 questions, with shuffled answers, instant explanations, a score breakdown by step and a review of your misses. Press 1–4 to answer from the keyboard.
- **Flashcards:** the whole glossary as flip cards, filterable by step.
- **Cheat sheet:** the numbers and rules worth memorizing (confidence levels, statistical power, sample sizes, test durations, attribution settings), key formulas, a "which solution when" table and common traps.
- **Glossary:** 82 terms in plain language, each linked back to its lesson.

## 🚀 Getting started

**Use it online.** The dashboard is hosted on Posit Connect Cloud at <https://novrisuhermi-marketing-science.share.connect.posit.cloud>. There is nothing to install, and it works on phones, tablets and laptops.

**Open it locally.** Download `index.html` and open it in any modern browser (Chrome, Edge, Safari or Firefox). No installation or internet connection is needed.

**Embed it in a website** such as Google Sites, a learning management system or a blog, with an iframe:

```html
<iframe src="https://novrisuhermi-marketing-science.share.connect.posit.cloud" width="100%" height="900"
        style="border:0;border-radius:16px" title="Marketing Science"></iframe>
```

**Link straight to a section.** The dashboard reads the part of the address after `#`, so a link such as `index.html#lab-lift` opens that page directly:

| Add to the address | Opens |
|---|---|
| `#assess`, `#hypothesize`, `#measure`, `#analyze`, `#recommend` | A lesson; add a section name to open it directly, e.g. `#analyze/regression` |
| `#lab-lift`, `#lab-attribution`, `#lab-mmm`, `#lab-regression`, `#lab-sql`, `#lab-picker` | A lab |
| `#practice/quiz`, `#practice/cards` | The quiz or the flashcards |
| `#cheatsheet`, `#glossary` | The reference pages |

## 🛠️ Under the hood

- **Self-contained:** HTML, CSS and JavaScript live in one file. The only optional external request is the Inter web font, which loads without blocking the page and falls back to the system font.
- **No libraries:** charts are hand-built SVG, and formulas are native MathML, so they stay crisp at any zoom level.
- **Responsive and accessible:** from phones to wide screens, with keyboard navigation, visible focus states, screen-reader labels and support for reduced motion.
- **No tracking:** progress, quiz scores and the appearance setting stay in the visitor’s own browser (local storage). The page has no analytics.

## 🗂️ Repository structure

```
marketing/
├── index.html   # The Marketing Science dashboard (one self-contained file)
└── README.md
```

## 👤 Author

Maintained by **Novri Suhermi**.
