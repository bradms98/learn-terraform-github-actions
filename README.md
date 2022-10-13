# Automate Terraform with GitHub Actions


This repo is a companion repo to the [Automate Terraform with GitHub Actions](https://learn.hashicorp.com/tutorials/terraform/github-actions?in=terraform/automation).

### Get SSH Keys working with github and VSCode's commit form GUI:
From Ubuntu shell:
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github-bradms98
code
```

VSCode should open and pull/push should work against my github repo