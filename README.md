# TIL
Today I Learned

# 2019-12-18

## Visual Studio Markdown Editing

https://code.visualstudio.com/docs/languages/markdown

* `Ctrl+Shift+V` Preview 
* `Ctrl+k V` Open Preview to the Sidebar
* `Ctrl+Shift+P` Open Command Palette and type `markdown`

## Ruby Formatting Syntax
```
"%.2f" % 123123.123
=> "123.12"

"%05d" % 123                              #=> "00123"
"%-5s: %016x" % [ "ID", self.object_id ]  #=> "ID   : 00002b054ec93168"
"foo = %{foo}" % { :foo => 'bar' }        #=> "foo = bar"
```

https://ruby-doc.org/core-2.6/String.html#method-i-25

## Ruby 

ruby 에서 `attr_accessor` 지정해 주면, instance variable 이 method 처럼 호출 될 수 있게 된다.

```
    attr_accessor :value
    def initialize(automobile)
      @value = value
    end

    def call
      value
    end
```

[2019 12-18](/2019/20191218.md)