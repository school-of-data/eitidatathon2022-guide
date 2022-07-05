---
layout: scenario-page
img: scenario-1.png
# img-attr: https://www.flaticon.com/free-icons/invest
# img-attr-title: Invest icons created by Flowicon - Flaticon
title: <span class="font-weight-light">Scenario 1&#58;</span> Help officials decide how to invest government revenues to support long-term development plans.
once: a new president was elected in an oil-rich country. During the election campaign, the winning candidate had set out an ambitious long-term vision for investments in education, healthcare and infrastructure. Upon taking office, the president tasked her minister of finance with putting together a plan for financing the government’s agenda. For decades, the country’s budget had relied overwhelmingly on revenues from the oil industry. However, recent volatility in oil prices and growing global calls for action on climate change made the minister hesitant about continuing to rely upon the oil industry as a way of financing the budget.
every: officials at the ministry of finance would wonder how to deliver the president’s campaign promises. The officials were unsure how volatility in international oil prices might impact the size of the government budget and what this would mean for the amount of money available for spending on the president’s priorities. The previous year, prices had dropped as low as $20 per barrel, forcing the previous government to make painful budget cuts. Now, prices were at $120 per barrel, leading to calls for an increase in spending. However, with global action on climate change gathering momentum, and many major economies investing heavily in low-carbon technologies to reduce their reliance on fossil fuels, officials were hesitant about assuming oil prices would remain at such high levels. They wanted to put together a sustainable spending plan that they would be able to finance even if oil prices dropped. But the officials did not know what the implications of different price scenarios really were for the amount of money they would have at their disposal.
until: officials were able to systematically forecast what different oil price scenarios would mean for the government’s ability to deliver on its election promises. Based on this, officials devised a long-term plan for investments in healthcare, education and infrastructure that would be feasible even if oil prices were low. The government put in place plans to diversify its economy to reduce its reliance on oil revenues.
keywords: [national politics, campaign promises, income forecasting, compromises, good governance, scenario modelling, government, decision-making]
reco: [""]
audience: ["<strong>government officials</strong> - they are the primary users and audience of your solution which should allow them to forecast government revenues based on different oil price scenarios."]
lookout: [""]
data_resource: [Summary data from EITI reports, "Revenue data", "Production data", "Price data", "EITI API"]
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
{% for item in site.collection_scenario_1_data %}
    <div class="bg-color-muted rounded px-4 py-2 mb-4 color-black" id="{{ item.id }}">
        <h2><strong>{{ item.name }}</strong></h2>
        <h3>What is it?</h3>
        <p>{{ item.what }}</p>
        <h3>Where to get it?</h3>
        <p>{{ item.where }}</p>
        <!-- <h3>Data dictionary</h3>
        <p></p> -->
        <h3>Tips and advice about the resource</h3>
        <p>{{ item.tips }}</p>
    </div>
{% endfor %}
</section>