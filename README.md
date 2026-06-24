Portfolio Website Deployment using AWS S3 and CloudFront

Project Overview

This project demonstrates how to host a static portfolio website using Amazon S3 and distribute it globally using Amazon CloudFront.

Steps Performed

1. Created Portfolio Website

- Developed a simple portfolio website using:
  - HTML
  - CSS

Files:

- index1.html
- styles.css

2. Created GitHub Repository

Repository Name:

- sivanesan-portfolio

GitHub Link:

- https://github.com/Sivanesan-26/sivanesan-portfolio

3. Created Amazon S3 Bucket

Bucket Name:

- sivanesan-portfolio

Region:

- Asia Pacific (Sydney) (ap-southeast-2)

4. Uploaded Website Files

Uploaded:

- index1.html
- styles.css

5. Enabled Static Website Hosting

S3 Bucket → Properties → Static Website Hosting → Enable

Index Document:

- index1.html

6. Accessed Website through S3

Website Endpoint:

- http://sivanesan-portfolio.s3-website-ap-southeast-2.amazonaws.com

7. Created CloudFront Distribution

Distribution Name:

- sivanesan-portfolio-cdn

Origin:

- S3 Website Endpoint

CloudFront Domain:

- d79rfzhwol5c7.cloudfront.net

Result

Successfully deployed a static portfolio website using AWS S3 and CloudFront.

Technologies Used

- HTML
- CSS
- GitHub
- Amazon S3
- Amazon CloudFront
