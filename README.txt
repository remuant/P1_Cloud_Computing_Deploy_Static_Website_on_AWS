Project 1, Udacity Cloud Developer Nanodegree: Deploy Static Website on AWS

Author: Rachel H*****
Date: June 13th 2020

Organization of information:
The information in this README has been ordered as per the project rubric.
For each point in the rubric the location of the relevant screenshots is indicated.
Screenshots were organized in separate folders for each rubric point.

----------------------------------------
Website Files


The student has created a S3 bucket: The S3 bucket is visible in the AWS Management console.
Screenshots: See screenshots provided in folder: Udacity_Cloud_Dev__Project_01_Screenshots/1_Create_S3_Bucket

All website files should be added to the S3 bucket:The student has submitted a screenshot showing all the website files uploaded to the newly created S3 bucket.
Screenshot: See screenshots provided in folder: Udacity_Cloud_Dev__Project_01_Screenshots/2_Upload_Files_to_S3_Bucket

The bucket configuration should be set up to support static website hosting:The S3 bucket is configured to support static website hosting.
Screenshot: See screenshots provided in folder: Udacity_Cloud_Dev__Project_01_Screenshots/4_Configure_S3_Bucket

The permission access to the bucket should be configured to allow public access:The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.
Screenshot: See screenshots provided in folder: Udacity_Cloud_Dev__Project_01_Screenshots/3_Secure_Bucket_via_IAM

----------------------------------------
Website Distribution


The website should be distributed via Cloudfront: CloudFront has been configured to retrieve and distribute website files.
Screenshot: See screenshots provided in folder: Udacity_Cloud_Dev__Project_01_Screenshots/5_Distribute_Website_via_CloudFront

----------------------------------------
Web Browser Access


Is the website publicly accessible?: The website should be accessible to anyone on the Internet via a web browser. The student should have provided the CloudFront endpoint URL for the website.
Screenshot: See screenshots provided in folder: Udacity_Cloud_Dev__Project_01_Screenshots/6_Access_Website_in_Web_Browser
CloudFront endpoint URL: d154undssjhci3.cloudfront.net
http://d154undssjhci3.cloudfront.net/index.html
