<span style="color:#2B98F0"># Serverless AWS Cost Optimization</span>


 ![Gateway](https://github.com/ValAug/Serverless_AWS_Cost_Optimization/blob/main/Diagram_Picture/cron-job.png)


<p align="center">
  <img src="https://img.shields.io/badge/-AWS-000000?style=flat&logo=Amazon%20AWS&logoColor=FF9900" alt="AWS">
  <img src="https://img.shields.io/badge/-Terraform-000000?style=flat&logo=Terraform" alt="Terraform">
</p>

This GitHub repository showcases the powerful trio of Terraform, AWS Lambda, and Event Bridge for achieving cost optimization in your AWS infrastructure. With a focus on automation and intelligent strategies, you can effectively reduce AWS expenditure without compromising performance or functionality.

## Key Features

- **Infrastructure as Code:** Define your AWS infrastructure in a declarative manner using Terraform configurations, enabling easy versioning, management, and environment reproducibility.

- **Lambda Functions:** Explore the creation of serverless functions using AWS Lambda to perform specific tasks in response to events. Examples include processing incoming data or triggering automated actions.

- **Event Bridge:** Learn how to leverage AWS Event Bridge to establish event-driven architectures, enabling decoupled communication between different services. This facilitates efficient cost optimization through event filtering and routing.

- **Cost Optimization Techniques:** Discover various techniques for AWS cost optimization, including intelligent resource scaling, serverless architecture design patterns, efficient event routing, and usage-based cost analysis.

- **Sample Workflows:** Find practical examples of cost optimization workflows that combine Terraform, Lambda functions, and Event Bridge rules. These workflows automate common tasks, minimize resource usage, and reduce unnecessary costs.

## Prerequisites

- You must have an AWS account and configure your CLI profile.
- Terraform must be installed. [Learn how to install Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli)

## Cautions

- As an AWS best practice, grant this code least privilege, providing only the necessary permissions to perform a task. For more information, see [Grant Least Privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege) in the *AWS Identity and Access Management User Guide*.
- This code has been tested in the __us-east-1__ AWS Region only. However, it should work in any other region.
- Running this code may result in charges to your AWS account.

## How to Run This Code

### Quick Start

```bash
cd vpc-endpoint-connection-with-s3
terraform init
terraform validate
terraform plan
terraform apply --auto-approve
