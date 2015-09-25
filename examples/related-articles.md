# `<related-article>`

Related article linking


## eLife
For linked articles within the eLife journal:


```xml
<article-meta>
...
<related-article ext-link-type="doi" id="ra1" related-article-type="commentary" xlink:href="10.7554/eLife.00013"/>
...
</article-meta>
```


For linked articles outside the eLife journal. This is not an elegant solution and was based on the only way the host could manage this link and for our team to be able to distinguish the linking:


```
<history>
    ...

<fn>
    <p>
        <mixed-citation publication-type="journal">
        <person-group person-group-type="author">
        <name><surname>Sirota</surname><given-names>M</given-names></name><name><surname>Dudley</surname><given-names>JT</given-names></name><name><surname>Kim</surname><given-names>J</given-names></name><name><surname>Chiang</surname><given-names>AP</given-names></name><name><surname>Morgan</surname><given-names>AA</given-names></name><name><surname>Sweet-Cordero</surname><given-names>A</given-names></name><name><surname>Sage</surname><given-names>J</given-names></name><name><surname>Butte</surname><given-names>AJ</given-names></name>
        </person-group>.
        <year>2011</year>. 
        <article-title>Discovery and Preclinical Validation of Drug Indications Using Compendia of Public Gene Expression Data</article-title>. 
        <source>Science Translational Medicine</source> <volume>3</volume>:<fpage>96ra77</fpage>. 
        doi: <pub-id pub-id-type="doi">10.1126/scitranslmed.3001318</pub-id>.</mixed-citation>
    </p>
</fn>
</history>
...
```


## PMC
Related articles in different journals, demonstrating use of @journal-id and @journal-id-type.

With DOI as @xlink:href:

From Front Neurosci. 2014; 8: 300; 10.3389/fnins.2014.00300
```xml
<related-article id="RA1" related-article-type="commentary-article" 
        journal-id="Brain Struct Funct" journal-id-type="nlm-ta" 
        xlink:href="10.1007/s00429-013-0684-6" ext-link-type="doi">...</related-article>
```

With @vol and @page:

From Front Oncol. 2014; 4: 235; 10.3389/fonc.2014.00235
```xml
<related-article id="RA1" related-article-type="commentary-article" 
        journal-id="Proc Natl Acad Sci U S A" journal-id-type="nlm-ta" 
        vol="111" page="29">...</related-article>
```

Related article defined soley by PubMed ID:

From Commun Integr Biol. 2014; 7: e29483; 10.4161/cib.29483
```xml
<related-article related-article-type="article-reference" 
        xlink:href="24643499" ext-link-type="pmid" id="REL1"/>
