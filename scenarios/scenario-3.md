---
layout: scenario-page
img: scenario-3.png
# img-attr: https://www.flaticon.com/free-icons/pie-chart
# img-attr-title: Pie chart icons created by Pixel perfect - Flaticon
title: Help improve how local populations engage with social spending data to ensure sustainable investments in their communities.
once: the mining sector of a resource-rich country was experiencing growing investor interest driven by strong global demand for minerals. Within this context, the populations living near mines wanted to understand if their communities really benefited from the mining sector’s activity. To answer that question, the Extractive Industries Transparency Initiative (EITI) published annual reports with detailed information about social spending by mining companies, which detailed the value of community payments made by companies as well as information on the intended purpose and beneficiaries of the payments. However, the EITI’s staff found that community members living near mining projects rarely read the reports.
every: EITI staff would wonder about the lack of interest in that data within communities. Speaking with community representatives, they found the explanation&#58; many community members were not aware that EITI reports contained that data, and those who did had difficulty making sense of the information as it was buried in long data tables. This was a problem, because the data could help community members better assess if companies delivered on their promised social spending and the extent to which it aligned with community priorities. Chief among those priorities was making sure that the investments were making the community more resilient and able to thrive even if the mining operations and related social payments would stop. But this wouldn’t be possible unless the information was presented in a more accessible and engaging way.
until: the EITI was able to present information on social payments in a much more compelling way. This allowed community members to better understand how company payments were impacting their lives. Community members started using EITI data to hold companies accountable when they were not making the payments they had committed themselves to or when money was being wasted on projects that communities did not want. This led to improvements in the governance of social payments, ensuring that they reached their intended beneficiaries, and genuinely improved the livelihoods of community members. 
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

