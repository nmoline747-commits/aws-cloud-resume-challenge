# aws-cloud-resume-challenge
My AWS Cloud Resume project
# AWS Cloud Resume Challenge

My personal resume website built as part of the [AWS Cloud Resume Challenge](https://cloudresumechallenge.dev/).

**[Live Site →](https://d2y7o0cwskqgik.cloudfront.net)**

**[Github Repo →](https://github.com/nmoline747-commits/aws-cloud-resume-challenge)**

## Architecture

- **Frontend**: Static HTML/CSS hosted on Amazon S3
- **CDN + HTTPS**: Amazon CloudFront with Origin Access Control
- **Backend**: Serverless visitor counter using AWS Lambda, API Gateway, and DynamoDB
- **CI/CD**: Fully automated deployment pipeline with GitHub Actions

## Features

- Responsive, clean resume design
- Live visitor counter (serverless)
- Automatic deployments on every code change
- Secure HTTPS with CloudFront
- Professional social links

## Technologies Used

- **AWS**: S3, CloudFront, Lambda, API Gateway, DynamoDB, IAM
- **Tools**: GitHub Actions, HTML/CSS, Python (for Lambda)

## What I Learned

- Static website hosting and global content delivery with S3 + CloudFront
- Building serverless applications with Lambda and DynamoDB
- Implementing secure CI/CD pipelines
- Infrastructure security best practices (OAC, IAM policies)
- Real-world application of concepts from the AWS Cloud Practitioner certification

## Future Enhancements

- Custom domain (resume.nickmoline.com)
- Architecture diagram
- Monitoring with CloudWatch
- Additional projects (highly available EC2 app, serverless TODO app)
