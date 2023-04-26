---
title: "Unclean Hands: A Prior Art Defense Exception"
subtitle: Allowing an alleged infringer to benefit from a breach of confidentiality by claiming prior art would be unfair and contrary to fundamental legal principles.

# Summary for listings and search engines
summary: Allowing an alleged infringer to benefit from a breach of confidentiality by claiming prior art would be unfair and contrary to fundamental legal principles.

# Link this post with a project
projects: []

# Date published
date: 2023-04-26

# # Date updated
# lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Maarten van den Heuvel**](https://unsplash.com/photos/_pc8aMbI9UQ)'
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

The prior art defense allows alleged patent infringers in China to avoid liability if they can prove that the technology or design in question was already publicly available before the filing of the patent. This defense aims to prevent improperly granted patents from being enforced and allows the public to freely use technology that is already in the public domain.

Article 67 of the Chinese Patent Law codifies the prior art defense. It states that “In a patent infringement dispute, where the alleged infringer has evidence to prove that the technology or design exploited forms part of prior art, such exploitation does not constitute infringement of patent right.” Prior art refers to anything that has been made available to the public anywhere in the world before the patent’s filing or priority date. This includes publications, public use, sales, and other events. If an alleged infringer can show that the technology was already public before the filing date, they are generally free to use it.

Confidential disclosures under nondisclosure agreements do not qualify as prior art because they are not public. But what if the receiving party breaches the confidentiality and publicly discloses the invention? In that case, the invention likely becomes prior art (although the discloser can still patent it within the 6-month grace period). Can an alleged infringer then assert a prior art defense based on the breaching party’s unauthorized disclosure?

The Supreme People’s Court (SPC) of China addressed this issue in Shanghai Huanxin Electronic v. Guangdong Farina Technology [(2020)最高法知民终1568号](https://m.iphouse.cn/verdict/show/id/1641280.html?code=l2ywY29pZpOaYQ==). Shanghai Huanxin accused Guangdong Farina of infringing its [patent](https://patents.google.com/patent/CN207817787U/en) on a connection handle for an automatic rental and sale terminal”. Guangdong Farina did not dispute that its product practiced the patented invention. However, it asserted that the invention had been publicly disclosed in an online article published prior to the filing date. Notably, Guangdong Farina itself authored and published the online article. Guangdong Farina was subject to a “Procurement contract” with Shanghai Huanxin, and its disclosure in the article breached the confidentiality obligation under that contract.

The SPC rejected Guangdong Farina’s prior art defense. It held that Guangdong Farina’s unauthorized disclosure could not support its defense because no one should benefit from their own illegal acts. Allowing an alleged infringer to benefit from a breach of confidentiality by claiming prior art would be unfair and contrary to fundamental legal principles. Therefore, an alleged infringer cannot claim that a technology is prior art based on its own unlawful public disclosure of it.

This case establishes an exception to the prior art defense in China, where the alleged prior art results from the defendant’s own breach of confidentiality. By refusing to allow Guangdong Farina to benefit from its own breach of confidentiality, the court upheld important moral and legal principles. At the same time, the decision provides guidance to lower courts on how to apply China's prior art defense in a fair and just manner in future cases. 

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
