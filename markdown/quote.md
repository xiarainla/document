一、Markdown使用电子邮件样式的>字符进行块引用。如果您熟悉在电子邮件中引用文本段落，那么您就知道如何在Markdown中创建块引用。如果您硬包装文本并>在每行之前放置一个，它看起来最好：

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

二、Markdown允许你变懒，只把它放在>硬包装段落的第一行之前：
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

三、可以通过添加以下附加级别来嵌套块引用（即块引用块引用）>：
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

四、Blockquotes可以包含其他Markdown元素，包括标题，列表和代码块：
> #### This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
     return shell_exec("echo $input | $markdown_script");
