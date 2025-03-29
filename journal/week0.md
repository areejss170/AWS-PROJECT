# Week 0 — Billing and Architecture




#  Week 0 — Digrams 

## Cruddur logical digram 
![Cruddur Logical Digram](https://github.com/user-attachments/assets/8fbf1661-b800-49d6-86bd-b63b2f7c3d75)

## AWS CLI 

update yml file to 
```
tasks:
  - name: aws-cli
    env:
      AWS_CLI_AUTO_PROMPT: on-partial
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
vscode:
  extensions:
    - 42Crunch.vscode-openapi

```
