# Giantess class
I wrote this to mess around with classes in Ruby.

## Using the predefined giantess scripts
Just run the Ruby files that end in `-gts`.

## Creating your own giantess
It should look like this:

```ruby
#!/usr/bin/ruby

require giantess # important, as this provides access to the Giantess class

GtsVarName = Giantess.new("Giantess", "heel", 50)
                        # name   # footwear # cruelty 
```

## Functions
### `NoticeTiny`
```ruby
GtsVarName.NoticeTiny
```
This will make the giantess notice the tiny.

If the giantess is bored, she will, depending on her cruelty level, either play with the tiny or step on it. 

If she is not bored, she will simply ignore the tiny.

By default, the giantess is bored, and will toggle between being bored or not.