#1. Introduction
I am beginning my cybersecurity learning journey by studying some of the fundamental concepts used in information security.

One of the first concepts I am learning is the CIA Triad.

The CIA Triad is a fundamental security model consisting of three principles:
• Confidentiality
• Integrity
• Availability
These principles help security professionals understand what needs to be protected when securing information and information systems.

##2. What is Cybersecurity?
Cybersecurity is the practice of protecting computers, networks, applications, devices, systems, and data from unauthorized access, misuse, damage, disruption, or theft.

Examples of assets that may need protection include:
• Personal information
• Passwords
• Financial information
• Databases
• Computer systems
• Networks
• Applications
• Cloud services
___
#3. The CIA Triad
The CIA Triad consist of:
a. C- confidentiality
b. I- integrity
c. A- Availability

#1. Confidentiality
Definition
Confidentiality means ensuring that information is accessible only to authorized individuals, systems, or processes.

In simple terms:
Confidentiality means preventing unauthorized people from accessing or viewing information.

Example:
A student's academic records should only be accessible to the student and authorized university staff.
An attacker who obtains the student's password and accesses their records would be a violation of confidentiality.

##Threats to Confidentiality
Examples include:
• Phishing - An attacker tricks a user into revealing sensitive information such as passwords or account credentials.
• Password theft - An attacker obtains a user's password and uses it to access protected information.
• Data breaches - Unauthorized individuals gain access to sensitive organizational or personal data.
• Eavesdropping - An attacker secretly monitors communications to obtain information.
• Social Engineering: An attacker manipulates a person into revealing confidential information or granting access.
• Spyware: Malicious software secretly monitors a user's activity or collects sensitive information.
• Unauthorized Access: An individual accesses a system, account, or database without permission.
• Shoulder Surfing: An attacker observes someone entering sensitive information, such as a password or PIN.
• Lost or Stolen Devices: A lost or stolen laptop, phone, or storage device may expose sensitive information stored on it.

Example:
An attacker sends a student a fake university login page. The student enters their username and password, which are then sent to the attacker. The attacker can now potentially access the student's academic information.
CIA principle affected: Confidentiality.


Key Question
Who is allowed to see this information?

Protecting Confidentiality
The goal is to prevent unauthorized people from accessing or viewing sensitive information.
Common controls

1. Strong Passwords
Users should use long, unique passwords that are difficult to guess.
Example:
Instead of:
password123
Use a strong, unique passphrase such as:
Blue-River!Coffee-72-Moon

2. Multi-Factor Authentication (MFA)
MFA requires users to provide more than one form of authentication.
For example:
Password + authenticator app code
Even if an attacker steals the password, they may still be unable to access the account.
Protects: Confidentiality

3. Encryption
Encryption converts readable information (plaintext) into an unreadable form (ciphertext) that can only be properly interpreted using the appropriate key.
For example:
Student Grade: A
↓ Encryption
8fK@92xL...
Encryption can protect data:
At rest — data stored on devices/databases
In transit — data moving across networks
Protects: Mainly Confidentiality

4. Access Control
Users should only have access to the information they actually need.
For example:
A university receptionist may need access to student contact information but may not need permission to modify examination grades.
This is related to the principle of least privilege:
Give users only the permissions necessary to perform their jobs.

5. Network Segmentation
A network can be divided into separate sections so that access to one area does not automatically provide access to everything else.
For example:
Student Network → Web Servers → Database Servers
If an attacker compromises one section, segmentation can make it harder to reach sensitive systems.

6. Security Awareness Training
Employees should be trained to recognize:
Phishing emails
Fake login pages
Social engineering
Suspicious attachments
Malicious links
This is especially important because humans can be targeted by attackers.


2. Integrity
Definition
Integrity means ensuring that information remains accurate, complete, trustworthy, and protected from unauthorized modification.

In simple terms:
Integrity means making sure information has not been improperly changed.

Example
Suppose a university database records a student's grade as:
Grade: A
If an unauthorized person changes it to:
Grade: F
the integrity of the information has been compromised.

Threats to Integrity
Examples include:
• Unauthorized Modification: Someone changes information without permission.
• Database Manipulation: An attacker modifies records stored in a database.
• Malware: Malicious software may modify, delete, or corrupt files.
• Man-in-the-Middle Attacks: An attacker intercepts communication and may alter information while it is being transmitted.
• Insider Threats: An authorized employee intentionally or accidentally modifies information improperly.
• Data Corruption: Information becomes inaccurate or damaged because of technical problems, malware, or other causes.
• Website Defacement: An attacker gains access to a website and changes its content.
• Unauthorized Transactions: An attacker modifies financial or transaction information without authorization.

Examples include:
Hashing
Digital signatures
Access controls
File permissions
Version control
Audit logs
Backups

Key Question
Can I trust that this information is accurate and has not been improperly changed?

Protecting Integrity
The goal is to ensure that information remains accurate, complete, and trustworthy.
Common controls
1. Hashing
A cryptographic hash can be used to detect whether data has been changed.
For example:
Original file → Hash → A81F...
If the file is modified:
Modified file → Hash → 93BC...
The different hash values indicate that the data has changed.
Important: Hashing is generally used for integrity verification, not for keeping data secret.

2. Digital Signatures
Digital signatures can help verify:
Who created/signed the information
Whether the information was modified after signing
They therefore provide important integrity and authenticity protections.

3. Access Controls and Permissions
Users should not have permission to modify information unless their job requires it.
For example:
A student might be allowed to view their grade but should not have permission to change it.

4. Audit Logs
Systems should record important activities such as:
Who logged in?
What did they access?
What did they change?
When did they change it?
If someone's grade is changed, an audit log may help investigators determine:
Who changed it, when, and from which account/system?
This is extremely important in security investigations and SOC environments.

5. Version Control
Organizations can maintain previous versions of important files or configurations.
If an unauthorized change occurs, security teams may be able to identify the change and restore the previous version.

6. Backups
Regular backups allow organizations to recover from:
Data corruption
Malware
Ransomware
Accidental deletion
Hardware failures
Backups are therefore important for both Integrity and Availability.


C. Availability
Definition

Availability means ensuring that authorized users can access information and systems when they need them.

In simple terms:
Availability means keeping systems and information accessible to authorized users when required.

Example
If a university student portal becomes unavailable during course registration, students may be unable to register for their courses.
This is an availability problem.

Threats to Availability
Examples include:
• Distributed Denial-of-Service (DDoS) Attacks: Attackers overwhelm a system or server with traffic, making it difficult or impossible for legitimate users to access it.
• Ransomware: Malicious software encrypts files or systems, preventing legitimate users from accessing them.
• Hardware Failure: Failure of servers, storage devices, or other hardware can make systems unavailable.
• Power Outages: Loss of electricity can cause systems and services to become unavailable.
• Network Failures: Problems with network infrastructure can prevent users from accessing systems.
• Server Crashes: A server failure can cause applications and services to stop working.
• Natural Disasters: Floods, fires, earthquakes, and other disasters can damage infrastructure.
• Resource Exhaustion: Excessive use of CPU, memory, storage, or other resources can cause a system to become unavailable.

Key Question
Can authorized users access the system when they need it?

Protecting Availability
The goal is to ensure that authorized users can access systems and information when they need them.
Common controls

1. Backups
Organizations should maintain reliable backups of important data.
A good backup strategy helps an organization recover after:
Ransomware → Data loss → Recovery from backup

2. Redundancy
Organizations can use multiple servers, storage systems, network connections, or other components.
If one fails:
Server A 
↓
Server B continues operating 
This reduces the impact of individual failures.

3. Failover Systems
A failover system automatically switches to another system when the primary system fails.
For example:
Primary Server → Failure 
↓
Backup Server → Takes over 

4. Load Balancing
A load balancer distributes traffic across multiple servers.
Instead of:
10,000 users → One server
Traffic can be distributed:
10,000 users
↓
Server A
Server B
Server C
Server D
This can improve performance and resilience.

5. DDoS Protection
Organizations can use DDoS protection services and network controls to detect and mitigate malicious traffic.
The goal is to prevent attackers from overwhelming the organization's systems.
6. Disaster Recovery
Organizations should have a plan for recovering systems after major incidents such as:
Cyberattacks
Fires
Floods
Power failures
Hardware failures
A disaster recovery plan answers questions such as:
What systems need to be restored first?
Where will systems be restored?
How quickly should they be restored?

7. System Monitoring
Security and IT teams monitor systems for problems such as:
High CPU usage
High memory usage
Network failures
Server crashes
Unusual traffic
Service outages
Early detection allows teams to respond before a small problem becomes a major outage.

A simple way I remember the CIA Triad is:
CONFIDENTIALITY → SEE
INTEGRITY → TRUST
AVAILABILITY → ACCESS

Threats Can Affect More Than One CIA Principle
It is important to understand that an attack does not always affect only one part of the CIA Triad.
For example, ransomware can affect all three principles.
• Confidentiality
If attackers steal sensitive files before encrypting them, confidential information may be exposed.
• Integrity
The attackers modify or encrypt the original files, meaning the information has been altered without authorization.
• Availability
Users can no longer access their files because they have been encrypted.
Therefore, a single ransomware incident can potentially affect:
• Confidentiality + Integrity + Availability
This is why cybersecurity professionals need to examine an incident carefully rather than automatically assigning an attack to only one category.



Real-World Example: University Student Portal

Consider an online university student portal containing:
Student names
Grades
Course information
Fee information
Personal information
Confidentiality
Only authorized users should be able to view private student information.

Integrity
Grades, fee balances, and other records should not be changed without authorization.

Availability
Students and authorized staff should be able to access the portal when they need it.

Therefore, a secure student portal needs all three elements of the CIA Triad.

9. Why the CIA Triad Matters
The CIA Triad provides a simple way to think about information security.
When analyzing a system or security incident, I can ask:
Was information exposed to someone who shouldn't see it?

Confidentiality
Was information changed or corrupted without authorization?

Integrity
Was a system or information made unavailable to authorized users?

Availability
This gives me a basic framework for understanding different cybersecurity threats and security controls.

10. What I Learned Today
• Today I learned that cybersecurity is not only about preventing hackers from breaking into systems.

• I learned that protecting information involves three major goals:

• Keeping information private (Confidentiality)

• Keeping information accurate and trustworthy (Integrity)

• Keeping systems and information accessible (Availability)
I also learned that different attacks can affect different parts of the CIA Triad.

My Key Takeaway
The easiest way for me to remember the CIA Triad is:

Confidentiality — Who can see it?
Integrity — Can I trust it?
Availability — Can I access it?

• Threats to information systems can compromise the confidentiality, integrity, availability, or even multiple principles of the CIA Triad simultaneously.
• Understanding these threats is important because cybersecurity professionals must be able to identify what is being attacked, how it is being affected, and which security controls can reduce the risk.
• This provides a foundation for understanding more advanced cybersecurity areas such as incident response, vulnerability management, threat detection, security monitoring, and SOC analysis.


Questions I Want to Explore Next
• How does encryption protect confidentiality?
• How does hashing help protect integrity?
• What is the difference between hashing and encryption?
• How do organizations maintain availability?
• How do cybersecurity professionals identify which part of the CIA Triad has been affected during an attack?
• How does the CIA Triad apply to a SOC Analyst's work?


 Authentication, Authorization & Accounting (AAA)
Topic: Authentication, Authorization & Accounting
Focus: Identity, permissions, and activity tracking

1. Introduction
After learning about the CIA Triad, I am now learning about Authentication, Authorization, and Accounting (AAA).
AAA is an important concept in cybersecurity because organizations need to determine:
•	Who is accessing a system
•	What that user is allowed to do
•	What activities the user performed
The three components are:
•	Authentication
•	Authorization
•	Accounting

2. Authentication
Authentication is the process of verifying the identity of a user, device, or system.
In simple terms:
Authentication answers: "Who are you?"
Examples of authentication methods include:
•	Passwords
•	PINs
•	Security keys
•	Authentication tokens
•	Fingerprints
•	Facial recognition
Authentication Factors
Authentication factors can include:
Factor	Meaning	Example
Something you know	Information you know	Password
Something you have	Something you possess	Phone/security key
Something you are	A biological characteristic	Fingerprint

3. Multi-Factor Authentication
Multi-Factor Authentication (MFA) requires two or more different authentication factors.
For example:
Password
    +
Authenticator code
    ↓
Access granted
The password represents something the user knows, while the authenticator device represents something the user has.
MFA provides additional protection if a password is compromised.

4. Authorization
Authorization determines what an authenticated user is allowed to access or perform.
In simple terms:
Authorization answers: "What are you allowed to do?"
For example, a university student may be allowed to:
•	View their grades
•	Register for courses
•	View their profile
But they should not be allowed to:
•	Modify another student's grades
•	Delete university records
•	Access administrator functions

5. Authentication vs Authorization
Authentication	Authorization
Who are you?	What can you do?
Verifies identity	Determines permissions
Uses credentials or biometric factors	Uses roles, permissions, and policies
A user must normally be authenticated before the system can determine what they are authorized to access.

6. Principle of Least Privilege
The Principle of Least Privilege means giving users, applications, and systems only the permissions necessary to perform their required tasks.
For example, a receptionist may need access to an appointment system but should not automatically have access to payroll or security administration systems.
The goal is to reduce the damage that could occur if an account is compromised.

7. Accounting
Accounting involves recording and tracking activities performed by users or systems.
It can also be referred to as auditing.
In simple terms:
Accounting answers: "What did you do?"
Examples of information that may be recorded include:
•	Login times
•	Logout times
•	User accounts
•	IP addresses
•	Files accessed
•	Actions performed
•	System changes
These records can be useful when investigating security incidents.

8. Why Accounting Is Important
If an employee's account is compromised, security professionals may use logs to investigate:
•	When the account was accessed
•	Where the login originated
•	What systems were accessed
•	What files were accessed
•	What actions were performed
This makes logging and monitoring important parts of cybersecurity operations.

9. AAA Summary
  A simple way for me to remember AAA is:
Authentication → Identity
Authorization → Permissions
Accounting → Activity

10. Connection to the CIA Triad
AAA supports the goals of the CIA Triad.
Confidentiality
Authentication and authorization help prevent unauthorized people from accessing information.
Integrity
Authorization helps prevent unauthorized users from modifying information.
Availability
Strong access controls can help prevent compromised accounts from being used to disrupt systems.

11. What I Learned Today
o	Today I learned the difference between authentication, authorization, and accounting.
The most important distinction I learned is:
Authentication verifies who you are, authorization determines what you can do, and accounting records what you did.
I also learned about the Principle of Least Privilege and why organizations should avoid giving users unnecessary permissions.

12. Key Takeaway
	AUTHENTICATION → WHO ARE YOU?
	AUTHORIZATION → WHAT CAN YOU DO?
	ACCOUNTING     → WHAT DID YOU DO?

13. Questions I Want to Explore
•	How does MFA work technically?
•	What is the difference between authentication and identification?
•	What are RBAC and ABAC?
•	How are passwords securely stored?
•	What are logs?
•	How does a SOC analyst use authentication logs?
•	What happens when an account is compromised?


 ACCESS CONTROL — Permissions, RBAC & Least Privilege
Topic: Access Control
Focus: Permissions, roles, RBAC, and least privilege

1. Introduction
After learning about Authentication and Authorization, I am now learning how organizations control what authenticated users are allowed to access and perform.
Access control is an important part of cybersecurity because simply identifying a user is not enough. Organizations must also determine what that user is permitted to do.

2. Permissions
A permission defines an action that a user or system is allowed to perform on a resource.
Common permissions include:
•	Read
•	Write
•	Modify
•	Delete
•	Execute
For example, a user may have permission to read a file but not modify or delete it.

3. Roles
A role is a collection of permissions associated with a particular responsibility or job function.
Examples include:
•	Employee
•	Manager
•	HR Administrator
•	SOC Analyst
•	Security Administrator
•	Database Administrator
Roles make it easier for organizations to manage permissions consistently.

4. Role-Based Access Control (RBAC)
RBAC stands for Role-Based Access Control.
With RBAC, permissions are assigned to roles, and users are assigned to those roles.
For example:
User
  ↓
Role
  ↓
Permissions
A SOC Analyst role might have permission to:
•	View security logs
•	Investigate alerts
•	Access security monitoring tools
However, the role may not have permission to modify payroll records or administer every system in the organization.

5. Principle of Least Privilege
The Principle of Least Privilege means giving a user, application, process, or system only the minimum permissions required to perform its intended function.
For example, a SOC analyst may need permission to read security logs but may not need permission to delete them.
Why it matters
If an account with excessive privileges is compromised, an attacker may be able to cause significantly more damage.
Least privilege reduces the potential impact of a compromised account by limiting unnecessary access.

6. Privilege Escalation
Privilege escalation occurs when an attacker gains privileges beyond those they should have.
Vertical Privilege Escalation
An attacker moves from a lower privilege level to a higher one.
Normal User
     ↓
Administrator
Horizontal Privilege Escalation
An attacker accesses another user's resources without necessarily gaining a higher privilege level.
Alice's Account
      ↓
Bob's Account

7. RBAC vs Least Privilege
These concepts are related but different.
RBAC determines permissions based on a user's role.
Least Privilege ensures that users, applications, and systems receive only the minimum permissions necessary.
Both can be used together to reduce unnecessary access.

8. Key Takeaways
I learned that:
•	Permissions define what actions can be performed.
•	Roles group permissions according to responsibilities.
•	RBAC assigns permissions through roles.
•	Least privilege limits access to what is actually necessary.
•	Excessive privileges can increase the impact of a compromised account.
•	Privilege escalation occurs when an attacker obtains unauthorized additional privileges.
Mental Model
Authentication
      ↓
Who are you?
      ↓
Authorization
      ↓
What can you do?
      ↓
Permissions / Roles
      ↓
Least Privilege
      ↓
Only the access you actually need

9. Questions I Want to Explore
•	How does RBAC work in Windows and Linux?
•	What is Attribute-Based Access Control (ABAC)?
•	How are Linux file permissions implemented?
•	What is the difference between a standard user and an administrator?
•	How do attackers exploit excessive privileges?
•	How does privilege escalation happen?
