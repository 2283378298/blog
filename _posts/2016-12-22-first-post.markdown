---
layout: post
title: "第一篇测试"
date: 2016-12-22 18:15 +0800
categories: news
---
![xx]({{ site.baseurl }}/images/cat.jpg)


[第一篇文章]({% post_url 2016-12-22-welcome-to-jekyll %})

----

**测试**

> 测试

----

- 得到
- 直呼
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
{% endhighlight %}

```ruby
def demo
  puts demo
  puts "Hi, #{name}"
  User Name: {{ user.username }}
  Password: {{ user.password }}
end
{% raw %}
  User Name: {{ user.username }}
  Password: {{ user.password }}
{% endraw %}
```

{% raw %}
```
User Name: {{ user.username }}
Password: {{ user.password }}
```
{% endraw %}