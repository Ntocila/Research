
# What is Web Security? 

Security is fundamentally about protecting assets. Assets may be tangible items, such as a Web page or your customer database — or they may be less tangible, such as your company's reputation. Security is a path, not a destination. As you analyze your infrastructure and applications, you identify potential threats and understand that each threat presents a degree of risk. Security is about risk management and implementing effective countermeasures.

# The Foundations of Security
Security relies on the following elements:

## Authentication

Authentication addresses the question: who are you? It is the process of uniquely identifying the clients of your applications and services. These might be end users, other services, processes, or computers. In security parlance, authenticated clients are referred to as principals.

## Authorization

Authorization addresses the question: what can you do? It is the process that governs the resources and operations that the authenticated client is permitted to access. Resources include files, databases, tables, rows, and so on, together with system-level resources such as registry keys and configuration data. Operations include performing transactions such as purchasing a product, transferring money from one account to another, or increasing a customer's credit rating.

## Auditing

Effective auditing and logging is the key to non-repudiation. Non-repudiation guarantees that a user cannot deny performing an operation or initiating a transaction. For example, in an e-commerce system, non-repudiation mechanisms are required to make sure that a consumer cannot deny ordering 100 copies of a particular book.

## Confidentiality

Confidentiality, also referred to as privacy, is the process of making sure that data remains private and confidential, and that it cannot be viewed by unauthorized users or eavesdroppers who monitor the flow of traffic across a network. Encryption is frequently used to enforce confidentiality. Access control lists (ACLs) are another means of enforcing confidentiality.

## Integrity

Integrity is the guarantee that data is protected from accidental or deliberate (malicious) modification. Like privacy, integrity is a key concern, particularly for data passed across networks. Integrity for data in transit is typically provided by using hashing techniques and message authentication codes.

## Availability

From a security perspective, availability means that systems remain available for legitimate users. The goal for many attackers with denial of service attacks is to crash an application or to make sure that it is sufficiently overwhelmed so that other users cannot access the application.

# What Are The Most Known Security threats?
The majority of web application attacks occur through cross-site scripting (XSS) and SQL injection attacks[2] which typically are made possible by flawed coding and failure to sanitize application inputs and outputs. These attacks are ranked in the 2009 CWE/SANS Top 25 Most Dangerous Programming Errors.[3]

* 37%	Cross-site scripting
* 16%	SQL injection
* 5%	Path disclosure
* 5%	Denial-of-service attack
* 4%	Arbitrary code execution
* 4%	Memory corruption
* 4%	Cross-site request forgery
* 3%	Data breach (information disclosure)
* 3%	Arbitrary file inclusion
* 2%	Local file inclusion
* 1%	Remote file inclusion
* 1%	Buffer overflow
* 15%	Other, including code injection (PHP/JavaScript), etc.
<br/>


## OWASP 

The Open Web Application Security Project (OWASP) provides free and open resources. It is led by a non-profit called The OWASP Foundation. The OWASP Top 10 - 2017 is the published result of recent research based on comprehensive data compiled from over 40 partner organizations. From this data, approximately 2.3 million vulnerabilities were discovered across over 50,000 applications.[5] According to the OWASP Top 10 - 2017, the ten most critical web application security risks include:[6]

* Injection
* Broken authentication
* Sensitive data exposure
* XML external entities (XXE)
* Broken access control
* Security misconfiguration
* Cross-site scripting (XSS)
* Insecure deserialization
* Using components with known vulnerabilities
* Insufficient logging and monitoring


<br/>
<br/>
<br/>
<br/>

## References
<a id="1">[1]</a> 
Microsoft Patterns & Practices 07/14/2010
https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff648636(v=pandp.10)?redirectedfrom=MSDN#what-do-we-mean-by-security

<a id="2">[2]</a> 
Wikipedia 27 May 2021 
https://en.wikipedia.org/wiki/Web_application_security

