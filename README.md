# Automate server deployment with GitHub Actions

## Requirements:
- OpenID/AWS setup completed.

1. Create your own repository
2. Copy infrastructure files from your **own branch** from https://github.com/muhammetkoele/ring-number-challenge-team-1 in your new repository
3. Create `.github/workflows folders`
4. Then inside `workflows`, create yaml file (deploy-infra.yaml) with aws and terraform instructions for GitHub actions.
6. Enter your arn:aws:iam role from AWS for role/github-actions-oidc on your deloy-infra.yaml
7. Push your code and that will trigger the GitHub Actions
