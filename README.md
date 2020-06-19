# Replication of "Longer-run economic consequences of pandemics" [(Jora, Singh, Taylor 2020)](https://www.frbsf.org/economic-research/publications/working-papers/2020/09/)

This notebook replicates the analysis of a recent working paper by [(Jorda, Singh, Taylor 2020)](https://www.frbsf.org/economic-research/publications/working-papers/2020/09/) that demonstrates the historical impact of major pandemic events on interest rates across Europe.

I achieve broadly similar results, though with some divergences. I hypothesize that the differences arise due to differences in our respective Kalman filters applied to the historical data on European real interest rates, especially in the earlier periods.

That said, that the results are so sensitive to somewhat arbitrary configuration of the Kalman filter suggests that the exact measured effects should be taken with some caution. One should keep in mind that there are only a small number of such pandemics, so any calculated effects are at best noisy estimates of the true impact. This can be see in the relatively wide confidence intervals reported in the original analysis.