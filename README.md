# 🔁 Leave Request Approval Automation  
### Automated by: SACHIN SAVKARE – Automation Specialist | Low-Code Trainer

This repository showcases a **real-world automation project** built using **Google Forms, Google Sheets, and n8n**.  
The objective: eliminate manual leave tracking and approvals, improve operational efficiency, and enable HR scalability across departments.

Built as part of my training program and implementation series for no-code/low-code automation professionals.

---

## 📘 About the Project

Manual leave approval workflows often suffer from:
- Delays in communication
- Missing records or unlogged leaves
- Unnecessary HR involvement in repetitive tasks

This project solves that through a fully automated pipeline:
- A Google Form for employees
- Google Sheet for data storage and tracking
- n8n for real-time processing, approvals, and notification flows

> **Suitable for:** HR teams, startups, internal IT automation, or as a learning template for automation engineers.

---

## ⚙️ Tech Stack

| Tool            | Purpose                           |
|-----------------|-----------------------------------|
| Google Forms     | Leave request input from employees |
| Google Sheets    | Data storage and centralized tracker |
| n8n              | Orchestrates workflow automation |
| Gmail (via n8n)  | Sends approval/notification emails |

---

[![Watch the Project](https://raw.githubusercontent.com/CB-AI-Toolkit-for-Professional/13.-E4-AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/main/Thumbnail.png)](https://www.youtube.com/watch?v=ISPovD_h0-E)

---

## 🔄 Automation Workflow

### 🔹 1. Workflow: Application Request 

 ![Step 1 - n8n Workflow](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Workflow%201.png)



### 🔹 2. Workflow: Approval  

![Step 2 - n8n Workflow](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Workflow%202.png)



### 🔹 3. Workflow: Rejection 

![Step 3 - n8n Workflow](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Workflow%20_reject.png)

---

## 🧾 Google Form Preview

The form collects all required information from employees:
![Google Form](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/google%20Form.png)


**Fields Include:**
- Submission Date  
- Employee ID, Name, Email  
- Department  
- Leave Start/End Dates  
- Reason for Leave  

---

## 📩 Email Notifications

Once the request is submitted, n8n handles communication via Gmail:

1. 📤 **Leave Application Sent to Manager**
   
![Leave Application Sent to Manager](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Mail%20recive%20to%20dept..JPG)



2. ✅ **Approval Email to Employee**
   
![Approval Email to Employee](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Mail_Approved.jpg)



3. ❌ **Rejection Email to Employee**
   
![Rejection Email to Employee](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Mail_Rejected.jpg)


---

## 📚 Documentation

To replicate or adapt this solution, follow the complete guides below:

- 📄 [Follow the Automation Guide](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Leave%20Approval%20Process%20Guide.pdf)  
  Step-by-step setup in n8n, including webhook logic and Google Sheet configuration.

- 📑 [Read the Full Automation Report](https://github.com/SachinSavkare/AI-Enables-Leave-Request-Approval-Automation-N8Nt-Approval/blob/main/Leave%20Automation%20Report.pdf)  
  Includes manual process breakdown, automation value, benefits, and system architecture.

---

## 💡 Key Benefits

- 🔁 End-to-end workflow automation with no manual intervention  
- ⏱️ 80% faster processing time  
- 👤 One-click manager decisions via secure email links  
- 🧾 Fully auditable and trackable leave system  
- ♻️ Easily customizable for other approval processes (e.g. travel, reimbursements)

---

## 👨‍🏫 About the Author

**Sachin Savkare**  
Automation Specialist | Trainer – Low-Code & AI Workflows  
🔗 [LinkedIn Profile (https://www.linkedin.com/in/sachin-savkare/)]  
📧 [https://codebasics.io/portfolio/Sachin-Savkare]

> Training professionals and teams on scalable, real-world automation using n8n, Make, Google Workspace, and more.

---

## 📄 License

Licensed under the [MIT License](./LICENSE).

---

> ⚙️ Built with precision for professionals who believe in automating smarter, not harder.
