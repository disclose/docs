---
layout: doc
title: diostatus - The disclose.io best practice maturity model
categories: [Projects]
tags: 
---
## Let's send best practice viral!

Disclose.io Status provides recognition to early adopters of vulnerability disclosure programs, and a clear path towards best practices for those wanting to become more advanced.

| |security.txt|Basic|Partial|Full|Full with CVD|
|:--:||:--:||:--:||:--:|:--:||:--:|
| |![](https://lh6.googleusercontent.com/rnkzsTQ0fBnb2Hm9hQIBgfWA0SEPljovWN_VDOoRlgCW4BtFUmWfzQf8nGT4tyuZFOuxv4GHGRJ6vToOqnm5o817BF8Xz3Gz9kUS1vUMEFYe_M0x8TA8SIieJwsZFCo5BK-oEq44)|![](https://lh3.googleusercontent.com/iPhCCRw-D7U_HMkiD99Wxaj_yR5NBelZY6BIbknX1wGF6fkTLhVl_D4_51Iy37i8bt5w4rCEw7S-YawxsOX19RkKbE7Z_2Vifp263enfItr14oI4gd-T_8stAtDamuPeQd2eZ6mE)|![](https://lh5.googleusercontent.com/Gj0PR4mgFgk8ORYr4KfHecKRb4xxC3tuMpVTjl8EBnttTZ0eOF5dK_JDiia2LfIXUYQtJUejxMn0jMGRIfuIv4iEDk58r9I533JMftD2NxLKTnSXAW_hpOm97e4Fee9PC-QUmNR9)|![](https://lh4.googleusercontent.com/BPPYhsUY2ZjYNi9ZC4OZQ9GrwBiVbyYnNXoBgdujBRGL511QKY0SG8Kar_2_Wdt8rKXw8p7481GJxOviNlj9SzkahLb_6nUKGPP9ECOs2WTnYEGBzZ-hDOa46yDEwXdaxePZuP4I)|![](https://lh3.googleusercontent.com/xFCVdCh-zLVOqx4wO7-Os_wx7wiErVW1W0B4uWMvMTz1AAv_t8T3z61alETphugcNiKVaMOoXrdztn6MozK1u407jVrmt_lTlS19l16OyVpOAuIGPqX7_RnJrCdnIScZ-JzN8-cY)
|**security.txt or dnssecuritytxt**|Yes|Optional|Optional|Optional|Optional|
|**Written policy**|No|Yes|Yes|Yes|Yes|
|**Good-faith statement**|No|No|Yes|Yes|Yes|
|**Explicit authorization**|No|No|No|Yes|Yes|
|**Public and proactive CVD timeline**|No|No|No|No|Yes|

In combination with the [Disclose.io Seal](https://github.com/disclose/dioseal), diostatus clearly communicates:

1. The **availability** of of a vulnerability disclosure program (VDP) or bug bounty program (BBP);
2. The degree of **legal safety** a finder can expect;
3. The types of **security research activities that are blessed** by the organization; and
4. The **maturity** of an organization's vulnerability intake program and, by extension, its overall cybersecurity program.

Leveraging network-effect to promote best practice is a core design goal of The disclose.io Project. Diostatus and dioseal together **create a "race-to-the-top"** by making adoption of best practice rewarding, desirable, and viral. 

## How is it managed?

[diodb](https://github.com/disclose/diodb) is the system of record for diostatus. diodb's open-source and transparent nature provides full insight into changes, additions, and even downgrades of a diostatus.

Each status level has a corresponding dioseal, which organizations can display on their security page, policy page, shopping cart checkout, or elsewhere on a website.