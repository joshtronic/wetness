# wetness

`wetness` is a `bash` script for checking a CSS file for duplicate properties.
Just like [Ellie Kemper][BJ], the aim of this script is to help make it DRY.

This script utilizes associative arrays in `bash` which requires version 4 or
better. OSX is still shipping with version 3.2 but you can easily upgrade to
4.2 with `brew install bash`.

## Usage

```sh
./wetness /path/to/file.css
```

## Installation

### OSX via Homebrew

```sh
brew tap joshtronic/homebrew-formulae
brew install wetness
```

  [BJ]: http://www.collegehumor.com/video/1183463/derrick-comedy-blowjob
