# Kitsunekko Scraper
Scrapes Kitsunekko.net for subtitles.

## Pre-requisites
* Python 3.X
* `bs4` through pip, for parsing HTML.

## Usage
`python scraper.py`

### Optional Arguments:
* `--force-dl`: By default, the application skips pre-existing subs. If you want to force a re-download, you can set this.
* `--use-local`: The main page gets downloaded to `./pages` before being operated on. If you set this flag, it won't re-download the page. This is primarily here for debug purposes.
* `--override-dir`: The default output dir for subs is `./data`. If you want to override this, you can pass it a string.