# Comparing and Evaluating Insurance Firms

In this project, a Supervision Manager has asked for help allocating scarce resources and identifying which firms their team should focus on. Supervisory resource may be allocated according to the following 
characteristics:

- Firm size (i.e. the biggest firms need more attention)   
- Changing business profile (are firms’ data changing substantially year-on-year?)   
- Outliers from the norm (when looking at a single reporting period, does a firm deviate 
significantly from the average?)

## Report 1: Resource Allocation Proposal
Once the data was fully cleaned and processed, several insights were distilled. Please see accompanying report for further details.
### Largest Firms

![biggest_assets](https://github.com/frostyrez/DS_Projects/assets/123249055/8a875dbf-8100-4510-b9f9-7b8f49056972)
<p align="center">
<i> Figure 1: Largest Firms by Net Written Premium </i>
</p>

![biggest_nwp](https://github.com/frostyrez/DS_Projects/assets/123249055/b6c66cd9-8606-45e5-af67-30be85b2255d)
<p align="center">
<i> Figure 2: Largest Firms by Total Assets </i>
</p>

### Most Volatile Firms

![largest_gcis](https://github.com/frostyrez/DS_Projects/assets/123249055/56e366fc-0f8d-4cd3-b0cf-5f364be800ff)
</p>
<i> Figure 3: Largest Single-Year Fluctuations in GCI from 2016 to 2020 </i>
</p>

![closeup_gci_jump](https://github.com/frostyrez/DS_Projects/assets/123249055/dfb6d3f1-747f-4236-b2a6-d10ecfe26906)
<p align="center">
<i> Figure 4: Firm 52- Variation in Gross Written Premium (GWP) and Gross Costs
Incurred (GCI) from 2016 to 2020 </i>
</p>

<br>

## Report 2: Anomaly Detection and ML Insights

![gwp_v_nwp](https://github.com/frostyrez/DS_Projects/assets/123249055/b3c32636-9ba1-46f0-8a5e-0fe9d0bfae15)
<p align="center">
<i> Figure 1: Gross Written Premium vs Net Written Premium </i>
</p>

![quad_outliers](https://github.com/frostyrez/DS_Projects/assets/123249055/9b95c995-dc82-44ff-861d-b8ba2e2cb232)
<p align="center">
<i> Figure 2: Outliers detected using a range of IQR factors </i>
</p>

![rr_outliers](https://github.com/frostyrez/DS_Projects/assets/123249055/099ebefc-1f85-42ae-a82e-2f078b6e2e6a)
<p align="center">
<i> Figure 3: Outlier firms by mean risk ratio </i>
</p>

![lin_v_q](https://github.com/frostyrez/DS_Projects/assets/123249055/85455f79-84d9-49c0-83cc-e4111dd93e5c)
<p align="center">
<i> Figure 4: Linear Regression vs Quantile Regression </i>
</p>
