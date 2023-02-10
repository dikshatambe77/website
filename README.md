# Static Website Creation
## Simple static website hosted on AWS S3 bucket

### Table Of Contents
[Introduction](#introduction) <br>
[Technologies Used](#technologies-used) <br>
[Setup](#setup) <br>
[Status](#status) <br>
[Conclusion](#conclusion)

### Introduction
This project is a demonstration of creating a static website on Amazon Web Services (AWS) using S3 buckets and policies. The website has been created using HTML and is hosted on AWS S3.


### Technologies Used
AWS S3 buckets
AWS policies
HTML


Note: AWS S3 permissions and settings screenshots are available in 'Setup' folder. The html code file - _index.html_ available in the 'code' folder.

### Setup
1. Create a new S3 bucket with a unique name.
2. Enable the static website hosting feature for the S3 bucket.
3. Create an index.html file and upload it to the S3 bucket.
4. Set appropriate permissions for the S3 bucket to ensure the website is accessible to everyone i.e. setting objects in S3 to Public
5. Accessing and testing the website the Website
6. You can access the website by using the website endpoint provided by AWS after enabling the static website hosting feature for the S3 bucket. The endpoint will be in the format: http://[bucket_name].s3-website-[region].amazonaws.com


### Status
Completed and Deployed. 
The website can be accessed using following url:
[Click here to access the website](http://dikshatambe.s3-website-ap-northeast-1.amazonaws.com "Diksha's Website")

### Conclusion
This project showcases the ease of creating a static website on AWS using S3 buckets and policies. By hosting a static website on AWS, you can benefit from the scalability, reliability, and security offered by the platform.
