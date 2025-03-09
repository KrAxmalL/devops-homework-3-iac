# Homework 3 (IaC)

## Creating the infrastructure
- To create the infrastructure - run the `terraform apply` command inside the `/terraform` folder

## Notes
- During the infrastructure creation the private key file will be generated inside the `/keys/private` folder. It can be used to access all of the created servers using SSH. It is created as a preventive measure to be able to access the created servers if adding the public keys from `/keys/public` folder will fail for some reason. Destroying the infrastructure with `terraform destroy` command will delete the private key as well.