# Flutter Analyze `pre-commit`

[`pre-commit`](https://pre-commit.com) hook for running Flutter anlyzer

Add the following in your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/ll886/flutter-analyze-pre-commit
  rev: "master"
  hooks:
    - id: flutter-analyze
      args: [lib/*]
```
