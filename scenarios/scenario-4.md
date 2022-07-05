---
layout: scenario-page
img: scenario-4.png
# img-attr: https://www.flaticon.com/free-icons/data-collection
# img-attr-title: Data collection icons created by Becris - Flaticon
title: <span class="font-weight-light">Scenario 4&#58;</span> Support government officials to analyse company disclosures in a context of volatility and uncertainty.
once: a country’s extractive industries were experiencing significant uncertainty as a result of the global energy transition. Commodity prices were volatile and the long-term prospects for the sector unclear. Some companies were ramping up production, others were scaling back their activities. This was resulting in big changes in the revenues the government was collecting from different companies. While EITI disclosures shed light on the payments companies were making, government officials were unsure whether those amounts reflected how much companies should have paid.
every: government officials would wonder how to assess the quality of company disclosures. They wanted to know whether companies were paying what they owed and whether the country was getting its fair share of the sector’s benefits. The officials had access to project-level data on revenue payments and production volumes. The officials thought that by combining this information with data on commodity prices they should be able to better understand whether companies were complying with their revenue obligations.
until: the government had a tool that allowed them to estimate how much revenue different projects should have paid based on the volume and value of their production. Where big discrepancies emerged between the amounts paid and the amounts that might have been expected, the government was able to engage companies for clarification. This provided a useful means for holding companies accountable and building trust around the accuracy of company payments.
keywords: []
reco: [""]
audience: [""]
lookout: [""]
data_resource: [Summary data from EITI reports, "Revenue data", "Production data", "EITI API"]
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
{% for item in site.collection_scenario_4_data %}
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