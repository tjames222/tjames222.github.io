---
layout: post
title:  "How to Setup and Host a Jekyll Blog"
date:   2022-06-17 11:05:51 -0700
categories: Tutorials
---
  
Install Tools
---
  
  1. Follow this `simple installation` process to get [Jekyll][jekyll-docs] installed
  2. Install `Ruby` - Simple [Ruby][ruby]
  3. Install `GCC` - Extremely involved -> This is the easy way: [GCC][gcc] 
  4. Install `Make` - [GNU Make][gnu] is a tool which controls the generation of executables and other non-source files -> you can use MinGW installation manager to install Make. Find the packages in the all packages section
  5. Open `cmd` and `cd` to `myblog`
  6. Run command: `bundle exec jekyll serve --livereload`
  7. Navigate to the below link to see local served site http://localhost:4000 (the cmd output will give you the localhost link if it is not 4000)
	
Deploy to GitHub
---
>This is a free way to host a public GitHub repo.
	
  1. Follow directions here: [GitHub Pages][github-pages]
  2. Copy files from `Jekyll setup` into the newly cloned Repo
  3. Navigate to the URL: In my case it is `https://tjames222.github.io/`
  4. You can also create a custom domain name: [Custom Domain][custom-domain]

[jekyll-docs]: https://jekyllrb.com/docs/
[ruby]: https://www.ruby-lang.org/en/downloads/
[gcc]: https://dev.to/gamegods3/how-to-install-gcc-in-windows-10-the-easier-way-422j
[gnu]: https://www.gnu.org/software/make/
[github-pages]: https://pages.github.com/
[custom-domain]: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
