---
date: 2023-06-19
tags: lit-review/read 2nd-basic 
aliases:
---
# A Comparison of Stochastic and Deterministic Channel Models for V2V Applications
## 2-3 Sentence Summary
Doesn't suggest one versus the other, however the stochastic model predicts a higher [packet error rate](packet%20error%20rate.md) than the deterministic model. No measurements to backup the simulations however poses the idea of simple scenarios benefiting from stochastic models (with less computation needed).
## Notes
Compares 2 [channel models](channel%20model.md) - ModBed ray optical deterministic vs. Quadriga stochastic.

[Link level](Link%20level.md) simulator

Two options - predict analytically ([ray tracing](Ray-tracing.md)) or statistically.

Questionable if stochastic model can model anything beyond what the measurement campaign measured.

[power delay profile](power%20delay%20profile.md) considered.
[packet error rate](packet%20error%20rate.md) is compared

>  It should be noted that the minimum needed received power S for any given communication pair depends on the one hand on the link configuration parameters as code rate and [data rate](../../../01%20-%20General%20Notes/data%20rate.md) and on the other hand on various RX specific parameters, especially the noise figure and the channel estimation algorithms.

[^1]
# References
[^1]: [A_Comparison_of_Stochastic_and_Deterministic_Channel_Models_for_V2V_Applications](../../03%20-%20University/Thesis/literature%20review/2nd%20-%20basic/A_Comparison_of_Stochastic_and_Deterministic_Channel_Models_for_V2V_Applications.pdf)