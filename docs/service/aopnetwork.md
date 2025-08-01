# AOP Network Builder

<!--- This file is autogenerated. Edit aopnetwork.json to make changes in this page. --->

web-based tool for building, visualizing, and analyzing Adverse Outcome Pathway (AOP) networks. It serves as an extended user interface for the AOP-Wiki RDF SPARQL endpoint.

![AOP Network Builder logo](https://raw.githubusercontent.com/VHP4Safety/cloud/main/docs/service/aopnetwork.png)

## Documentation

* Service Introduction: [AOP Network Tool introduction]()

* Workflow: []()

* Demo: To be added

<h4 id='tess-widget-materials-header'></h4>

<div id='tess-widget-materials-list' class='tess-widget tess-widget-list'></div>
<script>
  function initTeSSWidgets() {
    var query = 'aopnetwork';
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

* Development Cloud: Not available

* Login Required: No

* TRL: Not available

* Type: internal

* Contact: Javier Millán Acosta (javier.millanacosta@maastrichtuniversity.nl)

* API Type: REST API, Flask

* Categories: To be added

* Targeted Users: To be added

* Relevant VHP4Safety Use Case: To be added

## Technical Tool Specifications

* Provider: [Department of Bioinformatics (BiGCaT), Maastricht University](https://www.maastrichtuniversity.nl/research/bioinformatics)

* Citation: Not available

* Version: Not available

* License: Not available

* Source Code: [https://github.com/VHP4Safety/aop-app](https://github.com/VHP4Safety/aop-app)

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
    "@id" : "https://vhp4safety.github.io/cloud/service/aopnetwork",
    "name": "AOP Network Builder",
    "description": "web-based tool for building, visualizing, and analyzing Adverse Outcome Pathway (AOP) networks. It serves as an extended user interface for the AOP-Wiki RDF SPARQL endpoint.",
    "url": "https://aopapp.cloud.vhp4safety.nl/"
  }
</script>
