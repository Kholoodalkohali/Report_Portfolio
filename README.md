# Report_Portfolio
## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company specializing in personalized financial plans. They required secure and modernized operations for their RESTful web API. The primary issues addressed were securing sensitive financial data, complying with international data protection regulations like GDPR, and mitigating external threats such as SQL injection and cross-site scripting (XSS).

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

We systematically identified vulnerabilities through manual code reviews and static testing. Secure coding practices are crucial as they prevent potential exploits and breaches, ensuring data integrity, customer trust, and regulatory compliance. Software security enhances a company's overall well-being by safeguarding sensitive information, maintaining operational continuity, and protecting against financial and reputational damage.

## Which part of the vulnerability assessment was challenging or helpful to you?

The manual code review was both challenging and beneficial. It required deep understanding of the codebase and potential attack vectors. However, it was invaluable in uncovering nuanced vulnerabilities that automated tools might miss, thereby providing a comprehensive security assessment.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

We enhanced security by implementing measures such as input validation, API authentication, encryption, and access controls. In the future, leveraging a combination of automated tools (like dependency checks and vulnerability scanners) alongside manual code reviews will be essential. These approaches ensure a thorough assessment and enable tailored mitigation strategies based on specific vulnerabilities identified.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Post-refactoring, rigorous testing was conducted, including functional testing to ensure the application behaved as expected and security testing to validate the effectiveness of implemented safeguards. Automated regression testing and manual inspection of code changes helped verify that no new vulnerabilities were introduced.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Tools such as OWASP Java Encoder for input sanitization, dependency-check for identifying vulnerable libraries, and secure coding guidelines from OWASP were instrumental. Practices like continuous integration (CI) with security checks integrated into the build pipeline ensured ongoing vigilance against vulnerabilities.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I would showcase:

 - The comprehensive vulnerability assessment report highlighting critical findings and mitigation strategies.
 - Demonstrations of improved security posture through before-and-after comparisons.
 - Evidence of applying secure coding practices and industry-standard tools to enhance software security.
 - Insights into managing complex security challenges in a regulated industry, ensuring compliance and data protection.
