# IAM Permissions Explorer — Design Assignment

This project presents a simple and practical wireframe solution to help cloud security engineers identify and fix excessive or unused IAM permissions across multiple cloud accounts.

Check out the [Figma Project](https://www.figma.com/make/cezCA41jaF31OckrxYzGI9/Low-Fidelity-Wireframes-for-IAM-Permissions-Explorer?fullscreen=1&t=WxUJkeg5Wd8vvZzh-1).

---

## 🎯 Objective

Design a clean and easy-to-use interface that enables security teams to:

* Detect over-privileged identities
* Investigate risky permissions
* Safely remediate unused access
* Reduce manual IAM review effort

---

## 👤 User Persona

**Primary user:** Cloud Security Engineer

**Context:**

* Works with AWS / Azure / GCP environments
* Manages hundreds or thousands of identities
* Needs quick visibility into risky permissions
* Must fix access issues without breaking workloads

**Pain Points:**

* Hard to find unused permissions
* Too many identities to review manually
* Fear of removing permissions incorrectly
* Lack of clear risk prioritization

---

## 🧩 Solution Overview

The IAM Permissions Explorer provides a guided workflow:

1. **Discover** risky identities
2. **Investigate** permission usage
3. **Fix** excessive access safely

The design focuses on clarity, speed, and safe remediation.

---

## 🖼️ Wireframes

The following low-fidelity wireframes were created in Figma:

* **Screen 1 — IAM Explorer Dashboard**
  Shows identity risk overview and filtering.

* **Screen 2 — Identity Details View**
  Displays permission-level risk and usage.

* **Screen 3 — Fix Permissions Workflow**
  Guides safe removal of unused permissions.

---

## 🚀 Key Features

* Risk-based identity prioritization
* Usage visibility before remediation
* Guided least-privilege recommendations
* Safe preview before applying changes
* Multi-account filtering support

---

## 📊 Success Metrics

The design aims to improve:

* ⬇️ Time to identify over-privileged identities
* ⬇️ Manual IAM review effort
* ⬇️ Risk of accidental access removal
* ⬆️ Security team remediation speed
* ⬆️ Confidence in least-privilege enforcement

---

## 🛠️ Bonus — Development Discussion Items

Potential engineering considerations:

* IAM data ingestion from cloud providers
* Permission usage tracking logic
* Risk scoring model
* Safe rollback mechanism
* Performance for large identity datasets

---

## 📌 Notes

* This is a **low-fidelity UX wireframe exercise**
* Focus is on workflow clarity and practical usability
* Visual styling is intentionally minimal

---

**Author:** Jasveer Singh
**Role Target:** Product / Security UX Internship
