# 🚀 AWS DevOps Portfolio | Thananjeyan Pandian

[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)

A high-performance, responsive portfolio website designed for AWS DevOps professionals. This project demonstrates modern web design coupled with cloud-native deployment strategies.

## 🌐 Live Demo
**[Insert Your CloudFront URL Here]**

---

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid), JavaScript (ES6+)
- **Icons & Fonts:** FontAwesome 6.4, Google Fonts (Inter)
- **Deployment:** AWS S3 (Static Hosting)
- **CDN:** AWS CloudFront
- **CI/CD:** GitHub Actions

## ✨ Key Features
- **Zero-Jump Mobile Background:** Custom CSS logic to prevent background "shaking" on mobile browsers.
- **Glassmorphism UI:** Modern frosted-glass effect for skill and project cards.
- **Horizontal Overflow Fix:** Specialized mobile styles to prevent right-side sliding issues.
- **Automated Invalidation:** CI/CD pipeline integration for instant cache updates.

---

## 🏗 Cloud Architecture
The portfolio is hosted using a highly available AWS architecture:

1.  **S3 Bucket:** Stores the static assets (HTML, CSS, Images).
2.  **CloudFront:** CDN to serve the site from Edge locations globally.
3.  **ACM:** SSL/TLS certificates for secure HTTPS access.
4.  **GitHub Actions:** Automatically syncs code to S3 and triggers a CloudFront invalidation.

---

## 🚀 Deployment via GitHub Actions
To automate deployment, add these secrets to your GitHub Repository (**Settings > Secrets and variables > Actions**):

| Secret Name | Description |
| :--- | :--- |
| `AWS_S3_BUCKET` | The name of your S3 bucket |
| `AWS_ACCESS_KEY_ID` | Your IAM user access key |
| `AWS_SECRET_ACCESS_KEY` | Your IAM user secret key |
| `DISTRIBUTION_ID` | Your CloudFront Distribution ID |

---

## 📂 Project Structure
```text
├── images/               # Image assets (workstation.jpg, etc.)
├── index.html            # Main portfolio code
└── README.md             # Project documentation

---

## 👨‍💻 Author

**Thananjeyan Pandian** *AWS DevOps Engineer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thananjeyan-pandian-5aa204220/) 
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat&logo=github&logoColor=white)](https://github.com/Thananjeyan29)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:thananjeyan29@gmail.com)

---
*Built with ❤️ and AWS DevOps Principles.*
