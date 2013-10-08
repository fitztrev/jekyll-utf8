# Jekyll UTF-8

This plugin alters the default WEBrick behavior of `jekyll serve` and sets the Content-Type header of HTML files to **text/html; charset=utf-8**.

## Installation

```bash
gem install jekyll-utf8
```

## Usage

Create a file at `_plugins/jekyll-utf8.rb` with the following contents:

```ruby
require 'jekyll-utf8.rb'
```
