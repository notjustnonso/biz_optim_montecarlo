# biz_optim_montecarlo
Monte carlo simulation for business optimization

## Monte Carlo Simulation
This personal monte carlo project was developed in review of the HBS case Marsh & McLennan (A) revised in August 1992. 

In this simulation, we evaluate two aircraft hull insurance and make recommendations for which one is more cost-effective relative within a wide range of loss-scenarios over 10,000 simulation runs. Two plans under consideration are:

**(1) Loss Conversion Plan (LCP)** which has the following features:
- Annual premium calculated as 135% of incurred losses subject to:
    - max. annual rate of $1.05 per $100 insured value
    - min. annual rate of $.50 per $100 insured value
- Incentive credit calculated as 
    - 10% x (Tot. 3-yr premiums – Tot. 3-yr losses) provided plan runs for full 3-year term and total 3-year premiums > total 3-year losses

**(2) Profit Commission Plan (PCP)** which has the following features:
- Annual premium calculated as Losses plus $.25 per $100 insured subject to max. annual premium of 1% of insured value
- Incentive credit calculated as:
    - Tot. 3-yr premiums *less* Tot.3-yr losses + ($0.2 per $100 insured value/year x 3 years) if any excess exists
 
For the average industry crash-rate, we use findings from FAA research report between 9167 and 1968. During this period of time, 15,660,000 “equivalent hours” were recorded, with total losses of jet aircraft numbering 10. This translates to a crash rate of 0.006424 or 0.64%.

Plane insured value information is captured from the case. 

This is an example of a business planning and optimization problem that must take into account risk and uncertainty as we actually should.

The notebook is in the code folder, while the data on plane book/insured values are in the data folder.

Not to be reproduced for commercial purposes.
