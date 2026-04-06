



# Life

Here I write about daily life, thoughts, books, travel, and small moments.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
