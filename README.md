# conda-health-checks
A repository hosting various community-written health checks for `conda doctor`.

## conda doctor
The `conda doctor` subcommand diagnoses your conda environment for inconsistencies such as packages with missing files, packages with altered files, etc. Each check that `conda doctor` runs on your environment is called a "health check". `conda` now provides a new "health-check" plugin hook that allows you to write your own health-checks. Once installed these health-checks will then run, along with the health-checks shipped with `conda doctor` by default, everytime you run `conda doctor`.

## Writing your own health checks
Head over to the [conda plugin template](https://github.com/conda/conda-plugin-template/) repository and check out the various tutorials on writing plugins for conda.   
