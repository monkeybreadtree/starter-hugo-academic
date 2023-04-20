---
title: "Lost in Translation: How Imprecise Contract Terms Led to a Million-Dollar Software Licensing Dispute"
subtitle: The case provides an optimistic outlook on China’s improving IP protections, while highlighting the importance of careful drafting and translation for contracts across languages.

# Summary for listings and search engines
summary: The case provides an optimistic outlook on China’s improving IP protections, while highlighting the importance of careful drafting and translation for contracts across languages.

# Link this post with a project
projects: []

# Date published
date: 2023-04-19

# # Date updated
# lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Mihai Surdu**](https://unsplash.com/photos/8H9ph_Jp3hA)'
  focal_point: Smart
  placement: 2
  preview_only: false

# authors:
#   - admin
#   - 吳恩達

# tags:
#   - Academic
#   - 开源

# categories:
#   - Demo
#   - 教程
---

With the rapid development of technologies such as computer software and the Internet, Chinese courts are gaining more experience in applying laws to handle IP disputes arising from new technologies. A recent case adjudicated by the Guangzhou Intellectual Property Court demonstrates the court’s pragmatic approaches in interpreting software licensing contracts and determining copyright infringement.

In Softspeed v. Minth ((2019)粤73知民初1519号), [Softspeed](https://www.qad.com/about/news/-/room/read/2016/softspeed-consultant-group-distributes-qad-cloud-erp-in-china) sued [Minth Group](https://www.minthgroup.com/?lang=en) for allegedly exceeding its ERP software license. Under their 2013 contract, Minth Group purchased 478 “许可证” (licenses) but the type was not expressly specified. 

Two common types of software licenses in the softwary industry are named user license, authorizing designated individuals, and concurrent user license, limiting maximum simultaneous users regardless of identity. A named user license can only be used by one person, while a concurrent user license can be used by different people one at a time. For ERP software, named user licensing and per-user charges are typical.

Notably, the 2013 contract had a two-word English phrase “named user” following the Chinese term “许可证” but lacked a definition or explanation. The inclusion of this limited English phrasing in an otherwise Chinese contract did not seem sufficient to resolve uncertainty over the type of the license. Lacking express clarification, the Guangzhou Intellectual Property Court took a stance favoring the software copyright holder’s interests. The court interpreted “许可证” and “named user” based on industry practices and software specifications, finding the license was per-named user. 

Minth Group admitted installing the software on its server, providing login credentials to affiliates, and allowing over 1,000 different users remote access over two years. Despite Minth Group’s claims of broad access rights, the court ruled Minth Group had exploited a named user license into de facto concurrent licensing by exceeding its allowed number of users, infringing Softspeed’s copyright.

The case signals Chinese courts’ ability to interpret technology contracts and apply laws equitably. Overall, it provides an optimistic outlook on China’s improving IP protections. However, the case highlights the importance of careful drafting and translation for contracts across languages. 

The contract was ambiguous enough for Minth Group to claim it believed concurrent user licensing was intended and allowed broad access. This indicates the contract likely did not convey the licensing model Softspeed, as IP holder and software provider, would have implemented. Contracts require precision to avoid confusion and enforceability issues, especially for complex technologies. The experience highlights the need for meticulously localizing contracts to match industry standards and objectives.

<!-- ```python
import libr
print('hello')
```

## Overview

1. The Wowchemy website builder for Hugo, along with its starter templates, is designed for professional creators, educators, and teams/organizations - although it can be used to create any kind of site
2. The template can be modified and customised to suit your needs. It's a good platform for anyone looking to take control of their data and online identity whilst having the convenience to start off with a **no-code solution (write in Markdown and customize with YAML parameters)** and having **flexibility to later add even deeper personalization with HTML and CSS**
3. You can work with all your favourite tools and apps with hundreds of plugins and integrations to speed up your workflows, interact with your readers, and much more

[![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.](https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png)](https://wowchemy.com)

## Get Started

- 👉 [**Create a new site**](https://wowchemy.com/templates/)
- 📚 [**Personalize your site**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Tutorial](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to become a sponsor and help support Wowchemy's future ❤️](https://wowchemy.com/sponsor/)

As a token of appreciation for sponsoring, you can **unlock [these](https://wowchemy.com/sponsor/) awesome rewards and extra features 🦄✨**

## Ecosystem

- **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli):** Automatically import publications from BibTeX

## Inspiration

[Check out the latest **demo**](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the **showcase**](https://wowchemy.com/user-stories/) of personal, project, and business sites.

## Features

- **Page builder** - Create _anything_ with [**widgets**](https://wowchemy.com/docs/page-builder/) and [**elements**](https://wowchemy.com/docs/content/writing-markdown-latex/)
- **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
- **Create content** in [**Markdown**](https://wowchemy.com/docs/content/writing-markdown-latex/), [**Jupyter**](https://wowchemy.com/docs/import/jupyter/), or [**RStudio**](https://wowchemy.com/docs/install-locally/)
- **Plugin System** - Fully customizable [**color** and **font themes**](https://wowchemy.com/docs/customization/)
- **Display Code and Math** - Code highlighting and [LaTeX math](https://en.wikibooks.org/wiki/LaTeX/Mathematics) supported
- **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
- **Beautiful Site** - Simple and refreshing one page design
- **Industry-Leading SEO** - Help get your website found on search engines and social media
- **Media Galleries** - Display your images and videos with captions in a customizable gallery
- **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
- **Multi-language** - 34+ language packs including English, 中文, and Português
- **Multi-user** - Each author gets their own profile page
- **Privacy Pack** - Assists with GDPR
- **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
- **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Wowchemy and its templates come with **automatic day (light) and night (dark) mode** built-in. Alternatively, visitors can choose their preferred mode - click the moon icon in the top right of the [Demo](https://academic-demo.netlify.com/) to see it in action! Day/night mode can also be disabled by the site admin in `params.toml`.

[Choose a stunning **theme** and **font**](https://wowchemy.com/docs/customization) for your site. Themes are fully customizable.

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-themes/blob/master/LICENSE.md) license. -->
