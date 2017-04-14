# DrFuzz
> A bash script to find nasty strings in source code.

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

* 0.0.1 - Inital Release, Proof of concept

## Testing

* Ubuntu 16.04: No Bugs / Working
* Ubuntu 14.04: No Bugs / Working