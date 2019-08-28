# Deploy Static Website on AWS

The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. In this project, you will deploy a static website to AWS. 

First, you will create a S3 bucket, configure the bucket for website hosting, and secure it using IAM policies. Next, you will upload the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront. 

Lastly, you will access your website in a browser using the unique S3 endpoint.

# Website Files

## Criteria 1 -- The student has created a S3 bucket.

[S3 Bucket Created](https://github.com/xboudsady/udacity-project-1/blob/master/img/s3-bucket.png)

## Criteria 2 -- All website files should be added to the S3 bucket.

[S3 Site Contents](https://github.com/xboudsady/udacity-project-1/blob/master/img/s3-contents.png)

## Criteria 3 -- The bucket configuration should be set up to support static website hosting.

[S3 Web Hosting](https://github.com/xboudsady/udacity-project-1/blob/master/img/s3-web-hosting.png)

## Criteria 4 -- The permission access to the bucket should be configured to allow public access.

[S3 Bucket Policy](https://github.com/xboudsady/udacity-project-1/blob/master/img/s3-bucket-policy.png)

# Website Distribution

## Criteria 5 -- The website should be distributed via Cloudfront. 

[CloudFront - Config](https://github.com/xboudsady/udacity-project-1/blob/master/img/cloudfront-config.png)

## Site Screen Shot / [CloudFront Endpoint](http://d3ovydiusw04ri.cloudfront.net/index.html) / [S3 Static Site](http://udacity-website-xboudsady.s3-website-us-east-1.amazonaws.com/)

[Site Screen Shot](https://github.com/xboudsady/udacity-project-1/blob/master/img/site-screenshot.png)