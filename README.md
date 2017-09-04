# Norrin
![Norrin](https://github.com/wookiecooking/norrin-silversearcher/blob/master/assets/norrin.jpg?raw=true)

> A bash script to find a list of strings in a directory of source code.

This bash script is sugar / wrapper around [The Silver Searcher](https://github.com/ggreer/the_silver_searcher)

## Use Cases

Imagine you get a new client that happens to be also running a custom WordPress template, along with a server that hasnt been maintained with no recurring backups. The client's site gets hacked and infects it all, having you to hunt down nasty strings in wp-content/themes directory.

Norrin helps by searching directories of source code for user-supplied dictionary text files in parallel, I.E. automated grepping directories.

## Requirements

* bash 4.3 +
* [bc, an arbitrary precision calculator language](https://www.gnu.org/software/bc/manual/html_mono/bc.html)
* [The Silver Searcher](https://github.com/ggreer/the_silver_searcher)

## Quick Start

```bash
# give the script permisson to run
chmod +x norrin
# search by supplying a dictionary and the directory to search
./norrin /path/to/dict.txt /path/to/search
# Results will be saved to the current directory.
```

## Releases

* 0.0.2 - cleaned up and renamed file, moved date to it variable. added comments and cleaned up variable names.
* 0.0.1 - Inital release, proof of concept

## Testing

* Ubuntu 16.04: No Bugs / Working
* Ubuntu 14.04: No Bugs / Working

## Roadmap
TBA
