# Auto deploy an app with Jenkins - Terraform -  Ansible

In this sample, we will be automating almost all the steps in the automatic installation of a new Docker server.

Some of the goals of this sample:

- Create S3 bucket to store state for main Terraform code.
- Automate Terraform to create EC2 with Jenkins.
- Automatically generate Inventory for Ansible from Terraform output.
- Jenkins executes Ansible playbook to install Docker on newly created EC2.

![01-create-s3-bucket](./images/01-create-s3-bucket.jpg)

![02-github-ssh-key](./images/02-github-ssh-key.jpg)

![03-ec2-ssh-key](./images/03-ec2-ssh-key.jpg)

![04-ansible-plugin](./images/04-ansible-plugin.jpg)

![05-create-jenkins-pipeline](./images/05-create-jenkins-pipeline.jpg)

![06-pipeline-run-1](./images/06-pipeline-run-1.jpg)

![07-pipeline-run-2](./images/07-pipeline-run-2.jpg)

![08-pipeline-run-3](./images/08-pipeline-run-3.jpg)

![09-pipeline-run-4](./images/09-pipeline-run-4.jpg)

![10-pipeline-run-5](./images/10-pipeline-run-5.jpg)

(./images/11-pipeline-run-6.jpg)

(./images/12-pipeline-run-7.jpg)

Software version

|  Software |  Version |
|---|---|
| Docker | 20.10.14 |
| Docker Compose | 1.29.2 |
| AWS CLI | 1.19.1 |
|  Terraform | 1.1.8 |
| Ansible | 2.10.8 |
| Jenkins | 2.332.2 |
