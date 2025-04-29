<!--
Add here global page variables to use throughout your website.
-->
+++
author = "KMPSUJ"
title = "SeMPowisko 2025"
mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
# prepath = "yourproject"

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "SeMPowisko 2025"
website_descr = "Webpage for the XXIII International Math-Science conference SeMPowisko 2025"
website_url   = "https://sempowisko.com/2025"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\duallang}[2]{
@@multilang
@@lang-en
#1
@@
@@lang-pl
#2
@@
@@
}

\newcommand{\faq}[2]{~~~
<strong>
#1
</strong>~~~ #2}

\newcommand{\mailsempo}{[sempowisko2025@gmail.com](mailto:sempowisko2025@gmail.com)}

\newcommand{\SeMPowisko}{$\large \hbox{S} \normalsize \kern{-.25em}\raisebox{-0.2ex}{\hbox{e}}\raisebox{-.2ex}{\hbox{\large M\normalsize}}\kern-.1em \raisebox{.1ex}{\hbox{\large P\normalsize}}\kern-.3em \raisebox{.2ex}{\hbox{o}} \kern{-.2em} \raisebox{.4ex}{\hbox{w}}\raisebox{-.1ex}{\hbox{i}}\hbox{s}\raisebox{.2ex}{\hbox{k}}\kern-.25em \raisebox{-.2ex}{\hbox{o}}$}

\newcommand{\strike}[1]{~~~<span style="text-decoration:line-through">#1</span>~~~}

