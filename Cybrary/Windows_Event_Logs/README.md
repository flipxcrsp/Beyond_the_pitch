# 🪟 Windows Event Logs – Cybrary Lab

Analysis of Windows Event Logs, specifically around account creation (Event ID **4720**). 

Events were examined using both **Windows Event Viewer** & **Wazuh SIEM** for validation & correlation.

---

## 🧠 Objectives

- Use Windows Event Viewer to identify account creation logs
- Filter by Event ID `4720` (A user account was created)
- Validate results using Wazuh SIEM’s alert engine
- Correlate events with MITRE ATT&CK techniques

---

## 🛠️ Tools Used

- Windows Event Viewer
- Wazuh SIEM Dashboard
- PowerShell for service control (`net stop wazuh`, `net start wazuh`)
- Host file update for agent-server sync

---

## 📸 Screenshots

### Account Creation Analysis

- ![Account Created](./event_log_4720_pikachu_created_general.png)
- ![General Tab](./event_log_4720_pikachu_generalview.png)
- ![Timestamp View](./event_log_4720_pikachu_timestamp.png)
- ![XML Details](./event_log_4720_pikachu_xml_details.png)

---

### Challenge Instructions & Answers

- ![Instructions](./event_logs_challenge_instructions.png)
- ![Questions](./event_logs_challenge_questions_blank.png)
- ![Completed Answers](./event_logs_challenge_answers_complete.png)

---

### User Filtering with Event ID 4720

- ![Filter View](./event_logs_filter_challenge_view.png)
- ![Filtered Results](./event_logs_filter_results_user_creation.png)

---

### Individual Answers

- ![Q1 – Hermit](./event_logs_q1_answer_hermit.png)
- ![Q2 – Joker](./event_logs_q2_answer_joker.png)
- ![Q3/Q4 – Chariot/Domain](./event_logs_q3_q4_answer_chariot_domain.png)

---

### Support Tools & Host Adjustments

- ![Host File IP Entry](./hostfile_update_ip_entry.png)
- ![Event Viewer Launched](./launch_windows_event_viewer.png)
- ![Ping to Wazuh](./ping_result_wazuh_windows.png)
- ![Restart Wazuh Agent](./wazuh_service_restart_windows.png)
- ![IPConfig](./windows_cmd_ipconfig_result.png)
- ![Full Challenge Answers](./windows_event_logs_challenge_full_answers.png)
- ![IP Command](./windows_ip_a_command_result.png)
- ![Hosts File Config](./windows_ip_update_hosts_config.png)

---

## ✅ Outcome

Full investigation of Windows security events related to account creation, verified event ID 4720 presence using Event Viewer, & cross-validated data using Wazuh SIEM.

MITRE mapping (T1098), log correlation, PowerShell agent restarts, & network troubleshooting.

---

## 📄 Certificate of Completion

![Certificate - Windows Event Logs Basics](../Certificates/cybrary-cert-windows-event-logs-basics.png)
