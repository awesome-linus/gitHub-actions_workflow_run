# github-actions_workflow_run

## .github/workflows/workflow_run.yml
- workflows
どちらの指定方法でもOK。
```yml
on:
  workflow_run:
    workflows: ["Main Action"]
```

```yml
on:
  workflow_run:
    workflows:
      - Main Action
```
