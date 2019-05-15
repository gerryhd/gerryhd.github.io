---
title: lionsite
layout: default
---

<div>
<div id="bio-header" class="columns">
<div class="column">

<img src="{% asset_path badge.png %}">
<div>
<h4 id="lionsite">Gerardo 'Gerry' Hernandez</h4>
<div id="alias">(Lion the Golden)</div>
<p>
Hello. I am a software engineer from Mexico. I am a freelance
developer, and an adventurous Ruby on Rails enthusiast. I also
write for my blog here and sometimes make music and drawings.
</p>
</div>
</div>
</div>
<div id="footnote">
If you wanna know my opinion on things, check my blog.<br/>
If you want to know why I'm important, click on projects and check em out.<br/>
For work inquiries please click on "About me".<br/>
You can also reach me using the <a data-fancybox data-src="#modal-form" href="javascript:;"><strong>contact form  <i style="font-size: 250%;" class="fab fa-wpforms"></i></strong></a> </div>
<div id="social-media" class="columns">
<div class="column is-half is-offset-one-quarter">
<a href="https://www.facebook.com/Lionsite-639248599923794/"><div class="social-link"><i class="fab fa-facebook-square"></i></div></a>
<a href="https://twitter.com/lionthegolden"><div class="social-link"><i class="fab fa-twitter-square"></i></div></a>
<a href="https://steamcommunity.com/id/praisemyname"><div class="social-link"><i class="fab fa-steam-symbol"></i></div></a>
{% img linkst.gif %}
<a href=""><div class="social-link"><i class="fab fa-youtube"></i></div></a>
<a href="https://github.com/gerryhd/"><div class="social-link"><i class="fab fa-github"></i></div></a>
<a href="https://www.linkedin.com/in/luis-gerardo-hern%C3%A1ndez-quijano-44aa26145/"><div class="social-link"><i class="fab fa-linkedin"></i></div></a>
</div>
</div>
            <div style="text-align: center;">
            {% img blustar.gif %}<br/>
            {% img blustar.gif %}<br/>
            {% img blustar.gif %}<br/>
            {% img blustar.gif %}<br/>
            </div>
            <hr id="about-me-section">
<div class="columns">
<div id="skills" class="column is-2 is-offset-1">
<h1>Programming Skills</h1>
      {% include skill_meter.html name="Ruby" grade=4 color="c81f1e" %}
      {% include skill_meter.html name="Python" grade=3 color="333777" %}
      {% include skill_meter.html name="NodeJS" grade=3 color="333333" %}
      {% include skill_meter.html name="PHP" grade=2 color="8892bf" %}
</div>
<div id="about-me" class="column is-6" markdown="1">
<div style="margin: 5% 10%;" markdown="1">
{% include_relative about.md %}
</div>
</div>
</div>
<div style="display: none;" id="modal-form">
{% include formtastic.html %}
</div>
</div>
