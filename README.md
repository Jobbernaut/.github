# Jobbernaut Ecosystem

### *Navigate the vast space of the job market.*

**Jobbernaut** is a cloud-native, event-driven open core intelligence platform designed to automate the most tedious parts of the job search: data extraction, resume tailoring, and document management. It transforms a scattered manual process into a streamlined, intelligent pipeline.

---

## 🚀 The Architecture at a Glance

The ecosystem is composed of **5 decoupled micro-repositories** working in harmony.

| Repository | Role | Technology Stack |
| :--- | :--- | :--- |
| **[jobbernaut-infra](https://github.com/Jobbernaut/jobbernaut-infra)** | **Foundation** | **Terraform** (HCL), AWS IAM, S3, DynamoDB. |
| **[jobbernaut-tabs](https://github.com/Jobbernaut/jobbernaut-tabs)** | **Frontend** | **Next.js**, React, Tailwind CSS. |
| **[jobbernaut-backend](https://github.com/Jobbernaut/jobbernaut-backend)** | **Control** | **Python** (AWS Lambda), Boto3, Pydantic. |
| **[jobbernaut-tailor](https://github.com/Jobbernaut/jobbernaut-tailor)** | **Intelligence** | **Docker**, Python, LangChain (AI), TeXLive (LaTeX). |
| **[jobbernaut-extract](https://github.com/Jobbernaut/jobbernaut-extract)** | **Collection** | **Chrome Extension** (Manifest V3), JavaScript. |

> 📘 **Documentation:** For deep dives into the architecture, data flows, and setup guides, visit **[jobbernaut-docs](https://github.com/Jobbernaut/jobbernaut-docs)**.

---

## ⚡️ Key Features

* **One-Click Extraction:** Grab job details from LinkedIn/Indeed instantly with the Chrome Extension.
* **Serverless Orchestration:** Powered by **AWS Step Functions** to manage async AI workflows without managing servers.
* **AI-Driven Tailoring:** Uses LLMs to analyze job descriptions and optimize resume content dynamically.
* **LaTeX Precision:** Renders high-quality, ATS-friendly PDFs using a headless LaTeX engine.
* **Infrastructure as Code:** 100% of the cloud environment is defined and reproducible via Terraform.

## 📜 License

The entire Jobbernaut Ecosystem is source-available under the **PolyForm Noncommercial License 1.0.0**.
You are free to use, modify, and learn from this code for personal or non-commercial purposes.
