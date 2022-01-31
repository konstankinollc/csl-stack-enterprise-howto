## CSL Scanner Enterprise

![CSL Scanner - Flowchart](https://github.com/konstankinollc/csl-stack-enterprise-howto/blob/main/CSL%20Scanner%20-%20Flowchart.png)

### Prerequisites

In this section of the Guide, we will cover the following topics:

1. Installing and configuring AWS CLI, Terraform CLI and Git
2. Getting access to CSL Scanner Amazon Machine Image


#### 1. Installing and configuring AWS CLI, Terraform CLI and Git

To install AWS CLI version 2, please follow the link to respective AWS User Guide (https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).

To install Terraform CLI, please follow the link to respective HashiCorp Lear Tutorial (https://learn.hashicorp.com/tutorials/terraform/install-cli).

To install Git, please follow the link to respective Git Tutorial (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

#### 2. Getting access to CSL Scanner Amazon Machine Image

In order to access CSL Scanner, please provide Konstankino Associates your AWS account ID. You can send us an email with your AWS IAM user information or complete the project discovery form (https://galaxy.konstankino.com/public/forms/5222f0dbc48236443f9db0804ab7724e7f016c96a2819e87dc8d7fd34880de0f).

### Deployment

CSL Scanner is distributed as a set of AWS preconfigured services hosted on the AWS as an Amazon Machine Image and as a set of Terraform templates.

The CSL Scanner shall be deployed using Terraform templates in the following order:

1. Network layer
2. EC2 layer
3. Glue layer
4. API layer

To deploy each layer please refer to appropriate git repository folder.

### Deployment Outcome

CSL Scanner is deployed as a set of AWS preconfigured services, which include the following:

1. **Network layer**
	1. Amazon VPC
	2. Amazon NAT
	3. Private VPC subnet
	4. Public VPC subnet
	5. A set of VPC Security Groups
2. **Application layer**
	1. Amazon EC2
	2. Amazon EBS
3. **Batch processor layer**
	1. Amazon Glue
	2. Amazon Glue VPC Connection
	3. Amazon Glue Job Trigger
4. **API layer**
	1. Amazon API Gateway
	2. Amazon API Key
	3. Amazon API UsagePlan
	4. Amazon Lambda
5. **Monitoring & Operational layer**
	1. Amazon CloudWatch Logs


### Support

Currently we provide a few support tiers to deploy and operate the CSL Scanner.

#### Basic Support Tier

While we are expanding our capacity and serving more customers, we are limited to several engineers on staff who can help you. At this support tier, we answer general questions about application usage and sharing best practices. The average time to respond is more than 24 hours.

#### Enterprise Support Tier

At this Support Tier, we will deploy CSL Scanner Solution in your AWS Account. Also, additional services are available at this Tier. For a full list of services, please email us at info@konstankino.com. The average time to respond is less than 8 hours.

For further information contact the Konstankino Associates support team via email or through the channel provided as part of the CSL Scanner Enterprise License agreement.

Please email us at info@konstankino.com with your request to establish an Enterprise Support with us.

### Release notes

Check the latest release notes at this link.

### FAQ and Troubleshooting

The CSL Scanner solution writes operational logs to Amazon CloudWatch Log groups. Please refer to the individual layer CloudWatch Log group to troubleshoot the solution. You can also consider contacting us if you have any questions or seek help. Thank you.

