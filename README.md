# active-directory-helpdesk-labs 

This repository showcases a collection of simulated Active Directory (AD) labs that demonstrate common Tier 1 IT Helpdesk tasks. All labs were completed in a Windows Server environment hosted on AWS EC2, simulating a real-world enterprise setup.

These labs were designed to build hands-on experience with Active Directory user and group management, one of the core responsibilities of helpdesk and IT support roles.

## 💻 Environment
- **Platform:** AWS EC2
- **OS:** Windows Server
- **Tools Used:** Active Directory Users and Computers (ADUC), Remote Desktop Protocol (RDP)

# 🔐 Password Reset Lab (Active Directory)

## 📄 Description

This lab demonstrates how to perform a password reset for a user account in **Active Directory Users and Computers (ADUC)** — a common Tier 1 Help Desk task. This was done on a Windows Server running in an AWS EC2 environment.


## 🧰 Tools Used

- AWS EC2 (Windows Server 2019)
- Active Directory Users and Computers (ADUC)


## 📋 Scenario

> A user is unable to log into their workstation. You’ve been asked to reset their password and enforce a password change at next logon.


## 🧪 Steps Performed

### 1. Open Active Directory Users and Computers

Launched ADUC from the Start menu.

![Open ADUC](https://github.com/ReggieS22/active-directory-helpdesk-labs/blob/62833245db10c2609d42f748b5127a91267bdc1a/Active%20Directory%20password%20resets%20lab%20screenshots/open-aduc.png.png)


### 2. Locate the User & Reset the Password

Right-clicked the user account and selected **Reset Password**, entered a new temporary password, and enforced password change at next logon.

![Reset Password](./screenshots/password-reset.png)


### 3. Confirm Password Reset

Confirmed that the password reset was successful and saved changes.

![Confirmation](./screenshots/confirm-reset.png)


## ✅ Outcome

The password reset was completed successfully. The user can now log in using the new temporary password and will be required to create a new one at next login.


## 🧠 What I Learned

- Navigating ADUC to manage user accounts
- How to reset a user’s password and enforce best practices
- Simulating real help desk scenarios using cloud-hosted environments



## 📷 Screenshots
Each lab folder contains step-by-step screenshots of the process to provide visual documentation of the work performed.
