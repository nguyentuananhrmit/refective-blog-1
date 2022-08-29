---
title: "About"
permalink: "/about/"
layout: page
---

## Installation

Just fork this [repository](https://github.com/niklasbuschmann/contrast) and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/) and your page is done.

## Content

I took the class with the topic is welcome to the SSE&T class, which gave me much important information regarding my studies and future work. First, Dr. Jonathan Crellin introduced me to engineering-related subjects at RMIT. In particular, IT and software engineering are two fields that we find very difficult to distinguish because they have many similar features and functions, so the teacher spends much time explaining and giving me information about those two areas. After receiving that information, I realize that although these two industries have many similar elements, the core nature is entirely different. IT focuses on improving and upgrading existing software to make them more modern and convenient. On the other hand, software engineering will be concerned with the production, creation, and development of entirely new software or from the essential software. Next, the lecture deals with the issue of doing an internship before receiving an official university degree. The teacher gave us names of tech companies that we might be interning. It helps me to have a clear direction about the company I want to work for in the future. In addition, it also creates motivation and confidence for me to work hard and continue to improve myself and absorb new knowledge at RMIT. Third, the teacher introduced me to the subjects available in the IT field. He also gave me background information about the subjects we would take in my first year and the number of credits I have to complete in a course. Especially at RMIT, students must complete introductory courses to be eligible for advanced courses. This information will help me better understand what I will be learning in my first year and be able to plan my studies soon. Finally, Dr. Jonathan Crellin reminds us of the school's management regulations in students' learning process. Plagiarism is one of the acts the university will severely punish, and he also gave me examples of plagiarism. Students who make such mistakes may fail the course or be expelled. They are one of those valuable pieces of information that I must always keep in mind because if I get it wrong, it can directly affect my learning. At the same time, I can also find a solution to prevent plagiarism from that information.

 
## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
