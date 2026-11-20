---
layout: single
author_profile: true
---
<h1>Pieter D. Versloot | Rice Class of 2027</h1>
<h2>Quantitative Finance & Data Science Projects:</h2>

- <b>Options, Derivatives & Structured Products</b>
  - [BBVA Equity Derivatives Trading Intern Project: Dividend Pricing Rule](/files/Dividend_Pricing_Rule.pdf): pricing rule for dividend forecasts across 800+ stocks, adjusted for implied dividend volatility and the dividend risk premium.
  - [Black-Scholes Option Pricing Repository](https://github.com/pieter-portfolio/vol-01-black-scholes): the baseline model, priced three ways and tested.
    - 01: Closed-form pricer and no-arbitrage checks
    - 02: Brownian motion, quadratic variation, Itô, GBM
    - 03: Black-Scholes PDE, Feynman-Kac, finite-difference solver
    - 04: Monte Carlo and variance reduction
    - 05: Greeks and delta hedging, realized vs. implied vol *(in progress)*
    - 06: Implied volatility and the smile *(upcoming)*
    - 07: American options: binomial tree, Longstaff-Schwartz, PDE with early exercise *(planned)*

- <b>Portfolio Theory</b>
  - [Efficient Frontiers & Systematic Risk: A Visualization of Modern Portfolio Theory](https://sites.google.com/rice.edu/visualizing-portfolio-theory/home): interactive visualization of the efficient frontier, CML and CAPM; Best Visual at the Rice Data Showcase.

- <b>Commodities</b>
  - [Rice Energy Trading Group: WTI–Brent Basis Trade Pitch](https://docs.google.com/presentation/d/1msbzvXIJm1xnTtIMkXJ5lgGomaB42P4fbBi6NKqcfx4/edit?usp=sharing): long Brent / short WTI call combining supply, demand and geopolitical analysis with a Lasso model forecasting the weekly basis (0.80 Sharpe in a 2020–2025 backtest).
  - [HH–TTF Natural Gas Basis Forecasting](https://docs.google.com/presentation/d/1eUlRoAZMys2JvOSG8RVJl7GaERJn6B6n04v4QWFezrw/edit?usp=sharing): five machine-learning models forecasting the weekly Henry Hub–TTF spread from price, weather, rig count and financial-stress data; the Elastic Net trading signal returned a 2.51 Sharpe and 63.8% win rate out of sample (2023).
  - 
<h2>Skills & Interests:</h2>
<ul>
  <li>Data & Statistical Modeling: Python, R, SQL</li>
  <li>Financial Modelling: Excel, VBA</li> 
  <li>Quantitative Finance: Derivatives, Structured Products, Commodities</li>
  <li>Platforms & Databases: Bloomberg Terminal, S&P Capital IQ, FactSet, PitchBook</li>
</ul>

<div class="projects-grid">

<style>
.projects-grid{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 16px;
  margin-top: 12px;
}
.project-card{
  display:block;
  padding: 16px 16px 14px;
  border: 1px solid rgba(0,0,0,0.10);
  border-radius: 14px;
  background: rgba(255,255,255,0.85);
  text-decoration:none !important;
  transition: transform .12s ease, box-shadow .12s ease, border-color .12s ease;
}
.project-card:hover{
  transform: translateY(-2px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
  border-color: rgba(0,0,0,0.18);
}
.project-top{
  display:flex;
  flex-wrap:wrap;
  gap: 8px;
  margin-bottom: 10px;
}
.tag{
  font-size: 12px;
  padding: 3px 10px;
  border-radius: 999px;
  border: 1px solid rgba(0,0,0,0.12);
  opacity: 0.9;
}
.project-card h3{
  margin: 0 0 8px;
  font-size: 18px;
}
.project-card p{
  margin: 0 0 12px;
  color: rgba(0,0,0,0.68);
  line-height: 1.45;
}
.project-link{
  font-weight: 600;
}
</style>

