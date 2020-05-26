# openring.py
> generate a webring from rss feeds

## Dependencies

- `arrow`
- `jinja2` (optional)
- `feedparser`

## Usage

Put your feeds, one per line, into `feeds.txt`, and the script will
output raw HTML to STDOUT. Do with it what you will. Pass the `-j` flag
if you want it to render into a Jinja template. 

Doesn't work? Edit the script to suit your needs.

