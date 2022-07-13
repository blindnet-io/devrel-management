# blindnet devkit for Digital Insurance Apps

| **Author(s)** | [milstan](https://github.com/milstan) (milstan@blindnet.io)             |
| :------------ | :------------------------------------------------------------------------------------- |
| **PR**   | [TBD](TBD) |
| **Version**   | 1.0                                                                             |
| **Updated**   | 2022-07-13                                                                             |

## Client Profile : Steve

Steve is a health insurance app loved by digital natives who enjoy its user experience and simplicity.

## Context

Gaining users' trust is a key element of success in commercialization of digital services.
Where a human salesman is absent, trust is achieved through technology.

Privacy, giving users control over their data, and compliance with regulations are [key drivers of trust online](#references).

## Current Situation

Currently, if users what to exercise control over their data, restrict its processing or rights (granted by GDPR, CCPA or other regulations), they are expected to write an e-mail to **privacy@steveapp.com**.

This is problematic on several levels:
- **E-mail is not secure.**
Users might end-up disclosing confidential or health-related information over e-mail which would be a direct violation of [Article 32 of GDPR](https://gdpr-info.eu/art-32-gdpr/), heavily scantiness by most major in the EU.

- **Requests are difficult to automate**.
Expressed in the form of free text of an e-mail, Privacy Request must be read and processed by a human, which is cost-intense and slow. Linking the Requests and the responses to the actual data Steve has is very cumbersome and requires software development touching many components of the Steve backend system.

- **It is out of sync with the values of the brand**.
Steve is perceived as secure, modern, efficient, transparent. In other words everything this experience is not.

## Using blidnet devkit


## Need more?

blindnet devkit does much more. It is a complete solution for [privacy-enabled connectedness](https://github.com/blindnet-io/product-management/blob/main/refs/notion-of-privacy/notion-of-privacy.md), allowing developers to quickly gain ground on all the three pillars of privacy: [Transparency, Confidentiality and Control](https://github.com/blindnet-io/product-management/blob/main/refs/notion-of-privacy/principles/RFC-SPEP.md).

- Dealing with sensitive data? Offer end-to-end encryption using [blidnent's encryption services](https://github.com/blindnet-io/api-scala)
- Sharing Data with partners? Propagate users' Privacy Requests using blindnet's [Privacy Request Multicast Protocol](https://github.com/blindnet-io/product-management/blob/b7d2bd0aab509a5d83ed42822b0ba19e27bef905/refs/schemas/protocols/RFC-PRMP.md)

## References

- [Cisco 2022 Data Privacy Benchmark Study](https://www.cisco.com/c/en/us/about/trust-center/data-privacy-benchmark-study.html)
- [Blindnet's White Paper: The Mixed Feelings of Privacy. May 2022](../research/White-Paper-May-2022.pdf)