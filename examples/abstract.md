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

## Redalyc

Publish two abstract in two languages


```
<abstract xml:lang="es">
<title>Resumen</title>
<p>Para determinar la eficacia de los mapas conceptuales en el desarrollo de las competencias informacionales se seleccionaron, mediante la técnica de muestreo no probabilístico, 30 estudiantes matriculados en un curso de Gerencia en la Universidad de Puerto Rico en Bayamón (UPRB) durante el año académico 2012-2013. Se utilizó un enfoque de investigación cuantitativo y un diseño cuasi-experimental. Los estudiantes participaron en una unidad instruccional sobre búsqueda y evaluación de información, basada en mapas conceptuales. Para determinar el aprendizaje de los estudiantes se administró un examen que también fue utilizado comopreprueba. Para conocer su opinión sobre la estrategia implementada se administró un cuestionario de opinión. Debido a que hubo un aumento significativo en las medias aritméticas de lapospruebacuando se comparó con las medias de laprepruebase concluyó que los mapas conceptuales representan una estrategia efectiva para el aprendizaje de competencias de búsqueda y evaluación de información.</p>
</abstract>
<trans-abstract xml:lang="en">
<title>Abstract</title>
<p>To determine the effectiveness of concept mapping in developing information skills, through nonprobability sampling technique were selected 30 students enrolled in a Management course at the University of Puerto Rico at Bayamon during the academic year 2012-2013. A quantitative research approach and aquasiexperimentaldesignwasused. The students participated in an instructional unit on searching and evaluating information, based on concept maps. To determine student learning a test was used as a pre and posttest. To know the opinion of students on the strategy implemented an opinion questionnaire was administered. Because there was a significant increase in the arithmetic means of the posttest when compared with average pretest it was concluded that concept maps represent an effective strategy for learning skills of finding and evaluating information.</p>
</trans-abstract>
```