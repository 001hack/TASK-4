# Task 4: Setup and Use a Firewall on Linux

## Objective

Configure and test basic firewall rules to allow or block traffic. 🚦

## Tools

* **Windows Firewall** (for Windows)
* **UFW (Uncomplicated Firewall)** on Linux 🐧

## Deliverables

* Screenshot or configuration file showing applied firewall rules. 📸

## Steps

### 1. Open Firewall Configuration Tool 🛠️

Launch UFW from the terminal.

### 2. List Current Firewall Rules 📋

Check existing firewall rules.

### 3. Block Inbound Traffic on a Specific Port 🚫

Add a rule to block a port.

### 4. Test the Rule 🔒

Verify if the port is blocked.

### 5. Allow SSH Traffic (Port 22) ✔️

Allow incoming SSH connections.

### 6. Remove Block Rule 🧹

Delete the block rule to restore access.

### 7. Document Commands Used 📑

List commands executed during the task.

### 8. Summary of Firewall Function 🔍

Explain how firewalls filter network traffic.

---

## Outcome

Basic firewall management skills and understanding of traffic filtering. 🎯

---

## Summary of Commands

| Command                                        | Description                              |
| ---------------------------------------------- | ---------------------------------------- |
| `sudo ufw status verbose`                      | View current firewall status and rules.  |
| `sudo ufw status verbose > firewall_rules.txt` | Save the firewall rules to a file.       |
| `cat firewall_rules.txt`                       | View the contents of the saved file.     |
| `nano firewall_rules.txt`                      | Open the file in the `nano` text editor. |

---

## Conclusion 🎉

1. Installed and configured UFW on Kali Linux.
2. Applied firewall rules (blocked/unblocked ports).
3. Saved the firewall configuration to a file for documentation or submission.

---
