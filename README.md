> Man, if I put `brew update` into my .zshrc, I'll be so up to date on all the
> libraries I use! I NEVER remember to run that command.
>
> - Me, like a month ago

> HOLY CRAP, I have to wait through an entire network call AND download a bunch
> of metadate updates AND update homebrew EVERY SINGLE TIME I open a fucking
> tmux split?
>
> - Me, before I wrote this

#### this
```ruby
#! /usr/bin/env ruby

exec "brew update" if (1..10).to_a.sample == 1
```
