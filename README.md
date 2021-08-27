This is the code which accompanies the SIGIR 2020 paper [Detecting Concept Drift in Medical Triage](https://hamishhuggard.com/pdfs/detecting_biomedical_concept_drift.pdf) by Huggard et al.

Contents of repo
 * benchmark_data - the content of the benchmark datastreams
 * benchmark_results - the results of the benchmark experiments
 * referral_data - the content of the MIMIC-derived medical referral datastreams
 * referral_results - the content of the MIMIC-derived medical referral datastreams
 * CDDM_expeirments.ipynb - notebook in which the experiments are run and the data processed

To use this code you will need the Conda environment:
```
$ conda env create -f environment.yml
$ conda activate sigir2020
```

Credits: some of this code is derived from the [Tornado](https://github.com/alipsgh/tornado) framework.
