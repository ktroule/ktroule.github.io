---
title: "Presentaion"
layout: post
---

{% highlight python %}
class Presentation():
  def __init__(self, page_profile):
    self.page_profile = page_profile

  def presentation(self):
    if self.page_profile == 'ktroule':
    name = 'Kevin Troule'
    role = 'Computational biologist'
    passion = ['Statistical learning', 'Data analysis', 'Genommics', 'Health care']
    return f'Im {name}, a {role} who loves; {','.join(list(passion))}. Nice to meet you!'

Presentation(page_profile = 'ktroule')

> Im Kevin Troule, a Computational biologist who loves: Statistical learning, Data analysis, Genomics, Health care. Nice to meet you!
{% endhighlight %}