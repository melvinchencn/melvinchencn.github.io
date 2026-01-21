# Research

## Work in Progress


**Dynamic Macroeconomic Forecasting with Supervised Autoencoders and Uncertainty-Gated LSTMs**    [PDF](chen_imported_inflation_dsge.pdf)



This project develops a forecasting pipeline for high-dimensional macro panels that learns predictive factors and models their nonlinear dynamics in real time. I use supervised autoencoders to extract low-dimensional representations optimized for forecasting target variables, and an uncertainty-gated LSTM to adapt factor dynamics across regimes. The framework is evaluated on real-time vintages (e.g., FRED-MD-style panels) and benchmarked against standard linear and factor-based approaches. Results indicate improved accuracy—especially at turning points and over multi-step horizons—and provide a structured uncertainty decomposition into **factor-innovation uncertainty** and **factor-extraction error**.


---

**Measuring Factor-Based Uncertainty in Real-Time Data**  

This project studies how macro-uncertainty measurement changes when the information set is restricted to real-time releases rather than fully revised data. I construct a factor-based uncertainty index that explicitly accounts for real-time data revisions and factor proxy errors, and provide a theoretical decomposition that clarifies the sources of measured uncertainty. The analysis distinguishes uncertainty from shocks to latent factor innovations versus uncertainty induced by factor extraction and real-time measurement error. Empirically, the proposed index is compared to existing uncertainty measures and evaluated via forecasting and real-time performance diagnostics, highlighting when real-time implementation meaningfully alters inference and predictive content.


---

**Structural Estimation of Inflation Channel Heterogeneity: Imported Inputs vs Final Goods**  

This project studies how imported inflation transmits into domestic inflation through distinct channels associated with imported intermediate inputs versus imported final consumption goods. I develop and estimate a medium-scale New Keynesian DSGE model with a two-tier import structure, endogenous wage bargaining, labor market frictions, and nominal rigidities. The framework separates a supply-side marginal-cost channel from a demand-side expenditure-basket channel. Estimation using U.S. macroeconomic and trade data shows that intermediate-input inflation shocks generate more persistent domestic inflation via production costs and wage–price feedback, while final-goods shocks primarily reweight the consumption basket with shorter-lived inflation effects. The results highlight why import composition matters for monetary policy design during supply-chain disruptions and trade-policy shifts.
