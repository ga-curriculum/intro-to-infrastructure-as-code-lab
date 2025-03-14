<h1>
  <span class="headline">Infrastructure as Code (IaC) Lab</span>
  <span class="subhead">Building a Terraform Configuration</span>
</h1>

In this exercise, you'll create a Terraform configuration file that defines a simple web application infrastructure based on the provided requirements.

## Infrastructure Requirements

You are tasked with creating a Terraform configuration for a simple web application infrastructure.

The infrastructure should include the following components:

- A virtual machine (EC2 instance) to host the web application.
- A security group to control inbound traffic to the virtual machine.
- An Elastic IP address associated with the virtual machine.

The virtual machine should have the following specifications:

- **Instance type:** t2.micro
- **AMI ID:** ami-0c55b159cbfafe1f0
- **Tags:**
  - **Name:** WebServer
  - **Environment:** Production

The security group should allow inbound HTTP traffic (port 80) from anywhere.

## Review the Execution Plan

After creating your configuration file, use `terraform plan` to ensure your configurations would apply as you expect.

- Examine the execution plan and identify the resources that Terraform will create.

- Verify that the EC2 instance, security group, and Elastic IP address are included in the plan.

- Check the specified configurations, such as the instance type, AMI ID, and security group rules.

- Note any questions or observations you have about the execution plan.
