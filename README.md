[![Server deploy](https://github.com/leticiavalladares/ring-challenge-team1-ec2-nr3/actions/workflows/deploy-infra.yaml/badge.svg?branch=main)](https://github.com/leticiavalladares/ring-challenge-team1-ec2-nr3/actions/workflows/deploy-infra.yaml)

# Automate server deployment with GitHub Actions

### Requirements:
- OpenID/AWS setup completed.

### Steps:

1. Create your own repository
2. Copy infrastructure files from your **own branch** from https://github.com/muhammetkoele/ring-number-challenge-team-1 in your new repository
3. Create `.github/workflows folders`
4. Then inside `workflows`, create yaml file (deploy-infra.yaml) with aws and terraform instructions for GitHub actions.
5. Add permimssions on terraform-deployment if they were not already included:
```
    permissions:
      packages: write
      contents: read
      id-token: write
```
6. Add your arn:aws:iam role from AWS for role/github-actions-oidc on your deploy-infra.yaml
7. Push your code and that will trigger the GitHub Actions