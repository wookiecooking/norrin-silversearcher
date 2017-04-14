# DrFuzz

> A bash script to find a list of strings in a directory of source code.

This script is just sugar / wrapper around silver searcher, but enhancements  / functionality is incouraged.

## Use Cases

Imagine you get a new client that happens to be also running a custom WordPress template, along with a server that hasnt been maintained with no recurring backups. The client's site gets hacked and infects it all, having you to hunt down nasty strings in wp-content/themes directory.

Drfuzz helps by searching directories of source code for user-supplied dictionary text files in parallel, helping you clean up the mess and move on.

## Requirements

* bash 4.3 +
* [bc, an arbitrary precision calculator language](https://www.gnu.org/software/bc/manual/html_mono/bc.html)
* [The Silver Searcher](https://github.com/ggreer/the_silver_searcher)

## Quick Start

```bash
# give the script permisson to run
chmod +x drfuzz
# search by supplying a dictionary and the directory to search
./drfuzz /path/to/dict.txt /path/to/search
# Results will be saved to the current directory.
```

## Releases

* 0.0.2 - cleaned up and renamed file, moved date to it variable. added comments and cleaned up variable names.
* 0.0.1 - Inital Release, Proof of concept

## Testing

* Ubuntu 16.04: No Bugs / Working
* Ubuntu 14.04: No Bugs / Working

## Roadmap
TBA