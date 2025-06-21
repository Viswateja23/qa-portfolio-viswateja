# qa-portfolio-viswateja
# 👋 Hi, I'm Viswateja!

**Manual QA Engineer | Mobile QA Analyst**  
Hyderabad, India

---

With 6+ years at Amazon and a specialized 3-year focus on **manual testing for Amazon Fire Tablets**, I bring a keen eye for detail and a passion for ensuring users get the best experience. Currently transitioning fully into QA, I'm actively seeking opportunities as a Manual QA Engineer or Mobile QA Analyst.

---

## 🛠️ Skills & Tools

- **Manual Testing:** Functional, Regression, Smoke, Sanity
- **Mobile & Device Testing:** Amazon Fire Tablets (Fire 7, HD 8, HD 10, Max 11)
- **ADB:** Log capture, build validation, device commands
- **JIRA:** Bug tracking, test cycle management
- **OTA Testing:** Fire OS, update validation
- **Process:** SDLC, STLC, Defect Life Cycle
- **Test Design:** Excel, exploratory, documentation
- **Certifications:** ISTQB Foundation (In Progress)
- **Other:** Agile, reporting, team collaboration

---

## 📋 Sample Test Cases

### 🔐 Login Functionality – Basic Test Suite

| Test Case ID | Scenario                         | Steps                                    | Expected Result                         |
|--------------|----------------------------------|------------------------------------------|-----------------------------------------|
| TC_Login_001 | Valid login                      | Enter valid username/password → Login    | Redirect to home/dashboard              |
| TC_Login_002 | Invalid password                 | Enter valid username + wrong password    | Error: "Invalid credentials"            |
| TC_Login_003 | Empty fields                     | Leave all fields blank → Login           | Show required field errors              |
| TC_Login_004 | Password masking                 | Enter password field                     | Should show bullets (••••)              |
| TC_Login_005 | Remember Me                      | Check Remember Me → Login → Reopen app   | Session/token retained                  |

---
Project:
Title: Manual QA & OTA Validation for Fire Tablet Devices.
Objective: Performed end-to-end manual testing across Fire 7, 8, 10, and 11 devices, covering functional, regression, and OTA validation test cases using ADB and JIRA.
Test Execution:
- Executed 500+ test cases across functional, regression, and UAT cycles.
- Validated OTA updates and verified post-update system stability.
- Performed smoke, sanity, and full regression testing on Fire Tablets (7, 8, 10, 11).
- Captured logs using ADB and reported defects with clear steps and evidence.
- Identified and escalated high-priority and device-specific issues.
- Retested resolved defects and ensured closure in JIRA.
- Maintained detailed test reports and communicated status to QA leads.
- Verified post-deployment OTA builds by checking software version and performing smoke and regression tests.
- Collaborated with the dev team to align on deployment timelines and test new features immediately after release.
Bug Tracking:
- logged and tracked defects using JIRA, ensuring complete and accurate documentation.
- Included clear reproduction steps, screenshots, ADB logs, and screen recordings in each bug report.
- Collaborated with QA leads and developers to triage, prioritize, and resolve bugs.
- Verified and retested fixed issues in follow-up builds; ensured smooth bug lifecycle management.
  
## 🐞 Sample Bug Report

**Title:** Alexa Toggle Not Responding After OTA Update  
**Device:** Fire HD 10  
**Build:** Fire OS 8.3.2 – OTA Build 2025.06.12

**Steps to Reproduce:**
1. Go to Settings → Alexa  
2. Toggle Alexa ON  
3. Observe system response

**Expected:** Alexa should enable with confirmation  
**Actual:** Toggle resets to OFF, no system feedback  
**Severity:** High  
**Logs:** Collected via ADB (`adb logcat > alexa_issue.txt`)  
**Status:** Reported via JIRA to internal QA team  

---

## 🧪 Project Highlight: Fire Tablet OTA Build Validation

- Ran OTA update validation for Fire 7, Fire HD 8, Fire Max 11
- Verified system boot, Wi-Fi, settings, and app behaviors post-update
- Reported critical and UI bugs via JIRA with logs/screenshots
- Retested fixes and performed regression on key features
- Used ADB for debugging and log capture

---

## 📚 Certifications

- **ISTQB Foundation** (In Progress, Target: July 2025)
- Manual Testing (Udemy)
- Fire Tablet QA (Internal Amazon Training)

---

## 📫 Contact

- **Email:** viswateja944@gmail.com
<!-- - [LinkedIn](your-linkedin) | [Portfolio](your-website) -->

---

> *“I enjoy finding bugs before the user does. QA is where my attention to detail and curiosity align to improve real products.”*
MY QA Portfolio - Test cases, bug report and project work
