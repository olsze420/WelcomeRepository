# Welcome to my GitHub page!
 

# My Projects

1. Static Website launched on AWS using only terraform (michalolszewski.click)
a. S3 - static web location
b. Route53 - rerouting from owned domain to the website
c. Certificate Manager - SSL certification for the website
d. CloudFront - securing the website in HTTPS
![enter image description here](https://cloudisfree.com/projects/project-1/part-1/images/infrastructure.png)
2. Serverless Sending Application (sandbox usability only) 
a. S3 - static web for access to the app
b. API Gateway - handling PUT request from the website to Lambda
c. Lambda Function - Sending email/sms and passing information from rest API
d. Step Function - based on information from lambda invoking one of the functions
e. SNS & SES - sending email or sms
![enter image description here](https://cloudisfree.com/projects/project-2/part-1/images/infrastructure.png)
3. Database and Containers - WIP 

## Source codes

All the codes will be visible here, on my gitHub page with replaced some values into a placeholder for anyone to use it and check out themselves.
