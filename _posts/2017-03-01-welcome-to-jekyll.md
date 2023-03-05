---
title: "Welcome to Jekyll"
layout: post
---

{% highlight ruby %}
class HelloPages():
  def __init__(self, page_profile):
    self.page_profile = page_profile

  def presentation(self):
    if self.page_profile == 'ktroule':
    name = 'Kevin Troulé'
    role = 'Computational biologist'
    passion = ['Statistical learning', 'Data analysis', 'Genomes', 'Health care']
    retunr f'Im {name}, a {role} who loves {','.join(list(passion))}. Nice to meet you!'
{% endhighlight %}