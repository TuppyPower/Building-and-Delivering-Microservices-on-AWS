## project : Setting Up CodePipeline
This project explains what is code pipeline and how it can help us to orcharatetrate other aws services to set up continuous development and delivery of the software. This project covers how AWS CodeCommit , CodeBuild and CodeDeploy services create a pipeline to deliver automated software releases.


## Code action

Terraform directory conatins the terraform template to create the infrastructure. aws-code-pipeline directory contains the source code for sample microservice.
* Use `terraform init` to initialize the terraform template.
* Use `terraform plan` to see what all resources will be created using terraform.
* Use `terraform apply --auto-approve` to create the terraform resources in your AWS account.
* Use `terraform destroy --auto-approve` to delete the resources managed by the terraform in your AWS account.

### How to build source code
Use `mvn clean install` to build the source code. 
Use `java -j target/aws-code-pipeline*.jar` to run the spring boot application