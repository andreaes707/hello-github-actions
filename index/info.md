# Learning is important

## Github actions and yaml notes

### Descriptions
_some descriptions are only for this repository.._
* jobs:
  - base component of a workflow run
* build:
  - identifier attatched to this job
* name:
  - name of the job; displayed while workflow is running
* runs-on:
  - defines machine type for job
* steps:
  - linear sequence of operations that compile to make up a job
* uses: actions/checkout@v1
  - uses community action `checkout`
* ./action-a
  - provide a relative path to the action of selected branch
* with:
  - used to specify the input variables that will be available to the action within the runtime environement
