# yzhang_stdpopsim_pig_recomb

Formatting genetic map (recombination rate map) for pig species in
[stdpopsim](https://github.com/popsim-consortium/stdpopsim).

We used the IPython notebook in `format_for_stdpopsim.ipynb` to
format the recombination rate map into the `RateMap` format used
by `stdpopsim`.
See details in the notebook.

The maps were then shared with `stdpopsim` maintainers.

Here is metadata about the studies building the recombination rate maps.

## Johnsson et al. (2021)

This genetic map is from the study of Johnsson et al. (2021),
which worked with pedigree and SNP array genotype data from 9 commercial pig breeding populations
(including Landrace, Large White, Duroc, Hampshire, and Pietrain heritage).
Pedigrees were 20-30 generations deep,
with about 15,000 to 108,000 individuals per population.
Genotype information was available for 390,758 individuals,
with about 15,000 to 80,000 SNP markers across the autosomes (SSC1–18)
of the Sscrofa11.1 (GCA_000003025.6) / SusScr 11.1 reference genome.
The authors have used multilocus iterative peeling method using AlphaPeel to phase and impute the genotypes
as well as to call recombination events between parents and offspring,
which were then used to estimate recombination rates across the chromosomes in 1Mbp windows in males and females.
The publication supplement provides averaged rates across populations for males and females and sex-averaged.

Johnsson et al. (2021) Genetic variation in recombination rate in the pig.
Genetics Selection Evolution, 53:54.
https://doi.org/10.1186/s12711-021-00643-0

## Brekke et al. (2022)

This genetic map is from the study of Brekke et al. (2022),
which worked with pedigree and SNP array genotype data from five commercial pig breeding populations
(Landrace, Large White, Duroc, Pietrain, and synthetic).
Pedigrees had about 17,000 to 96,000 individuals per population.
Genotype information was for 390,758 individuals,
with 50,705 SNP markers across the autosomes (SSC1–18)
of the Sscrofa11.1 (GCA_000003025.6) / SusScr 11.1 reference genome.
The authors constructed breed- and sex-specific and sex-averaged linkage maps
using LepMap3 providing per marker recombination rates.
The authors have shared the estimated maps.

Citation: Brekke et al. (2022). Recombination rates in pigs differ between breeds, sexes and individuals, and are associated with the RNF212, SYCP2, PRDM7, MEI1 and MSH4 loci.
Genetics Selection Evolution, 54:33.
https://doi.org/10.1186/s12711-022-00723-9
