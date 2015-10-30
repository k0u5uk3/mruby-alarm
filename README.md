# mruby-alarm   [![Build Status](https://travis-ci.org/k0u5uk3/mruby-alarm.png?branch=master)](https://travis-ci.org/k0u5uk3/mruby-alarm)
Alarm class
## install by mrbgems
- add conf.gem line to `build_config.rb`

```ruby
MRuby::Build.new do |conf|

    # ... (snip) ...

    conf.gem :github => 'k0u5uk3/mruby-alarm'
end
```
## example
```ruby
p Alarm.hi
#=> "hi!!"
t = Alarm.new "hello"
p t.hello
#=> "hello"
p t.bye
#=> "hello bye"
```

## License
under the MIT License:
- see LICENSE file
