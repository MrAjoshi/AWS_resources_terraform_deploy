<<<<<<< HEAD
# devops-project-1# AWS_resources_terraform_deploy
=======
# AWS_resources_terraform_deploy
>>>>>>> 80aa103 (first commit)

🛠️ How it works — Step-by-Step:

    GitHub Repo Setup
    Clone or fork the repo:
    git clone https://github.com/MrAjoshi/AWS_resources_terraform_deploy

    Configure AWS Credentials
    Use an IAM user with appropriate permissions and set up your environment with aws configure or Jenkins credentials.

    Setup Jenkins Job

        Create a freestyle or pipeline job in Jenkins

        Integrate with GitHub (via webhook or periodic scan)

        Use a Jenkinsfile (or shell commands) to:

            terraform init

            terraform plan

            terraform apply -auto-approve

    Pipeline Execution
    Every code commit triggers the pipeline:

        Jenkins pulls latest Terraform code

        Validates infrastructure changes

        Applies updates to AWS seamlessly
