# Awesome-Agile-Portfolio-Management

# Awesome-Agile-Portfolio-Management
**Top Agile Portfolio Management (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Lean Portfolio Management, Capacity Planning, Strategic Alignment & SAFe Program Boards*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Agile Portfolio Management**. These tools enable organizations to connect strategy to execution—prioritizing investments, allocating capacity across teams, managing dependencies, and governing agile delivery at scale—from fully managed enterprise platforms with scenario modeling and financial governance to self-hosted project suites that give organizations complete control over their portfolio data and workflows.

**Examples** include Jira Align, Planview, Targetprocess, Broadcom Rally, Digital.ai Agility, Clarity PPM, Dragonboat, Meisterplan, Workfront, and Portfolio for Jira (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, portfolio governance, and open agile planning infrastructure. **Critical note**: True open-source agile portfolio management—with SAFe program boards, capacity heatmaps, and financial scenario modeling—is extremely sparse. The projects below provide **project/portfolio management platforms** with agile planning capabilities, **SAFe scaling boards**, or **governance-focused PPM tools**. None replicate the depth of Jira Align or Planview for enterprise lean portfolio management.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Jira Align](https://www.atlassian.com/software/jira/align)**
  **Enterprise agile planning and portfolio management** for SAFe and scaled agile frameworks. Connects strategy to execution across portfolios, programs, and teams. **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: large enterprises running SAFe or similar scaled agile frameworks needing strategy-to-delivery traceability.

- **[Planview](https://www.planview.com/)**
  **Strategic Portfolio Management (SPM)** platform with capacity planning, financial governance, and scenario modeling. **Pricing**: Quote-only; enterprise subscriptions negotiated with sales, typically annual or multi-year commitments . **Free tier**: None. **Best for**: PMOs needing mature portfolio-to-project traceability, prioritization workflows, and capital visibility .

- **[Targetprocess](https://www.targetprocess.com/)** (Apptio)
  **Agile portfolio and work management** with customizable views for SAFe, LeSS, and Kanban. **Pricing**: Quote-only. **Free tier**: None. **Best for**: mid-market to enterprise organizations wanting flexible agile portfolio visualization.

- **[Broadcom Rally](https://www.broadcom.com/)**
  **Agile ALM and portfolio management** (formerly CA Agile Central). **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises with existing Broadcom investments needing agile planning at scale.

- **[Digital.ai Agility](https://digital.ai/)**
  **Agile planning and portfolio management** (formerly VersionOne). **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting enterprise agile planning with DevOps integration.

- **[Clarity PPM](https://www.broadcom.com/)** (Broadcom)
  **Enterprise project and portfolio management** with financial governance and resource planning. **Pricing**: Quote-only. **Free tier**: None. **Best for**: large enterprises needing formal PPM with investment oversight.

- **[Dragonboat](https://www.dragonboat.io/)**
  **Product operations and portfolio platform** with capacity planning and OKR alignment. **Pricing**: Quote-only. **Free tier**: None. **Best for**: product operations teams needing data-driven capacity allocation.

- **[Meisterplan](https://meisterplan.com/)**
  **Lean portfolio and resource management** with capacity planning and scenario simulation. **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting lean PPM focused on resource capacity and project prioritization.

- **[Workfront](https://www.workfront.com/)** (Adobe)
  **Enterprise work management** with portfolio planning and resource management. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting unified work management across marketing, IT, and operations.

- **[Portfolio for Jira](https://www.atlassian.com/software/jira)** (Advanced Roadmaps)
  **Portfolio planning within Jira** for cross-team dependency mapping and scenario modeling. **Pricing**: Included with Jira Premium/Enterprise. **Free tier**: Limited on Jira Free. **Best for**: Jira-centric organizations wanting portfolio visibility without leaving the Atlassian ecosystem.

## Open-Source GitHub Projects

- **[OpenProject](https://github.com/opf/openproject)**
  **Leading open source project management software for product, project and portfolio management** (GPL-3.0) — **the most comprehensive open-source option for agile portfolio management** with enterprise-grade features and a mature community . **Features**: **Project and portfolio management** across multiple projects; **Agile boards (Kanban, Scrum, SAFe)**; product and release planning with roadmaps; Gantt charts for scheduling; time tracking, cost reporting, and budgeting; wikis, forums, and meeting management; baseline comparison; integrations with Nextcloud, GitHub, GitLab, and more . **Adoption**: Trusted by Deutsche Bahn, Fraunhofer Institut, Deutsches Museum, and the European Commission; part of the openDesk sovereign workplace suite . **Tech stack**: Ruby on Rails, PostgreSQL. **Deploy**: Self-hosted (Docker, package installers) or OpenProject Cloud. **Trade-off**: **Community Edition lacks Enterprise add-ons** (advanced security, premium integrations, portfolio/resource management features are gated) . Heavier than lightweight agile tools; intended for organizations needing governance and portfolio views. **Best for**: enterprises, public institutions, and teams wanting a Jira/Monday alternative with true portfolio management, SAFe boards, and budgets—self-hosted with full data sovereignty.

- **[LibrePlan](https://www.libreplan.org/)**
  **Web-based project and portfolio management platform** (AGPL-3.0) — **a governance-focused option for public sector and regulated environments** . **Features**: **Project and portfolio planning**; resource allocation and capacity management; issue and risk tracking; project governance and transparency; milestone monitoring; auditability through self-hosted infrastructure . **Version 1.6.0** adds issue/risk log management, document repositories, project pipeline overview, and expanded translations . **Tech stack**: Java. **Deploy**: Self-hosted (Docker images available). **Trade-off**: **Public-sector and governance orientation**—less agile-native than OpenProject. No SAFe program boards or lean portfolio ceremonies. UI may feel dated compared to modern SaaS tools. **Best for**: public administrations, NGOs, and educational institutions wanting sovereign portfolio governance without SaaS dependency.

- **[Kendis](https://hub.docker.com/r/kendisdocker/kendis)**
  **Agile Scaling Platform with real-time program board** (Docker image, license per vendor) — **the most purpose-built open-source option for SAFe program-level planning** . **Features**: Specialized boards for **SAFe®, Spotify Model, Nexus, LeSS, Scrum @Scale**, or custom scaling models; **real-time program board with dependencies management**; capability of "real-time" planning—teams drag features to sprints and create stories; visual management of dependencies between features across all teams; feature progress visualization across sprints and teams; tracking external vendors and milestones . **Integration**: 2-way integration with Atlassian Jira (Cloud, Server, Data Center) and Microsoft Azure DevOps/TFS . **Deploy**: Docker (`docker pull kendisdocker/kendis`). **Trade-off**: **Kendis itself is proprietary/commercial**—the Docker image is a distribution method, not an open-source license. It is included here as the closest tool to SAFe program board functionality, but **it is not open source**. No portfolio-level financial planning or capacity heatmaps. **Best for**: SAFe organizations wanting a real-time program board with Jira/Azure DevOps integration—**verify licensing terms before adoption**.

- **[Plane](https://github.com/makeplane/plane)**
  **Modern project management platform** (AGPL-3.0 for Community Edition) — **a fast-growing open-source Jira/Linear alternative** . **Features**: Work items, cycles (sprints), modules, and views; rich text Pages with AI capabilities; analytics and burn-down charts; custom filters and saved views . **Tech stack**: Next.js, TypeScript, PostgreSQL. **Deploy**: Self-hosted (Docker) or Plane Cloud. **Trade-off**: **Optimized for team-level issue tracking, not portfolio governance**—no SAFe program boards, capacity planning, or financial modeling. Closer to Linear than Jira Align. **Best for**: software teams wanting a modern, fast issue tracker with agile cycles—not enterprise portfolio management.

### Additional Strong Open-Source Options

- **Tuleap** — Open-source ALM and agile management tool (GPL-3.0). Comprehensive ALM with customizable workflows. **Note**: Listed as a Jira Align alternative and Meisterplan alternative . Strong on development lifecycle, less on portfolio-level capacity planning. **Best for**: development teams wanting open-source ALM with agile planning.
- **Taiga** — Agile project management (MPL-2.0 and AGPL-3.0). Scrum and Kanban focus. **Note**: Listed as a Meisterplan alternative . Team-level agile execution, not portfolio governance. **Best for**: Scrum teams wanting open-source agile tooling.
- **Redmine (enhanced)** — Open-source project management (GPL). Highly customizable with plugins. **Note**: Requires self-maintenance and plugin management; UI and integration experience less polished than commercial alternatives . **Best for**: technical teams willing to invest in customization and maintenance.

**Frameworks for building custom systems**: Combine **OpenProject** as the portfolio and agile planning backbone with **LibrePlan** for governance-focused public sector planning, **Plane** for team-level agile execution, and **Kendis** (if commercial licensing is acceptable) for SAFe program boards with Jira integration—creating an agile portfolio stack. **None of these replicate the enterprise lean portfolio management depth** of Jira Align or Planview; organizations needing SAFe portfolio ceremonies, financial guardrails, and capacity heatmaps will require commercial platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agile portfolio management platforms handling strategic and financial data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for confidential planning information.
- **The "enterprise agile portfolio platform" vs. "project/portfolio management suite" vs. "team-level agile tool" distinction is critical.** **Jira Align, Planview, Targetprocess, Rally, Digital.ai Agility, Clarity PPM, Dragonboat, Meisterplan, and Workfront** are **enterprise portfolio platforms**—they provide capacity planning, financial governance, and SAFe portfolio ceremonies. **OpenProject and LibrePlan** are **project/portfolio management suites**—they combine agile boards with portfolio views and budgets, but lack the lean portfolio management depth of Jira Align. **Plane and Taiga** are **team-level agile tools**—issue tracking and sprints, not portfolio governance. **Kendis** is a **SAFe program board**—but it is **proprietary**, not open source . **No open-source project replicates Jira Align or Planview for enterprise lean portfolio management.**
- **OpenProject is the most mature open-source option for portfolio and agile planning.** It combines portfolio views, SAFe boards, roadmaps, Gantt charts, and budgets in one platform, is trusted by major European institutions, and has been in development since 2012 . **The trade-off**: Community Edition gates portfolio/resource management features behind Enterprise tiers , and the platform is heavier than lightweight agile tools.
- **LibrePlan is the choice for public sector governance**, with project and portfolio planning, resource allocation, and auditability . **The trade-off**: it is not agile-native—no SAFe program boards, no lean portfolio ceremonies. It is PPM with governance, not agile portfolio management.
- **Kendis is included as the closest SAFe program board**, but **it is not open source**—it is a commercial product distributed as a Docker image . **Do not adopt it expecting open-source licensing.** Verify terms with the vendor.
- **Plane is a team-level tool, not a portfolio platform.** It is excellent for issue tracking and sprints, but it has no capacity planning, financial modeling, or SAFe portfolio features . **Do not confuse a modern Jira alternative with Jira Align.**
- **Pricing opacity is universal across commercial vendors.** Jira Align, Planview, Targetprocess, Rally, Digital.ai, Clarity PPM, Dragonboat, Meisterplan, and Workfront all require sales contact. OpenProject publishes transparent Enterprise pricing (Basic €5.95/user/month, Professional €10.95, Premium €15.95) . **Validate with direct vendor conversations against your portfolio size and governance needs.**
- Self-hosted open-source solutions require proper server setup, security hardening, backup configuration, and ongoing maintenance. **Portfolio data is strategically sensitive**—ensure your deployment meets your organization's security and confidentiality requirements before storing planning data.

---

**Made for developers, PMO teams, and organizations building transparent agile portfolio management solutions.**
Let's make Agile Portfolio Management more open, data-driven, and strategy-aligned.
