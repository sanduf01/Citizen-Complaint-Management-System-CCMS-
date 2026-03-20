# Citizen Complaint Management System (CCMS)

## Overview 🚀
The **Citizen Complaint Management System (CCMS)** is a web/mobile platform for citizens to report governance issues like corruption, service delays, policy violations, election problems, and misconduct directly to authorities. 

**Key Goals** (from SRS):
- Promote transparency and accountability
- Enable complaint submission, tracking, and resolution
- Provide admin dashboards and analytics for officials

**Repo Focus**: SRS documentation for future PHP/MySQL implementation.

[![SRS Version](https://img.shields.io/badge/SRS-1.0-blue)](Mini%20Project%20-%20SRS.pdf)

---

## 📋 Features
| Feature | Description |
|---------|-------------|
| User Registration/Login | Secure signup with email/phone + OTP/National ID verification |
| Complaint Submission | Form with text, location, images/videos; auto-confirmation via SMS/email |
| Complaint Tracking | Real-time status updates for citizens |
| Admin Dashboard | Filter/assign/update complaints by category/location/status |
| Reports | Trends analytics, PDF/CSV export |


## 🛠️ Tech Stack
| Component | Technology |
|-----------|------------|
| Backend | PHP |
| Database | MySQL |
| Web Server | Apache / Nginx |
| Frontend | Responsive HTML/CSS/JS (Chrome, Firefox, Edge) |
| Integrations | National ID API, SMS/Email APIs |


## 👥 User Roles
| Role | Skills | Responsibilities |
|------|--------|------------------|
| **Citizen** | Low | Submit/track complaints |
| **Admin Officer** | Medium | Review/assign/update complaints, generate reports |
| **System Admin** | High | Manage users, security, backups |

---




## 🛠️ Installation & Setup
**Current**: Documentation-only repo. For future implementation:

1. Clone repo: `git clone <repo-url>`
2. Setup LAMP stack (Linux/Apache/MySQL/PHP)
3. Import DB schema (TBD)
4. Configure `.env`: DB creds, API keys (National ID, SMS/Email)
5. `composer install` (PHP deps, TBD)
6. Run: `php -S localhost:8000`

See SRS Section 2.4 for details.

---

## 💡 Usage

### Citizen Flow
1. Register/Login (email/phone + OTP)
2. Submit complaint: Text + location + media
3. Track status via dashboard/notifications

### Admin Flow
1. Login to dashboard
2. Filter/assign complaints
3. Update status + add remarks
4. Generate/export reports

---

## 🗺️ Roadmap (from SRS)
- **Immediate**: Backend (PHP/MySQL), basic UI
- **Next**: API integrations (National ID/SMS)
- **Future**: Mobile app, GIS mapping (TBD-1), push notifications (TBD-3)
- **Non-functional**: Security (HTTPS/encryption), 99% uptime

---

## 📚 Documentation
- **[Full SRS PDF](./Mini%20Project%20-%20SRS.pdf)**: Detailed requirements, use cases
- References: [IEEE SRS](https://www.ieee.org/), [CPGRAMS](https://pgportal.gov.in/)

---

## 📌 License
MIT License - Free to use/adapt with attribution.

---

**Made by [Sanduni Fernando](https://github.com/sanduf01)**  
[Download CV](https://raw.githubusercontent.com/sanduf01/my-portfolio/main/portfolio/public/Sanduni%20Fernando%20CV.pdf) | [LinkedIn](https://linkedin.com/in/sanduf01)