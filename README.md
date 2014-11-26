farbox_templates
================


About
-----
This project is about jinja2 templates for [farbox blog](http://yih.farbox.com). 
this is Jinja2 syntax, besides farbox, other blog platform with Jinja2 templates can work too.

To use these templates, take farbox for example, you can copy the template folder and put it under your XXX.farbox.com folder, then set your `Template Priority` to `Custom Template`. make sure the template folder name just be **template**. I suggest you to see more details below for each template.

Details
-------
this part is some description of each template. when using anyone of them, rename the folder to **template**.

### html5 UP - Alpha
this template comes from [html5 UP](http://html5up.net/), and currently the only template in this project. a little adjust was made to fix into farbox blog.

#### pages included
for now, this template has three main page: [home(index)](http://yih.farbox.com), [archive](http://yih.farbox.com/archive), [post](http://yih.farbox.com/post/2014-11-17) and a simple 404 page.

#### comment system
the comment system I used is *disqus*, and the corresponding script codes are in './includes/comments.html', you should get your own comment code instead, this proccess is not hard, just go to the [disqus](http://disqus.com), and follow the instruction. Since farbox default template can use disqus too, maybe there is another way to install your comment system.

#### google code prettify
for better using, [google code prettify](https://code.google.com/p/google-code-prettify/wiki/GettingStarted) JavaScript added. 
The codes(C++, Python, html, etc.) you post will look more beautiful than default template. But, too long code present in a blog? no good, it's ugly. don't present source code too often, or you can just remove the google code prettify system.