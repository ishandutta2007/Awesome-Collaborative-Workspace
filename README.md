# Awesome-Collaborative-Workspace

# Awesome-Collaborative-Workspace

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Team Wikis, Docs, Whiteboards & Knowledge Management*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Workspaces**. These tools help teams co-create documents, manage knowledge, and coordinate projects in a shared digital space.

**Examples** include Microsoft Loop, Notion, Coda, Confluence, Craft, Roam Research, Nuclino, Basecamp, Anytype, and Slite (the category leaders).

**Open-source emphasis**: The open-source collaborative workspace ecosystem is **exceptionally mature and diverse**. **AppFlowy** is the leading open-source Notion alternative with AI capabilities, self-hosting, and no vendor lock-in . **AFFiNE** brings docs, whiteboards, and databases together in a local-first architecture with full offline support . **Docmost** provides an open-source Confluence and Notion alternative with real-time collaboration and permissions . **Huly** offers an all-in-one platform covering project management, chat, CRM, and HRM . This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global collaborative workspace market is estimated at **~$15B in 2026**, growing toward **~$40B by 2032** at a **~18% CAGR**. The sector is **moderately fragmented** — **Notion** leads with a **generous free tier** for individuals but hits limits fast at **1,000 blocks** , while **Coda** uses a unique **Maker billing model** where editors and viewers are **entirely free** . **Confluence** offers a **free tier for 10 users** with **2 GB storage** , and **Basecamp** provides a **permanent free plan** with **1 project and 5 users** . **Roam Research** stands apart with **no free tier** — only a **31-day trial** before **$15/month** . No single vendor holds a winner-take-all position; teams typically choose based on workflow fit rather than feature parity.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Notion](https://www.notion.so/)** | **The category-defining all-in-one workspace.** Docs, wikis, databases, and project management in one flexible canvas. | **Plus**: **$12/user/month** (annual) or **$15/month**; **Business**: **$18/user/month** (annual) or **$22/month**; **Enterprise**: Custom . | **Free**: **1,000 content blocks**, **10 guests**, **5 MB file upload limit**, **7-day page history** . | **~$10B valuation (private)** |
| **[Microsoft Loop](https://www.microsoft.com/en-us/microsoft-loop)** | **Microsoft's collaborative canvas with portable components.** Loop components sync across Teams, Outlook, Word, and Whiteboard in real time. | **Free in preview** for anyone with a Microsoft account . Advanced governance features may require a commercial license post-GA . | **Free in preview** — no license needed for personal preview . Workspace structure follows OneDrive/SharePoint permissions . | **~$281B revenue (Microsoft FY2025)** |
| **[Coda](https://coda.io/)** | **All-in-one doc platform with Maker billing.** Only pay for Doc Makers (creators/editors); Editors and viewers are entirely free . | **Pro**: **$12/Doc Maker/month** (min 3); **Team**: **$36/Doc Maker/month** (min 3) . Negotiated discounts: 15–30% off list . | **Free**: Unlimited Doc Makers, limited features, unlimited sharing, folders, no size/object limits for personal docs . | **Part of Superhuman (private)** |
| **[Confluence](https://www.atlassian.com/software/confluence)** | **Atlassian's enterprise wiki.** Deep integration with Jira and the Atlassian ecosystem. | **Standard**: **$6.70/user/month** (1–100 users, monthly) . Volume discounts for larger teams . | **Free forever for 10 users**, **2 GB storage**, Community Support . | **~$4B revenue (Atlassian FY2025)** |
| **[Craft](https://www.craft.do/)** | **Document editor with local-first architecture and AI assistant.** Native Mac, iPad, and iPhone apps. | **Plus**: **~$5–8/month**; **Family**: **~$10–15/month**; **Team**: **~$12–20/month** . AI quota varies by tier . | **Starter (Free)**: **1,500 content blocks**, **1 GB storage**, **25 MB per file**, **7-day version history**, **~15–25 AI conversations lifetime** . | **Private (~$50M+ raised est.)** |
| **[Nuclino](https://www.nuclino.com/)** | **Lightweight, collaborative wiki and knowledge base.** Visual graph view for connected knowledge. | **Starter**: **$6/user/month** (monthly) or **$4.50** (annual) . **Business**: **$10/user/month** (monthly) or **$7.50** (annual) . | **Free**: **Up to 50 items**, **2 GB total storage**, collaborative wiki and docs, **full REST API access** . | **Private (~$10M+ raised est.)** |
| **[Basecamp](https://basecamp.com/)** | **The project management pioneer.** Simple, flat-rate pricing with no per-user fees on paid plans. | **Freelancer**: **$25/month** (3 projects, 20 users max); **Studio**: **$59/month** (10 projects, unlimited users) . | **Free**: **1 project**, **5 users**, **1 GB file storage**, Pings for private conversations . | **Private (~$100M+ revenue est.)** |
| **[Slite](https://slite.com/)** | **Knowledge base for remote teams.** Now part of Superhuman . | **Standard**: **$8/user/month** (annual) . **Knowledge Suite**: **$20/user/month** (min 10 users) . | **14-day free trial** on Standard plan . **No permanent free tier** . | **Part of Superhuman (private)** |
| **[Roam Research](https://roamresearch.com/)** | **Graph-based note-taking for networked thinking.** Bidirectional linking and block references. | **Pro**: **$15/month** or **$165/year** . **Believer**: **$500 upfront** for 5-year commitment . | **No free tier** — only a **31-day trial** then **$15/month** . | **Private (~$200M valuation est.)** |
| **[Anytype](https://anytype.io/)** | **Local-first, encrypted workspace.** Self-host your data for free forever; pay for backup storage only . | **Not yet charging** — currently in beta. Future pricing: pay for resources consumed (backup storage) . **50% discount** for active contributors . | **Free forever with self-hosting**. **1 GB free backup storage** on Anytype's infrastructure . | **Private (~$20M+ raised)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[AppFlowy](https://github.com/AppFlowy-IO/AppFlowy-Web)** — **The leading open-source Notion alternative.** AI collaborative workspace with docs, wikis, grids, kanban boards, and databases. **Self-hosting available; no vendor lock-in**. AGPLv3 . | [![Stars](https://img.shields.io/github/stars/AppFlowy-IO/AppFlowy?style=social&color=white)](https://github.com/AppFlowy-IO/AppFlowy/stargazers) | ~60,000 |
| **[AFFiNE](https://github.com/toeverything/AFFiNE)** — **Next-gen knowledge base merging docs, whiteboards, and databases.** Local-first, offline-first, privacy-focused. Free replacement for Notion & Miro . MIT + proprietary components . | [![Stars](https://img.shields.io/github/stars/toeverything/AFFiNE?style=social&color=white)](https://github.com/toeverything/AFFiNE/stargazers) | ~50,000 |
| **[Docmost](https://github.com/docmost/docmost)** — **Open-source Confluence and Notion alternative.** Real-time collaboration, spaces, permissions, groups, comments, page history, search, file attachments, diagrams (Draw.io, Excalidraw, Mermaid). AGPL 3.0 . | [![Stars](https://img.shields.io/github/stars/docmost/docmost?style=social&color=white)](https://github.com/docmost/docmost/stargazers) | ~10,000 |
| **[Huly](https://github.com/huemordev/huly-project)** — **All-in-one project management platform.** Alternative to Linear, Jira, Slack, Notion, and Motion. Includes Chat, Project Management, CRM, HRM, and ATS. Self-host with Docker . | [![Stars](https://img.shields.io/github/stars/hcengineering/platform?style=social&color=white)](https://github.com/hcengineering/platform/stargazers) | ~12,000 |
| **[Logseq](https://github.com/logseq/logseq)** — **Privacy-first knowledge management and collaboration platform.** Focuses on longevity and user control. Supports Markdown and Org-mode, PDF annotation, task management. Local-first with DB version . | [![Stars](https://img.shields.io/github/stars/logseq/logseq?style=social&color=white)](https://github.com/logseq/logseq/stargazers) | ~38,000 |
| **[TriliumNext](https://github.com/TriliumNext/Trilium)** — **Hierarchical personal knowledge base with scripting.** Note versioning, relation maps, mind maps, geo maps, Excalidraw canvas, REST API. Scales to 100,000+ notes. OpenID and TOTP integration . | [![Stars](https://img.shields.io/github/stars/TriliumNext/Trilium?style=social&color=white)](https://github.com/TriliumNext/Trilium/stargazers) | ~28,000 |
| **[SiYuan](https://github.com/siyuan-note/siyuan)** — **Privacy-first personal knowledge management system.** Block-level references, Markdown WYSIWYG, local-first storage. v3.8.0 adds LAN peer sync, database views, and mobile improvements . | [![Stars](https://img.shields.io/github/stars/siyuan-note/siyuan?style=social&color=white)](https://github.com/siyuan-note/siyuan/stargazers) | ~25,000 |
| **[Joplin](https://github.com/laurent22/joplin)** — **Privacy-focused note-taking app with sync.** Windows, macOS, Linux, Android, iOS. Markdown editor, web clipper, end-to-end encryption . | [![Stars](https://img.shields.io/github/stars/laurent22/joplin?style=social&color=white)](https://github.com/laurent22/joplin/stargazers) | ~45,000 |
| **[Excalidraw](https://github.com/excalidraw/excalidraw)** — **Virtual hand-drawn style whiteboard.** Collaborative and end-to-end encrypted. Infinite canvas, dark mode, shape libraries, export to PNG/SVG, local-first autosave . | [![Stars](https://img.shields.io/github/stars/excalidraw/excalidraw?style=social&color=white)](https://github.com/excalidraw/excalidraw/stargazers) | ~90,000 |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Collaborative workspaces handle potentially sensitive organizational data; ensure proper access controls and compliance with data protection regulations.
- **Open-source reality**: The open-source ecosystem for collaborative workspaces is **exceptionally mature and diverse**. **AppFlowy** is the leading open-source Notion alternative with AI capabilities and self-hosting . **AFFiNE** merges docs, whiteboards, and databases with local-first architecture . **Docmost** provides an open-source Confluence alternative with real-time collaboration . **Huly** covers project management, chat, CRM, and HRM in one platform . **Logseq**, **TriliumNext**, **SiYuan**, and **Joplin** serve privacy-focused knowledge management . **Excalidraw** delivers collaborative whiteboarding with E2E encryption . However, **commercial platforms** (Notion, Coda, Confluence) provide **polished UX, managed infrastructure, and enterprise integrations** that open-source alternatives may lack. The open-source path is **genuinely viable** for teams seeking data sovereignty and cost control.
- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Slite was acquired by Superhuman** and no longer offers a free tier . **Roam Research has no free tier** — only a 31-day trial . **Anytype is still in beta** and not yet charging .

---

**Made for product managers, team leads, knowledge workers, and open-source enthusiasts.**
Let's make collaborative workspaces more open, transparent, and user-controlled.
