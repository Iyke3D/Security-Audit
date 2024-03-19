# Security-Audit
Google Cybersecurity Training Portfolio - Conduct a Security Audit 
<p>Security Audits are sets of reviews which are required to know whether the organization
meets policies, procedures and controls.</p>
<p>It is essential to have both internal and external audit in place as it will help to monitor 
threats, risks or vulnerabilities that the organization may face.</p>
<p>Consider the following scenario:</p></br>
<p><strong>Synopsis</strong></p>
<p>Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

<strong>Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.</strong> </p>
<p>The IT Manager also has also added the current assets (to protect from threat actors) and additional comments as shown below:</p>
<p><strong>Current assets</strong></p>
<p>Assets managed by the IT Department include:
<ol>
<li>On-premises equipment for in-office business needs</li>
<li>Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.</li>
<li>Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse</li>
<li>Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management</li>
<li>Internet access</li>
<li>Internal network</li>
<li>Data retention and storage</li>
<li>Legacy system maintenance: end-of-life systems that require human monitoring</li>
</ol>
</p>
<p><strong>Additional comments</strong>
The potential impact from the loss of an asset is rated as medium, because the IT
department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because <i><b>Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure.</b></i> Review the following bullet points for
specific details:
<ol>
<li>Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.</li> 
<li>Encryption is not currently used to ensure confidentiality of customers’ credit
card information that is accepted, processed, transmitted, and stored locally in
the company’s internal database.</li>
<li>Access controls pertaining to least privilege and separation of duties have not
been implemented.</li>
<li>The IT department has ensured availability and integrated controls to ensure
data integrity.</li>
<li>The IT department has a firewall that blocks traffic based on an appropriately
defined set of security rules.</li>
<li>Antivirus software is installed and monitored regularly by the IT department.</li>
<li>The IT department has not installed an intrusion detection system (IDS).</li>
<li>There are no disaster recovery plans currently in place, and the company does
not have backups of critical data.</li>
<li>The IT department has established a plan to notify E.U. customers within 72
hours if there is a security breach. Additionally, privacy policies, procedures, and
processes have been developed and are enforced among IT department
members/other employees, to properly document and maintain data.</li>
<li>Although a password policy exists, its requirements are nominal and not in line
with current minimum password complexity requirements (e.g., at least eight
characters, a combination of letters and at least one number; special
characters).</li>
<li>There is no centralized password management system that enforces the
password policy’s minimum requirements, which sometimes affects
productivity when employees/vendors submit a ticket to the IT department to
recover or reset a password.</li>
<li>While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.</li>
<li>The store’s physical location, which includes Botium Toys’ main offices, store
front, and warehouse of products, has sufficient locks, up-to-date
closed-circuit television (CCTV) surveillance, as well as functioning fire
detection and prevention systems.</li></ol></p>
<p><strong>Recommendations</strong></p>
<p>After assessing the current risk layed out by the IT Manager at Botium Toys, it is obvious that no proper security controls are in place. Consequently, internal and external security controls should be implemented.</p> <p><b>Firstly</b>, the Principle of Least Priviledge and Separation of Duties should be enforced in the organization. This should limit access to customer's data to only those who are responsible to handle such data e.g. Accounting department.</p>
<p><b>Secondly</b>, a password policy must be adhered to and 2FA (2 Factor Authentication) which each employee must have within the working environment.</p>
<p><b>Thirdly</b>, encryption techniques should be employed in the web application design process where each customer's data must be saved properly using <i><b>AES 256-bit encryption</b></i> both during online transactions and in the database management systems storing their data.</p>
<p><b>Finally</b>, compliance procedures and strategies must be created and followed thoroughly to avoid any fines both now and in the future. The NIST CSF and the GDPR best practices must be applied during this process.</p>

