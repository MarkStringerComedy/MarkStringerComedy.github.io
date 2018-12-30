![Stand up comedy](StandUpBanner.jpg)
# Mark Stringer Comedy 

**This a record of my attempt to perform 50 open mic comedy gigs in 2019.  I also want to write 180 jokes (3 jokes a minute? hey! that's a one hour show).  I want to laugh a lot - and who knows? Maybe make somebody else laugh as well.**

## Gigs
<ul>
{% for gig in site.gigs %}
    <li>
      <a href="{{ gig.url }}">{{ gig.title }}</a>
    </li>
  {% endfor %}
</ul>

## Jokes

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

