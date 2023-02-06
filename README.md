# Automated Deployment of Required IAM Roles for AWS Security Lake

AWS Security Lake requires an IAM role *AmazonSecurityLakeMetaStoreManager*. The trust policy and permissions required for the role are documented in the [Create necessary IAM roles](https://docs.aws.amazon.com/security-lake/latest/userguide/getting-started.html#prerequisite-iam-roles) section of the [Amazon Security Lake documentation](https://docs.aws.amazon.com/security-lake/latest/userguide/what-is-security-lake.html).

To make it easier to get started with Amazon Security Lake the CloudFormation stack in this repository automates the deployment of the required IAM role *AmazonSecurityLakeMetaStoreManager*. 

Click on the button below to launch the [AmazonSecurityLakeMetaStoreManager_IAM_Role.yaml](https://github.com/ev2900/SecurityLake_AmazonSecurityLakeMetaStoreManager/blob/main/AmazonSecurityLakeMetaStoreManager_IAM_Role.yaml) stack

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=open-search-deleteddocuments&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/opensearch_deleteddocuments.yaml)
