# AWS Website Terraform module

Terraform module which creates an website (S3/CloudFront/HTTPS) on AWS.

## Usage

```hcl
module "website" {
  source = "lunii/website/aws"

  bucket_name = "my-bucket"
  zone        = "zone-id"
  dns         = "my.website.com"
}
```
