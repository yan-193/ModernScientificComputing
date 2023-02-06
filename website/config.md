<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Jinguo Liu"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/", "_ignore/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Course AMAT5315"
website_descr = "The modern way of learning scientific computing"
website_url   = "https://modernascientificcomputing.giggleliu.github.io/"

website_url = get(ENV, "PREVIEW_FRANKLIN_WEBSITE_URL", "modernascientificcomputing.giggleliu.github.io") # Just put the website name
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}