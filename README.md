# RavenHawk Tumblr Publisher

Basic Tumblr publishing tools for WordPress posts, queue processing, OAuth connection, and post logging.

This repository contains the RavenHawk Tumblr Publisher plugin package, update manifest, and repository documentation for RavenHawkTech.

## Current Version

**v2.0.0**

## Features

- Tumblr-focused WordPress publishing workflow
- Tumblr OAuth connection flow
- Queue and retry controls
- Local queue/log tracking
- Tumblr rate-limit status display
- Post-level Tumblr publishing checkbox
- RavenHawkTech admin menu grouping
- GitHub manifest-based update metadata

## Workflow

```text
WordPress → Tumblr
```

Existing Tumblr automations can continue forwarding posts to Instagram or Facebook when configured outside this plugin.

## Admin Settings

Open:

```text
RavenHawkTech → Tumblr Publisher
```

Queue/log tools are available under:

```text
RavenHawkTech → Tumblr Queue / Logs
```

## Repository Structure

This repository tracks the plugin package instead of the extracted plugin source files.

```text
/
├─ README.md
├─ SECURITY.md
├─ COPYRIGHT.md
├─ .gitignore
├─ releases/
│  └─ ravenhawk-tumblr-publisher.zip
└─ updates/
   └─ ravenhawk-tumblr-publisher.json
```

The package contains the full WordPress plugin folder, including the plugin PHP file, includes, admin icon assets, and plugin README.

## Installation

1. In WordPress Admin, go to **Plugins → Add Plugin**.
2. Click **Upload Plugin**.
3. Choose the RavenHawk Tumblr Publisher package.
4. Click **Install Now**.
5. Activate the plugin.
6. Open **RavenHawkTech → Tumblr Publisher** in WordPress Admin.

## RavenHawkTech

Website: https://ravenhawktech.com

## License

GPL-3.0 unless otherwise noted.
