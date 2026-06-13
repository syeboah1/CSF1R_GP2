# Investigation of CSF1R variants in the GP2 Population


`GP2 ❤️ Open Science 😍`

[![DOI]
[![License: MIT]

**Last Updated:** May 2026

## Summary
This is the online repository for the short communication titled **"Frequency of CSF1R Variants in the Global Parkinson’s Genetics Program Cohort
".**

## Citation
If you use this repository or find it helpful for your research, please cite the corresponding manuscript:

> Frequency of CSF1R Variants in the Global Parkinson’s Genetics Program Cohort
>> Manuscript DOI: coming soon
>> 
>>  GitHub DOI: 

### Data Statement 
* All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson's Disease (AMP-PD) and are available via application on the website. The GP2 PD case and control data are available via the GP2 analysis platform (https://gp2.org; release 10: 10.5281/zenodo.15748014. 
* Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub
* Summary statistics from the Million Veteran's Program were made available through a collaboration, apply for access here: https://www.mvp.va.gov/pwa/mvp-data-available-research
* Analyses conducted on the UKBiobank were performed on the DNANexus platform, apply for access here: https://www.ukbiobank.ac.uk/enable-your-research/apply-for-access


### Helpful Links 
- [GP2 Website](https://gp2.org/)
    - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)



# Repository Orientation 
- The `analyses/` directory includes all analyses discussed in the manuscript

```
├── LICENSE.txt
├── README.md
└── analyses
    ├── 01_Burden_Assoc_GP2_R10_WGS.ipynb
    └── 02_Burden_Assoc_GP2_R10_IMP.ipynb
```

---
### Analysis Notebooks
* Languages: Python, bash

| Directory  | Notebooks                   | Description                                                                       |
|------------|-----------------------------|-----------------------------------------------------------------------------------|
| analysis/  01_Burden_Assoc_GP2_R10_WGS.ipynb  | SKAT Test and Association for CSF1R variants in GP2 R10 whole genome sequencing  |
| analysis/  | 02_Burden_Assoc_GP2_R10_IMP.ipynb |SKAT Test and Association for CSF1R Variants in GP2 R10 neurobooster array     |
| analysis/  | METAL.ipynb                 |Analysis description    |


---

# Software 
|               Software              |  Version(s) |                              Resource URL                              |       RRID      |                                               Notes                                               |   |
|:-----------------------------------:|:-----------:|:----------------------------------------------------------------------:|:---------------:|:-------------------------------------------------------------------------------------------------:|:-:|
|     Python Programming Language     | 3.9 and 3.10 |                         http://www.python.org/                         | RRID:SCR_008394 | pandas; numpy; seaborn; matplotlib; statsmodel; used for general data wrangling/plotting/analyses |   |
|                PLINK                |     2.0 and 1.9    |                   http://www.nitrc.org/projects/plink                  | RRID:SCR_001757 |                                     used for genetic analyses                                     |   |
| ANNOVAR | 2020-06-08 | http://www.openbioinformatics.org/annovar/	| RRID:SCR_012821 | Genetic annotation software |
|DRAGEN|v.3.7.8|https://developer.illumina.com/dragen|NA|Used for variant calling for Illumina data.|
|gnomAD|v.4.1|http://gnomad.broadinstitute.org/|RRID:SCR_014964|Used to retrieve population frequency data.|
|RVTests|v.2.1.0|http://genome.sph.umich.edu/wiki/RvTests|RRID:SCR_007639|Used for burden analyses.|
| Variant Effect Predictor (VEP) | 115 | https://useast.ensembl.org/info/docs/tools/vep/index.html? | RRID:SCR_007931 | Genetic annotation software |
| SAMTOOLS | 1.23 | RRID:SCR_002105 | HTSlib: tabix, bgzip. For compressing and indexing VCF files
