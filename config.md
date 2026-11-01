# Site Configuration

<!--
Add here global page variables to use throughout your
website.
The website_* must be defined for the RSS to work
-->
@def website_title = "Albert R. Gnadt"
@def website_desc  = "Official Website of Albert R. Gnadt"

<!-- markdownlint-disable MD034 -->
@def website_url = "https://gnadt.github.io"
<!-- markdownlint-enable MD034 -->

@def author = "Albert R. Gnadt"
@def year   = "2026"

@def mintoclevel = 2

@def robots_disallow = ["assets/", "files/"]

<!--
Add here files or directories that should be ignored by Franklin, otherwise
these files might be copied and, if markdown, processed by Franklin which
you might not want. Indicate directories by ending the name with a `/`.
-->
@def ignore = ["files/dev/", "node_modules/", "franklin", "franklin.pub"]

<!--
Add here global latex commands to use throughout your
pages. It can be math commands but does not need to be.
For instance:
* \newcommand{\phrase}{This is a long phrase to copy.}
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
