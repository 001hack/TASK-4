# 🚀 **Task 4: Setup and Use a Firewall on Linux**

Hello GitHub Fam! 👋
This is my **fourth task** as part of my **Cybersecurity Internship with Elevate Labs**.

In this task, I analyzed a suspicious email sample to identify common phishing indicators. This hands-on activity helped me better understand how attackers attempt to trick users—and how to recognize the red flags. 🎯

---

## 🎯 Objective

Configure and test basic **firewall rules** to allow or block network traffic.

---

## 🛠️ Tools Used

* **Windows Firewall** (for Windows users)
* **UFW (Uncomplicated Firewall)** on Linux 🐧

---

## ✅ Deliverables

* Screenshot or configuration file showing applied firewall rules. 📸

---

## 🔧 Steps Followed

### 1. Open Firewall Configuration Tool

Launched the UFW tool via the terminal.

### 2. List Current Firewall Rules

Checked existing firewall rules using verbose mode.

### 3. Block Inbound Traffic on a Specific Port

Added a rule to block a specific port (e.g., `sudo ufw deny 8080`).

### 4. Test the Rule

Used tools like `telnet`, `nmap`, or a browser to verify the port was blocked.

### 5. Allow SSH Traffic (Port 22)

Ensured SSH access remained open using:

```bash
sudo ufw allow 22
```

### 6. Remove Block Rule

Removed the previously blocked rule using:

```bash
sudo ufw delete deny 8080
```

### 7. Document Commands Used

Captured and saved all executed commands and current firewall status.

### 8. Summary of Firewall Function

Explained how firewalls act as gatekeepers by filtering incoming/outgoing traffic based on rules.

---

## 📑 Summary of Commands

| Command                                        | Description                             |
| ---------------------------------------------- | --------------------------------------- |
| `sudo ufw status verbose`                      | View current firewall status and rules. |
| `sudo ufw status verbose > firewall_rules.txt` | Save the firewall rules to a file.      |
| `cat firewall_rules.txt`                       | Display the saved firewall rules.       |
| `nano firewall_rules.txt`                      | Edit/view the rules in a text editor.   |

---

## 🔍 Summary of Firewall Function

A **firewall** is a security system that monitors and controls incoming and outgoing network traffic based on pre-defined rules. It acts as a barrier between a trusted internal network and untrusted external networks. By configuring rules, we can:

* Allow legitimate traffic (like SSH)
* Block unauthorized access (e.g., to specific ports)
* Reduce attack surfaces and improve system security

---

## 📝 Outcome

* Installed and configured **UFW** on **Kali Linux**.
* Applied rules to **block and unblock specific ports**.
* Saved and documented firewall configurations for reference and reporting.
* Gained practical experience in **traffic filtering** and **firewall management**.

---

## 🎉 Conclusion

This task helped reinforce foundational concepts in **network security**. Managing firewall rules using UFW not only improves system defense but also deepens understanding of how systems enforce access control at the network level.

---

> 📁 *Thank you for checking out my task! More cybersecurity adventures coming soon.* 🔐✨

---
