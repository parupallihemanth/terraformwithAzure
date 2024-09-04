Terraform Basic workflow

1. Terraform init: Used to initialize terraform config files and download providers
2. Terraform validate: Validates config files to ensure syntactically valid and internernally consistant
3. Terraform plan: Creates an execution plan and Determines what actions are necessary to achieve the desired state specified in config files.
4. Terraform apply: Applys changes specified in config files to achieve desired state. Apply scans the current directory for the configuration and applies the changes appropriatetly
5. Terraform destroy: Destroys the terraform managed resources and asks for confirmation

Terraform Blocks
1. Terraform block : Specifies terraform CLI version, Providers name and version, Backend information/configuration(Manage state)
2. Providers block : Heart of the Terraform, Declare, install  and use remote providers, Belong to root module
3. Resource block: Used to declare and  create resources like resourcegroups, vnets, subnets, VM's etc. Can also configure post resource creation actions like install softwares and run script files.
4. locals block:
5. variables block:
6. output block:
7. Data block:
8. Modules block:
