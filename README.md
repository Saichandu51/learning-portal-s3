# Learning Portal - Static Website on AWS S3

This project is a simple **Learning Hub** web portal that provides curated course links. It is deployed as a static website using **Amazon S3** for cost-effective, highly available hosting.

---

## 🌐 Features

- Static website hosted on **Amazon S3**
- Publicly accessible via S3 static hosting
- Simple HTML layout for course links
- Secure using **IAM roles and S3 bucket policies**

---

## 📁 Project Structure


---

## 🚀 AWS Deployment Steps

1. Created an S3 bucket with a unique name (e.g., `learning-portal-s3`)
2. Enabled **Static Website Hosting**
3. Uploaded `web.html` to the bucket
4. Set bucket policy to allow public read access
5. Configured **index document** as `web.html`
6. Verified website at `http://<bucket-name>.s3-website-<region>.amazonaws.com/`
7. Website link `https://learning-portal51.s3.ap-south-1.amazonaws.com/web.html`

---

## 🔐 IAM and Security

- Used IAM roles and custom bucket policies to restrict/allow access securely
- Ensured only read access is granted to public for website content

---

## 📦 Technologies Used

- **HTML**
- **CSS**
- **Amazon S3**
- **IAM**
- **Git & GitHub**

---


## 🧑‍💻 Author

**Saichandu Anukonti.**  
GitHub: [Saichandu51](https://github.com/Saichandu51)

