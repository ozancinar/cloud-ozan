
# BMDExpress-3

<!--- This file is autogenerated. Edit bmdexpress_3.json to make changes in this page. ---> 

A tool to perform dose response modeling for high dimensional dose-response analysis.

![BMDExpress-3 logo](https://raw.githubusercontent.com/VHP4Safety/cloud/main/docs/service/bmdexpress_3.png)

## Documentation

#### VHP4Safety Documentation

* Service Introduction: []() 

* Workflow: []() 

* Demo: []() 

<h4 id='tess-widget-materials-header'></h4>

<div id='tess-widget-materials-list' class='tess-widget tess-widget-list'></div>
<script>
  function initTeSSWidgets() {
    var query = 'bmdexpress_3';
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

* Stage: 

* Sub-Stage: 

* Development Cloud: Not available

* Login Required: 

* TRL: 

* Type: external

* Contact: Scott Auerbach (auerbachs@niehs.nih.gov)

* API Type: 

* Categories: To be added

* Targeted Users: To be added

* Relevant VHP4Safety Use Case: To be added

## Techincal Tool Specifications

* Provider: []()

* Citation: [10.1186/1471-2164-8-387](https://doi.org/10.1186/1471-2164-8-387)

* Version: 3.20.0106

* License: 

* Source Code: [https://github.com/auerbachs/BMDExpress-3](https://github.com/auerbachs/BMDExpress-3)

* Docker: []()

* Bio.tools: []()

* FAIRsharing: []()

* TeSS: []()

* RSD: []()

* Wikipedia: []()

<script type="application/ld+json">
  {
    "@context": "https://schema.org/",
    "@type": "SoftwareApplication",
    "http://purl.org/dc/terms/conformsTo": {
      "@type": "CreativeWork", "@id": "https://bioschemas.org/profiles/ComputationalTool/1.0-RELEASE"
    },
    "@id" : "https://vhp4safety.github.io/cloud/service/bmdexpress_3",
    "name": "BMDExpress-3",
    "description": "A tool to perform dose response modeling for high dimensional dose-response analysis.",
    "url": ""
  }
</script>
