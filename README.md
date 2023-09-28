# Sample Cypress Project with Azure Parallelization

This is a simple illustration of the implementation of test parallelization with azure matrix

## Prerequisite
1. Understanting of creating a [yaml](https://learn.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline?view=azure-devops&tabs=java%2Ctfs-2018-2%2Cbrowser) file
2. Availability of [Parallel jobs](https://learn.microsoft.com/en-us/azure/devops/pipelines/licensing/concurrent-jobs?view=azure-devops&tabs=ms-hosted)
3. Azure project with multiple/[scale-set](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/scale-set-agents?view=azure-devops) agents

## Steps
1. Setup the parallel.yaml file as your pipeline definitions
2. Execute the test.
3. In the artifact sections, view the "combined-results" folder. The parallel execution should be presented combined.
