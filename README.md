# devops--task-3
# Task 3 - Provisioning Docker with Terraform

## Objective:
Use Terraform to provision a Docker container (nginx).

## Steps Followed:
- Created `main.tf` using the `kreuzwerker/docker` provider
- Ran `terraform init`, `terraform plan`, and `terraform apply`
- Verified with `docker ps` and `curl`
- Cleaned up using `terraform destroy`

## Output:
Nginx container was deployed and exposed on port 8080.

## Screenshot:
(Attach images of your terminal output here)
