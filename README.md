# GitHub Actions Demo

## Manual Execution
Select test scenario:
- **success**: All jobs succeed
- **failure**: Multiple jobs fail
- **mixed**: Some jobs fail

### Automatic Execution
- Push to `main` or `develop` branch
- Pull request to `main` branch

control the execution of jobs by commit message
- `[fail-quality]` - Fail code quality check
- `[fail-unit]` - Fail unit tests
- `[fail-integration]` - Fail integration tests
- `[fail-security]` - Fail security scan

```bash
git commit -m "Add test feature [fail-unit]"
```

