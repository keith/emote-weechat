# emote-weechat

This is a simple [weechat](https://weechat.org/) plugin that allows you
insert unicode faces into the current buffer.

## Usage:

1. `/emote tableflip`
1. `(╯°□°）╯︵ ┻━┻`
1. Profit.

## Installation

Copy the script to `~/.weechat/python/autoload`

```sh
mkdir -p ~/.weechat/python/autoload
wget https://raw.githubusercontent.com/keith/emote-weechat/master/emote.py ~/.weechat/python/autoload
```

This is a python rewrite of [this plugin](https://weechat.org/scripts/source/emote.scm.html/)
