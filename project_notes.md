# COMMIT MESSAGE FORMAT

# Commit Message Format

```text
<type>(<scope>): <short description>

<body>

<footer>
```

### type:
- feat (a new feature)
- fix (a bug fix)
- docs (documentation only changes)
- style (formatting, missing semicolons, etc.;no code change)
- refactor (code change that neither fixes a bug nor adds a feature)
- perf (perfomance improvement)
- test (adding missing tests or correcting exitsing)
- chore (changes to build process, auxiliary tools, libraries)
### scope 
- a short noun descibing what area you're touching (e.g. `dvc`, `pipeline`, `mlflow`, `ci`)
### short description
- imperative, <= 50 characters
### body
- why and how, wrapped at ~72 characters (optional)
### footer
- metadata like `BREAKING CHANGE:` or issue references (`Closes #23`) (optional)

## EXAMPLES OF MLOps Repo
- ``feat(dvc): initialize DVC and add raw dataset``
- ``chore(deps): bump mlflow from 1.29.0 to 1.30.0``
- ``fix(pipeline): correct data path in dvc.yaml stage preprocess``
- ``test(train): add pytest for training script edge cases``
- ``docs(README): add usage examples for``\dvc repro
