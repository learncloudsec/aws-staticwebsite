# aws-staticwebsite
AWS Static Web Site Cloud Formation Template using S3, Route 53 and CloudFront

Forked from https://github.com/Celidor/aws-staticwebsite

The web site content is from the AWS "Build a Static Web Site" quick start tutorial.

* Clone the repository using Git, the git command should work directly from PowerShell
* Log in to AWS console, select North Virginia region, Cloud Formation, Create Static
* Upload the staticwebsite.yaml file.
* Enter details as prompted, selecting your own domain
* Approve the certificate once you receive the email
* Once the S3 bucket is created, upload the web site content
* Give all objects in the bucket read permissions by Everyone
