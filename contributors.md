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



## eLife

```xml

<!-- Authors, their affiliations and roles. Includes corresponding, equal contribs, deceased, on behalf of, group authors -->
<contrib-group>
<contrib contrib-type="author" equal-contrib="yes" id="author-23">
<name>
<surname>Alegado</surname>
<given-names>Rosanna A</given-names>
<suffix>Jnr</suffix>
</name>
<xref ref-type="aff" rid="aff1">1</xref>
<xref ref-type="aff" rid="aff2">2</xref>
<xref ref-type="fn" rid="equal-contrib">&#x2020;</xref>
<xref ref-type="other" rid="par-1"/>
<xref ref-type="other" rid="par-2"/>
<xref ref-type="fn" rid="con1"/>
<xref ref-type="fn" rid="conf2"/>
<xref ref-type="fn" rid="pa1">&#xb6;</xref>
<xref ref-type="other" rid="dataro1"/>
<xref ref-type="other" rid="dataro2"/>
</contrib>
<contrib contrib-type="author" equal-contrib="yes" id="author-17">
<name>
<surname>Brown</surname>
<given-names>Laura W</given-names>
</name>
<uri content-type="orcid">http://orcid.org/0000-0002-7361-560X</uri>
<xref ref-type="aff" rid="aff2">2</xref>
<xref ref-type="fn" rid="equal-contrib">&#x2020;</xref>
<xref ref-type="other" rid="par-1"/>
<xref ref-type="other" rid="par-3"/>
<xref ref-type="fn" rid="con2"/>
<xref ref-type="fn" rid="conf2"/>
<xref ref-type="fn" rid="pa2">&#x2016;</xref>
</contrib>
<contrib contrib-type="author" id="author-3">
<name>
<surname>Cao</surname>
<given-names>Shugeng</given-names>
</name>
<xref ref-type="aff" rid="aff2">2</xref>
<xref ref-type="fn" rid="equal-contrib2">&#x2021;</xref>
<xref ref-type="fn" rid="con3"/>
<xref ref-type="fn" rid="conf2"/>
</contrib>
<contrib contrib-type="author" id="author-4">
<name>
<surname>Dermenjian</surname>
<given-names>Renee Kathryn</given-names>
</name>
<xref ref-type="aff" rid="aff2">2</xref>
<xref ref-type="fn" rid="equal-contrib2">&#x2021;</xref>
<xref ref-type="fn" rid="con4"/>
<xref ref-type="fn" rid="conf2"/>
<xref ref-type="other" rid="pa3"/>
</contrib>
<contrib contrib-type="author" deceased="yes" id="author-5">
<name>
<surname>Zuzow</surname>
<given-names>Richard</given-names>
</name>
<xref ref-type="aff" rid="aff3">3</xref>
<xref ref-type="fn" rid="con5"/>
<xref ref-type="fn" rid="conf2"/>
<xref ref-type="other" rid="pa3"/>
<xref ref-type="fn" rid="fn1">&#x2a;&#x2a;</xref>
</contrib>
<contrib contrib-type="author" id="author-6">
<name>
<surname>Fairclough</surname>
<given-names>Stephen R</given-names>
</name>
<xref ref-type="aff" rid="aff1">1</xref>
<xref ref-type="other" rid="par-6"/>
<xref ref-type="fn" rid="con6"/>
<xref ref-type="fn" rid="conf2"/>
</contrib>
<contrib contrib-type="author" corresp="yes" id="author-7">
<name>
<surname>Clardy</surname>
<given-names>Jon</given-names>
</name>
<xref ref-type="aff" rid="aff2">2</xref>
<xref ref-type="corresp" rid="cor1">&#x2a;</xref>
<xref ref-type="other" rid="par-4"/>
<xref ref-type="other" rid="par-5"/>
<xref ref-type="fn" rid="con7"/>
<xref ref-type="fn" rid="conf1"/>
</contrib>
<contrib contrib-type="author" corresp="yes" id="author-8">
<name>
<surname>King</surname>
<given-names>Nicole</given-names>
</name>
<xref ref-type="aff" rid="aff1">1</xref>
<xref ref-type="corresp" rid="cor2">&#x2a;</xref>
<xref ref-type="other" rid="par-1"/>
<xref ref-type="other" rid="par-2"/>
<xref ref-type="other" rid="par-3"/>
<xref ref-type="other" rid="par-4"/>
<xref ref-type="other" rid="par-5"/>
<xref ref-type="fn" rid="con8"/>
<xref ref-type="fn" rid="conf2"/>
</contrib>
<on-behalf-of>for the HIV Genome-to-Genome Study and the Swiss HIV Cohort Study</on-behalf-of>
<contrib contrib-type="author">
<collab>NISC Comparative Sequencing Program</collab>
<xref ref-type="fn" rid="ga">&#xa7;</xref>
<xref ref-type="other" rid="gal1"/>
</contrib>
<contrib contrib-type="author">
<collab>eLife staff group</collab>
<xref ref-type="fn" rid="ga">&#xa7;</xref>
<xref ref-type="other" rid="gal2"/>
</contrib>
<aff id="aff1">
<label>1</label>
<addr-line>
<named-content content-type="department">Department of Molecular and Cell Biology</named-content>
</addr-line>, <institution>University of California, Berkeley</institution>, <addr-line>
<named-content content-type="city">Berkeley</named-content>
</addr-line>, <country>United States</country>
</aff>
<aff id="aff2">
<label>2</label>
<addr-line>
<named-content content-type="department">Department of Biological Chemistry and Molecular Pharmacology</named-content>
</addr-line>, <institution>Harvard Medical School</institution>, <addr-line>
<named-content content-type="city">Boston</named-content>
</addr-line>, <country>United States</country>
</aff>
<aff id="aff3">
<label>3</label>
<addr-line>
<named-content content-type="department">Department of Biochemistry</named-content>
</addr-line>, <institution>Stanford University School of Medicine</institution>, <addr-line>
<named-content content-type="city">Stanford</named-content>
</addr-line>, <country>United States</country>
</aff>
</contrib-group>


<!-- group author names -->
</contrib-group>
<contrib-group id="gal1">
<contrib contrib-type="author non-byline">
<name>
<surname>Mullikin</surname>
<given-names>Jim</given-names>
</name>
</contrib>
<contrib contrib-type="author non-byline">
<name>
<surname>Mulvany</surname>
<given-names>Ian</given-names>
</name>
</contrib>
<contrib contrib-type="author non-byline">
<name>
<surname>Bloggs</surname>
<given-names>J</given-names>
</name>
</contrib>
</contrib-group>
<contrib-group id="gal2">
<contrib contrib-type="author non-byline">
<name>
<surname>Dodd</surname>
<given-names>Melissa</given-names>
</name>
</contrib>
<contrib contrib-type="author non-byline">
<name>
<surname>Rogers</surname>
<given-names>Fran</given-names>
</name>
</contrib>
<contrib contrib-type="author non-byline">
<name>
<surname>Patterson</surname>
<given-names>Mark</given-names>
</name>
</contrib>
<contrib contrib-type="author non-byline">
<name>
<surname>Harrison</surname>
<given-names>Melissa</given-names>
</name>
</contrib>
</contrib-group>

<!-- footnotes -->
<author-notes>
 <corresp id="cor1">
 <label>&#x2a;</label>For
 correspondence:<email>jon_clardy@hms.harvard.edu</email>(JC);</corresp>
 <corresp id="cor2">
 <email>nking@berkeley.edu</email>(NK)</corresp>
 <fn fn-type="other" id="equal-contrib">
 <label>&#x2020;</label>
 <p>These authors contributed equally to this work</p>
 </fn>
 <fn fn-type="other" id="equal-contrib2">
 <label>&#x2021;</label>
 <p>These authors contributed equally to this work</p>
 </fn>
 <fn fn-type="other" id="ga">
 <label>&#xa7;</label>
 <p>For list of group authors see Acknowledgements</p>
 </fn>
 <fn fn-type="present-address" id="pa1">
 <label>&#xb6;</label>
 <p>Department of Wellcome Trust, Sanger Institute, London, United Kingdom</p>
 </fn>
 <fn fn-type="present-address" id="pa2">
 <label>&#x2016;</label>
 <p>Department of Biological Chemistry and Molecular Pharmacology, Harvard
 Medical School, Boston, United States</p>
 </fn>
 <fn fn-type="present-address" id="pa3">
 <p>eLife Sciences editorial Office, eLife Sciences, Cambridge, United
 Kingdom</p>
 </fn>
 <fn fn-type="other" id="fn1">
 <label>&#x2a;&#x2a;</label>
 <p>Deceased</p>
 </fn>


 <?xml version="1.0" encoding="UTF-8"?>
<funding-group>
<award-group id="par-1">
<funding-source>Howard Hughes Medical Institute <ext-link xlink:href="http://www.crossref.org/fundref/">FundRef identification ID: </ext-link>
<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000011</named-content></funding-source>
<principal-award-recipient>
<name>
<surname>King</surname>
<given-names>Nicole</given-names>
</name>
<name>
<surname>Alegado</surname>
<given-names>Rosanna A</given-names>
</name>
<name>
<surname>Brown</surname>
<given-names>Laura W</given-names>
</name>
</principal-award-recipient>
</award-group>
    <award-group id="par-2">
        <funding-source>National Institutes of Health <ext-link xlink:href="http://www.crossref.org/fundref/">FundRef identification ID: </ext-link>
            <named-content content-type="funder-id">http://dx.doi.org/10.13039/100000002</named-content></funding-source>
        <award-id>F32 GM086054</award-id>
        <principal-award-recipient>
            <name>
                <surname>King</surname>
                <given-names>Nicole</given-names>
            </name>
            <name>
                <surname>Alegado</surname>
                <given-names>Rosanna A</given-names>
            </name>
        </principal-award-recipient>
    </award-group>
    <award-group id="par-3">
        <funding-source>National Institutes of Health <ext-link xlink:href="http://www.crossref.org/fundref/">FundRef identification ID: </ext-link>
            <named-content content-type="funder-id">http://dx.doi.org/10.13039/100000002</named-content></funding-source>
            </funding-source>
        <award-id>F32 GM089018</award-id>
        <principal-award-recipient>
            <name>
                <surname>Brown</surname>
                <given-names>Laura W</given-names>
            </name>
            <name>
                <surname>King</surname>
                <given-names>Nicole</given-names>
            </name>
        </principal-award-recipient>
    </award-group>
    <award-group id="par-4">
        <funding-source>National Institutes of Health <ext-link xlink:href="http://www.crossref.org/fundref/">FundRef identification ID: </ext-link>
            <named-content content-type="funder-id">http://dx.doi.org/10.13039/100000002</named-content></funding-source>
        <award-id>R01 GM086258</award-id>
        <principal-award-recipient>
            <name>
                <surname>Clardy</surname>
                <given-names>Jon</given-names>
            </name>
            <name>
                <surname>King</surname>
                <given-names>Nicole</given-names>
            </name>
        </principal-award-recipient>
    </award-group>
    <award-group id="par-5">
        <funding-source>National Institutes of Health <ext-link xlink:href="http://www.crossref.org/fundref/">FundRef identification ID: </ext-link>
            <named-content content-type="funder-id">http://dx.doi.org/10.13039/100000002</named-content></funding-source>
        <award-id>R01 GM099533</award-id>
        <principal-award-recipient>
            <name>
                <surname>Clardy</surname>
                <given-names>Jon</given-names>
            </name>
            <name>
                <surname>King</surname>
                <given-names>Nicole</given-names>
            </name>
        </principal-award-recipient>
    </award-group>
    <award-group id="par-6">
        <funding-source>National Institutes of Health <ext-link xlink:href="http://www.crossref.org/fundref/">FundRef identification ID: </ext-link>
            <named-content content-type="funder-id">http://dx.doi.org/10.13039/100000002</named-content></funding-source>
        <award-id>T32 HG00047</award-id>
        <principal-award-recipient>
            <name>
                <surname>Fairclough</surname>
                <given-names>Stephen R</given-names>
            </name>
        </principal-award-recipient>
    </award-group>
    <funding-statement>The funders had no role in study design; collection, analysis,
        and interpretation of data; writing the article; and or the decision to submit
        to the journal.</funding-statement>
</funding-group>



<back>
 … 
 <sec id="sec2342" sec-type="additional-information">
 <title>Additional information</title>
 <fn-group content-type="competing-interest">
 <title>Competing interests</title>
 <fn fn-type="conflict" id="conf1">
 <p>JC: Reviewing editor, <italic>eLife</italic>.</p>
 </fn>
 <fn fn-type="conflict" id="conf2">
 <p>The other authors declare that no competing interests exist.</p>
 </fn>
 </fn-group>
 <fn-group content-type="author-contribution">
 <title>Author contributions</title>
 <fn fn-type="con" id="con1">
 <p>RAA, Conception and design, Acquisition of data, Analysis and interpretation
 of data, Drafting or revising the article</p>
 </fn>
 <fn fn-type="con" id="con2">
 <p>LWB, Conception and design, Acquisition of data, Analysis and interpretation
 of data, Drafting or revising the article</p>
 </fn>
 <fn fn-type="con" id="con3">
 <p>CS, Acquisition of data, Analysis and interpretation of data, Drafting or
 revising the article</p>
 </fn>
 <fn fn-type="con" id="con4">
 <p>RKD, Acquisition of data, Analysis and interpretation of data</p>
 </fn>
 <fn fn-type="con" id="con5">
 <p>RZ, Acquisition of data, Analysis and interpretation of data</p>
 </fn>
 <fn fn-type="con" id="con6">
 <p>SRF, Acquisition of data, Analysis and interpretation of data</p>
 </fn>
 <fn fn-type="con" id="con7">
 <p>JC, Conception and design, Analysis and interpretation of data, Drafting or
 revising the article</p>
 </fn>
 <fn fn-type="con" id="con8">
 <p>NK, Conception and design, Analysis and interpretation of data, Drafting or
 revising the article</p>
 </fn>
 </fn-group>
 ...
</back>


