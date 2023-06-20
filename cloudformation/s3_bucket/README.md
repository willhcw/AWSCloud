# S3 Bucket CloudFormation Template

## Description

This CloudFormation template creates an S3 bucket with customizable options. You can specify the bucket name and choose whether to enable versioning. Additionally, the template enforces public access restrictions on the bucket.

## Parameters

The template expects the following parameters:

- **BucketName**: Enter a unique name for the S3 bucket.
- **EnableVersioning**: Choose whether to enable versioning for the S3 bucket.
- **BlockPublicAcls**: Choose whether to block public ACLs for the S3 bucket.
- **BlockPublicPolicy**: Choose whether to block public bucket policies for the S3 bucket.
- **IgnorePublicAcls**: Choose whether to ignore public ACLs for the S3 bucket.
- **RestrictPublicBuckets**: Choose whether to restrict public bucket policies for the S3 bucket.

## Usage

To deploy the CloudFormation stack and create the S3 bucket, follow these steps:

1. Open the AWS Management Console and navigate to the CloudFormation service.
2. Click "Create stack" and select "With new resources (standard)".
3. In the "Specify template" section, choose "Upload a template file" and select the CloudFormation template file.
4. Fill in the required parameters and customize the options as desired.
5. Click "Next" to proceed.
6. On the following pages, you can customize the stack options, tags, and review the configuration.
7. Finally, click "Create stack" to deploy the S3 bucket.

## Outputs

The CloudFormation stack will create the following outputs:

- **S3BucketURL**: The URL of the S3 bucket.
- **S3BucketARN**: The Amazon Resource Name (ARN) of the S3 bucket.

## Authors

- Will Hu (cwhu223@gmail.com)
