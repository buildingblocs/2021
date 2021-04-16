---
layout: default
published: true
---

<section class="jumbo">
    <div class="main-div">
        <h1>
            {{ site.title }}<br>
            <span class="huge">2021</span>
        </h1>
        <p>
            {{ site.date }} 
            <br/>
            {{ site.location }}
        </p>
	<p>
	    <h3>BuildingBloCS is going international with <a href="https://cte-stem2021.nie.edu.sg/">CTE-STEM 2021</a>!</h3>
        <h3>Registration for BuildingBloCS 2021 is now open!</h3>
        <a class="btn brand" href="{{ site.baseurl }}/join-us/">Sign up now!</a>
	</p>
    <br/>
    </div>
</section>

## Theme: Computational Thinking and AI Education

With the increasing importance of Computing education and AI literacy globally, this year's theme will be on Computational Thinking and Artifical Intelligence Education!

## Organisers

<section class="organisers">
    {% for organiser in site.data.organisers %}
    <a href="{{ organiser.url }}">
        <img src="{{ site.baseurl }}/assets/img/{{ organiser.img }}" title="{{ organiser.title }}" />
    </a>
    {% endfor %}
</section>

## Partners

<section class="organisers">
    {% for partner in site.data.partners %}
    <a href="{{ partner.url }}">
        <img src="{{ site.baseurl }}/assets/img/{{ partner.img }}" title="{{ partner.title }}" />
    </a>
    {% endfor %}
</section>
