# `<contrib-group>` and `<fn-group>`

Authors, their affiliations and roles.

## PeerJ

```xml
<contrib-group content-type="authors">
  <contrib id="author-1" contrib-type="author" equal-contrib="yes" corresp="yes">
    <name>
      <surname>One</surname>
      <given-names>Author</given-names>
    </name>
    <xref ref-type="aff" rid="aff-1">1</xref>
    <email>author.one@example.com</email>
  </contrib>
  <contrib id="author-2" contrib-type="author" equal-contrib="yes">
    <name>
      <surname>Two</surname>
      <given-names>Author</given-names>
    </name>
    <xref ref-type="aff" rid="aff-2">2</xref>
  </contrib>
  <contrib id="author-3" contrib-type="author">
    <name>
      <surname>Three</surname>
      <given-names>Author</given-names>
    </name>
    <xref ref-type="aff" rid="aff-2">2</xref>
  </contrib>
  <contrib id="author-4">
    <collab><institution>Example Institution</institution></collab>
  </contrib>
  <contrib id="author-5" contrib-type="author" xlink:href="https://github.com/scikit-image/scikit-image/graphs/contributors">
    <collab>the scikit-image contributors</collab>
  </contrib>
  <aff id="aff-1"><label>1</label><institution>Stellenbosch University</institution>, <addr-line>Stellenbosch</addr-line>, <country>South Africa</country></aff>
  <aff id="aff-2"><label>2</label><institution>Department of Computer Science, University of North Carolina at Chapel Hill</institution>, <addr-line>Chapel Hill, NC</addr-line>, <country>USA</country></aff>
</contrib-group>

<!-- footnotes -->
<back>
  <sec sec-type="additional-information">
    <fn-group content-type="author-contributions">
      <title>Author Contributions</title>
      <fn id="contribution-1" fn-type="con">
        <p><xref ref-type="contrib" rid="author-1">Author One</xref> conceived and designed the experiments, performed the experiments, contributed reagents/materials/analysis tools, prepared figures and/or tables, reviewed drafts of the paper.</p>
      </fn>
      <fn id="contribution-2" fn-type="con">
        <p><xref ref-type="contrib" rid="author-2">Author Two</xref> conceived and designed the experiments, analyzed the data, contributed reagents/materials/analysis tools, wrote the paper, prepared figures and/or tables, reviewed drafts of the paper.</p>
      </fn>
      <fn id="contribution-3" fn-type="con">
        <p><xref ref-type="contrib" rid="author-3">Author Three</xref> analyzed the data, contributed reagents/materials/analysis tools, wrote the paper, reviewed drafts of the paper.</p>
      </fn>
      <fn id="contribution-4" fn-type="con">
        <p><xref ref-type="contrib" rid="author-4">Author Four</xref> analyzed the data, contributed reagents/materials/analysis tools, wrote the paper, prepared figures and/or tables, reviewed drafts of the paper.</p>
      </fn>
    </fn-group>
  </sec>
</back>
