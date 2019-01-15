# Windows 10 Prepare Guide
## Document Overview
### Purpose
This document is aimed at assisting NHS organisations who are in the process of planning their Windows 10 adoption. It summarises the main areas to be considered in the preparation phase of a Windows 10 adoption programme, helping NHS organisations to complete their deployment by January 2020, the point at which Windows 7 operating systems cease to be supported.

The guide is part of a suite of guidance documents including Prepare, Prerequisites, Top Windows 10 Recommendations, Deploy, and Operate. It is intended to be read in its entirety and to inform the planning process. It is not designed to be a prescriptive recipe, but rather to highlight the most important areas to consider.

The document is split into the following sections:

**Document Overview**

Introduces this document, its sections, guiding principles and context

**Windows as a Service**

Explains what Windows as a Service (WaaS) is, along with information on Windows features and team organisation

**How to prepare for Windows as a Service (WaaS)**

This section covers the areas you need to consider in preparing to move to WaaS

**Application Compatibility**

Explains the way in which application compatibility is addressed with Windows 10 and discusses the discovery process

**Windows Defender ATP**

Information around Windows Defender ATP
**Windows Analytics – Upgrade Readiness**

An overview of the Windows Upgrade Readiness tool and its benefits

**Key Steps**

Provides a list of key activities to prepare for Windows 10

### Audience
This document is intended for use by experienced IT managers and as such assumes a prior understanding of managing a large (1000+ device) Windows estate.  
### Implementation Principles
At a high-level, the following outlines the Microsoft recommended goals for NHS to adopt Windows 10:
- Develop a centralised application catalogue to consolidate information about applications and their usage in your organisation
- Enrol in Windows Analytics Upgrade Readiness to help plan and manage your upgrade project
- Utilise Windows Analytics Upgrade Readiness workflow framework to drive Windows 10 upgrade process
- Define your application compatibility approach. For more information refer to the Prepare guide
- Deploy a pre-built Windows 10 image based on NCSC guidelines
- Use legacy application hosting services to remove reliance on local installation for older applications
- Develop a managed approach for the migration of user data
- Make use of System Centre Configuration Manager (shortened to SCCM, or ConfigMgr) upgrade/implementation services
- Adopt Windows as a Service (WaaS) as the ongoing operating model
With the release of Windows 10, Microsoft introduced a new operating system concept: Windows as a Service (commonly shortened to WaaS). In its most basic form, WaaS simply means that the Windows operating system will be more regularly updated with new features and capabilities.

More information can be found [here](https://docs.microsoft.com/en-us/windows/deployment/update/waas-quick-start)

The aim of this guide is to help explain the background to WaaS and to help you prepare the changes will be required in your environment to successfully deploy Windows 10.

Windows 10 gains new functionality with twice-per-year feature update releases. The following graphic shows the rapid rate at which new features are introduced with each new version:


![W10 releases](https://geoffyoung101.github.io/doc-repo/eachrelease.jpg)






