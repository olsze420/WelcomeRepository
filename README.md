# Welcome to my GitHub page!
## A bit about me:
Hi! 
My name is Michał Olszewski at the time of writing this I am a 3rd year Computer Science Student at PJATK in Warsaw.
Previously I have studied Finance, Investment and Risk in Glasgow Scotland.

While working in finance I became passionate about technical possibilities of improvements in various processes and tasks. Simply put: why do it yourself every day/week/month manually when you can just run a script to do it exactly the same (and exactly being a firm statement which I will get to in a while) for you. More time to do other important stuff, or a wee break.
 
 That's when I decided it's time to move my career focus to CS and started a new degree. Since starting this degree I had the priviledge to get my first tech focused role after 1 semester. I have worked for Natwest Group in Warsaw as Data developer. My main focus was data visualisation using tableau and AWS athena (SQL), but my day to day work also consisted of ETL jobs done with AWS Glue (Python based scripts). That's probably when I got interesed slightly more in Cloud based computing and noticed that values that are presented by the DevOps ideology are closely aligning with my own. 
 The best way to put it, there's always room for improvement and development. And the DevOps mindset and set of tools is working to enable that to the best of possibilities. 
 And here comes the part which, I'd say I love the most in Cloud based infrastucture which is Infrastracture as Code, which going back to my initial statement allows you to build and develop infrastructure after the initial code creation in exactly the same way on many different environments and with little or even no exhaustion. 
 Having this possible with just one tool (like terraform, which I'm very keen on learning, as it simply puts a lot of joy in me, seeing how much can be done so easily) is in my mind a massive technical milestone for all companies that want to stay technically relevant.

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
