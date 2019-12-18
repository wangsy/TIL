# TIL
Today I Learned

# 2019-12-18

## Ruby Formatting Syntax
```
"%.2f" % 123123.123
=> "123.12"

"%05d" % 123                              #=> "00123"
"%-5s: %016x" % [ "ID", self.object_id ]  #=> "ID   : 00002b054ec93168"
"foo = %{foo}" % { :foo => 'bar' }        #=> "foo = bar"
```

https://ruby-doc.org/core-2.6/String.html#method-i-25

[2019 12-18](/2019/20191218.md)