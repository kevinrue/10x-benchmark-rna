This folder is meant to contain all resources necessary for running the workflow, for example reference sequences or databases.
Wherever feasible, they can also be downloaded programmatically via rules defined in the pipeline.

# Input data

Input data is currently internal.
It was downloaded as follows.

```bash
rsync -avz h1:/ifs/home/kevin/projects/10x-quant/snakemake_alevin_10x/results/alevin/pbmc_1k_v3 resources/alevin
```
