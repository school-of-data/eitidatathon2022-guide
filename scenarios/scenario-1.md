---
layout: scenario-page
img: scenario-1.png
# img-attr: https://www.flaticon.com/free-icons/invest
# img-attr-title: Invest icons created by Flowicon - Flaticon
title: Help officials decide how to invest government revenues to support long-term development plans.
once: a new president was elected in an oil-rich country. During the election campaign, the winning candidate had set out an ambitious long-term vision for investments in education, healthcare and infrastructure. Upon taking office, the president tasked her minister of finance with putting together a plan for financing the government’s agenda. For decades, the country’s budget had relied overwhelmingly on revenues from the oil industry. However, recent volatility in oil prices and growing global calls for action on climate change made the minister hesitant about continuing to rely upon the oil industry as a way of financing the budget.
every: officials at the ministry of finance would wonder how to deliver the president’s campaign promises. The officials were unsure how volatility in international oil prices might impact the size of the government budget and what this would mean for the amount of money available for spending on the president’s priorities. The previous year, prices had dropped as low as $20 per barrel, forcing the previous government to make painful budget cuts. Now, prices were at $120 per barrel, leading to calls for an increase in spending. However, with global action on climate change gathering momentum, and many major economies investing heavily in low-carbon technologies to reduce their reliance on fossil fuels, officials were hesitant about assuming oil prices would remain at such high levels. They wanted to put together a sustainable spending plan that they would be able to finance even if oil prices dropped. But the officials did not know what the implications of different price scenarios really were for the amount of money they would have at their disposal.
until: officials were able to systematically forecast what different oil price scenarios would mean for the government’s ability to deliver on its election promises. Based on this, officials devised a long-term plan for investments in healthcare, education and infrastructure that would be feasible even if oil prices were low. The government put in place plans to diversify its economy to reduce its reliance on oil revenues.
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

