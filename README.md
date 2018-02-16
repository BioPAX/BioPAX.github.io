# BioPAX.org
(http://biopax.github.io)

Biological Pathways Exchange (BioPAX) is a standard language that aims to enable integration, exchange, visualization and analysis of biological pathway data. Specifically, BioPAX supports data exchange between pathway data groups and thus reduces the complexity of interchange between data formats by providing an accepted standard format for pathway data. It is an open and collaborative effort by the community of researchers, software developers, and institutions. BioPAX is defined in [OWL DL](http://www.w3.org/TR/owl-features/) and is represented in the RDF/XML format. [BioPAX Paper](http://www.nature.com/nbt/journal/v28/n9/full/nbt.1666.html) was published in Nature Biotechnology in 2010.

## "Hello World" example:
```
<?xml version="1.0" encoding="UTF-8"?>
<rdf:RDF
 xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
 xmlns:owl="http://www.w3.org/2002/07/owl#"
 xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
 xmlns:bp="http://www.biopax.org/release/biopax-level3.owl#" xml:base="">
<owl:Ontology rdf:about="">
 <owl:imports rdf:resource="http://www.biopax.org/release/biopax-level3.owl#" />
</owl:Ontology>
  <bp:Protein rdf:about="http://my.example.com/biopax#HelloWorld">
    <bp:displayName rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Hello World!</bp:displayName>
  </bp:Protein>
</rdf:RDF>
```

## Links:
* BioPAX ontology and documentation [releases](http://www.biopax.org/release/)
* BioPAX ontology [visualization](http://vowl.visualdataweb.org/webvowl/#iri=http://www.biopax.org/release/biopax-level3.owl) using WebVOWL (cool!)
* BioPAX secification [sub-project](https://github.com/BioPAX/specification)
* BioPAX model [examples](https://github.com/BioPAX/specification/blob/master/Level3/examples/)
* BioPAX [archive and downloads](http://www.biopax.org/downloads/biopax/)
 
## PS:
Official BioPAX web site www.biopax.org has been at CBIO MSKCC until 2013; 
then it moved to Sourceforge (Project-Web hosting, biopax.sf.net), and  
its configuration and some content were in the Hg [repository](http://hg.code.sf.net/p/biopax/site).
Now, we are migrating from Sourceforge.


Sincerely yours,

BioPAX team.
