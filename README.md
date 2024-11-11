# Automated Deployment of Required IAM Role for AWS Security Lake

<img width="275" alt="map-user" src="https://img.shields.io/badge/cloudformation template deployments-7-blue"> <img width="85" alt="map-user" src="https://img.shields.io/badge/views-640-green"> <img width="125" alt="map-user" src="https://img.shields.io/badge/unique visits-217-green">

AWS Security Lake requires an IAM role *AmazonSecurityLakeMetaStoreManager*. The trust policy and permissions required for the role are documented in the [Create necessary IAM roles](https://docs.aws.amazon.com/security-lake/latest/userguide/getting-started.html#prerequisite-iam-roles) section of the [Amazon Security Lake documentation](https://docs.aws.amazon.com/security-lake/latest/userguide/what-is-security-lake.html).

To make it easier to get started with Amazon Security Lake the CloudFormation stack in this repository automates the deployment of the required IAM role *AmazonSecurityLakeMetaStoreManager*.

Click on the button below to launch the [AmazonSecurityLakeMetaStoreManager_IAM_Role.yaml](https://github.com/ev2900/SecurityLake_AmazonSecurityLakeMetaStoreManager/blob/main/AmazonSecurityLakeMetaStoreManager_IAM_Role.yaml) CloudFormation stack.

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=AmazonSecurityLakeMetaStoreManager-IAM-Role&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/AmazonSecurityLakeMetaStoreManager_IAM_Role.yaml)

The ARN of the IAM role is available in the outputs of the CloudFormation stack. The arn can be passed to Security Lake when you are enabling it - as pictured below

<img alt="IAM_Intergration" width="800" src="https://github.com/ev2900/SecurityLake_AmazonSecurityLakeMetaStoreManager/blob/main/README/IAM_Intergration.png">
