---
layout: scenario-page
img: scenario-4.png
# img-attr: https://www.flaticon.com/free-icons/data-collection
# img-attr-title: Data collection icons created by Becris - Flaticon
title: <span class="font-weight-light">Scenario 4&#58;</span> Supporting government officials to understand company disclosures in a context of volatility and uncertainty
once: a country’s extractive industries were experiencing significant uncertainty as a result of the global energy transition. Commodity prices were volatile, and some companies were ramping up production, while others were scaling back their activities. This was resulting in big changes in the revenues the government was collecting. Citizens were demanding answers from the government about why the revenues paid by some companies varied so dramatically from year to year.
every: government officials would wonder how to respond to the questions coming from citizens. While EITI disclosures shed light on the payments companies were making, officials needed a way of explaining what was driving the changes in payments. They wanted to know to what extent revenue flows were influenced by factors like commodity prices, production volumes, project costs or the nature of the country’s fiscal regime.
until: the government had a tool that allowed them to better explain the revenue payments being made by companies. This helped the government to build trust with civil society and companies around the sector’s revenue flows.
keywords: [trust, accountability, uncertainty, disclosures, data quality, data validation, government payments]
reco: ["The <strong>pain point</strong> in this scenario involves: <ul><li>understanding what drives changes in revenue payments.</li></ul>", "An <strong>entry point</strong> for your solution can be in the the <strong>accounting and budget forecasting processes</strong> of the government, <strong>EITI reporting</strong>, or even the <strong>revenue payments reporting</strong> of extractive companies.", "An example of a country with multiple years of revenue and production data is <a href='https://drive.google.com/drive/folders/0B361RU22DTPfd1d4NERBQUgzVHc?resourcekey=0-Ju6bXQ-PU6Zh_07ecZ1BdQ&usp=sharing'>Senegal</a>.", "You can also use the <a href='https://eiti.org/api'>EITI API</a> to fetch specific datasets based on your needs.", "<strong>Remember: We do not expect perfect solutions</strong>—the focus of this event is on prototyping ideas, rather than creating perfect tools."]
audience: ["<strong>government officials</strong> - your solution should enable government officials to determine and understand what drives changes in the payments."]
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