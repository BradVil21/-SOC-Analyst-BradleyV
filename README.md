# SOC Analyst 🔎

[Introduction: This GitHub repository is a collection of hands-on projects that showcase my skills and experience in <b>Security Operations Center (SOC)</b> analysis. These projects are designed to reflect real-world scenarios and demonstrate the technical and analytical expertise required to succeed as a <b>SOC Analyst</b>].

What You'll Find Here:
<div>
  <ul>
    <li>Threat Detection & Response: Using Python and security tools to identify and mitigate potential risks.</li>
    <li>Log Analysis: Parsing, filtering, and analyzing logs to uncover suspicious activity and actionable insights.</li>
    <li>Network Traffic Monitoring: Analyzing packets to detect anomalies and secure critical data.</li>
    <li>Incident Response Simulations: Investigating mock breaches and crafting detailed incident reports.</li>
    <li>SIEM Implementation: Setting up and utilizing tools like Splunk and ELK for log aggregation and monitoring.</li>
    </ul>
</div>

These projects reflect my dedication to building a career in cybersecurity and my ability to apply industry best practices to protect and defend systems against evolving threats.

Feel free to explore, provide feedback, and reach out via <a href="https://www.linkedin.com/in/bradley-vilsaint-414329267/">Linkedin</a> or Email if you’d like to collaborate or discuss my work. To avoid my email from getting leaked, please view my LinkedIn profile.
<br>
# Phishing Email Detection and Analysis ✉️
<b>Project Description:</b>
In this project, I leverage the Let's Defend SOC platform to simulate and analyze real-world phishing email incidents. The goal is to demonstrate my ability to identify, investigate, and mitigate phishing threats as part of a proactive security operations workflow.
<div>
  <b>Objectives:</b>
  <ul>
      <li>When was it sent?</li>
      <li>What is the email's SMTP address?</li>
      <li>What is the sender's address?</li>
      <li>What is the recipient's address?</li>
      <li>Is the mail content suspicious?</li> 
      <li>Are there any attachments?</li> 
  </ul>
  To view: Install .docx <b></b><a href="">Phishing Email Detection</a></b> PLEASE VIEW DOCUMENT ATTACHED TO THIS REPOSITORY. 
</div>
<br>
<b>Summary:</b> 
As a result of the sandbox analysis of the Excel file attached to the e-mail, it is seen that it is harmful. In the sandbox analysis, c2 addresses are obtained. When c2 addresses are searched through log management, it is seen that there is access, therefore it is understood that the malicious Excel file is run. When the source address is determined on Log Management and searched on Endpoint Management, it is observed that it is a LarsPRD device. When the Browser History and Network Connections of the LarsPRD device are examined, it has been clarified that the LarsPRD device communicates with malicious addresses. When LarsPRD's CMD History is examined, it is observed that the regsvr32 command, which is included in Excel 4.0 macros, is run. <b>This alert was closed as a True Positive.</b><br>

# Phishing URL Detection 🛜
<b>Project Description:</b>
This project my work on implementing a phishing alert detection system using the Let's Defend platform. Let's Defend is an open-source Security Operations Center (SOC) platform for incident response and threat detection. In this project, I focused on detecting phishing alerts by integrating threat intelligence, analyzing suspicious emails, and leveraging automated detection mechanisms within Let's Defend. The primary goal was to identify phishing attempts in real-time by evaluating various indicators, such as Suspicious URLs and domains, Email header anomalies, Malicious attachments or links, and Behavioral analysis of phishing attempts
<div>
  <b>Objectives:</b>
  <ul>
    <li>When was it accessed?</li>
    <li>What is the source address?</li>
    <li>What is the destination address?</li>
    <li>Which user tried to access?</li>
    <li>What is the User Agent?</li>
    <li>Is the request blocked?</li>
  </ul>
  To view: Head over to this repository <b></b><a href="https://github.com/BradVil21/LetsDefend-Phishing-Detection/tree/main">Phishing URL Detection</a></b>
</div>
<br>
<b>Summary:</b> 
After thoroughly investigating the alert, I discovered that the user, identified as "Ellie" under the account "EmilyComp," had accessed several suspicious links. To ensure a comprehensive analysis, I conducted due diligence by inputting the provided links into third-party URL detection tools. These tools confirmed that each link was associated with malicious activity, specifically categorizing them as either malware or phishing URLs. As a result of this confirmation, I took immediate action to contain the affected device and prevent any further security threats. I then escalated the alert, classifying it as a true positive, meaning that it was a legitimate security threat. <b>This alert was closed as a True Positive.</b><br>




