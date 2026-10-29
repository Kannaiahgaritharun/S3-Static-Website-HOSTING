 
# AWS S3 Static Website Hosting

## 📌 Project Overview

This project demonstrates how to host a static website using **Amazon Simple Storage Service (Amazon S3)**. The website is built using HTML and CSS and is hosted directly from an S3 bucket without requiring a traditional web server.

## 🎯 Objectives

- Create an Amazon S3 bucket.
- Upload an HTML website to S3.
- Enable static website hosting.
- Configure public read access for website files.
- Access the hosted website using the S3 website endpoint.

## 🛠️ Technologies Used

- **Amazon S3** – Static website hosting and file storage.
- **HTML5** – Website structure and content.
- **CSS3** – Website styling and responsive design.
- **AWS Management Console** – Cloud resource configuration.

## 🏗️ Architecture

```text
       User / Web Browser
               |
               v
       S3 Website Endpoint
               |
               v
       Amazon S3 Bucket
               |
               v
          index.html
               |
               v
       HTML + CSS Website
```

## ⚙️ Implementation Steps

1. Created an S3 bucket named `tharun-s3-static-website-2026`.
2. Created a website using HTML and CSS.
3. Uploaded `index.html` to the S3 bucket.
4. Enabled static website hosting in the bucket properties.
5. Configured the index document as `index.html`.
6. Configured the necessary bucket permissions for public website access.
7. Accessed the website using the S3 static website endpoint.

## 📂 Project Structure

```text
AWS-S3-Static-Hosting/
│
├── index.html
└── README.md
```

## 🌐 How to Access the Website

1. Open the AWS Management Console.
2. Navigate to Amazon S3 and select the project bucket.
3. Open the **Properties** tab.
4. Find the **Static website hosting** section.
5. Open the **Bucket website endpoint**.

**Live Website:** Add your S3 website endpoint here after deployment.

## 🔐 Security Considerations

- Public access is enabled only when required for the website.
- The bucket should contain only files intended for public viewing.
- AWS Block Public Access settings and bucket policies must be configured carefully.
- Never store credentials, private documents, or sensitive information in a public website bucket.

## ✅ Project Outcome

Successfully configured an Amazon S3 static website hosting environment to serve a custom HTML webpage through an AWS website endpoint.

## 📚 What I Learned

- Creating and configuring Amazon S3 buckets.
- Uploading and managing objects in S3.
- Enabling static website hosting.
- Understanding bucket policies and public access.
- Deploying a basic website on AWS cloud infrastructure.

## 👨‍💻 Author

**Tharun**

Project: AWS S3 Static Website Hosting
