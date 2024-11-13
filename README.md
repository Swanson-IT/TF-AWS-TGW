# TF-AWS-TGW

# Terraform AWS Transit Gateway Module

This Terraform module creates a Transit Gateway in AWS.

## Usage

To use this module, include it in your Terraform configuration, specifying the required variables.

### Example

```hcl
module "transit_gateway" {
  source = "github.com/Swanson-IT/TF-AWS-TGW?v1.0" # Use v1.0 tag

  name        = "my-transit-gateway"          # Desired name for the Transit Gateway
  description = "Main transit gateway for VPCs" # Optional description, default is "