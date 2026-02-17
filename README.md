# yzhang_stdpopsim_pig_recomb

Formatting genetic map (recombination rate map) for pig species in
[stdpopsim](https://github.com/popsim-consortium/stdpopsim).

We downloaded the supplemental table S3 from Johnsson et al. (2021).
The file is saved as `Johnsson_2021/Johnsson_2021_sex_average_rec_map.tar.gz`.
The table holds sex-averaged map of the landscape of pig recombination rate in 1-Mb windows.
The supplemental table S1 and S2 respectively hold
male and female map of the landscape of pig recombination rate in 1-Mb windows,
which could be useful in future.

We then used the Python code in `format_for_stdpopsim.ipynb` to
format the recombination rate map into the `RateMap` format used
by `stdpopsim` - see more [here](https://github.com/popsim-consortium/stdpopsim/blob/d9982aadc409446369080bc36825b992c5647477/docs/development.rst?plain=1#L1333).

The maps were then shared with maintainters to include them into `stdpopsim`.

Johnsson et al. (2021) Genetic variation in recombination rate in the pig
https://doi.org/10.1186/s12711-021-00643-0
