# Deloitte Australia Cybersecurity Job Simulation

This repository contains my work from the **Deloitte Australia Cybersecurity Virtual Experience Program**, where I participated as a cybersecurity analyst responding to a real-world scenario for a high-profile client, **Daikibo Industrials**.

---

## 📌 Overview

**Client:** Daikibo Industrials  
**Situation:** A news outlet leaked confidential data about Daikibo. Around the same time, a production line outage raised concerns about the integrity of their internal systems. The client suspected that their **telemetry dashboard**,used to monitor factory operations, may have been compromised by an external attacker.

---

## 🧪 Tasks Completed

### 1. Web Log Analysis

I reviewed a structured `web_requests.log` file containing HTTP requests made to the telemetry dashboard. Each block of data represented web traffic from a single internal IP address and included login attempts, static asset requests, and API calls.

Using a structured log inspection approach, I:

- Traced legitimate user session flows (Login → Dashboard UI → API)
- Analyzed request intervals and patterns
- Identified one account, **`mdB7yD2dp1BFZPontHBQ1Z`**, exhibiting suspicious, automated API request behavior

### 2. Client Advisory Report

After the analysis, I compiled a professional advisory report for Daikibo. The report:

- Outlined the investigative method  
- Confirmed **no signs of external breach**  
- Flagged abnormal internal activity  
- Recommended auditing the identified user and strengthening monitoring of API usage

---

## 🧰 Tools & Resources Used

- **Notepad** – For reviewing log files line by line  
- **Web Log Analysis Guide** – Provided during the simulation  
- **Manual Pattern Recognition** – To track API request flow and detect automation patterns

---

## 💡 Skills Demonstrated

- Security Log Analysis  
- Threat Detection & Investigation  
- Analytical Thinking  
- Report Writing  
- Communication of Technical Findings  
- Cybersecurity Incident Response

---

## 📁 Repository Contents

- `web_requests.log` – Raw log data from Daikibo’s internal dashboard  
- `log_analysis_guide.pdf` – Guide used to interpret HTTP request patterns  
- `daikibo_advisory_report.pdf` – Final report sent to the client summarizing findings

---

## 👤 Author

**Temple Nnanna Idam-Nkama**  
Cybersecurity Analyst | Tech Enthusiast
🔗 [LinkedIn Profile](https://www.linkedin.com/in/temple-nnanna-idam-nkama-isc2-cc-gmnse-9b5a78327/)

---

This simulation was a strong practical experience in incident investigation, showcasing the value of methodical log analysis and clear communication with clients in cybersecurity operations.

