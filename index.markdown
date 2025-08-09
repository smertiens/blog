---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Welcome!
---

I am a former Web and Python developer turned physician training in internal medicine. This is my personal blog where I write mostly write about my way to discovering understanding machine and deep learning methods. Although familiar with Python there is much to learn about the mechanisms, methods and mathematics behind the ever growing amount of AI tools, not only in the medical field. I believe that trying to communicate and explain topics in a graphical and simple way is a cornerstone in successfull learning. 

## Recent posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>