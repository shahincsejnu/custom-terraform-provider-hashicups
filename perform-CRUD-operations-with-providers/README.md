# CRUD with Providers

- In this tutorial, you will use a Terraform provider to interact with a fictional coffee-shop application, HashiCups.
- In the process, you will learn how providers map target APIs to Terraform in order to create, read, update, and delete resources.

## Terraform Plugins

- Terraform is comprised of Terraform Core and Terraform Plugins
- Terraform Core reads the configuration and builds the resource dependency graph.
- Terraform Plugins (providers and provisioners) bridge Terraform Core and their respective target APIs. 
- Terraform provider plugins implement resources via basic CRUD (create, read, update, and delete) APIs to communicate with third party services.
- While most Terraform providers manage cloud infrastructure (e.g. AWS, Azure and GCP providers), providers can serve as an interface to any API and allow Terraform to potentially manage any resource.

## Example

- The Terraform `HashiCups provider` interfaces with the product's REST API `through a` GoLang client library`. This allows you to manage HashiCups orders through Terraform.


## Flow

- folowed [this tutorial](https://learn.hashicorp.com/tutorials/terraform/provider-use?in=terraform/providers)

- OS-ARCH is `linux_amd64` (for this one had a lot of trouble, did use `linux_x86_64`)

- rest just follow the tutorial