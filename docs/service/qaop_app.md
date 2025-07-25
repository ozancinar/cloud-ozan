# qAOP-App

<!--- This file is autogenerated. Edit qaop_app.json to make changes in this page. --->

An interactive tool offering an overview and dynamic time‐course predictions of KEs and AOs via ODE‐based qAOP models, based on VHP4Safety case studies.

No screenshot available.

## Documentation

* Service Introduction: [qAOP App: Predicting Key Events and Adverse Outcomes Over Time](https://docs.vhp4safety.nl/en/latest/tutorials/qaop_app/qaop_tutorial.html)

* Workflow: To be added

* Demo: To be added

<h4 id='tess-widget-materials-header'></h4>

<div id='tess-widget-materials-list' class='tess-widget tess-widget-list'></div>
<script>
  function initTeSSWidgets() {
    var query = 'qaop_app';
    if (query.trim() != '') {
      TessWidget.Materials(document.getElementById('tess-widget-materials-list'),
                           'SimpleList',
                           {
                             opts: {
                               enableSearch: false
                             },
                             params: {
                               pageSize: 5,
                               q: query
                             }
                           });
      document.getElementById('tess-widget-materials-header').innerHTML = 'Documentation from ELIXIR TeSS'
    }
}
</script>
<script async='' defer='' src='https://elixirtess.github.io/TeSS_widgets/components/js/tess-widget-standalone.js' onload='initTeSSWidgets()'></script>


## VHP4Safety Service Metadata

* Stage: <span class="glossary_term">[https://vhp4safety.github.io/glossary#VHP0000102](https://vhp4safety.github.io/glossary#VHP0000102)</span>

* Sub-stage: <span class="glossary_term">[https://vhp4safety.github.io/glossary#VHP0000023](https://vhp4safety.github.io/glossary#VHP0000023)</span>

* Development Cloud: [https://qaop.vhp4safety.nl/](https://qaop.vhp4safety.nl/)

* Login Required: Not available

* TRL: Not available

* Type: internal

* Contact: Filippo Di Tillio (f.di.tillio@lacdr.leidenuniv.nl)

* API Type: Not available

* Categories: To be added

* Targeted Users: To be added

* Relevant VHP4Safety Use Case: To be added

## Technical Tool Specifications

* Provider: [Leiden University](https://www.universiteitleiden.nl/en)

* Citation: Not available

* Version: Not available

* License: Not available

* Source Code: [https://github.com/VHP4Safety/qAOP-app](https://github.com/VHP4Safety/qAOP-app)

* Docker: Not available

* Bio.tools: Not available

* FAIRsharing: Not available

* TeSS: Not available

* RSD: Not available

* Wikipedia: Not available

<script type="application/ld+json">
  {
    "@context": "https://schema.org/",
    "@type": "SoftwareApplication",
    "http://purl.org/dc/terms/conformsTo": {
      "@type": "CreativeWork", "@id": "https://bioschemas.org/profiles/ComputationalTool/1.0-RELEASE"
    },
    "@id" : "https://vhp4safety.github.io/cloud/service/qaop_app",
    "name": "qAOP-App",
    "description": "An interactive tool offering an overview and dynamic time‐course predictions of KEs and AOs via ODE‐based qAOP models, based on VHP4Safety case studies.",
    "url": "https://qaop.vhp4safety.nl/"
  }
</script>
