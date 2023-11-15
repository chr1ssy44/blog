# christina's blog
Hello, *welcome* to my **blog**! Here I will discover new ways to debug 👾 problems in coding 💻. I hope you will follow me in my *journey* by reading my blog!

![A professional photo of me..coming soon](/assets/)
![bar graph](output.jpg/assets/)

## Recent Posts
<ul>
    {% for post in site.posts %}
    <li>
    <a href="/blog{{post.url}}"> {{post.title}}</a>
    </li>
    {%endfor%}
</ul>