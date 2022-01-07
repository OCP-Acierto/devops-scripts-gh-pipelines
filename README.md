# Github Reusable Actions on Workflows

## Use action on workflows

```yaml
jobs:
  JOB_ID:
    name: <JOB NAME>
    uses: OCP-Acierto/devops-scripts-gh-pipelines/.github/workflows/deploy_k8s_configmap.yaml@master
    with:
      variable_x: <VALUE>
      variable_y: <VALUE>
    secrets:
      secret_x: ${{ secrets.SECRET }}
      secret_y: ${{ secrets.SECRET }}
```
