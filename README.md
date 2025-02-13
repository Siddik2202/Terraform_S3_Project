# Terraform_S3_Project
1. Set the provider.tf file
2. Then initialize using Terraform init command
3. After applying terraform 
4. Set Ownership of s3 bucket.
5. Then change the ownership, get public access go to aws_s3_bucket_acl
6. Then website configuration go to aws_s3_bucket_acl_bucket_website_configuration
7. Then go to aws_s3_object and set files and bucket name
8. Now store the object in s3



*** I have mention some steps not all but befor that
you need to do two thisng
1) AWS CLI configure 
2) Initialize Terraform in your directory then you can run main.tf file but objects and files should be exist like, image, .html file.
