<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Christoph Ortner"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "ACE Web"
website_descr = "Atomic Cluster Expansion"
website_url   = "https://cortner.github.io/ACEweb/"
+++

@def prepath = "ACEweb"

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
