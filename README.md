# Will Rathgeb Data Science Honors Thesis

The American Community Survey (ACS) data used in this research is not currently included in this repository due to the large size of the extract file. The extract was obtained through [IPUMS](https://usa.ipums.org/usa/). It contains every ACS from 2006-2023. The variables included in the extract are: 'YEAR', 'SERIAL', 'NUMPREC', 'STATEFIP', 'MORTAMT1', 'MORTAMT2', 'TAXINCL', 'INSINCL', 'PROPINSR', 'PROPTX99', 'RENTGRS', 'CONDOFEE', 'MOBLHOME', 'COSTELEC', 'COSTGAS', 'COSTWATR', 'COSTFUEL', 'HHINCOME', 'PERNUM', 'PERWT', 'MOMLOC', 'POPLOC', 'SPLOC', 'MOMLOC2', 'POPLOC2', 'AGE', 'INCTOT', 'INCWELFR', 'INCSUPP', 'INCEARN'.

To recreate the results from this paper, begin by downloading this ACS dataset. From there, the .ipynb's in /notebooks can be run in the following order:
- clean_admin_data.ipynb
- get_snap_enrollments.ipynb
- snap_gap_estimation.ipynb
- get_scm_covariates.ipynb
- scm_with_covariates.ipynb
- scm_no_covariates.ipynb