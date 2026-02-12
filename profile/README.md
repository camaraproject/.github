## Welcome 👋

Welcome to the GitHub of the CAMARA technical project. General information about the project can be found on the [Website](https://camaraproject.org), within the [Wiki](https://lf-camaraproject.atlassian.net/wiki/x/AgDe) and in the [Governance](https://github.com/camaraproject/Governance) repository. Please read the [Project Charter](https://github.com/camaraproject/Governance/blob/main/ProjectCharter.md) if you want to know what CAMARA and its APIs are about.

---

> [!NOTE]
> **Latest news:** CAMARA publishes a position on how network capabilities can enable **network-aware AI applications** using the Model Context Protocol (MCP).
> **[CAMARA charts a path for network-aware AI applications with MCP](https://camaraproject.org/2026/01/12/camara-charts-a-path-for-network-aware-ai-applications-with-mcp/)**

---

## 📍 Where do I start?

CAMARA brings together multiple APIs, repositories, and working groups.
The right starting point depends on **what you are looking for**.

---

### 🔎 I want to explore CAMARA APIs

If you want to understand **which APIs exist**, which sub-project or working group owns them, and their current maturity, CAMARA provides multiple entry points depending on the level of detail you are looking for:

👉 **[CAMARA API Overview (website)](https://camaraproject.org/api-overview/)**

👉 **[CAMARA API Portfolio (interactive, cross-release)](https://camaraproject.github.io/releases/portfolio.html)**

Both entry points provide access to CAMARA APIs and link to their corresponding API descriptions.

The **API Overview** is well suited for a high-level introduction and browsing by topic.
The **API Portfolio** provides a detailed, up-to-date view across releases, ownership, and maturity.

Together, these are the recommended entry points for **visitors, architects, and decision makers**.

---

### 🛠️ I want to use or implement a specific API

If you already know which API you are interested in:

Start with the **API Portfolio** and select the API (for implementation, use the latest meta-release, currently **Fall25**), then follow the link to the **API repository release** on GitHub, read the repository README and API documentation, and review the published OpenAPI and test specifications. If you are looking for live implementations offered by operators, see the **[GSMA Open Gateway operator map](https://open-gateway.gsma.com/map)**.

If you are implementing an API, you may also need:
- **[Security and Interoperability Profile](https://github.com/camaraproject/IdentityAndConsentManagement/blob/main/documentation/CAMARA-Security-Interoperability.md)** and **[Access and User Consent Management](https://github.com/camaraproject/IdentityAndConsentManagement/blob/main/documentation/CAMARA-API-access-and-user-consent.md)** (Identity & Consent Management)
- **[CAMARA API Design Guide](https://github.com/camaraproject/Commonalities/blob/main/documentation/CAMARA-API-Design-Guide.md)** and further documents such as the **[API Testing Guidelines](https://github.com/camaraproject/Commonalities/blob/main/documentation/API-Testing-Guidelines.md)** in the **[Commonalities](https://github.com/camaraproject/Commonalities)** repository

These documents are maintained by the respective working groups and apply across APIs. When implementing an API from a specific meta-release, use the corresponding release of these documents.

---

### 🤝 I want to participate in the CAMARA community

If you want to **join discussions, attend meetings, or contribute**, you will need
access to CAMARA's collaboration and communication tools.

Start here:
- **[Getting Started with CAMARA (community tools & access)](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/pages/14557496/Getting+Started+with+CAMARA)**

This page explains how to set up a Linux Foundation ID (LFID) and SSO, how to join mailing lists and Zulip channels, and how CAMARA collaboration is organized.

Participation in CAMARA is **free for individuals**.

Organizations may choose to join CAMARA as a **Participating Organization** or as a **member/sponsor**, which provides additional involvement, representation, and influence in the project:

👉 **[Join CAMARA – organizational participation and membership](https://camaraproject.org/join/)**

---

### ✍️ I want to contribute to an API or specification

If you plan to contribute changes (specifications, tests, documentation), start with the following entry points:

- **[Contributing Guidelines](https://github.com/camaraproject/Governance/blob/main/CONTRIBUTING.md)** (project-wide contribution process), **[Project Charter](https://github.com/camaraproject/Governance/blob/main/ProjectCharter.md)** and **[Project Structure and Roles](https://github.com/camaraproject/Governance/blob/main/ProjectStructureAndRoles.md)**
- **[Commonalities](https://github.com/camaraproject/Commonalities)** (API design guidelines and common artifacts)
- **[Identity and Consent Management](https://github.com/camaraproject/IdentityAndConsentManagement)** (if you want to contribute to security, identity, or consent topics)
- **[Propose a new API](https://github.com/camaraproject/Governance/blob/main/documentation/API-Onboarding-and-Lifecycle.md)** (API onboarding and lifecycle)

Each repository contains its own README; contribution guidance is typically found across the README, issues, meeting information, minutes, and existing practice.

---

### 🏁 I maintain an API or drive releases

If you are a **maintainer, codeowner, or release manager**, start with the following entry points:

- **[API Release Guidelines](https://github.com/camaraproject/ReleaseManagement/blob/main/documentation/API_Release_Guidelines.md)** (release process and rules)
- **[API Readiness Checklist](https://github.com/camaraproject/ReleaseManagement/blob/main/documentation/API-Readiness-Checklist.md)** (release requirements)
- **[CAMARA wiki](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/overview)** pages for meta-release milestones and coordination

Release coordination and cross-repository status tracking are currently handled through the wiki (as used for the Fall25 meta-release). As the new release process is rolled out, maintainers and codeowners will increasingly declare release intent via `release-plan.yaml`, with automation taking over much of the manual tracking, while the authoritative rules continue to live in GitHub repositories.

---

### Looking for something else?

This page is intentionally kept concise.
If you are unsure where to go next, browse the **[CAMARA wiki](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/overview)** for meeting minutes, working groups, and release tracking, or explore the **[Governance](https://github.com/camaraproject/Governance)**, **[Release Management](https://github.com/camaraproject/ReleaseManagement)**, **[Commonalities](https://github.com/camaraproject/Commonalities)**, **[Identity and Consent Management](https://github.com/camaraproject/IdentityAndConsentManagement)**, and **[API Backlog](https://camaraproject.org/api-backlog/)** repositories for project-wide rules and guidelines.
