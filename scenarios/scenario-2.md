---
layout: scenario-page
img: scenario-2.png
# img-attr: https://www.flaticon.com/free-icons/voice
# img-attr-title: Voice icons created by Aldo Cervantes - Flaticon
title: Help empower citizens to give their voice in the debate around energy transition.
once: there was a country that was rich in oil reserves, which found itself over time in a situation where many aspects of the country had become dependent on income from the oil industry&#58; jobs, subsidies, public benefits, local government budgets etc. Civil society groups had been campaigning for years to transition away from the country’s reliance on fossil fuels, including through calls for carbon pricing. But there was no easy answer as to how that transition should happen, and how to do it fairly. 
every: civil society groups debated potential options for using carbon pricing to incentivise a shift away from fossil fuels but were aware that citizens would have to be consulted to ensure that their concerns were heard. Specifically, the idea of using carbon pricing to generate revenue that could be invested in the transition was something that needed to be discussed with the communities most dependent on oil resources. But community meetings were not enough&#58; they wanted a tool that would allow any citizen, regardless of their skill level, to understand the impact of different carbon pricing scenarios and how the revenue generated could be spent. 
until: a consensus emerged among civic organisations about the best way to communicate the need for the energy transition and the scenarios that would appear the fairest to the local communities most impacted by it.
---

<section class="d-flex flex-wrap justify-content-between align-items-center" id="intro">
    <div class="col-md-3 col-lg-2">
    <figure>
        {% if page.img-attr %}
        <a href="{{ page.img-attr }}" target="_blank" title="{{ page.img-attr-title }}">
            <img class="img-fluid" src="{{ site.baseurl }}/assets/img/scenarios/{{ page.img }}">
        </a>
        {% else %}
        <img class="img-fluid" src="{{ site.baseurl }}/assets/img/scenarios/{{ page.img }}">
        {% endif %}
    </figure>
    </div>
    <div class="col-md-9 col-lg-10">
        <p style="font-size: xx-large"><strong class="color-primary-1 mt-4">{{ page.title }}</strong></p>
    </div>
</section>

<section class="color-primary-2 rounded px-4 pt-2 pb-4 my-4" style="border: 6px solid" id="scenario">

<h1 class="color-primary-2">The scenario</h1>

<p><strong>Once upon a time,</strong> {{ page.once }}</p>
<p><strong>Every day,</strong> {{ page.every }}</p>
<p><strong class="color-primary-1" style="font-size: xx-large">This is where your proposal comes in.</strong></p>

<p><strong class="color-primary-1">How will you address the problems and challenges being faced everyday?</strong></p>
<p><strong class="color-primary-1">What changes will your solution bring so that...</strong></p>

<p><strong>Finally,</strong> {{ page.until }}</p>

</section>

<section class="color-primary-3 rounded px-4 pt-2 pb-4 my-4" style="border: 6px solid" id="starter-kit">

<h1 class="color-primary-3">Scenario Starter Kit</h1>

</section>

<section class="color-primary-4 rounded px-4 pt-2 pb-4 my-4" style="border: 6px solid" id="data-documentation">

<h1 class="color-primary-4">Data documentation</h1>

</section>
