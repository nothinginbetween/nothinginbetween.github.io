---
layout: default
---

<section class="posts">
    <ul>
        {% for post in site.posts %}
        <li>
            <div class="mypost">
                <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
                </h3>
                <p class="postsummary">{{post.summary}}</p>
                <p class="postdate" datetime="{{ page.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d,
                    %Y" }}</p>
            </div>
        </li>
        {% endfor %}
    </ul>
</section>