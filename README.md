# Simple Search
Simple search is a program that prompts you for a search, then opens the webbrowser of choice and searches the search engine of choice with that search,

this is a program I made for myself so i can press super+s and a dmenu window pops up so i can search very very easily

# Usage

`simple-search <search>`

# Install

```sh
git clone https://www.github.com/euro20179/simple-search
cd simple-search
chdmod +x simple-search
sudo cp simple-search /usr/local/bin
```

# dependencies
* grep
* sed
* a webbrowser (the default is surf)

# Config

there are a few environment variables,

`KEEP_SS_HISTORY`, whether or not to keep a log of searches in `SS_HISTORY`
`SS_HISTORY`, the path to the history file
`SS_BROWSER`, the browser to use (must support a commandline argument for a url), i think most browsers do
`SS_SEARCH_ENGINE`, the search engine to use instead of duckduckgo (must be a url)
wherever you want the search to be in the url put %search%
