# aws-security-standards-iac
This repository bundles all remediation instructions for
[AWS Security Hub](https://aws.amazon.com/security-hub/) findings as Infrastructure as Code.

## Shortcomings of Security Hub
Some findings barely solve the issue. Although it's hard for a tool like Security Hub to tackle or
test some issues,a pointer to those could have been easily added to the documentation.
"[RDS.10: IAM authentication should be configured for RDS instances](https://docs.aws.amazon.com/securityhub/latest/userguide/securityhub-standards-fsbp-controls.html#rds-10-remediation)"

## IaC: CloudFormation
Where possible complete CloudFormation templates are provided. For other findings standalone
codesnippets are provides as most likely they need to be wired into existing resources.

## IaC: Others
Don't hesitate if you want to contribute in Terraform, CDK, Pullumi or any other kind of IaC.
