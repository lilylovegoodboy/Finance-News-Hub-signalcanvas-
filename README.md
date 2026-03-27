# Finance News Hub SignalCanvas UI

Open-source UI shell for an event-driven market research workspace.

This repository mainly includes:

- frontend pages
- shared UI
- layout and interactions
- user manual pages
- base product structure

It shows how a workspace built around:

- event thesis
- lead-theme observation
- simulated human investing
- retail heat

can be organized and presented.

## Scope

This is **not** the full production trading system and **not** a full strategy open-source repo.

This public repo focuses on:

- page design
- information architecture
- UI components and interactions
- user manual and product explanation
- presentation-layer organization

It does **not** include:

- core strategy logic
- ranking and scoring rules
- lead-theme inference rules
- simulator execution engine details
- production secrets or private data sources

## Included modules

- news home
- thesis engine page
- simulator page
- retail heat page
- user manual
- dark mode, navigation, card system, responsive layout

## Structure

```text
app/
  templates/
    base.html
    index.html
    thesis_engine.html
    simulator.html
    retail_heat.html
    user_manual.html
  static/
    style.css
mock/
screenshots/
```

## Design principles

- layer complex information before showing details
- let users see the conclusion before the evidence
- embed AI explanations into modules instead of floating chat only
- open the product shell, keep the strategy core private

## Disclaimer

This open-source part is for product design, learning, and interface reference only.

It is **not** investment advice. Markets are risky. Make decisions carefully.
