# Site Configuration

<!-- Global page variables. The website_* must be defined for RSS to work. -->
@def website_title = "Albert R. Gnadt"
@def website_desc  = "Official Website of Albert R. Gnadt"

<!-- markdownlint-disable MD034 -->
@def website_url = "https://gnadt.github.io"
<!-- markdownlint-enable MD034 -->

@def author = "Albert R. Gnadt"
@def year   = "2026"

@def mintoclevel = 2

@def robots_disallow = ["assets/"]

<!-- Files or directories to be ignored during Franklin processing. -->
@def ignore = ["_dev/"]

<!-- Global latex commands. They can be math commands, but do not need to be. -->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
