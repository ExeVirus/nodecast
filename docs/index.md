---
layout: default
---

A Rolling release, interview-centered podcast all about being a player, community member, modder, and just about everything else in the Minetest world!

New episodes are released every 1st and 3rd Friday of the month, as close to 00:00:00 UTC as possible (often not hit, but I'm catching up)

Currently hosted through pcloud (cloud backup service), and YouTube. Many many more platforms are in the works, but podcasts are frowned upon by the music streaming industry, so please be patient.

____

# Episodes

____

{% assign posts = site.posts | sort: 'permalink' %}
{% for post in posts %}
-  [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{% endfor %}
