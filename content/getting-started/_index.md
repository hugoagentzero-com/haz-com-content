---
title: Getting Started
layout: single
---

## Overview

HAZ is a Hugo theme with a non-traditional approach. It's not a “drop in a theme folder and restyle” kit. It's not vanilla Hugo with a coat of cheap paint. It's more than that. It's why we refer to it as a **theme-work**. For example, let's start with the architecture…

**Client-friendly. Developer-focused. Agents love it.**

## Architecture

One of HAZ’s primary benefits is a **decoupled architecture**. Three Hugo modules combine to form a site:

- **Core** — The shared foundation: Atomic-design building blocks, shortcodes, baseline CSS, helpers, and more. You reference Core as a **module** and don’t have to fork it (unless you feel you must). Effectively an external library of tools your Child leans on. As features are added to Core, they become available to your project — without having to update your project.

- **Child** — The site’s customized presentation layer on top of Core: `hugo.yaml`, HAZ’s own `settings.yaml`, brand CSS, custom Atomics, etc. In a more traditional sense, the Child is the closest thing to a regular Hugo theme. It is the **build root** (`hugo server`, Pages). Decoupled from Core so you can customize without sweating Core updates. Decoupled from Content so developers/agencies keep structure safe from a client’s curiosity — **Client Test** in practice.

- **Content** — Pages, posts, media, and the Markdown authors actually write. Combined with the Child (and Core underneath), this is what becomes the final site. Clients and content folks live here.

## Two ways to get started

There are two ways to get started:

{{< haz_do add="callout" type="steps" step="1" title="Basic" >}}
The fastest, most friction-free way to take HAZ for a spin. All GitHub (browser / GitHub UI). No local Hugo. Free sample: do A, B, C and in about X minutes you have a working site.
{{< /haz_do >}}

{{< haz_do add="callout" type="steps" step="2" title="Standard" >}}
While it’s possible to use Basic full time, once you fall in love with HAZ you’ll likely want to upgrade to Standard. Local Hugo, faster feedback, deeper child work. Same architecture — more control.
{{< /haz_do >}}

This guide assumes **GitHub** (repos + modules + Pages). Other hosts wait.

## More soon

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
