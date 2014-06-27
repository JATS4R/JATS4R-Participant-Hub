# `<caption>`

Figure and table captions.

## PeerJ

```xml
<!-- figure -->
<fig id="fig-1">
  <label>Figure 1</label>
  <caption>
    <title>Illustrating the angles of the H+ model when the hydrogen bond acceptor is sp<sup>2</sup> hybridized.</title>
    <p>Θ is the angle between atoms A and B. Φ<sub>X</sub> is the angle between the hydrogen and […]</p>
  </caption>
  <graphic mimetype="image" mime-subtype="png" xlink:href="http://example.org/fig-1.png"/>
</fig>

<!-- table -->
<table-wrap id="table-1">
  <label>Table 1</label>
  <caption>
    <title>General linear models describing variation in wing pigmentation in <italic>Calopteryx maculata</italic>.</title>
    <p>Parameter estimates from general linear models (weighted by square root of sample size) describing variation in wing pigmentation in <italic>Calopteryx maculata</italic> males. DF = 1 for all parameters.</p>
  </caption>
  <alternatives>
    <graphic mimetype="image" mime-subtype="png" xlink:href="https://example.org/table-1.png"/>
    <table>…</table>
  </alternatives>
</table-wrap>
```

## eLife

```xml
<!-- figure where there are figure supplements we have to use the fig-group container, some figures also have source data -->
<fig-group>
<fig id="fig1" position="float">
<object-id pub-id-type="doi">10.7554/eLife.00013.003</object-id>
<label>Figure 1.</label>
<caption>
<title>TEXT</title>
<p>TEXT<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.003">http://dx.doi.org/10.7554/eLife.00013.003</ext-link>
</p>
p>
<supplementary-material id="SD1-data">
<object-id pub-id-type="doi">10.7554/eLife.00013.004</object-id>
<label>Figure 1&#x2014;source data 1.</label>
<caption>
<title>TEXT</title>
<p>TEXT</p>
<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.004">http://dx.doi.org/10.7554/eLife.00013.004</ext-link>
</p>
</caption>
<media mime-subtype="xlsx" mimetype="application" xlink:href="elife00013s001.xlsx"/>
</supplementary-material>
</p>
</caption>
<graphic xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="elife00013f001"/>
</fig>
<fig id="sfig1" position="float" specific-use="child-fig">
<object-id pub-id-type="doi">10.7554/eLife.00013.005</object-id>
<label>Figure 1&#x2014;figure supplement 1.</label>
<caption>
<title>TEXT</title>
<p>TEXT</p>
<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.005">http://dx.doi.org/10.7554/eLife.00013.005</ext-link>
</p>
</caption>
<graphic xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="elife00013fs001"/>
</fig>
</fig-group>


<!-- table -->
<table-wrap id="tbl1" position="float">
<object-id pub-id-type="doi">10.7554/eLife.00013.009</object-id>
<label>Table 1.</label>
<caption>
<p>Species tested for colony induction</p>
<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.009">http://dx.doi.org/10.7554/eLife.00013.009</ext-link>
</p>
</caption>
<table frame="hsides" rules="groups">...</table>
<table-wrap-foot>
<fn id="tblfn1">
<label>&#x2a;</label>
<p>No rosette colonies observed, &#x2b; rosette colonies observed</p>
</fn>
</table-wrap-foot>
</table-wrap>










