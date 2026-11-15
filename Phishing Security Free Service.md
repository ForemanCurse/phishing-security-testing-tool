# Phishing Security Testing Tool

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:0F9B0F&height=220&section=header&text=Phishing%20Security%20Testing%20Tool&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Train%20Your%20Team%20To%20Spot%20The%20Bait%20Before%20It%20Bites&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.2.0-0F9B0F?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-96.8K-000000?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FF3366?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20docker-00C9FF?style=for-the-badge&logo=docker&logoColor=black)

</div>

---

## 🎣 The Best Defense Is A Controlled Offense

It is a terrifying statistic: over 90% of successful cyberattacks begin with a phishing email. Firewalls and antivirus software are essential, but they cannot stop a user from clicking a malicious link. The human element is always the weakest link in the security chain.

**Phishing Security Testing Tool** is a powerful, open-source platform designed to help organizations test and train their employees. It allows security teams to simulate realistic phishing campaigns, track who clicks, and immediately enroll those users in targeted educational training.

This is not a malicious tool. It is a defensive weapon. It includes a built-in SMTP server, a library of realistic email templates (e.g., "Password Reset," "Invoice Attached," "HR Policy Update"), and a comprehensive dashboard to analyze the results. It is the ultimate tool for building a security-aware culture in your company.

---

## 🛡️ The Three Pillars Of Simulation

We have designed the tool to cover the entire lifecycle of a phishing awareness campaign.

| Phase | Description | Example Features |
| :--- | :--- | :--- |
| **1. The Campaign Builder** | Design realistic emails and landing pages | Drag-and-drop editor, template library |
| **2. The Execution Engine** | Send emails safely without triggering spam filters | SMTP relay, throttling, domain spoofing |
| **3. The Analytics Dashboard** | Track clicks, data submission, and reporting rates | Real-time charts, user risk scores |

<img width="900" height="486" alt="uuvMQkt1V2rwqKAO7oPT0ttYc" src="https://github.com/user-attachments/assets/10073920-0955-4507-97c8-e36aca1388c4" />

---

## ✨ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Realistic Templates** | Over 50 email templates mimicking real-world attacks |
| **Landing Page Cloner** | Clone legitimate login pages to train users on fake sites |
| **User Risk Scoring** | Automatically calculate a risk score for every employee |
| **Automated Training** | Redirect users who fail to a mandatory security lesson |
| **GDPR Compliant** | Data is anonymized and stored securely |
| **Dockerized** | Spin up the entire stack in seconds |

---

<div align="center">

### 🔗 Ready to test your team?

[![Get Tool](https://img.shields.io/badge/🎣_GET_TOOL-000000?style=for-the-badge&logoColor=white)](https://share.google/0rXBxdPSnPUk95ieu)

</div>

---

## ⚙️ Quick Setup

You will need Docker and a domain name (for hosting the fake landing pages).

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/phishing-security-testing-tool.git

# Step 2: Navigate into the directory
cd phishing-security-testing-tool

# Step 3: Launch the stack with Docker Compose
docker-compose up -d

# Step 4: Access the dashboard
# Navigate to http://localhost:8080
```

Once the dashboard loads, create an admin account. Navigate to the "Campaigns" tab to start your first simulation. The tool will guide you through selecting a target group, choosing a template, and scheduling the send.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-0F9B0F?style=for-the-badge&logoColor=white)](https://share.google/0rXBxdPSnPUk95ieu)

</div>

---

## 🧠 Under The Hood: The Phishing Engine

How does a phishing simulation actually work? It is all about the **Click Tracking**.

When you send an email, the tool embeds a unique, invisible pixel (a 1x1 transparent image) and a unique tracking link. The link points to your server, not the real website.

When the user opens the email, the pixel loads, recording the "Open" event. When they click the link, they are redirected to a cloned login page. If they enter their credentials, the tool captures the submission (but does not store the password, only the fact that they were tricked) and redirects them to a training video.

The dashboard aggregates all these events. It generates a report showing you exactly which departments are vulnerable to which types of attacks (e.g., Engineering falls for "Server Upgrade" emails, while HR falls for "Policy Updates").

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>


---

## 🤝 Community & Contributing

Security awareness is a community effort. If you have created a new email template, improved the analytics dashboard, or want to add support for a new language, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-template`).
3. **Commit** your changes (`git commit -m 'Add new template'`).
4. **Push** to the branch (`git push origin feature/new-template`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your campaign results, ask for help with SMTP setup, and discuss the latest trends in social engineering.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@phishing-tool.dev.

---

<div align="center">

### ⭐ If this tool secures your team, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FF3366?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username/phishing-security-testing-tool)

---

### 🚀 Start training your team today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00C9FF?style=for-the-badge&logoColor=black)](https://share.google/0rXBxdPSnPUk95ieu)

<sub>Crafted with precision and ❤️ by the Phishing Security Testing Tool community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0F9B0F,100:000000&height=120&section=footer)

</div>
