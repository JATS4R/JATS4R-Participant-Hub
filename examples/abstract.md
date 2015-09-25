# `<abstract>`

Abstracts - multiple

The @specific-use attribute may be used to identify a processing purpose, such as RSS feed or pronunciation.
The optional @abstract-type attribute may be used to identify special types of abstracts, for example, graphical abstracts, stereochemical abstracts, ASCII abstracts for sending to small devices, and Table-of-Contents abstracts that are so short they are inserted as annotations into a Table of Contents. See the attribute page for @abstract-type for a list of suggested types.

See http://jats.nlm.nih.gov/archiving/tag-library/1.1d3/attribute/abstract-type.html for suggested usage of @abstract-type attribute

## eLife

Currently publish two types of abstract. The main abstract does not take an @abstract-type attribute

```xml
<abstract>
                <object-id pub-id-type="doi">10.7554/eLife.00013.001</object-id>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>
                    <bold>DOI:</bold>
                    <ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.001"
                        >http://dx.doi.org/10.7554/eLife.00013.001</ext-link>
                </p>
            </abstract>
            <abstract abstract-type="executive-summary">
                <object-id pub-id-type="doi">10.7554/eLife.00013.002</object-id>
                <title>eLife digest</title>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>
                    <bold>DOI:</bold>
                    <ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.002"
                        >http://dx.doi.org/10.7554/eLife.00013.002</ext-link>
                </p>
            </abstract>
            </custom-meta-group>
```



## PMC

Abstract and author-summary abstract

From PLoS Genet. 2015 May; 11(5): e1005048; 10.1371/journal.pgen.1005048

```xml
      <abstract>
        <p>Whole-genome regression methods are being increasingly used for the analysis 
        and prediction of complex traits and diseases. ...</p>
      </abstract>
      <abstract abstract-type="summary">
        <title>Author Summary</title>
        <p>Whole-genome regression (WGR) methods are being increasingly used for inferring 
          the proportion of variance that can be explained by a linear regression on a massive 
          number of markers, called &#x02018;genomic heritability.&#x02019; ... </p>
      </abstract>
```
    
Abstract, TOC abstract, and author-summary abstract

From PLoS Biol. 2014 May; 12(5): e1001860; 10.1371/journal.pbio.1001860

```xml
      <abstract abstract-type="toc">
         <p>The structure of a ribosome assembly factor in complex bound to a ribosomal protein 
           uncovers a chaperoning function that uses RNA mimicry and is regulated by ATP hydrolysis.</p>
      </abstract>
      <abstract>
        <p>During biogenesis of the 40S and 60S ribosomal subunits, the pre-40S particles are exported 
          to the cytoplasm prior to final cleavage of the 20S pre-rRNA to mature 18S rRNA.  ... </p>
      </abstract>
      <abstract abstract-type="summary">
        <title>Author Summary</title>
        <p>Ribosomes are the cellular machines responsible for all protein synthesis. ... </p>
      </abstract>
```
