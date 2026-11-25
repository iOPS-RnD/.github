# Security Policy

This document outlines the security guidelines and best practices for contributing to and using this project.

## Responsible Disclosure

If you discover a security vulnerability, please **do not** report it publicly. Instead, follow the responsible disclosure process:

1.  **Report the issue** privately through GitHub private vulnerability reporting: open the **Security** tab of the affected repository and select **Report a vulnerability**.
2.  Provide a detailed description, including:
    - Steps to reproduce the issue.
    - Potential impact.
    - Any recommended mitigation steps.
3.  We will acknowledge receipt of your report and work towards a resolution as soon as possible.

## Handling of Sensitive Information

This repository shall **not** contain or disclose information whose handling is restricted by law, regulation or contract, such as security-sensitive information about critical infrastructure. Contributors must ensure that:

- No confidential infrastructure details are shared.
- No sensitive operational data is included in public discussions.
- No security credentials, API keys, or access details are exposed.

For example:

- **kraftsensitiv informasjon** (power-sensitive information) is regulated under Norwegian law, including:
  - [Forskrift om sikkerhet og beredskap i kraftforsyningen](https://webfileservice.nve.no/API/PublishedFiles/Download/5690526d-60af-4cd5-b7fc-51c87cb66f48/202119965/3425769) (Kraftberedskapsforskriften, the Power Contingency Regulation): governed by the Norwegian Water Resources and Energy Directorate (NVE)
  - [NVE Report on ICT Security in the Power Sector](https://publikasjoner.nve.no/rapport/2017/rapport2017_26.pdf): covers encryption and secure handling of power-sensitive data

## Security Best Practices

To ensure a secure development environment, adhere to the following:

- Follow **secure coding principles** to prevent vulnerabilities.
- Regularly update dependencies to mitigate security risks.
- Use **strong authentication mechanisms** when accessing infrastructure.
- Limit access based on the **principle of least privilege**.
- Enable **logging and monitoring** to detect security incidents.

## Reporting Security Issues

If you suspect a security issue or improper handling of sensitive information:

1.  **Do not disclose publicly.**
2.  Report it privately through GitHub private vulnerability reporting, as described above.
3.  Provide necessary details to help investigate the issue.

## Thank You

We appreciate your help in keeping this project and its users safe. Your adherence to these guidelines helps ensure a secure and responsible development environment.

------------------------------------------------------------------------

Adapted from Talk2PowerSystem (<https://github.com/statnett/Talk2PowerSystem>), licensed CC BY-NC-SA 4.0. Changes were made.
