gollum -- With facebook like and share
======================================

## Installation

```bash

$ git clone git@github.com:iamsreeju/gollum.git
$ cd gollum
$ gem build gollum.gemspec
$ gem install gollum-3.0.0.gem
$ sudo apt-get install libicu-dev (If gollum installation failed, then try again)
$ mkdir ../testing
$ cd  ../testing
$ git init
$ gollum

Check with http://localhost:4567

For facebook share and like option, a different URL is hardcoded instead of localhost. Facebook integration loads the URL into the popup before sharing which will not work with localhost URLs.