---
title: How Much Joy Can HAZ Bring You?
layout: single
---

{{< haz_do add="list_toc" >}}
- [Features](#features)
{{< /haz_do >}}

## Features 

### Note: This is a WIP. Each of these will be fleshed out soon.

- Architecture
  - Logical & intentional. From the decoupled Hugo modules of Core, Child, and Content, to the forward-thinking sysManifest, HAZ was thoughtfully designed. HAZ is pattern-tastic, which both humans and agents love. HAZ is a model citizen of "A place for everything and everything has its place." 

  - Benefit: Productivity and maintainability. Less thinking, more doing.  

- Atomic Design
  - Speaking of architecture, a foundational mental model of HAZ is Brad Frost's Atomic Design {add link(s) here}. HAZ is engineered around the idea that large pieces (e.g., a page) are actually made up of medium-sized pieces, and medium pieces are made up of still smaller pieces. It's a concept that hits full stride in the sysManifest (which we'll get to shortly). The crown on top is Presets. Once you discover Presets you'll wonder how you even Hugo'ed without them. 
  
  - Call them objects. Or call them components. We simply refer to them as Atomics. 

  - Benefits: Reusability and predictability. 

- "Let Hugo be Hugo"  
  - We kept the good bits (modules, hugo.yaml, etc.) but then we layered what we affectionately think of as Hugo 3000 on top. If you're a Hugo veteran, nearly all of that experience will carry forward. If you're a Hugo virgin, you'll be spoiled by HAZ and lucky you, won't even realize it. 

  - Benefits: TODO 


- Router-driven
  - A Hugo first! This isn't simply a cliche "game changer", this is engineering nirvana. Gone are the days of Hugo page templates bloated with business logic - which was always an anti-pattern, as well as a struggle to maintain. The page doesn't interpret the request, the request drives which "page" the sysManifest should provide. Honestly, this is something you're going to have to see to believe. For now, we promise you an Ah-Ha moment is in your future. 

  - Benefit: Flexibility, reusability, freedom, and sanity

- The sysManifest
  - What is the DOM but a series of nested objects? HAZ's sysManifest is the same concept but implemented using Atomics (see Atomic Design above). Put another way, Atomics are a collection of building blocks and the sysManifest is how you stitch them together. Page layouts aren't built, they're configured. Naturally paired with the Router, the sysManifest is a paradigm your agent will thank you for. 

  - Benefit: TODO 

- It's CM-eSque
  - With HAZ, collections of structured data (e.g., team, FAQ, etc.) can be kept in .yaml files in a database-lite sort of way. That is, static Atomics can be generated dynamically (aka hydrated) based on static "CMS" content. Plus, HAZ includes a handful of helper functions for getting this done. No problem for you; or your agent. 

  - Benefit: TODO

- SEO and Head Tags
  - If you're an SEO asking, "But HAZ-y baby, what about MY needs?" HAZ has the tags for you. From the obvious - favicon, title, description, og:*, twitter:*, etc. - to the less so - preload, prefetch, preconnect - HAZ shows up fully prepared (read: no additional Hugo module required). Plus, the settings.yaml often allows you to define global defaults (e.g., for og:image) that page front matter can override. 

  - Benefit: SEO and performance tags are native 


- Shortcode: haz_img
  - Speaking of performance, the speed freaks are going to freak for this shortcode. Why? Because, HAZ can take a basic img tag with a single src file and magically turn that into a full-blown responsive web design power tool with sizes and srcset, and using WebP compression; all based on breakpoints that you're able to custom configure. The haz_img shortcode is proof that HAZ walks the mobile-first talk. 

  - Benefit: Performance! No more serving desktop-sized assets to a mobile device



  ------------------------------

- Client-proof DX / Client Test



- Other Shortcodes
  - haz_do
  - haz_tbd

- Settings
  - head tag defaults
  - Shortcode whitelist

- Available out of the box
  - Search (Pagefind)
  - Blog paging / pager
  - Light mode / Dark mode
  - See also: Shortcodes

- Accessibility
  - Skip to main
  - Default font {name}

- But wait there's more...
  - Zero required dev tooling
  - Socials
  - Back to Top
  - Fluid type & measure
  - Simple.css
  - Dedicated taxonomy term pages, with descriptions, etc
  - Posts meta box





