# AWS-Health-Check
aws_resource_tracker
#!/bin/bash

########################################################################
# Author: KS199
# Date: 23rd-Feb-2024
# Version: Draft version
# This script will report the aws usage
########################################################################
#
#
#AWS S3
#AWS EC2
#AWS Lambda
#AWS IAM Users
#
#

# list s3 buckets
aws s3 ls

# list EC2 instances
aws ec2 describe-instances

# list lambda
aws lambda list-functions

# list IAM users
aws iam list-users
