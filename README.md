\# Infrastructure as Code (IaC) with Terraform \& Docker



\## Overview

This project provisions a local Docker container running an Nginx web server using Terraform and the `kreuzwerker/docker` provider.



\## Prerequisites

\- Terraform v1.x+

\- Docker Engine / Docker Desktop



\## Steps Executed

1\. `terraform init` - Initialized provider plugins.

2\. `terraform plan` - Reviewed execution plan for container and image provisioning.

3\. `terraform apply` - Provisioned Nginx container exposed on port 8080.

4\. `terraform state list` \& `terraform state show` - Verified state tracking.

5\. `terraform destroy` - Cleaned up and terminated local resources.



\## Verification

\- Container mapped: `localhost:8080` -> internal port `80`.

\- Execution logs recorded in `execution\_logs.txt`.

