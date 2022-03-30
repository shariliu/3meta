This github repository contains all the data and code needed to reproduce the figures and results from the paper 'Knowing before doing: Review and mega-analysis of action understanding in pre-reaching infants'

## High level directory structure
- `analysis` - folder including all data and code
- `analysis/formatted_data` - csv and codebook for data from 8 included papers
- `analysis/orig_data` - data as originally submitted
- `analysis/ma_study_designs.csv` - csv of study designs for each condition, see [codebook](https://docs.google.com/spreadsheets/d/1-tEF2RZS6OjN8_kEeWTIHrI-lr5VpvC_58wk4X7YUC0/edit#gid=1931065704)
- `analysis/ma_study_data.csv` - csv of looking time preference (unexpected - expected) for each subject for each condition
- `analysis/fulldata.csv` - csv combining information from `ma_study_designs.csv` and `ma_study_data.csv`, see scripts to reproduce
- Analysis scripts `.Rmd and .html`: `ma_1` (script for mega-analysis), `descriptives_ESs` (tidying data and getting descriptives like N) `3meta_brms` (exploratory Bayesian)
- `*.rds` - brms models


```
    .
    ├── README.md
    ├── analysis
    │   ├── 3meta_brms.Rmd
    │   ├── 3meta_brms.html
    │   ├── analysis.Rproj
    │   ├── brms_figures
    │   │   ├── constraints_brms.afdesign
    │   │   ├── constraints_complex.png
    │   │   ├── constraints_simple.png
    │   │   └── goals_brms.afdesign
    │   ├── constraints.brms.causal_gaussian.rds
    │   ├── constraints.brms.efficient_gaussian.rds
    │   ├── constraints.brms.full.rds
    │   ├── constraints.brms.full.scaled_gaussian.rds
    │   ├── constraints.brms.full.simplerfx.rds
    │   ├── constraints.brms.full.simplerfx_gaussian.rds
    │   ├── constraints.brms.full_gaussian.rds
    │   ├── constraints.brms.intercept.rds
    │   ├── constraints.brms.intercept_gaussian.rds
    │   ├── constraints.brms.training_gaussian.rds
    │   ├── descriptives_ESs.Rmd
    │   ├── descriptives_ESs.html
    │   ├── figures
    │   │   ├── Figure2_manipulations.afdesign
    │   │   ├── effects_cooks_bothtasks.afdesign
    │   │   └── mittens.afdesign
    │   ├── formatted_data
    │   │   ├── csv_and_codebook
    │   │   │   ├── choi2018.csv
    │   │   │   ├── choi2018_codebook.csv
    │   │   │   ├── choi_ongoing.csv
    │   │   │   ├── choi_ongoing_codebook.csv
    │   │   │   ├── gerson2014a_ibd.csv
    │   │   │   ├── gerson2014a_ibd_codebook.csv
    │   │   │   ├── gerson2014b_cd.csv
    │   │   │   ├── gerson2014b_cd_codebook.csv
    │   │   │   ├── liu_unpublished.csv
    │   │   │   ├── liu_unpublished_codebook.csv
    │   │   │   ├── luo2011.csv
    │   │   │   ├── luo2011_codebook.csv
    │   │   │   ├── skerry2013_liu2019.csv
    │   │   │   ├── skerry2013_liu2019_codebook.csv
    │   │   │   ├── woo_unpublished_study2.csv
    │   │   │   ├── woo_unpublished_study2_codebook.csv
    │   │   │   ├── woo_unpublished_study3.csv
    │   │   │   └── woo_unpublished_study3_codebook.csv
    │   │   └── xlsx
    │   │       ├── choi2018.xlsx
    │   │       ├── gerson2014a_cd.xlsx
    │   │       ├── gerson2014b_ibd.xlsx
    │   │       └── luo2011.xlsx
    │   ├── fulldata.csv
    │   ├── goals.brms.full.rds
    │   ├── goals.brms.full.simplefx.rds
    │   ├── goals.brms.full.simplefx_gaussian.rds
    │   ├── goals.brms.full_gaussian.rds
    │   ├── goals.brms.intercept.rds
    │   ├── goals.brms.intercept_gaussian.rds
    │   ├── ma_1.Rmd
    │   ├── ma_1.html
    │   ├── ma_1_cache
    │   │   └── ...
    │   ├── ma_1_files
    │   │   └── ...
    │   ├── ma_study_data.csv
    │   ├── ma_study_designs.csv
    │   └── orig_data
    │       ├── Luo 2011_data for Meta-analysis.xlsx
    │       ├── MittensData_ChildDevelopment14_Gerson&Woodward.xlsx
    │       ├── MittensData_IBD_Gerson&Woodward14.xlsx
    │       ├── Pumpkin_data for Meta-analysis.xlsx
    │       ├── liu_unpublished.csv
    │       ├── lumi_data_deid.csv
    │       ├── woo_scg-study2-wide.csv
    │       ├── woo_scg-study3-wide.csv
    │       ├── woo_unpublished_study3.csv
    │       └── woo_unpublished_study3_codebook.csv
```

## Resources:
1. [Metalab](http://metalab.stanford.edu/) including information about the [contribution challenge](https://docs.google.com/document/d/1WH6y-7Hq-BRs7PAfH7jJY8qvPdBcy8IeHxfXeaqAJUI/edit)
2. Templates and examples:
- Metadata [template](https://docs.google.com/document/d/12SpehtoFfIvUjUBHYvi9rnIKeXAYduFdofRlQ0HAh5s/edit)
- PRISMA [flowchart](https://docs.google.com/presentation/d/1DKY8BTZZ82bGyGwpGsyyzsilOqE1F1NcDLTKWtCe9AY/edit#slide=id.p) and [general info](http://prisma-statement.org/) about the PRISMA workflow
- Meta-analysis [template](https://docs.google.com/spreadsheets/d/12Y_2BcFSu48t0F8a_xrY1Ro2fJoCIV1h8O627WNcrjY/edit#gid=0) for final, included studies 
- Literature search [template](https://docs.google.com/spreadsheets/d/1mtN4g6FddpBljQzrR-mS0y414M9wQNjK4Vz09nLOe2s/edit#gid=0) for documenting the process of sorting through potentially relevant papers 

 