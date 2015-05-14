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

