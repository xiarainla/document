一、如果要标记一小段行内代码，你可以用反引号把它包起来(`)

Use the `printf()` function.

二、如果要在代码区段内插入反引号，你可以用多个反引号来开启和结束代码区段

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

三、通过在代码块的前后输入三反引号 ```，可创建围栏代码块

```
function test() {
  console.log("notice the blank line before this function?");
}
```

四、语法突显


    ```ruby
    require 'redcarpet'
    markdown = Redcarpet.new("Hello World!")
    puts markdown.to_html
    ```


```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
