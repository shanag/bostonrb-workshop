# Other Tools to Help You Learn Ruby
### ri
ri is a tool to look up ruby documentation:

```ruby
$ ri String.split
= String.split

(from ruby core)
------------------------------------------------------------------------------
  str.split(pattern=$;, [limit])   => anArray
------------------------------------------------------------------------------

Divides str into substrings based on a delimiter, returning an array of
these substrings.
```

![](/images/warning.png) If running ri doesn't work and you've installed ruby using rvm, try running this command first:

```ruby
$ rvm docs generate
```

You can do a lot with it:

* ri Class -- looks up the class documentation and shows all the methods available.
* ri Class.method -- looks up a specific method on a class or module.
* ri method -- searches all classes for matching methods

### irb

We've already introduced irb above, but it can't be stressed enough
that having an interactive live session with ruby is invaluable. You
can learn a lot from it.
You can do stuff like:

```ruby
$ irb
>> "blah".methods
=> [:<=>, :==, :===, :eql?, :hash, :casecmp, :+, :*, :%, :[], :[]=, :insert, :length, :size...]
```

All of these methods are available for any string. You can then use
ri to look up the method documentation. It is a great way to find goodies!


### Online Resources

[Ruby Quickref](http://www.zenspider.com/Languages/Ruby/QuickRef.html)  
Google - searching "ruby" and whatever you're looking for usually leads to good stuff.  
[Ruby Koans](http://rubykoans.com/) - a great set of lessons in an interactive form.  
[Test First Training](http://testfirst.org) - learn Ruby, one test at a time.  
[Learn to Program by Chris Pine](http://pine.fm/LearnToProgram) - also available as [a book](http://pragprog.com/book/ltp2/learn-to-program).  
[The Pickaxe](http://pragprog.com/book/ruby3/programming-ruby-1-9) - The definitive ruby reference (and has a great tutorial too).  
[Why's (poignant) Guide to Ruby](http://www.scribd.com/doc/8545174/whys-Poignant-Guide-to-Ruby) - the (crazy) guide to ruby... Try it, you might like it.  

## Next Step

Go on to [Getting Started](getting_started)
