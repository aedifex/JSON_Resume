# JSON resume

Store your resume as a JSON file! Apply DevOps principles to maintaining an up-to-date resume, deploy to S3 in seconds. Get excited, tell your friends.

----

[![aedifex](https://circleci.com/gh/aedifex/JSON_Resume.svg?style=svg)](https://app.circleci.com/pipelines/gh/aedifex/JSON_Resume)


### Longer description...

Tired of getting your resume up to date? Every wondered how you could apply programming, DevOps, and a CI/CD pipeline to maintaining a professional resume or CV? If these are the kinds of questions that keep you up at night, this is the right git repository for you!

This project leverages several technologies to create a CI/CD process which builds, updates, and pushes your resume to an S3 bucket for static hosting. Now, rather than sending a PDF to a prospective employer, you can impress them by sending them a URL! Exciting, I know.

There are several components to this project.

1. JSON resume, an open schema representing your resume / CV as a JSON object.

2. CircleCI

CircleCI is the best CI tool in the market. Period. You can get up and running in minutes with a scalable CI/CD tool at your fingertips. A project like this certainly falls into the free tier.


3. AWS

Specifically we're using S3 with a bit of Route53 thrown into the mix.

4. Terraform

We'll use Terraform to create our bucket and set up the appropriate ACLs.
