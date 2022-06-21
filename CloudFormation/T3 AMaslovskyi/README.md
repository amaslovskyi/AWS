# CloudFormation deploy S3, CloudFront, Route53

To create a stack set you need add some parameters:
* DomainName - The DNS name of an existing Amazon Route 53 hosted zone
* BucketName - Amazon S3 files bucket name
* HostedZoneId - Amazon Route53 Hosted Zone Id for DomainName
* CertificateArn - Certificate Link