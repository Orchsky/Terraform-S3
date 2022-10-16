# Terraform Notes
- IAC Fundamentals: immutable infrastructure, ease of use, ease of scalability
- Cloud agnostic IAC tools --> terraform, pulumi
- Cloud native IAC tools --> cloud formation, azure arm, google cloud deployment
- What is cloud agnostic --> being able to use the same tool for multiple clouds

## Terraform installation and pre-requisites
- [Download for mac](https://www.terraform.io/downloads) (you can use homebrew from terminal to install or just download the file itself from the URL)

- [Download for windows](https://www.terraform.io/downloads) (you can use chocolatey to install terraform or you can download file from URL) (choco install terraform)

- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

### Steps to get started
- Create IAM user with necessary permissions and programatic access
- export environmental variables (check recording of class)
- Setup your directory and check in main.tf file
- Write provider configurations
