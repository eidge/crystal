# until

An `until` executes its body until its condiiton is *truthy*. An `until` is just syntax sugar for a while with the condition negated:

``` ruby
until some_condition
  do_this
end

# The above is the same as:
while !some_condition
  do_this
end
```

An `until` can also be used in its suffix form, causing the body to be executed at least once. `break` and `next` can also be used inside an `until`.