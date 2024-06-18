---
layout: default
---
# About

About me [about](./about)

# SAGE3

SAGE3 [the Smart Amplified Group Environment](https://sage3.sagecommons.org) is an open-source collaboration software designed for real-time interactive information and visualization sharing. Seamlessly complementing video conferencing tools like Zoom, Microsoft Teams, and Google Meets, it enhances group environments for information-rich collaboration.

With continuing funding from the National Science Foundation for the past 20 years, SAGE3 is the most powerful information collaboration platform in the world. SAGE3 users can collaborate on their laptops, meeting room projectors, and on large tiled display walls, which have been definitively shown to enable people to think, brainstorm, discover and reach decisions with greater speed, accuracy, comprehensiveness and confidence.


## Links

 - Description: [https://sage3.sagecommons.org/?page_id=921](https://sage3.sagecommons.org/?page_id=921)
 - Repository: [https://github.com/SAGE-3/next](https://github.com/SAGE-3/next)
 - Developer site: [https://sage-3.github.io/](https://sage-3.github.io/docs/intro)


# Posts
{% for post in site.posts %}
 
<ul>
 
<li><h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3></li>
 
</ul>
{% endfor %}

