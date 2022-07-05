---
layout: scenario-page
img: scenario-2.png
# img-attr: https://www.flaticon.com/free-icons/voice
# img-attr-title: Voice icons created by Aldo Cervantes - Flaticon
title: <span class="font-weight-light">Scenario 2&#58;</span> Help empower citizens to give their voice in the debate around energy transition.
once: there was a country that was rich in oil reserves, which found itself over time in a situation where many aspects of the country had become dependent on income from the oil industry&#58; jobs, subsidies, public benefits, local government budgets etc. Civil society groups had been campaigning for years to transition away from the country’s reliance on fossil fuels, including through calls for carbon pricing. But there was no easy answer as to how that transition should happen, and how to do it fairly. 
every: civil society groups debated potential options for using carbon pricing to incentivise a shift away from fossil fuels but were aware that citizens would have to be consulted to ensure that their concerns were heard. Specifically, the idea of using carbon pricing to generate revenue that could be invested in the transition was something that needed to be discussed with the communities most dependent on oil resources. But community meetings were not enough&#58; they wanted a tool that would allow any citizen, regardless of their skill level, to understand the impact of different carbon pricing scenarios and how the revenue generated could be spent. 
until: a consensus emerged among civic organisations about the best way to communicate the need for the energy transition and the scenarios that would appear the fairest to the local communities most impacted by it.
keywords: [trust, narrative, dialogue, income forecasting, scenario modelling, compromises, local impact, citizens, pedagogy, carbon emissions, non-technical audience]
reco: []
audience: []
lookout: []
data_resource: [Summary data from EITI reports, "Revenue data", "Production data", "Carbon emissions data", "Carbon pricing data", "EITI API"]
---

<section class="color-primary-3 rounded px-4 pt-2 pb-4 my-4" style="border: 6px solid" id="starter-kit">
<h1 class="color-primary-3">Scenario Starter Kit</h1>
<h2><strong>Recommendations for your design process</strong></h2>
<p>
    <ul class="color-black">
    {% for item in page.reco %}
        <li>{{ item }}</li>
    {% endfor %}
    </ul>
</p>

<!-- <h2><strong>Glossary of key terms</strong></h2>
<p></p> -->

<h2><strong>Who will be your audience and users?</strong></h2>
<p>The key stakeholders for this scenario are:
    <ul class="color-black">
    {% for item in page.audience %}
        <li>{{ item }}</li>
    {% endfor %}
    </ul>
</p>

<!-- <h2><strong>Things to look out for</strong></h2>
<p>
<ul class="color-black">
    {% for item in page.lookout %}
        <li>{{ item }}</li>
    {% endfor %}
    </ul>
</p> -->

<h2><strong>Recommended data and resources</strong></h2>
<p>
    <ul class="color-black">
    {% for item in page.data_resource %}
        <li>{{ item }}</li>
    {% endfor %}
    </ul>
</p>

</section>


<section class="color-primary-4 rounded px-4 pt-2 pb-4 my-4" style="border: 6px solid" id="data-documentation">
<h1 class="color-primary-4">Data and resource documentation</h1>
{% for item in site.collection_scenario_2_data %}
    <div class="bg-color-muted rounded px-4 py-2 mb-4 color-black" id="{{ item.id }}">
        <h2><strong>{{ item.name }}</strong></h2>
        <h3>What is it?</h3>
        <p>{{ item.what }}</p>
        <h3>Where to get it?</h3>
        <p>{{ item.where }}</p>
        <!-- <h3>Data dictionary</h3>
        <p></p> -->
        <h3>Tips and advice about the resource</h3>
        <p>
        <ul class="color-black">
        {% for tip in item.tips %}
            <li>{{ tip }}</li>
        {% endfor %}
        </ul>
        <!-- {{ item.tips }} -->
        </p>
    </div>
{% endfor %}
</section>

<section class="pt-2 pb-4 container-fluid bg-color-muted" id="apply">
  {% include scenario-apply.html %}
</section>