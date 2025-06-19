🔓 Unlock a Locked Active Directory Account

## 📄 Description

This lab simulates unlocking a user account in **Active Directory Users and Computers (ADUC)** — a common request handled by Tier 1 Help Desk technicians. This lab was performed on a Windows Server hosted in AWS EC2.

---

## 🧰 Tools Used

- AWS EC2 (Windows Server 2019)
- Active Directory Users and Computers (ADUC)

---

## 📋 Scenario

> A user has called the helpdesk after being locked out of their account due to multiple failed login attempts. Your job is to locate and unlock the account in Active Directory.

---

## 🧪 Steps Performed

### 1. Locate the Locked User in ADUC

Used ADUC to find the user account suspected of being locked out.

![Find Locked User](./screenshots/find-locked-user.png)

---

### 2. Open User Properties and Unlock

Opened the user's properties and navigated to the **Account** tab. Unchecked the **“Account is locked out”** box.

![Unlock Checkbox](./screenshots/unlock-checkbox.png)

---

### 3. Confirm Unlock

Confirmed the changes and ensured the account was no longer locked.

![Unlock Confirmation](./screenshots/unlock-confirmation.png)

---

## ✅ Outcome

The user account was successfully unlocked. The user was able to log in without further issues.

---

## 🧠 What I Learned

- How to identify and resolve a locked account in Active Directory
- Navigating account properties and permissions
- Simulating real-world helpdesk account management issues
