### RDMULTI

The `rdmulti` package provides Stata and R implementation of RD plots, estimation, inference and extrapolation methods for RD designs with multiple cutoffs and multiple scores.

This work was supported in part by the National Science Foundation through grants [SES-1357561](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1357561).

## Stata Implementation

To install/update in Stata type:
```
net install rdmulti, from(https://raw.githubusercontent.com/rdpackages/rdmulti/master/stata) replace
```

- Help: [rdmc](stata/rdmc.pdf), [rdmcplot](stata/rdmcplot.pdf), [rdms](stata/rdms.pdf).

- Replication: [do-file](stata/rdmulti_illustration.do), [rdmcplot illustration](stata/rdmcplot_illustration.do), [dataset1](stata/simdata_multic.dta), [dataset2](stata/simdata_cumul.dta), [dataset3](stata/simdata_multis.dta).

## R Implementation

To install/update in R type:
```
install.packages('rdmulti')
```

- Help: [R Manual](https://cran.r-project.org/web/packages/rdmulti/rdmulti.pdf), [CRAN repository](https://cran.r-project.org/package=rdmulti).

- Replication: [R-script](R/rdmulti_illustration.R), [rdmcplot illustration](R/rdmcplot_illustration.R), [dataset1](stata/simdata_multic.csv), [dataset2](stata/simdata_cumul.csv), [dataset3](stata/simdata_multis.csv), [R illustration](R/rdmulti_illustration.pdf)

## References

For overviews and introductions, see [rdpackages website](https://rdpackages.github.io).

### Software and Implementation

- Cattaneo, Titiunik and Vazquez-Bare (2020): [Analysis of Regression Discontinuity Designs with Multiple Cutoffs or Multiple Scores](references/Cattaneo-Titiunik-VazquezBare_2020_Stata.pdf), _Stata Journal_, forthcoming.

### Technical and Methodological

- Keele and Titiunik (2015): [Geographic Boundaries as Regression Discontinuities](references/Keele-Titiunik_2015_PA.pdf), _Political Analysis_ 23(1): 127-155.

- Cattaneo, Keele, Titiunik and Vazquez-Bare (2016): [Interpreting Regression Discontinuity Designs with Multiple Cutoffs](references/Cattaneo-Keele-Titiunik-VazquezBare_2016_JOP.pdf), _Journal of Politics_ 78(4): 1229-1248. [Supplemental Appendix](references/Cattaneo-Keele-Titiunik-VazquezBare_2016_JOP--Supplement.pdf).

- Cattaneo, Keele, Titiunik and Vazquez-Bare (2020): [Extrapolating Treatment Effects in Multi-Cutoff Regression Discontinuity Designs](references/Cattaneo-Keele-Titiunik-VazquezBare_2021_JASA.pdf), _Journal of the American Statistical Association_, forthcoming. [Supplemental Appendix](references/Cattaneo-Keele-Titiunik-VazquezBare_2021_JASA--Supplement.pdf).

<br>
<br>
