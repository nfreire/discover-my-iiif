---


---

<h1 id="pumi">PuMI</h1>
<p>PublishMyIIIF (PuMI) is a <strong>tool</strong> for Cultural Heritage (CH) institutions that have a IIIF service and want <strong>to maximize the discoverability</strong> of their digitized CH objects, <strong>in Internet search engines and Cultural Heritage aggregators</strong>.</p>
<p>PuMI provides discoverability functionality by implementing some key technologies and W3C recommendations for interoperability of IIIF services with Internet search engines, Linked Data, and CH specific portals. The key technologies are <a href="http://schema.org">Schema.org</a>, <a href="https://www.sitemaps.org/">Sitemaps</a>, <a href="https://www.w3.org/Protocols/rfc2616/rfc2616-sec12.html">HTTP Content Negotiation</a>, <a href="https://en.wikipedia.org/wiki/Microformat">microformats</a>, <a href="https://www.w3.org/RDF/">RDF</a>, and <a href="https://iiif.io/api/discovery">IIIF Change Discovery</a>.</p>
<p>To enable the functionality provided by PuMI, a data provider needs to have a running IIIF server, implementing the IIIF Presentation API. Some key parts of the IIIF specifications must be implemented by the service. To enable PuMI, a IIIF service must provide:</p>
<ul>
<li>IIIF  Presentation API <a href="https://iiif.io/api/presentation/2.1/">version 2</a> or <a href="https://iiif.io/api/presentation/3.0/">version 3</a></li>
<li>IIIF Presentation API <a href="https://iiif.io/api/presentation/3.0/#51-collection">Collection</a>(s)</li>
<li>Structured metadata regarding the digital CH objects must be referenced from within the Manifests (through ‘seeAlso’ properties)</li>
<li>Metadata must be available in one of the following models:
<ul>
<li><a href="https://pro.europeana.eu/resources/standardization-tools/edm-documentation">Europeana Data Model</a></li>
<li><a href="http://schema.org">Schema.org</a></li>
<li><a href="http://dublincore.org/">Dublin Core</a></li>
</ul>
</li>
</ul>

