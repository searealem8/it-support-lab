# 🛠️ IT Support Lab: Automated Help Desk Toolkit

This is a simulated IT support project built to showcase real-world IT skills for entry-level roles. It includes automation scripts, troubleshooting guides, and help desk ticket simulations.

---

## 📁 Project Structure

it-support-lab/
├── setup-scripts/
│ └── install_chrome.sh
├── troubleshooting-guides/
│ ├── printer_issues.md
│ └── outlook_errors.md
├── automation/
│ └── log_parser.py
├── tickets_resolved/
│ └── ticket_001_network_issue.md
└── README.md

---

## ⚙️ Setup Scripts

### `install_chrome.sh`

```bash
#!/bin/bash
echo "Installing Google Chrome..."
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome*.deb
sudo apt-get install -f
