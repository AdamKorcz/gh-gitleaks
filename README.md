# GitHub Secret Scanning Test — Gitleaks

This repository runs a **Gitleaks** scan on every push and pull request using a GitHub Actions workflow.

**Workflow:** `.github/workflows/secret-scan-gitleaks.yml`

```yaml
uses: gitleaks/gitleaks-action@v2
