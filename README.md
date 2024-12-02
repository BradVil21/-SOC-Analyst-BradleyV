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

Feel free to explore, provide feedback, and reach out via <a href="https://www.linkedin.com/in/bradley-vilsaint-414329267/">Linkedin</a> or Email if you’d like to collaborate or discuss my work. To avoid my personal email from getting leaked, please view on my Linkedin profile.
<br>
# Phishing Email Detection and Analysis ✉️
Project Description:
In this project, I leverage the Let's Defend SOC platform to simulate and analyze real-world phishing email incidents. The goal is to demonstrate my ability to identify, investigate, and mitigate phishing threats as part of a proactive security operations workflow.
<div>
  <b>Objectives:</b>
  <ul>
      <li>When was it sent?</li>
      <li>What is the email's SMTP address?</li>
      <li>What is the sender address?</li>
      <li>What is the recipient address?</li>
      <li>Is the mail content suspicious?</li> 
      <li>Are there any attachment?</li> 
  </ul>
  To view: Install .docx <b></b><a href="">Phishing Email Detection</a></b>
</div>
<br>
<b>Summary:</b> 
As a result of the sandbox analysis of the excel file attached to the e-mail, it is seen that it is harmful. In the sandbox analysis, c2 addresses are obtained. When c2 addresses are searched through log management, it is seen that there is access, therefore it is understood that the malicious excel file is run. When the source address is determined on Log Management and searched on Endpoint Management, it is observed that it is a LarsPRD device. When the Browser History and Network Connections of the LarsPRD device are examined, it has been clarified that the LarsPRD device communicates with malicious addresses. When LarsPRD's CMD History is examined, it is observed that the regsvr32 command, which is included in Excel 4.0 macros, is run. <b>This alert was closed as a True Positive.</b>




