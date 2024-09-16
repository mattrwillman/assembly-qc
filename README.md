# assembly-qc

# To do:

Require BUSCO database download before running BUSCO. Downloading database as part of analysis can cause issues with parallel runs. Rerunning Snakemake currently resolves this issue, but downloading database as a seperate rule before analysis would prevent initial job quit.
