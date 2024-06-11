# dummy-release-drafter

Dummy repo for testing out Release Drafter GitHub Action Workflow. This repo is intended to only validate the Release Drafter GitHub Action Workflow.

## Usage

GitHub Actions Workflow

| Workflow | Description |
|----------|----------|
| autolabeler | Auto labels PRs base on GitHub Issues Labels |
| cd   | Continuous Deployment to trigger on main branch that creates GitHub Release Changelog draft |
| deploy-lambda | Executor Workflow Action that performs the aws-cli lambda deployment |
| release | UI use to manually trigger the deploy-lambda Workflow Action |

## Resources

- https://github.com/release-drafter/release-drafter
