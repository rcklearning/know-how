---
title: 'The Power Pages Paradox - How the Design Studio, Dataverse and the Portal Management App Work Together'
date: 2025-02-22
author: Robert Knowles
permalink: /posts/2025/my-first-post
tags:
  - power pages
  - new developers
---

## Part 1 - Where do I start and why?

Working in different parts of the Power Platform is a given when creating well-rounded solutions. Even when Microsoft gives us the tools to avoid opening multiple tabs, I will often find I leave the Default solution open somewhere for quick reference. Largely though, I can navigate to make.powerapps and go from there.

With Power Pages though, you have the opportunity, and perhaps even the necessity, of working in three quite distinct ways to build your first low-code site. (This is without touching upon Power Automate flows, Copilot Studio, managing your files via Github, using XRM toolbox wizadry or perhaps Powershell...)

Firstly, if coming from a Power Apps background, I'm probably going to prefer creating forms for my Basic Forms in a Dataverse solution, but this can also be achieved in the Design Studio. If i've done the latter, it's a lot easier to quickly create a form and add it to a page, but Dataverse gives you greater control over the nuts and bolts. Going via the Data section of the Deisgn Studio is fine, but you may then find it harder to piece together things like relationships to other tables.

If I start with the Design Studio, I can probably piece together a pretty decent site without ever leaving. But as the MS docs themselves highlight, advanced customisation is more readily available via the Portal Management app. Whilst those familiar with make.powerapps may recognise this app - it's a Model-Driven App (MDA) after all - it can be a pretty daunting place when it first loads. And unlike our friendly Design Studio, there's far fewer clues provided to help you on your way!

So perhaps, if you're coming to Power Pages from a Dataverse/Power Apps background, the Portal Management app might be the perfect place to develop your site? Well, sort of...

The benefit of the Design Studio is the ease with which you can see what you've made. After all, the fundamentals of any website are its accessibility and ease of use. Toiling away in the darkness of the Portal Management app, you can't even sync your changes without stepping into the light. It's also, paradoxically, harder to create really engaging sites from the Portal Management app unless you're a front-end whizz to begin with - why bother when the Design Studio allows me to use Flex Containers with no code?

As you can probably guess from this rather circular argument - there is no "right" way to approach Power Pages development and, regardless of your starting point, a hybrid approach involving lots of tabs is unavoidable to create a really solid site. To help you understand where you may have to switch and give you a nudge where to start, i've created a trusty Venn diagram to help:









So, that's that then? Well, nearly...in Part 2,i'll go into more detail about how the hybrid approach can quickly get a little confusing, especially when it comes to advanced customisation and documenting your sites config.
