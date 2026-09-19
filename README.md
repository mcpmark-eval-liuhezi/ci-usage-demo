# ci-usage-demo

Demo repository for measuring GitHub Actions CI cost per workflow run.

## Viewing usage for a run

Open a workflow run's page on GitHub and check the **Usage** section, or call
`GET /repos/{owner}/{repo}/actions/runs/{run_id}/timing` to get the billable
time for each job.

