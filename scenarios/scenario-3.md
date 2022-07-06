---
layout: scenario-page
img: scenario-3.png
# img-attr: https://www.flaticon.com/free-icons/pie-chart
# img-attr-title: Pie chart icons created by Pixel perfect - Flaticon
title: <span class="font-weight-light">Scenario 3&#58;</span> Improving how local populations engage with social spending data to ensure sustainable investments in their communities.
once: the mining sector of a resource-rich country was experiencing growing investor interest driven by strong global demand for minerals. Within this context, the populations living near mines wanted to understand if their communities really benefited from the mining sector’s activity. To answer that question, the Extractive Industries Transparency Initiative (EITI) published annual reports with detailed information about social spending by mining companies, which detailed the value of community payments made by companies as well as information on the intended purpose and beneficiaries of the payments. However, the EITI’s staff found that community members living near mining projects rarely read the reports.
every: EITI staff would wonder about the lack of interest in that data within communities. Speaking with community representatives, they found the explanation&#58; many community members were not aware that EITI reports contained that data, and those who did had difficulty making sense of the information as it was buried in long data tables. This was a problem, because the data could help community members better assess if companies delivered on their promised social spending and the extent to which it aligned with community priorities. Chief among those priorities was making sure that the investments were making the community more resilient and able to thrive even if the mining operations and related social payments would stop. But this wouldn’t be possible unless the information was presented in a more accessible and engaging way.
until: the EITI was able to present information on social payments in a much more compelling way. This allowed community members to better understand how company payments were impacting their lives. Community members started using EITI data to hold companies accountable when they were not making the payments they had committed themselves to or when money was being wasted on projects that communities did not want. This led to improvements in the governance of social payments, ensuring that they reached their intended beneficiaries, and genuinely improved the livelihoods of community members. 
keywords: [data visualisation, EITI report, local communities, pedagogy, actionable information, social payments data]
reco: ["The <strong>pain point</strong> in this scenario involves: <ul><li>helping local populations understand how energy transition might affect their livelihoods.</li></ul>", "An <strong>entry point</strong> for your solution can be in the process of <strong>EITI reporting</strong> or in the <strong>information meetings with local population</strong>.", "You can choose a specific country with good social spending data as the subject of your proposal.", "Using the information available in the reports and other external sources, try to incorporate other parameters in your solution that provide details about the community (e.g. are most of them employed in the mining industry?) and other impacts that the mining industry has on the community (e.g. environmental impact).", "Think about how your solution can help communicate the potential of the energy transition to local communities.", "<strong>Remember: We do not expect perfect solutions</strong>—the focus of this event is on prototyping ideas, rather than creating perfect tools."]
audience: ["<strong>EITI staff</strong> - your solution should make it easier for EITI staff to communicate effectively with the community.", "<strong>Community members</strong> - your solution should enable community members to easily access, understand, and share information about how community payments by mining companies are being used."]
lookout: [""]
data_resource: [Summary data from EITI reports, Social and environmental expenditures, EITI API]
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
{% for item in site.collection_scenario_3_data %}
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