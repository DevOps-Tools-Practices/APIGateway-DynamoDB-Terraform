# APIGateway-DynamoDB-Terraform


## Getting started

Make sure have a Terraform version in your local computer [terraform installation](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)



## Execution

1. To confirm the installation of Terraform, run the below command to check the version:

```
terraform version
```

2. Initialize Terraform by running the below command,

```
terraform init
```

Note: terraform init will check for all the plugin dependencies and download them if required, this will be used for creating a deployment plan

3. To generate the action plans run the below command,

```
terraform plan
```

4. To create all the resources declared in main.tf configuration file, run the below command:

```
terraform apply
```

5. Approve the creation of all the resources by entering yes.

6. Id’s of all the resources created by terraform will be visible there.

