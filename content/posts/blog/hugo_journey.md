---
title: "Go Hugo, a journey"
date: 2023-03-01T12:36:52-07:00
draft: true
description: "A brief overview of building my portfolio site using Hugo, exploring why I chose Hugo over other site generators, and a more detailed look at a few challenges I overcome while integrating my workflow."
---
<!--more-->
## Going Up
As I prepare to graduate, part of that process includes updating my professional profile, resume, and, most importantly, my portfolio. The information design program required students to use Adobe's portfolio in preparation for their internships during their 2nd year of studies.

{{< admonition warning "Goodbye, Adobe :(fas fa-rocket fa-fw):" true >}}
While the decision to use Adobe's portfolio has many advantages, it comes with a few significant draw backs:
1. **Price tag** is the major deterent, specifically the push to a annual subscription model.
1. **Formulaic offerings** which look great but offer little in terms of customizability.
1. **Uninspired user experience** that offers tedious formatting options and leaves me frustrated.

For the price, I find Adobe's offering to be prohibitively restrictive while simultaneously including far more than my work requires. 
{{< /admonition >}}

## Static Site Generators
By definition, Static Site Generators (SSGs) serve a website from a prebuilt set of files within a repository, such as git. There are many flavours of SSGs, each with their own set of features and capabilities. The most popular of which are Gatsby, Jekyll, 11ty, Next.js, Astro, Docusaurus, and Hugo.

### Trial by fire
Despite my technical inclinations, I wanted a portfolio solution which required minimal configuration and dependencies. I experimented with a few different SSGs, initially Gatsby and then Eleventy, but I encountered a series of incompatibilities and node.js errors which discouraged further usage. 

{{< admonition question "Welcome, Hugo :(fas fa-grin fa-fw):" true >}}
{{< link "https://gohugo.io/" Hugo >}} is a static site generator written in Go. I chose Hugo because it satisfys the following criteria:
1. **Headless** allows me to write entries in plain text using markdown instead of formatting text within Adobe's portfolio content management system (CMS).
1. **Markdown** is used for page content and meta data.
1. **Shortcodes** for javascript libraries like lazy image loading and lightbox galleries.
1. **TOML** language is used for configuration.
1. **Instant previews** save time and help troubleshooting.
{{< /admonition >}}

## Building 
The process of building the portfolio site was split between two workflows, formatting existing work and creating the actual site. 
