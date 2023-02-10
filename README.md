Static Website Creation
Simple static website hosted on AWS S3 bucket

Table Of Contents
Introduction
Technologies Used
Setup
Status
Future Improvements

Introduction
This project is a demonstration of creating a static website on Amazon Web Services (AWS) using S3 buckets and policies. The website has been created using HTML and is hosted on AWS S3.

Technologies Used
AWS S3 buckets
AWS policies
HTML

Setup
# Create a new S3 bucket with a unique name.
# Enable the static website hosting feature for the S3 bucket.
# Create an index.html file and upload it to the S3 bucket.
# Set appropriate permissions for the S3 bucket to ensure the website is accessible to everyone i.e. setting objects in S3 to Public
# Accessing and testing the website the Website
# You can access the website by using the website endpoint provided by AWS after enabling the static website hosting feature for the S3 bucket. The endpoint will be in the format: http://[bucket_name].s3-website-[region].amazonaws.com

Status
Completed and Deployed. 
The website can be accessed using following url:
http://dikshatambe.s3-website-ap-northeast-1.amazonaws.com

Conclusion
This project showcases the ease of creating a static website on AWS using S3 buckets and policies. By hosting a static website on AWS, you can benefit from the scalability, reliability, and security offered by the platform.
