Final Security Assessment Report

Assessment Scope

Target: Metasploitable2

Assessment Type: Vulnerability Assessment and Validation

Testing Platform: Kali Linux

. Methodology

The assessment followed a structured methodology:

1. Environment Setup
2. Network Reconnaissance
3. Service Enumeration
4. Vulnerability Scanning
5. Vulnerability Validation
6. Risk Assessment
7. Reporting

. Key Findings

. Finding 1: Anonymous FTP Access

. Description:
The FTP service allowed authentication using anonymous credentials.

. Impact:
Unauthorized users may access exposed resources.

. Recommendation:
Disable anonymous FTP authentication and enforce user-based access controls.

. Finding 2: SMB Share Exposure

. Description:
SMB resources were discoverable and accessible.

. Impact:
Sensitive information may be exposed to unauthorized users.

. Recommendation:
Restrict SMB access and apply the principle of least privilege.

. Finding 3: Outdated Services

. Description:
Multiple legacy services were identified during enumeration.

. Impact:
Older software versions may contain publicly known vulnerabilities.

. Recommendation:
Update all services to supported versions and implement patch management.

Overall Risk Assessment

Risk Level: Medium

The target environment contains multiple weaknesses that increase attack surface and facilitate reconnaissance and unauthorized access activities.

. Conclusion

The assessment successfully identified and validated several security weaknesses within the target environment. Implementing the recommended remediation measures would significantly reduce the risk of exploitation and improve the overall security posture of the system.

Skills Demonstrated

- Vulnerability Assessment
- Penetration Testing Methodology
- Service Enumeration
- Vulnerability Validation
- Risk Analysis
- Security Reporting
- Linux Administration
- Network Analysis