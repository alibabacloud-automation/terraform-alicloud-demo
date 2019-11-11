terraform-alicloud-demo
=====================================================================

[Module Description]

[Module Architecture Picture]

[The Resources used to Module]

----------------------

Usage
-----

[Module Usage Description]

## Inputs

| Name | Description | Type | Default | Required | Vaild When |
|------|-------------|:----:|:-----:|:-----:|:-----:|
| region | The region ID used to launch this module resources. If not set, it will be sourced from followed by ALICLOUD_REGION environment variable and profile | string  | - | no  | - |
| profile | The profile name as set in the shared credentials file. If not set, it will be sourced from the ALICLOUD_PROFILE environment variable. | string  | - | no  | - |
| shared_credentials_file | This is the path to the shared credentials file. If this is not set and a profile is specified, $HOME/.aliyun/config.json will be used. | string  | - | no  | - |
| skip_region_validation | Skip static validation of region ID. Used by users of alternative AlibabaCloud-like APIs or users w/ access to regions that are not public (yet). | bool  | false | no  | - |
......

## Outputs

| Name | Description |
|------|-------------|
| xxx    |     xxx      |
......

Terraform version
-----------------
Terraform version 0.12.0+ is required for this module to work.

Authors
-------
[Author Info]

Reference
---------
* [Terraform-Provider-Alicloud Github](https://github.com/terraform-providers/terraform-provider-alicloud)
* [Terraform-Provider-Alicloud Release](https://releases.hashicorp.com/terraform-provider-alicloud/)
* [Terraform-Provider-Alicloud Docs](https://www.terraform.io/docs/providers/alicloud/)

