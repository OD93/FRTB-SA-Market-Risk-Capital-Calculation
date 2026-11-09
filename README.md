# FRTB-SA Market Risk Capital Calculation

## Project Overview

This project demonstrates the implementation of the **Fundamental Review of the Trading Book – Standardised Approach (FRTB-SA)** using Python.

The objective is to understand how financial institutions classify trading book positions, identify market risk factors, calculate risk sensitivities, apply risk weights and correlation assumptions, and estimate illustrative regulatory capital requirements under the Basel market risk framework.

The project uses a sample trading portfolio consisting of equities, government and corporate bonds, interest rate swaps, FX forwards, commodity futures, and options.

## Project Objectives

- Analyse and validate trading book positions.
- Map financial instruments to relevant market risk factors.
- Calculate Delta and Vega sensitivities.
- Estimate Curvature risk for options.
- Calculate Default Risk Charge (DRC).
- Apply Residual Risk Add-On (RRAO) to an illustrative exotic instrument.
- Apply risk weights to sensitivities.
- Demonstrate risk bucket classification and correlation-based aggregation.
- Consolidate risk components into an illustrative capital summary.

## Methodology and Workflow

The project follows a simplified FRTB-SA workflow:

1. **Trading Book Construction:** Create a sample portfolio containing multiple financial instruments and asset classes.
2. **Data Validation:** Perform checks for duplicate trades, missing values, invalid positions, and inconsistent records.
3. **Market Data Integration:** Incorporate historical equity, FX, and commodity prices, alongside illustrative interest rate curves, credit spreads, and implied volatility data.
4. **Risk Factor Mapping:** Map each trade to its relevant risk classes, risk factors, buckets, and sensitivity types.
5. **Sensitivity Calculation:** Calculate Delta and Vega sensitivities and estimate option Curvature risk.
6. **Default Risk Charge:** Demonstrate an illustrative calculation of Jump-to-Default (JTD), Loss Given Default (LGD), and DRC.
7. **Residual Risk Add-On:** Demonstrate an illustrative RRAO calculation for an exotic option.
8. **Risk Weighting:** Apply illustrative risk weights to Delta and Vega sensitivities.
9. **Risk Aggregation:** Demonstrate equity risk buckets, correlation matrices, and sensitivity aggregation.
10. **Capital Summary:** Consolidate the calculated risk components into an illustrative FRTB-SA summary.

## Risk Components Covered

| Component | Description |
|---|---|
| Delta | First-order sensitivity to underlying risk factors |
| Vega | Sensitivity to changes in implied volatility |
| Curvature | Non-linear option risk under market shocks |
| DRC | Default risk associated with credit positions |
| RRAO | Residual risk associated with specified instruments |

## Technology Stack

- **Python** – Core programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical calculations and matrix operations
- **yfinance** – Historical market data retrieval
- **Matplotlib** – Data visualisation (where applicable)
- **Jupyter Notebook** – Interactive development and analysis

## Project Outputs

The implementation generates CSV-based reports, including:

- Trading book validation report
- Risk factor mapping report
- Delta sensitivity report
- Vega sensitivity report
- Curvature risk report
- Default Risk Charge report
- Residual Risk Add-On report
- Risk-weighted sensitivity reports
- Equity risk bucket and correlation matrix reports
- Equity SBM aggregation summary
- Illustrative FRTB-SA capital summary

## Key Concepts Demonstrated

- Fundamental Review of the Trading Book (FRTB)
- Standardised Approach (SA)
- Sensitivity-Based Method (SBM)
- General Interest Rate Risk (GIRR)
- Credit Spread Risk (CSR)
- Risk factor classification and mapping
- Risk weights and correlation parameters
- Bucket-level risk aggregation
- Jump-to-Default (JTD)
- Regulatory capital estimation

## Important Note

This is an **educational Python implementation** designed to demonstrate the core concepts and computational workflow of FRTB-SA.

Certain risk weights, correlations, sensitivities, recovery rates, and shock assumptions are illustrative. The calculations do not represent a complete Basel-compliant regulatory capital engine. A production implementation would require the applicable Basel framework and jurisdiction-specific regulatory rules, prescribed risk factors, detailed instrument valuation, and full within-bucket and across-bucket aggregation methodologies.

## Learning Outcome

The project provides practical exposure to market risk analytics, trading book risk classification, sensitivity calculations, risk aggregation, and regulatory capital concepts using Python.
