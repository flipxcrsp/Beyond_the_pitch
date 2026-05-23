# 🛡️ Wazuh SIEM Labs – Search Expressions & Event Correlation

Labs using the **Wazuh SIEM** to analyze Windows security logs, filter events using Lucene syntax, & correlate alerts with MITRE ATT&CK TTPs.

---

## 📊 Wazuh Main Dashboard

Explore event levels, MITRE correlations, & alert timelines.

![Main Dashboard](wazuh_main_dashboard.png)

---

## 🔍 Using Lucene Filters for Precision Search

Filtering specific logs using `rule.description`, `manager.name`, `eventID`, & usernames with DQL syntax.

![User Creation Filter](wazuh_event_filter_user_created_t1098.png)

---

## 📎 MITRE Technique T1098 - User Account Creation

Wazuh detected the creation of the `Pikachu` account & mapped it to MITRE ATT&CK T1098 (Persistence).

![Pikachu Event](wazuh_pikachu_event_details_t1098.png)

---

## 📄 Correlating Alerts & Viewing Event Details

In-depth alert breakdown including rule IDs, agent info, & timestamps.

![Event Detail](wazuh_event_apparmor_denied_details.png)

---

## ✅ SIEM Challenge Completion

Completed challenge by identifying correct users, filters, & answering correlation questions in Wazuh.

![Challenge Result](wazuh_challenge_results.png)

---

### 📸 Other Notable Screens

<table>
  <tr>
    <td><img src="wazuh_mitre_t1098_pikachu_details.png" width="400"/></td>
    <td><img src="wazuh_data_visualization.png" width="400"/></td>
  </tr>
  <tr>
    <td><sub>MITRE T1098 Alert (User Creation)</sub></td>
    <td><sub>Data Visualization of Alerts</sub></td>
  </tr>
  <tr>
    <td><img src="wazuh_event_apparmor_denied_details.png" width="400"/></td>
    <td><img src="wazuh_interface_breakdown.png" width="400"/></td>
  </tr>
  <tr>
    <td><sub>AppArmor DENIED Alert</sub></td>
    <td><sub>Interface Module Breakdown</sub></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><img src="wazuh_concepts_overview.png" width="400"/></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><sub>Elastic Modules Overview</sub></td>
  </tr>
</table>

---

## 🧠 Skills Practiced

- SIEM log correlation
- Lucene/DQL search syntax
- Event Viewer + Wazuh side-by-side analysis
- MITRE ATT&CK mapping
- Real-world alert triage & filtering

---

## 🏁 Outcome

CEUs are always welcome.

### 📜 Certificate of Completion

<img src="../Certificates/cybrary-cert-siem-basics.png" width="500"/>

[🔗 View PDF Certificate](../Certificates/cybrary-cert-siem-basics.pdf)

---

## 📄 Additional Certification

This lab is part of the broader **SIEM Search Expressions in a SIEM** series. The certificate earned for mastering DQL search syntax & SIEM query logic is included here due to its strong relevance to the Wazuh search filters & log analysis exercises.

<img src="../Certificates/cybrary-cert-search-expressions-in-a-siem.png" width="500"/>

[🔗 View PDF Certificate – Search Expressions in a SIEM](../Certificates/cybrary-cert-search-expressions-in-a-siem.pdf)

