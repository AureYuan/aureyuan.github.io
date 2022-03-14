***
# Welcome !
Welcome to my blogs' repository.   
I will write down the develop process here.  
***
<br>

### About ***Jekyll***
Github recommend user to use jekyll as their web design tool and github use it to generate our website ***by default***. <br>
However, jekyll does not support Windows yet, and I do not want to install environment in order to use jekyll.<br>
So I decided to config jekyll myself and try to find a way let github render my website as I want.

### Ways to create my blogs
Since Github use jekyll by default, so the only downside of not install jekyll into local is you cannot test it locally and immediately. <br>
Therefore, I am going to try all files manually. My ***final goal*** is to achieve whatever the website I want. <br>
<p>
It is clear that Jekyll will create website layout according to the order of layers that has specified in <i>_layouts</i> directory.<br>
In my homepage, layout will show like below:

>default.html
>>page.html
>>>index.html

they are connected through the command 
[{{ content }}](https://jekyllrb.com/tutorials/convert-site-to-jekyll/#2-identify-the-content-part-of-the-layout)
, and this command allow the text pass through all layers of layout.
</p>
