  <header>
      <h1>{{ site.title | default: site.github.repository_name }}</h1>
      <h2>{{ site.description | default: site.github.project_tagline }}</h2>
    </header>
{% for post in site.posts %}   
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://myname.github.com{{ post.url }}#disqus_thread"></a></small></p>            
{% endfor %}

---
layout: post
title: About Github & Github Page
---

### Build a blog with github pages
- A tutorial with Jekyll: Fork [barryclark/jekyll-now](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/) 
- Getting started with writing and formatting on GitHub: [English](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github) [Chinese](https://docs.github.com/cn/github/writing-on-github/basic-writing-and-formatting-syntax)

### How to work with git: refer to [廖雪峰git教程](https://www.liaoxuefeng.com/wiki/896043488029600)
#### Learnt:
- Installation: [How to Install GitHub for Mac](https://www.instructables.com/How-To-Install-GitHub-For-Mac/)
  Download zip; Unzip; Drag to Applications; Open
-  Use git with command line:
   [configuration](https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496)
   [creat a repo](https://www.liaoxuefeng.com/wiki/896043488029600/896827951938304)

#### Next:
- Use git with command line:
  [remote control](https://www.liaoxuefeng.com/wiki/896043488029600/898732864121440)
