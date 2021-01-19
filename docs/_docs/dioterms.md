---
layout: doc
title: dioterms - Open-source vulnerability disclosure policies.
categories: [Core projects]
tags: 
---
Repo:
Status:
Maintainer/s: 
To do/s:

---
> Note: While we've engaged the legal opinion of many, this does not constitute legal advice. Please consult your legal counsel for the specific suitability of the disclose.io terms in your organization.

## Choosing terms

Organizations that wish to use the disclose.io as a basis for vulnerability disclosure policies (VDPs) should first choose the boilerplate that is the best fit for their organization. The dioterms repo contains a number of different options:

-   [Generic terms](https://github.com/disclose/dioterms/blob/master/generic-core-terms.md) designed to provide maximum flexibility whilst maintaining bi-lateral safety and readability,
-   [Regionalized terms](https://github.com/disclose/dioterms/tree/master/regional) which accommodate the laws and languages of country or jurisdiction of the organization,
-   [Verticalized terms](https://github.com/disclose/dioterms/tree/master/vertical) which take the nuances of different industries or use-cases (e.g. election infrastructure) into account, and
-   [Simple Safe Harbor](https://github.com/disclose/dioterms/tree/simple-safeharbor/simple-safe-harbor.md) which is designed to add Safe Harbor language to VDPs and bug bounty programs which are already in place.
    
### About Safe Harbor

The core requirements for disclose.io's definition of Full Safe Harbor are for the organization’s policy to provide:

-   Authorization against anti-hacking laws
-   Exemption from anti-circumvention laws
-   Exemption from violation of the TOS/AUP during security testing
-   A statement acknowledging good-faith.
    

The intention of Safe Harbor language provided by disclose.io is for it to be followed specifically, with minor, if any, modifications. If modifications are made, the four tenets laid out above are the most important to address in your policy.

Policies missing any of the core tenets above, but that still contain a good-faith statement committing not to pursue legal action on security researchers, meet the criteria for Partial Safe Harbor.

Important reminder: Authorizations and exemptions from legal liability only cover what is in scope and under the control of the organization using the policy. For example, an organization using disclose.io terms may authorize you to research their own systems, but they cannot authorize you to research systems they do not own. Likewise, an organization using disclose.io terms cannot prevent a third party lawsuit if you breach the third party’s systems or data. Researchers and organizations are still expected to comply with all applicable laws.

### Additional terms

In each template we've also provided boilerplate examples for the additional terms section:

-   Scope (Required) – A complete list of "In-Scope" properties for which the organization is explicitly allowing and encouraging good-faith security research. Keep in mind that a true vulnerability disclosure program considers the entire attack surface of the organization running the program, so erring on the side of inclusiveness is best practice with respect to scope.
-   Out-of-Scope (Optional) - A non-exhaustive list of systems and security testing activities that the organization strongly wishes to discourage testing against, and
-   Rewards (Optional) – Information on whether or not the program offers a form of payment for valid, unique issues, as well as the type and parameters of that compensation.
-   Official Communication Channels (Required) – A full list of the communication methods that are made available by the organization to receive and communicate about vulnerability submissions.
-   Disclosure Policy (Required) – A clear policy outlining the conditions under which a researcher can disclose the details of a reported issue to third parties.
    

### Disclosure types

The terms provide for three types of vulnerability disclosure:
-   Coordinated Disclosure: A researcher can share details of the vulnerability after a fix has been applied and the program owner has provided permission to disclose or after a clearly-stated time has passed from submission, whichever is sooner;
    
-   Discretionary Disclosure: The researcher or the program owner can request mutual permission to share details of the vulnerability after approval is explicitly received; or
    
-   Non-Disclosure: Researchers are required to keep vulnerability details and the existence of the program itself confidential.
    

## Next steps
Once you've published your policy, you can:
-   Add the appropriate [disclose.io seal](https://github.com/disclose/dioseal) to your public program brief,
-   Submit a pull request to add your program to the [open-source disclose.io program list](https://github.com/disclose/diodb),
-   Let the world [know](https://twitter.com/disclose_io) you're joining the movement!
-   Contribute back to the [disclose.io](https://disclose.io/) project!