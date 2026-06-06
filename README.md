# Leadership Portfolio Redesign

A product design exercise focused on transforming a performance dashboard into a narrative-driven career portfolio.

🔗 **Live Demo:** https://om-dhomne.github.io/leadership-portfolio-redesign/

---

## Overview

Traditional performance dashboards are effective at displaying metrics, but often fail to communicate the story behind those metrics.

This project redesigns a monthly employee performance report into a leadership portfolio that helps multiple stakeholders quickly understand:

* How the month went
* What was accomplished
* What business impact was created
* Where growth opportunities exist
* What barriers were encountered
* Whether the employee is on track for promotion

The redesign prioritizes storytelling, information hierarchy, and decision-making over metric-heavy reporting.

---

## Problem Statement

The original portfolio contained rich performance data but lacked a clear narrative structure.

Users could see scores, KPIs, deliverables, and capability ratings, but still struggled to answer key questions:

* Was this a strong month?
* Why was it strong?
* What needs improvement?
* Is promotion readiness visible?
* What should happen next?

The challenge was to preserve all six required sections while making the experience easier to understand for employees, supervisors, HR reviewers, and mentors.

---

## Target Users

### Employee

* What did I achieve this month?
* What should I improve next?
* Am I progressing?

### Supervisor

* Was this a good month?
* What evidence supports that?
* What coaching is required?

### HR / Promotion Committee

* Is performance improving over time?
* Is promotion readiness visible?

### Mentor / Future Self

* What patterns are emerging?
* What strengths and weaknesses are recurring?

---

## Design Goals

* Transform dashboard → portfolio
* Prioritize narrative over metric overload
* Improve information hierarchy
* Support multiple stakeholders
* Preserve data integrity
* Make the portfolio externally understandable
* Create a document suitable for promotion and performance discussions

---

## Information Architecture

Monthly In Review

↓

What I Delivered

↓

Business Impact

↓

Strengths & Growth Areas

↓

Barriers & Resolutions

↓

Career Outlook

---

## Key Design Decisions

### 1. Narrative-First Hero Section

The redesign begins with a clear performance verdict instead of leading with raw metrics.

A short summary statement communicates the meaning of the month, while supporting metrics provide evidence underneath.

---

### 2. Single-Column Reading Experience

Instead of a dashboard-style multi-column layout, the portfolio follows a full-width reading flow.

This encourages understanding and reflection rather than rapid metric scanning.

---

### 3. Progressive Disclosure

Important insights are shown immediately while supporting evidence remains available through expandable sections.

This allows both quick reviews and deep dives without overwhelming the reader.

---

## Section Logic

| Section                  | Primary Question Answered                              |
| ------------------------ | ------------------------------------------------------ |
| Monthly In Review        | How did this month go?                                 |
| What I Delivered         | What was actually accomplished?                        |
| Business Impact          | Did the work create measurable outcomes?               |
| Strengths & Growth Areas | What strengths and gaps define readiness?              |
| Barriers & Resolutions   | What constrained performance and how was it addressed? |
| Career Outlook           | What should happen next?                               |

---

## Artifacts

### Hand-Drawn Wireframe

Used to define:

* Information hierarchy
* Section order
* Narrative flow
* Visual weight distribution

### Design Rationale

Documents:

* Design decisions
* Tradeoffs
* Assumptions
* Future improvements

### Final Portfolio

Interactive HTML implementation of the redesigned experience.

---

## Preview

### Monthly In Review

![Hero Section](assets/hero.png)

### Strengths & Growth Areas

![Growth Areas](assets/growth-areas.png)

### Career Outlook

![Career Outlook](assets/career-outlook.png)

---

## Before vs After

### Before

* Dashboard-like presentation
* Metrics were isolated
* Promotion readiness difficult to infer
* Weak narrative structure

### After

* Story-driven portfolio
* Clear monthly verdict
* Stronger information hierarchy
* Explicit growth and promotion narrative
* Improved portability across stakeholders

---

## Learnings

The most important lesson from this project was that information hierarchy matters more than visual polish.

The challenge was not creating new data, but helping users make sense of existing data.

A well-structured narrative can significantly improve understanding without changing the underlying dataset.

---

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript

---

## Repository Structure

```text
.
├── index.html
├── README.md
├── assets/
│   ├── hero.png
│   ├── growth-areas.png
│   ├── career-outlook.png
│   └── wireframe.jpg
├── docs/
│   ├── Design_Rationale.pdf
│   └── Wireframe.pdf
└── LICENSE
```

---

## Future Improvements

If given additional time, I would explore:

* Multiple stakeholder views (Employee / Manager / HR)
* Multi-month trend visualizations
* Promotion-readiness forecasting
* User testing with managers and employees
* Exportable PDF portfolio mode

---

## Author

**Om Dhomne**

Chemical Engineering Undergraduate @ IIT Madras

Interested in Product, Analytics, AI, and Startup Ecosystems.

LinkedIn: https://linkedin.com/in/omdhomne

---

Created as part of a Product Management / Product Design internship assignment focused on information architecture, UX thinking, storytelling with data, and stakeholder-centric design.
