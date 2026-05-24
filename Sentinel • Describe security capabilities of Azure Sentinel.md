<h1  align="center"><a href="https://learn.microsoft.com/api/achievements/share/en-us/RosanaFSS/9AW3DNXU?sharingId=932A0CC7C9841E29">Describe security capabilities of Azure Sentinel</a></h1>
<p align="center"><img width="600px" src="https://github.com/user-attachments/assets/b59828d4-50d3-4050-b322-78952c73732a"><br>If you find it helpful, consider coming back for research.<br><p align="center"><a href="https://githubhttps://github.com/user-attachments/assets/f9d56f26-bf87-4309-b5d8-f98cbb0302b0com/RosanaFSS"><img src="https://img.shields.io/github/followers/RosanaFSS?label=Follow&style=for-the-badge&logo=github&color=24292e" alt="Follow Rosana on GitHub"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/COMPLETED-2026%2C%20MAY%2024-444444?style=for-the-badge&logo=calendar-check" alt="Completion Date"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://www.linkedin.com/in/rosanafssantos/"><img src="https://img.shields.io/badge/Connect-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"></a></p><br>

```
Today's threat landscape is more sophisticated than ever because threat actors are using AI to automate and scale their attacks.
AI/ML capabilities in SIEM & SOAR solutions come into play to help security teams detect these sophisticated threats, cut the noise, and respond accurately and faster than manual processes allow.
```

```
SIEM (Security Information and Event Management) systems provides the visibility needed to detect threats across the entire environment. They:
▪  aggregate logs:        gathering log data and security events from many sources and consolidates them into a single platform.
▪  correlate:             analysing collected data to look for patterns, relationships, and anomalies that might indicate a threat.
▪  alert:                 generate alerts for suspicious activity.
▪  create incidents:      group related alerts automatically into incidents.
▪  surface threats:       provide a centralized view of security activity across the entire organization.
```

```
SOAR (Security Orchestration, Automation, and Response) systems SOAR provides the automation to respond to those threats quickly and consistently through the use of playbooks with predefined sequence a of automated actions triggered by specific alerts or incident types. SOAR can connect different security tools and systems to work together (Orchestration) automatically (Automation). Can be triggered i.e. when a user account sign-in activity is flagged as suspicious:
▪  disable the Account.
▪  send a Notification to the security team.
▪  open an Incident Ticket in the help desk system.
▪  gather additional Context about the user's recent activity.
```

```
SIEM & SOAR together delivers:
▪  a single source of data and context for security events across the enterprise.
▪  automated responses that reduce the time between detecting a threat and containing it.
▪  consistent, repeatable processes for common threat scenarios, reducing the chance of human error.
▪  more time for security analysts to focus on complex investigations that require human judgment.
```

```
Microsoft Sentinel
As a SIEM Microsoft Sentinel provides a unified view of threats across the entire enterprise and supports across:
Ⓞ  Collection     : Built-in and custom connectors normalize data and provide a uniform view.
Ⓞ  Detection      : Analytics rules, AI-powered detections, and grouping related alerts into incidents minimize false positives.
                     Three approaches for detection:
                     - Rule-based detection
                     - AI/ML detection
                     - Threat intelligence matching
Ⓞ  Investigation  : AI-assisted tools and proactive threat hunting understand the full scope of an attack and find its root cause.
Ⓞ  Response       : Built-in orchestration & automation lead to rapid incident response limiting the impact of threats without requiring manual intervention.
```

```
Microsoft Sentinel
Microsoft Sentinel provides an extensible security platform comprised of:
▪  data lake
▪  graph
▪  MCP server
```

```
Microsoft Sentinel integrates with Microsoft Security Copilot to bring AI-assisted capabilities directly into security operations workflows. Rather than replacing analyst judgment, the integration surfaces relevant context faster—so your team can investigate and respond to threats more efficiently.

How the integration works
The integration between Microsoft Sentinel and Security Copilot works across two experiences:

The embedded experience in the Microsoft Defender portal: Because Microsoft Sentinel incidents are unified with Microsoft Defender XDR incidents in the Defender portal, Security Copilot capabilities are available for any incident—including those that originate in Microsoft Sentinel. Analysts can summarize incidents, analyze scripts, assess suspicious files, and generate reports without leaving the portal.
The standalone Security Copilot experience: Security Copilot connects to Microsoft Sentinel as a data source through two plugins—Microsoft Sentinel and Natural language to KQL for Microsoft Sentinel. These plugins allow analysts to ask questions about incidents and data in a conversational, chat-based interface.

Security Copilot capabilities in the Defender portal
When Microsoft Sentinel is onboarded to the Defender portal, the following Security Copilot capabilities are available for Microsoft Sentinel incidents and data.
Ⓞ   Incident summarization
Ⓞ   Guided responses
Ⓞ   Script and command-line analysis
Ⓞ   File analysis
Ⓞ   Identity and device summarization
Ⓞ   Incident report generation
Ⓞ   Natural language to KQL for threat hunting
```

```
Threat Intelligence: Security Copilot consolidates and summarizes threat intelligence to help security teams understand which threats are most relevant to their environment. Analysts can ask Copilot to summarize threats based on their organization's exposure levels or find threat actors that might target their industry.

AI agents: Security Copilot includes autonomous AI agents that operate in the background. For Microsoft Sentinel, the most relevant is the Dynamic Threat Detection Agent—an always-on service that uses AI to correlate alerts, events, anomalies, and threat intelligence across Microsoft Defender and Microsoft Sentinel environments. When it identifies a threat that traditional rule-based detection missed, it generates a dynamic alert with full context, natural language explanations, mapped MITRE ATT&CK techniques, and recommended remediation steps.

The standalone experience: In the standalone Security Copilot portal, the Microsoft Sentinel plugin lets analysts interact with their security data conversationally. Analysts can ask questions like "What are the top five high priority Microsoft Sentinel incidents?" or "Tell me about the entities associated with that incident." The Microsoft Sentinel incident investigation promptbook assembles a sequence of prompts automatically—retrieving the incident report, related alerts, reputation scores, and details about users and devices involved—giving analysts a structured starting point.

Why this integration matters
Security operations teams deal with high volumes of alerts, complex investigations, and time pressure. The integration of Microsoft Sentinel with Security Copilot helps address those challenges by:

Reducing investigation time: AI-generated summaries, script analysis, and file analysis help analysts understand incidents in minutes rather than hours.
Making hunting more accessible: Natural language queries remove a technical barrier, enabling analysts who aren't KQL experts to participate in proactive threat detection.
Streamlining documentation: Automated incident reports save time on post-investigation paperwork.
Keeping humans in control: Security Copilot provides suggestions and surfaces information—analysts make the final decisions.
```

<p align="center"><img width="600px" src="https://github.com/user-attachments/assets/20248186-48e9-41c6-8b34-4a8bcd469d1b"><br>
                  <img width="600px" src="https://github.com/user-attachments/assets/2566f9a6-90fe-483d-a7c7-d2a9a7239212"></p>

```
In this module, you learned about security information and event management (SIEM) and security orchestration, automation, and response (SOAR)—the two foundational technologies behind modern security operations centers. You explored how AI and machine learning are increasingly central to SIEM/SOAR, helping security teams detect sophisticated threats, reduce alert fatigue, and respond faster. You then discovered the key capabilities Microsoft Sentinel provides, including data collection, AI-powered threat detection, investigation, automated response, and the Content hub. Finally, you learned about Microsoft Security Copilot—a generative AI-powered security assistant—and how it integrates with Microsoft Sentinel through plugins in the standalone experience and the embedded Copilot experience in the Microsoft Defender portal.

Now that you've completed this module, you're able to:

Define the concepts of SIEM and SOAR, and describe the role of AI in modern security operations.
Describe how Microsoft Sentinel provides threat detection and mitigation capabilities.
Describe Microsoft Security Copilot and how it integrates with Microsoft Sentinel.
```

