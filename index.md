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
        <a class="btn brand" href="https://tinyurl.com/bbcs21-discord">Sign up now!</a>
	</p>
    <br/>
    </div>
</section>

## Theme: Computational Thinking and AI Education

With the increasing importance of Computing education and AI literacy globally, this year's theme will be on Computational Thinking and Artifical Intelligence Education!

<!--
## Format

Celebrating our 5th year, BuildingBloCS will be back with more exciting events and activities for everyone! This year, BuildingBloCS '21 will be held alongside the **[5th Internationl Computational Thinking Education - STEM Conference](https://cte-stem2021.nie.edu.sg/ "CTE-STEM 2021 Website")**, and we hope you can join us there!

## Workshops

**Workshop materials** and **sign-up** can be found here.<br><br>
[More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/pre-event/workshop)

## Pre-events

**Programming puzzles, pop quizzes, fun facts** will be here. The pre-events will boost your Computing prowess and help you to contribute to the progress of Singapore as a Smart Nation one step at a time, they are definitely not to be missed!<br><br>
[More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/pre-event)

## Event

[Registration is open! >>]({{ site.baseurl }}/register)

A line up of **games, talks, workshops and winpetition** will be conducted on **{{ site.date }} {{ site.location }}**! Come and join us for this year's BuildingBloCS and together let us all help to build Singapore into a **Smart Nation**!<br><br>
[More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/events-and-workshops)
-->

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
