# github-actions-oidc-example
Just playing around with GitHub Actions OIDC support

| Claim | Scenario | Value |
| --- | --- | --- |
| `sub` | When pushing a tag | `repo:dtinth/github-actions-oidc-example:ref:refs/tags/v0.0.1-1` |
|  | When pushing to a branch | `repo:dtinth/github-actions-oidc-example:ref:refs/heads/main` |