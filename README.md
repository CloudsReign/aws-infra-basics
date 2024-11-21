# S3 Bucket Setup with Versioning

This section provides a step-by-step guide to create an S3 bucket and enable versioning using AWS CLI.

## Step 1: Create an S3 Bucket

Run the following command to create an S3 bucket. Replace `my-bucket-name` with a globally unique name for your bucket, and specify your desired region.

```bash
aws s3api create-bucket --bucket my-bucket-name --region us-east-1

aws s3api put-bucket-versioning --bucket my-bucket-name --versioning-configuration Status=Enabled


