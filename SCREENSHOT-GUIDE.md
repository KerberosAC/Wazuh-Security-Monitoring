# Wazuh screenshot guide

All images below came from `Cyber Home Lab Doc 1.docx` in the image order embedded in that document. The corresponding file is saved in the `screenshots/` directory.

| Original document image | Repository filename | What it actually shows |
|---|---|---|
| `image109.png` | `screenshots/01-virtualbox-wazuh-vm.png` | VirtualBox Wazuh server VM details |
| `image112.png` | `screenshots/02-ubuntu-manager-ip-address.png` | Ubuntu ip addr output showing Wazuh server network interface |
| `image110.png` | `screenshots/03-wazuh-installation-command.png` | Wazuh installation assistant command from lab instructions |
| `image111.png` | `screenshots/04-wazuh-installation-complete-REDACTED.png` | Wazuh successful installation summary with password masked |
| `image113.png` | `screenshots/05-ubuntu-package-source-check.png` | Ubuntu apt package-source and update check |
| `image114.png` | `screenshots/06-wazuh-dashboard-login.png` | Wazuh web login page |
| `image115.png` | `screenshots/07-windows-agent-deployment-wizard.png` | Windows agent deployment wizard with manager address |
| `image116.png` | `screenshots/08-windows-agent-powershell-setup.png` | Windows PowerShell Wazuh agent installation and service startup |
| `image117.png` | `screenshots/09-windows-endpoint-overview.png` | Enrolled Windows endpoint Wazuh dashboard |
| `image118.png` | `screenshots/10-kali-linux-agent-wizard.png` | Kali Linux Wazuh agent deployment wizard |
| `image119.png` | `screenshots/11-endpoint-network-inventory.png` | Wazuh endpoint network inventory |
| `image121.png` | `screenshots/12-vulnerability-summary.png` | Wazuh vulnerability detection summary counts |
| `image122.png` | `screenshots/13-vulnerability-records.png` | Wazuh vulnerability findings table |
| `image127.png` | `screenshots/14-file-integrity-monitoring-settings.png` | Windows ossec.conf file integrity monitoring settings |
| `image125.png` | `screenshots/15-virustotal-integration-configuration.png` | Wazuh ossec.conf VirusTotal integration block with placeholder API key |
| `image128.png` | `screenshots/16-eicar-test-samples.png` | EICAR harmless antivirus test sample files |
| `image129.png` | `screenshots/17-virustotal-detection-events.png` | Wazuh VirusTotal integration events for EICAR test files |

**Excluded:** `image123.png` shows a personal VirusTotal API portal; `image124.png` offers no useful configuration result; `image126.png` is a documentation reference rather than an observed security event. `image120.png` shows auxiliary installer files and commands, but adds little beyond the installation steps. Images outside the Wazuh section belong to other home-lab topics (pfSense, Snort, Nessus, Action1, and Active Directory).

**Security:** `image111.png` was cropped and its password field covered. Do not upload the unedited original installation image; it contains several Wazuh account passwords.

**Evidence scope:** Linux agent deployment wizard does not establish active enrollment; VirusTotal alert is for EICAR test files, not real malware.
