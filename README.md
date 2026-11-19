# Testing AWS AIDA alerts

*description of the project*

**Timeframe** 2026-11-05 - 2027-02-11

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/testing-aws-aida-alerts-2026](https://cra-test-arc.canada.ca/testing-aws-aida-alerts-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-11-19

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(GST/HST for businesses)
    node4(Claim a GST/HST rebate)
    node5(GST/HST new housing rebate)
    node6(Business registration with the CRA)
    node7(Excise and specialty taxes)
    node8(Underused Housing Tax)
    node9(Global minimum tax)
    node10(Savings and pension plans)
    node11(RRSPs and related plans)
    node12(The Home Buyers' Plan)
    node13(Payroll)
    node14(Benefits)
    node15(Public pensions)
    node16(Old Age Security)
    node17(Guaranteed Income Supplement)
    node18(Canada Revenue Agency #40;CRA#41;)
    node19(Internal Audit and Program Evaluation)
    node20(Internal Audit and Program Evaluation Reports - 2026)
    node21(CRA Multimedia library)
    node22(Individuals video gallery)
    node23(Webinar – Be scam smart)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node2 --> node6
    node2 --> node7
    node7 --> node8
    node7 --> node9
    node2 --> node10
    node10 --> node11
    node11 --> node12
    node2 --> node13
    node1 --> node14
    node14 --> node15
    node15 --> node16
    node16 --> node17
    node1 --x node18
    node18 --x node19
    node19 --> node20
    node18 --x node21
    node21 --> node22
    node22 --> node23

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node5,node6,node8,node12,node13,node17,node23 inscope
```
