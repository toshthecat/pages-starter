---
layout: default
title: GettiN ABbA BaCK from teh futr
quote: "Never half-ass two things. Whole-ass one thing".
cite: Ron Swanson
---

If you aren't going to smash peggy then don't talk to me.

1. [Create a Github account](https://github.com/join)
2. [Fork this repository](https://github.com/chesshacker/pages-starter/fork)
3. Edit the `_config.yml` file

{% highlight yaml %}
title: {{ site.title }}
description: >
  {{ site.description | rstrip }}
baseurl: "{{ site.baseurl }}" # the subpath of your site
url: "{{ site.url }}"
email: {{ site.email }}
github_username:  {{ site.github_username }}
linkedin_username: {{ site.linkedin_username }}
twitter_username: {{ site.twitter_username }}
{% endhighlight %}

That's it! You should now have a website of your own.

https://`your github username`.github.io/pages-starter/

There's so much more you can do with GitHub Pages, so don't stop here.
Explore the code in this project and start making it your own.
Continue on to the [Resources]({{ "/resources" | prepend: site.baseurl }})
section to learn more about GitHub Pages and other handy tools.

If you have questions, please let me know. I am glad to help!
