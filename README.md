# PIX Adoption in Brazil

**Status:** planned

## Question
How quickly did PIX displace cards, TED/DOC and boletos, and how does adoption vary by user type and region?

## Premises
- PIX is a network-effects technology; adoption should follow an S-curve.
- Substitution is heterogeneous across instruments.

## Method
1. Pull monthly PIX statistics from BCB Open Data (API) and payment-instrument series from the BCB.
2. Fit logistic/Gompertz diffusion curves to transaction counts and values.
3. Compute instrument shares over time; test structural break at launch (Nov/2020).
4. Regional/user-type breakdown where data allows.

## Deliverables
Share-of-payments chart, diffusion fit with parameters, short note linking results to monetary-sovereignty questions (Drex).

## Stack
Python (pandas, scipy, plotly); BCB Open Data API.
