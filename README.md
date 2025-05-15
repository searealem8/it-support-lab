# 🛠️ IT Support Lab: Automated Help Desk Toolkit

This is a simulated IT support project built to showcase real-world IT skills for entry-level roles. It includes automation scripts, troubleshooting guides, and help desk ticket simulations.

---

## 📁 Project Structure


---

## ⚙️ Setup Scripts

### `install_chrome.sh`

```bash
#!/bin/bash
echo "Installing Google Chrome..."
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome*.deb
sudo apt-get install -f
net stop spooler
net start spooler

log_parser.py
with open("system.log") as file:
    for line in file:
        if "ERROR" in line:
            print(line)


ticket_001_network_issue.md

Click **Commit changes**.

---

### 💻 STEP 4: Add Files (Copy and Paste)

#### 1. `install_chrome.sh`

File path: `setup-scripts/install_chrome.sh`

```bash
#!/bin/bash
echo "Installing Google Chrome..."
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome*.deb
sudo apt-get install -f

log_parser.py - automation/log_parser.py
with open("system.log") as file:
    for line in file:
        if "ERROR" in line:
            print(line)
printer_issues.md - troubleshooting-guides/printer_issues.md
# 🖨️ Printer Issue - Troubleshooting Guide

**Issue:** Printer not printing

**Fix Steps:**
1. Check cables and power
2. Ensure it's set as the default printer
3. Restart Print Spooler:

4. Update drivers
ticket_001_network_issue.md - tickets_resolved/ticket_001_network_issue.md
# 🧾 Help Desk Ticket - Network Issue

**User:** John Doe  
**Problem:** Cannot connect to Wi-Fi  
**Resolution Steps:**
- Rebooted router
- Checked IP config
- Disabled/Enabled Wi-Fi adapter
- Issue resolved


