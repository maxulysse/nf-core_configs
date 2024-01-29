# nf-core/configs: NYU HPC Configuration

All nf-core pipelines have been successfully configured for use on the HPC Cluster at New York University.

To use, run the pipeline with `-profile nyu_hpc`. This will download and launch the [`profile.config`](../conf/profile.config) which has been pre-configured with a setup suitable for the NYU HPC cluster. Using this profile, a docker image containing all of the required software will be downloaded, and converted to a Singularity image before execution of the pipeline.

## Below are non-mandatory information e.g. on modules to load etc

Before running the pipeline you will need to load Nextflow and Singularity using the environment module system on PROFILE CLUSTER. You can do this by issuing the commands below:

```bash
## Load Nextflow modules
module purge
module load nextflow/23.04.1
```
