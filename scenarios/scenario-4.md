---
layout: scenario-page
img: scenario-4.png
# img-attr: https://www.flaticon.com/free-icons/data-collection
# img-attr-title: Data collection icons created by Becris - Flaticon
title: <span class="font-weight-light">Scenario 4&#58;</span> Help create a better data reconciliation process in a context of uncertainty.
once: EITI member countries published annual reports that included information on revenue flows in the extractive industries. Every year, the EITI went through data reconciliation processes in order to ensure that the data provided by the national government matched with the data provided by other stakeholders. Of particular interest was the data related to transfers of extractive sector revenues between the national government and subnational governments&#58; in a context where the government’s income from the sector varied widely from year to year, and with the energy transition promising even more uncertainty, efficiently reconciling disclosures related to the transfers made by the national government and the amounts received by subnational governments was becoming a pressing issue.
every: during the preparation of the annual report, each country’s EITI secretariat would work together with an Independent Administrator (IA) to ask the relevant agencies of both the national and the subnational governments to fill in a form on subnational transfers. If any discrepancy in the data submitted by each side appeared, a tedious, weeks-long process started to reconcile the data&#58; a back and forth of manual review, emails, excel file attachments and meetings that everyone involved found inefficient. 
until: the process of collecting and reconciling data became much more efficient, leading to a speedier validation process and an earlier release of the data to the public.
keywords: [data sharing, data collection process, streamlining, data reconciliation, national government, subnational government, financial transfer]
data_resource: [Summary data from EITI reports, Subnational transfers data]
---


<section class="color-primary-3 rounded px-4 pt-2 pb-4 my-4" style="border: 6px solid" id="starter-kit">
<h1 class="color-primary-3">Scenario Starter Kit</h1>
<h2><strong>Recommendations for your design process</strong></h2>
<p></p>

<!-- <h2><strong>Glossary of key terms</strong></h2>
<p></p> -->

<h2><strong>Who will be your audience and users?</strong></h2>
<p></p>

<h2><strong>Things to look out for</strong></h2>
<p></p>

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
    <div class="bg-color-muted rounded px-4 py-2 mb-4 color-black">
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