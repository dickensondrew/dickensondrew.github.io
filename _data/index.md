---
layout: home
---

# Welcome to My Courses!

Browse course materials for:
- [COMP 101: Intro to Programming](/comp101)
- [COMP 202: Data Structures](/comp202)

---

**Latest Announcements**  
{% for post in site.posts limit:3 %}  
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %-d, %Y" }})  
{% endfor %}