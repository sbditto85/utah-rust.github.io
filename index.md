layout: default.liquid
---
## Announcements!

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}

## Meetups

[2018 August]({{ site.base_url }}/events/2018-08-09-meetup-3-hack-and-learn.html)

[2018 July]({{ site.base_url }}/events/2018-07-19-meetup-2-how-to-start-hacking-in-rust.html)

[2018 June]({{ site.base_url }}/events/2018-06.html)
