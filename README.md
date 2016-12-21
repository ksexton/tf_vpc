
## Inputs

| Name | Description | Default | Required |
|------|-------------|:-----:|:-----:|
| name | The name of the VPC. | - | yes |
| cidr | The CIDR of the VPC. | - | yes |
| public_subnet | The public subnet to create. | - | yes |
| enable_dns_hostnames | Should be true if you want to use private DNS within the VPC | `true` | no |
| enable_dns_support | Should be true if you want to use private DNS within the VPC | `true` | no |

## Outputs

| Name | Description |
|------|-------------|
| public_subnet_id |  |
| vpc_id |  |
| cidr |  |

