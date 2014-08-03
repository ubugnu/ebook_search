# Ebook search tool on Calibre public online servers

This is a simple tool that allows you to:

* Search ebooks on a list of online Calibre servers
* Add online Calibre servers

## Dependencies

This script uses the native programs found in nearly any Linux distribution.

## Getting Started

Nothing to do apart downloading the shell script and installing Tor if not already done. If the script is not executable make it so:
```bash
chmod +x ebook_search
```
## Examples

Using the keyword "php":

```bash
./ebook_search --search "php"
# OR using shortcuts
./ebook_search -s "php"
```

Adding a repository:

```bash
./ebook_search --add http://127.0.0.1:8080
# OR using shortcuts
./ebook_search -a http://127.0.0.1:8080
```

### Hint

> Use [Google](https://www.google.com/search?q=inurl:browse/category/allbooks) to find such servers

## Support us

If this programs was helpful for you, please consider making a small [donation](https://www.paypal.com/fr/cgi-bin/webscr?cmd=_flow&SESSION=xZa9pm9CBWqIcw5Nb092dTDOdXRGV0TmOwr0spmz--1H_a7yYLSPQaVJCKa&dispatch=5885d80a13c0db1f8e263663d3faee8d69a70501aadbc2ff6a1e7e8cc0df6b0b) :-)