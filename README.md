# Time-Varying Beta Estimation

This project analyzes the **time-varying market betas** of major US banking stocks (Citigroup, JPMorgan Chase, Bank of America, Wells Fargo, Goldman Sachs, Bank of New York Mellon) relative to Fama–French factors (Market, SMB, HML). Using daily return data, it compares **constant betas from OLS regressions** with **dynamic betas estimated via a GARCH-based approach**.

The workflow includes:

* Preprocessing of stock and factor return data.
* Estimation of OLS benchmark betas.
* Estimation of time-varying betas with confidence intervals.
* Export of a **comparison table** in LaTeX format, summarizing mean, variability, and range of dynamic betas against OLS.
* Visualization of beta dynamics with **95% confidence intervals** and OLS reference lines.

The results highlight how banks’ exposures to market risk evolve over time, with notable variation around periods of heightened volatility. This illustrates the value of time-series econometric methods (such as GARCH) for capturing **dynamic factor exposures** in financial institutions.
