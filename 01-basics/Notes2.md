Portfolio Deployed

Learned how to deploy a website on AWS cloud.
Used S3 buckets and Cloud Front to host the portfolio

**S3 buckets :** an S3 bucket is a fundamental storage container used for holding data in the form of "objects" within the Amazon Simple Storage Service (S3).

Objects: These are the actual files (like images, videos, or logs) stored in a bucket. Each object consists of the data itself, a unique key (the file name/path), and metadata

Regional Location: When you create a bucket, you choose an AWS Region. This helps with latency and data residency requirements, as your data is physically stored in that specific geographic area.

Key Features
Scalability: S3 automatically scales to handle any amount of data, from a few kilobytes to petabytes.

Durability: It is designed for 99% durability, meaning it is built to protect data against loss.

Versioning: This feature allows you to keep multiple versions of an object, protecting you from accidental deletions or overwrites.

Common Use Cases
Backup and Recovery: Securely storing critical business data for emergency restoration.
Static Website Hosting: You can configure a bucket to host static web content like HTML, CSS, and images.

**Amazon CloudFront** is a Content Delivery Network (CDN). It speeds up the delivery of your website, videos, and apps by storing (caching) copies of your files in a global network of data centers called "Edge Locations." When a user visits your site, CloudFront delivers the data from the closest location, drastically reducing load times