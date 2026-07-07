# 🎬 Netflix Clone on AWS

A simple **Netflix-inspired video streaming web application** built using **HTML with inline CSS and JavaScript**. The application is hosted on **Amazon EC2** using **Apache HTTP Server (httpd)**, while video content is stored and streamed directly from **Amazon S3**.

---

## 📖 Project Overview

This project demonstrates how to deploy a static web application on **Amazon EC2** and integrate it with **Amazon S3** for cloud-based media streaming. The application provides a clean Netflix-inspired interface where users can stream or download videos directly from the browser.

---

## ✨ Features

- 🎬 Netflix-inspired user interface
- 📺 Stream videos directly from Amazon S3
- ⬇️ Download videos directly from Amazon S3
- ☁️ Hosted on Amazon EC2
- 🌐 Apache HTTP Server (httpd)
- 📱 Responsive single-page web application
- ⚡ Lightweight implementation using a single HTML file
- 🔗 Direct integration between Amazon EC2 and Amazon S3
- 🎥 HTML5 video player with playback controls

---

## 🛠 Technologies Used

- HTML5
- Inline CSS
- Inline JavaScript
- Amazon EC2
- Amazon S3
- Apache HTTP Server (httpd)
- AWS IAM

---

## ☁️ AWS Architecture

```text
                    User
                      │
                      ▼
         Amazon EC2 (Apache HTTP Server)
                      │
                      ▼
         Netflix Clone Web Application
                      │
                      ▼
          Amazon S3 Bucket (Video Storage)
                 │                  │
                 ▼                  ▼
         Video Streaming     Video Download
```

---

## 📁 Project Structure

```text
netflix-clone/
│
├── index.html
├── README.md
│
├── app-working/
│   └── endpoint.mp4
│
├── screenshots/
│   ├── app-overview1.png
│   ├── app-overview2.png
│   ├── ec2instance-overview.png
│   ├── iam-role.png
│   ├── s3bucket.png
│   └── s3bucket-overview.png
│
└── videos-used/
    ├── demo1.mp4
    └── demo2.mp4
```

---

## 📷 Screenshots

### 🎬 Application Overview

![Application Overview](screenshots/app-overview1.png)

![Application Overview](screenshots/app-overview2.png)

---

### ☁️ Amazon EC2 Instance

![EC2 Instance](screenshots/ec2instance-overview.png)

---

### 🔐 IAM Role

![IAM Role](screenshots/iam-role.png)

---

### 🪣 Amazon S3 Bucket

![S3 Bucket](screenshots/s3bucket.png)

![S3 Bucket Overview](screenshots/s3bucket-overview.png)

---

## 🎥 Demo

A short screen recording demonstrating the application is included in this repository.

**▶️ Demo Video:** [Watch Demo](app-working/endpoint.mp4)

https://github.com/iamayan17/netflix-clone/tree/main/app-working/endpoint.mp4

> **Note:** If GitHub does not play the video directly in the README, click the link above to open it from the repository.

---

## 🚀 Deployment Steps

1. Launch an Amazon EC2 instance.
2. Install and configure Apache HTTP Server (httpd).
3. Upload the `index.html` file to the Apache web root directory.
4. Create an Amazon S3 bucket.
5. Upload the required video files to Amazon S3.
6. Configure bucket permissions and CORS.
7. Update the S3 video URLs inside `index.html`.
8. Access the application using the EC2 Public IP address.
9. Stream or download videos directly from the application.

---

## 🎯 Learning Outcomes

- Deploying a static website on Amazon EC2
- Configuring Apache HTTP Server (httpd)
- Using Amazon S3 for cloud media storage
- Streaming videos from Amazon S3
- Downloading videos from Amazon S3
- Managing AWS IAM permissions
- Integrating Amazon EC2 with Amazon S3
- Building a simple cloud-based streaming application

---

## 🌟 Future Enhancements

- User authentication
- Search functionality
- Movie categories
- Video thumbnails
- Watch history
- Multiple user profiles
- CloudFront integration
- Secure streaming using pre-signed URLs
- Backend API for dynamic content

---

## 👨‍💻 Author

**Ayan Ahmed**

GitHub: https://github.com/iamayan17

---

## ⭐ Support

If you found this project helpful, please consider giving this repository a **⭐ Star**.

Thank you for visiting this project!
