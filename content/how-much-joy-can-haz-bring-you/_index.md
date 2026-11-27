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

- Additional HAZ shortcodes
  - We love a straightforward mobile-first layout but all text and no eye candy makes HAZ a dull theme. Aside from the mentioned haz_img, HAZ Core also includes haz_do, and haz_tbd. The former has a number of options, the latter amounts to: if you can configure it in the sysManifest, you can place it in an .md with haz_tbd. These are another case of seeing is believing. 


  - Benefit: TODO

- Accessibility Matters
  - As HAZ was built out, asking, "What about accessiblity?" was a common discussion with the agent. To that point, accessiblity is a process. It's not set it once and forget it. HAZ does its best to be mindful of accessibility, because the little things do add up. For example, the default font, Atkinson Hyperlegible, is considered a very good choice. Things like "Skip to main" and the blog's meta box using <dl><dt><dd> are examples of things HAZ has baked in.

  Disclaimer: It would be disengeneuos of us to make broad hyperbolic claims about HAZ and accessiblity. We're always thinking about it, and trying our best. We hope that once the tool is in your hands you do the same. It would mean a lot to HAZ if you did. 

  - Benefit: TODO 




- Settings Galore
  - HAZ is no different than any other tool, "Opinions are like agents, we all have them." That said, as often as possible HAZ allows its sensible defaults to be overridden, or provides some other configuration "hook".  We've already mentioned how many of the head tags have configurable defaults, which obviously pure genius. There's also the shortcodes whitelist that allows the dev / agency to limit the client's ability to (putting it bluntly) muck it up. 

  - Benefit: TODO

- Site Search via Pagefind
  - Search is one of those things that keeps people away from static sites. "Nice work, but how do you find anything?" Pagefind is a Hugo search solution recommended by gohugo.io. HAZ followed that lead and built a set of Atomics in Core that make adding it absurdly easy: local assets, a HAZ modal, index after the Hugo build. No third-party account. No "please install a search module" homework.

  Full disclosure: Pagefind itself is robust. We've been so focused on HAZ that we haven't pushed past basic site search — yet. For example, what do PF filters look like in the context of HAZ? Such exploration is on the HAZ TODO. 

  - Benefit: Static doesn't mean "no search." Visitors can actually find the page.


- Also Available Out of the Box
  - Blog paging / pager
    - Link to blog post
  - Light mode / Dark mode
    - Link to blog post
  - Fluid type sizing
    - Link to blog post
  - Back to Top
    - Link to blog post
  - Zero required dev tooling
  - Socials added and maintained via the Hugo CMS
    - Link to blog post
  - Reliable industry standard dependencies: Simple.css and Font Awesome (free)
    - Link to blog posts
  - Dedicated taxonomy term pages, with descriptions, etc
    - Link to blog post


- But wait! There's more... to come...
  - The beauty of HAZ's architecture (Atomics + sysManifest) is that new features can be added to Core, while those silos are optional to any Child projects downstream. In other words, Core's depth and breadth can grow without undermining your Child projects.  

  In an ideal future, other developers and agencies will also contribute. They'll submit PRs - following HAZ's patterns and best practices - to Core. These PRs will be things that were initially implemented via a Child. 

  - Benefit: TODO







