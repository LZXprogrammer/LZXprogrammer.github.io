---
layout: default
title:  "Welcome to LZXprogrammer@Blog!"
date:   2018-04-25 17:50:00
categories: main
excerpt: "这是一个摘要"
---

<ul>
  {% for post in site.posts %}
    <li>
      <!-- <a href="{{ post.url }}">{{ post.title }}</a> -->
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

欢迎读者进入我的博客！
## 特点：
我是一个PHPer，这个博客主要以技术为主。目标冲向 `全栈工程师`。

还有很多别的项目可以去我的 [LZXprogrammer Github][LZX@github] 查看。

[LZX@github]: https://github.com/LZXprogrammer

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

<!-- You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com -->