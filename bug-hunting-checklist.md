# Bug Hunting Checklist

## 1. Understand the Target:
- **Research**: Gather information about the target application, including its purpose, technologies used, and potential attack vectors.
- **Scope**: Determine the scope of your bug hunting activities, including allowed testing areas and prohibited actions.

## 2. Choose Bug Hunting Tools:
- **Burp Suite**: Utilize Burp Suite for intercepting and manipulating web traffic, scanning for vulnerabilities, and analyzing responses.
- **OWASP ZAP**: Employ OWASP ZAP for automated scanning, passive and active vulnerability detection, and manual testing.
- **Nmap**: Conduct network reconnaissance and discover open ports and services using Nmap.
- **Dirb / Dirbuster**: Enumerate directories and files on web servers to discover hidden resources.
- **SQLMap**: Test for SQL injection vulnerabilities by automating the process of detecting and exploiting SQL injection flaws.
- **Metasploit**: Use Metasploit for penetration testing, exploit development, and post-exploitation activities.
- **Sublist3r / Amass / OWASP Amass**: Perform subdomain enumeration to identify additional attack surface.
- **Fuzzing Tools**: Experiment with fuzzing techniques using tools like Radamsa or AFL to identify unexpected behavior or vulnerabilities.

## 3. Perform Reconnaissance:
- **Footprinting**: Gather information about the target organization, its employees, and infrastructure through public sources and social media.
- **Subdomain Enumeration**: Enumerate subdomains using tools like Sublist3r, Amass, or OWASP Amass to identify potential targets.
- **Network Scanning**: Conduct port scanning and service enumeration using Nmap to identify open ports and services.

## 4. Web Application Testing:
- **Authentication Testing**: Test for authentication vulnerabilities such as brute force attacks, weak passwords, and insecure authentication mechanisms.
- **Input Validation Testing**: Test for input validation vulnerabilities such as SQL injection, XSS, CSRF, and command injection.
- **Session Management Testing**: Test for session management vulnerabilities such as session fixation, session hijacking, and insecure session tokens.
- **Error Handling Testing**: Test for error handling vulnerabilities such as information disclosure, stack traces, and verbose error messages.
- **Business Logic Testing**: Test for business logic vulnerabilities such as authorization flaws, insecure direct object references (IDOR), and insecure file uploads.

## 5. Mobile Application Testing (Optional):
- **Static Analysis**: Analyze the source code of mobile applications using tools like MobSF or QARK to identify security issues.
- **Dynamic Analysis**: Intercept and analyze network traffic using Burp Suite or OWASP ZAP to identify vulnerabilities in communication protocols and APIs.
- **Rooting / Jailbreaking**: Root or jailbreak test devices to access and analyze application data stored in insecure locations.

## 6. Reporting and Collaboration:
- **Documentation**: Document your findings in a clear and detailed report, including the steps to reproduce the vulnerability and its potential impact.
- **Responsible Disclosure**: Follow responsible disclosure guidelines when reporting vulnerabilities to organizations, and ensure that sensitive information is handled securely.
- **Collaboration**: Collaborate with other bug hunters and security researchers through bug bounty platforms, forums, and communities to share knowledge and experiences.

## 7. Continuous Learning and Improvement:
- **Stay Updated**: Keep abreast of the latest security vulnerabilities, tools, and techniques by reading blogs, attending conferences, and participating in online courses.
- **Practice Ethical Hacking**: Ensure that your bug hunting activities are legal and ethical, and obtain permission before testing any application or network.
