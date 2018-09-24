# devdocs
### Interactive CLI/zsh command for devdocs.io

1. Installation

Copy the main script (devdocs) to your local bin-path (/usr/local/bin | ~/.local/bin | ...) or whatever dir is in your *$PATH*

2. Usage

`$zsh:> docs`

Then the script starts an interactive prompt that will guide you through searching/listing devdocs.io handbooks on the cli

3. Dependencies

* zsh
* ag (aka the silver searcher)
* yank (on debian/fedora yank-cli)
* peco (similar to yank, it's on (github)[http://github.com/peco/peco])
* manu (it's a tool for downloading/extracting devdocs.io to your local machine/cli: (github)[https://github.com/byteclubfr/manu] - please install and use it first to actually provide searchable content; example install of devdocs package: `$zsh:> manu pull javascript`)
* elinks (the cli-browser is used to display the specific extracted docs, please adapt the script if you prefer lynx, w3m, ...)
