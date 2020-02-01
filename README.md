# Terraform module AWS Security Groups
Module creates and provisions AWS Security Groups and manages rules.
Full post and instructions can be found here https://www.opsmag.com/terraform-module-aws-security-groups

#### Module Features
  - Create security groups.
  - Security group rules.
  - Ingress nested rules.
  - Egress nested rules.

#### Requirements
Terrform version 0.12+

#### Usage and instruction

Use resource provisioning template from directory examples and siple fill up variables.tf

```sh
$ terraform init
$ terraform plan
$ terraform apply
```
#### Version history
0.1.0 - Initial release

Author: [Boris Karaoglanov](https://www.opsmag.com/boris)
Webiste: [OpsMag.com](https://www.opsmag.com)