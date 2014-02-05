# Superfight

An implementation of superfight code

This is an example for a class

## Installation

Add this line to your application's Gemfile:

    gem 'superfight', github: 'noahpatterson/superfightGem'

And then execute:

    $ bundle

## Usage

Simply adds a supefight simulator.

```
puts 'What is your first fighters name?'
fighter_a = $stdin.gets
puts 'what is you second fighters name?'
fighter_b = $stdin.gets

match = Match.new(Fighter.new(fighter_a), Fighter.new(fighter_b))

puts "The winner of match is .......... #{match.winner.name}"
```

## Contributing

1. Fork it ( http://github.com/<my-github-username>/superfight/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
