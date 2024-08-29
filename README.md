# CIS AWS Cloudtrail Sentinel Policies for Terraform
This library, provides prescriptive Terraform policies that can be used to establish secure Terraform configuration 
for Amazon Web Services Vpc Resources included in CIS v3.0.0. 
The policies that are contained in this library are based on the [CIS Amazon Web Services Benchmarks](https://docs.aws.amazon.com/securityhub/latest/userguide/cis-aws-foundations-benchmark.html).
Terraform Cloud/Enterprise users can use the policies in this library to establish a foundational level of security for the services that they are 
adopting in Amazon Web Services.

> This Policy Library is not an exhaustive list of all of possible configurations and architecture that is available in Amazon Web Services. 
> If you have questions, comments, or have identified ways for us to improve this library, 
> please create [a new GitHub issue](https://github.com/hashicorp/policy-library-aws-cloudtrail-terraform/issues/new/choose).
>
> Alternatively, We welcome any contributions that improve the quality of this library! 
> To learn more about contributing and suggesting changes to this library, refer to the [contributing guide](https://github.com/hashicorp/policy-library-aws-cloudtrail-terraform/blob/main/CONTRIBUTING.md).

### Policies supported via Sentinel

The following CIS standards have equivalent Sentinel policies written for them. These policies get enforced between the `plan` and `apply` phase whenever a run gets queued in TFC/TFE.

- [vpc-flow-logging-enabled](./docs/policies/vpc-flow-logging-enabled.md)