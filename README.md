# Distance-to-Default
Computed Distance to Default for firms from the COMPUSTAT universe, each year from 1970 to 2020.

3 methods to calculate distance to default were implemented.

Method 1: Naive Computation using the KMV model
Method 2: Directly Solving for the Unknowns
Method 3: Distance Default using the KMV model: Iterative Method

Merged COMPUSTAT and CRSP data to get fundamental and market variables respectively. Computed DD and PD for these firms for each year (as of Jan 1 of each year)
Computed the correlations between these three measures of DD and PD
Compute the descriptive statistics for NBER recession and NBER recession .

Plotted DD and PD with the recession data and generated insights (https://fred.stlouisfed.org/series/USREC)
Plotted DD and PD along with Moody's BAA-Fed Fund Spread (https://research.stlouisfed.org/fred2/series/BAAFFM)
Plotteed DD and PD against the Cleveland Financial Stress Index (https://research.stlouisfed.org/fred2/series/CFSI)
