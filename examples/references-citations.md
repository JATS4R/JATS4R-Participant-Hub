# References / citations

References (citation of software/data/versions/law cases)

See:

* [GitHub issues](https://github.com/JATS4R/elements/labels/references-citations).
* [Draft recommendations](https://docs.google.com/document/d/13uGZ4UqplHkT9VvaXnuboLZ2IRCx3SH7PTQJk24CiRk/) (Google doc).
  Most of the text from this document has moved there.

Please add examples below.


# Data Citations - citing data sets in references

## Best practice example

See [draft recommendations](https://docs.google.com/document/d/13uGZ4UqplHkT9VvaXnuboLZ2IRCx3SH7PTQJk24CiRk/)

```xml
<ref id="d1">
  <element-citation publication-type="data">
    <person-group person-group-type="author">
      <collab>The Concerto Consortium</collab>
      <name>
        <surname>van Beethoven</surname>
        <given-names>Ludwig</given-names>
      </name>
      <name>
        <surname>Liszt</surname>
        <given-names>F</given-names>
      </name>
    </person-group>
    <person-group person-group-type="curator">
      <name>
        <surname>Bach</surname>
        <given-names>JS</given-names>
      </name>
    </person-group>
    <data-title>Title of data set</data-title>
    <year iso-8601-date="2014">2014</year> 
    <source>Repository Name</source>
    <pub-id pub-id-type="doi" assigning-authority='figshare'
      xlink:href="http://dx.doi.org/99.1234/1234321">99.1234/1234321</pub-id>
    <version designator="16.2">16th version, second release</version>
  </element-citation>
</ref>
```


### Nature Publishing Group examples

Example with CrossRef DOI URL as text and link

```xml
<ref-list content-type="data-citations">
  <ref id="d1">
    <element-citation>
      <source>Long Term Ecological Research Network</source>
      <ext-link ext-link-type="public-website" specific-use="url"
        xlink:href="http://dx.doi.org/10.6073/pasta/379a6cebee50119df2575c469aba19c5">http://dx.doi.org/10.6073/pasta/379a6cebee50119df2575c469aba19c5</ext-link>
      <year>2015</year>
      <collab>
        <contrib-group>
          <contrib>
            <name>
              <surname>Sharma</surname>
              <given-names>S.</given-names>
            </name>
          </contrib>
        </contrib-group>
      </collab>
      <etal/>
    </element-citation>
  </ref>
</ref-list>
```

Example with database entry ID as text and full URL as link

```xml
<ref id="d1">
  <element-citation>
    <source>Gene Expression Omnibus</source>
    <ext-link ext-link-type="geo" 
      specific-use="url" 
      xlink:href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE59088"
      >GSE59088</ext-link>
    <year>2014</year>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>Schjerling</surname>
            <given-names>P.</given-names>
          </name>
        </contrib>
        <contrib>
          <name>
            <surname>Vissing</surname>
            <given-names>K.</given-names>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>
```

Examples with database entry ID as text and link (Full URL in HTML from lookup 
of database ID in @ext-link-type in ontology)

```xml
<ref id="d5">
  <element-citation>
    <source>ArrayExpress</source>
    <ext-link ext-link-type="arrayexpress.platform" specific-use="id" xlink:href="E-MTAB-2332">E-MTAB-2332</ext-link>
    <year>2014</year>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>The Rat Genome Sequencing and Mapping Consortium</surname>
            <given-names/>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>
....
<ref id="d7">
  <element-citation>
    <source>Biological Magnetic Resonance Data Bank</source>
    <ext-link ext-link-type="bmrb" specific-use="id" xlink:href="1002">1002</ext-link>
    <year>2014</year>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>Chazin</surname>
            <given-names>Walter</given-names>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>
....
<ref id="d30">
  <element-citation>
    <source>PeptideAtlas</source>
    <year>2014</year>
    <ext-link ext-link-type="peptideatlas" specific-use="id" xlink:href="PASS00416">PASS00416</ext-link>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>Metz</surname>
            <given-names>T.</given-names>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>
```

## eLife examples

Example 1

```xml
<ref id="bib46">
  <element-citation publication-type="data">
    <person-group person-group-type="author">
      <name><surname>Ly</surname>
        <given-names>T</given-names></name>, <name><surname>Endo</surname>
        <given-names>A</given-names></name>, <name>
        <surname>Lamond</surname><given-names>Angus I</given-names></name>
    </person-group>
    <year>2014</year>
    <source>Proteomics dataset</source>
    <ext-link ext-link-type="uri" xlink:href="http://proteomecentral.proteomexchange.org"
      >http://proteomecentral.proteomexchange.org</ext-link>
  </element-citation>
</ref>
```

Example 2

```xml
<ref id="bib46">
  <element-citation publication-type="web">
    <person-group person-group-type="author">
      <name>
        <surname>Schuman</surname>
        <given-names>M</given-names>
      </name>
      <name>
        <surname>Barthel</surname>
        <given-names>K</given-names>
      </name>
      <name>
        <surname>Baldwin</surname>
        <given-names>IT</given-names>
      </name>
    </person-group>
    <year>2012</year>
    <comment>Data from: Herbivory-induced volatiles function as defenses increasing
      fitness of the native plant <italic>Nicotiana attenuata</italic> in nature.
      Dryad Digital Repository.</comment>
    <ext-link ext-link-type="uri" xlink:href="http://dx.doi.org/10.5061/dryad.gs45f"
      >http://dx.doi.org/10.5061/dryad.gs45f</ext-link>
  </element-citation>
</ref>
```

## Examples from "Adapting JATS to support data citation"

Database on CD-ROM, DVD, or disk

```xml
<mixed-citation publication-type="data" publication-format="disk">
  <name><surname>Walker</surname><given-names>MM</given-names></name>, 
  <name><surname>Keith</surname><given-names>LH</given-names></name>. 
  <data-title>EPA's Clean Air Act air toxics database</data-title> [disk]. 
  <publisher-loc>Boca Raton (FL)</publisher-loc>: 
  <publisher-name>Lewis Publishers</publisher-name>; 
  <date-in-citation content-type="copyright-year"
    iso-8601-date="1992">1992-1993</date-in-citation>.
  4 computer disks: 3 1/2 in.
</mixed-citation>
```

Record from a web data repository

```xml
<mixed-citation publication-type='data'>
  <name><surname>Benz</surname><given-names>Michael</given-names></name>;
  <name><surname>Braband</surname><given-names>Henrik</given-names></name>;
  <name><surname>Schmutz</surname><given-names>Paul</given-names></name>;
  <name><surname>Halter</surname><given-names>Jonathan</given-names></name>; 
  <name><surname>Alberto</surname><given-names>Roger</given-names></name>.
  <data-title>C21 H49 Al Cl7 N7 O7 Tc</data-title>,
  version <version>130981</version>. From
  <source>Crystallography Open Database</source>,
  accession <pub-id pub-id-type='accession' 
    assigning-authority='crystallography open database'
    xlink:href='http://www.crystallography.net/cod/1517518.html'>1517518</pub-id>.
</mixed-citation>
```
                
Record from the Protein Data Bank

```xml
<mixed-citation publication-type='data'>
  <name><surname>Heinz</surname><given-names>D.W.</given-names></name>,
  <name><surname>Baase</surname><given-names>W.A.</given-names></name>,
  <etal>et. al.</etal>
  <data-title>How amino-acid insertions are allowed in an alpha-helix of T4 
  lysozyme</data-title>.
  <source>RCSB Protein Data Bank</source>,
  accession <pub-id pub-id-type='accession' assigning-authority='pdb'
    xlink:href='http://www.rcsb.org/pdb/explore/explore.do?structureId=102l'>102l</pub-id>.
  <pub-id pub-id-type='doi'
    xlink:href='http://dx.doi.org/10.2210/pdb102l/pdb'>10.2210/pdb102l/pdb</pub-id>
</mixed-citation>
```

Data record from FigShare

```xml
<mixed-citation>
  <name><surname>Mulvany</surname><given-names>Ian</given-names></name>,
  <data-title>citing-dataset-elements</data-title>.
  <source>FigShare</source>, 
  <date-in-citation content-type=’pub-date’ 
    iso-8601-date='2014-06-30'><day>30</day><month>06</month>
  <year>2014</year></date-in-citation>,
  <pub-id pub-id-type='doi' xlink:href='http://dx.doi.org/10.6084/m9.figshare.1088363'
    assigning-authority='figshare'>10.6084/m9.figshare.1088363</pub-id>.
</mixed-citation>
```

Page from Encyclopedia of Life

```xml
<mixed-citation>
  <person-group person-group-type='curator'>
    <name><surname>Frankis</surname><given-names>Michael</given-names></name>
  </person-group>, curator.
  "<data-title>Mountain bluebird</data-title>."
  <source>Encyclopedia of Life</source>, available from 
  <ext-link ext-link-type='uri' 
    xlink:href='http://eol.org/pages/1177542'>http://eol.org/pages/1177542</ext-link>.
  Accessed 30 Mar 2015.
</mixed-citation>
```

Add Health

```xml
<mixed-citation>
  <name><surname>Harris</surname><given-names>Kathleen Mullan</given-names></name>.
  <date-in-citation content-type="pub-date"><year>2009</year></date-in-citation>.
  <data-title>The National Longitudinal Study of Adolescent to Adult Health 
    (Add Health), Waves I & II, 1994–1996; Wave III, 2001–2002; Wave IV, 
    2007-2009</data-title>
  [machine-readable data file and documentation].
  <publisher-loc>Chapel Hill, NC</publisher-loc>:
  <publisher-name>Carolina Population Center, University of North Carolina at
    Chapel Hill</publisher-name>. 
  DOI: <pub-id pub-id-type='doi'
    xlink:href='http://dx.doi.org/10.3886/ICPSR27021.v9'>10.3886/ICPSR27021.v9</pub-id>
</mixed-citation>
```


## JATS4R sample so far

Example 1

```xml
<ref id="XXXX">
  <element-citation publication-type="data">
    <person-group person-group-type="author">
      <contrib>
        <collab>The JATS Standing Committee</collab>
      </contrib>
      <contrib>
        <name>
          <surname>Maloney</surname>
          <given-names>Chris</given-names>
        </name>
      </contrib>
      <contrib>
        <name>
          <surname>Seligy</surname>
          <given-names>M</given-names>
        </name>
      </contrib>
      <contrib>
        <name>
          <surname>Randall</surname>
          <given-names>L</given-names>
        </name>
      </contrib>
    </person-group>
    <person-group person-group-type="curator">
      <contrib>
        <collab>JATS4R Working Group</collab>
      </contrib>
    </person-group>
    <data-title>Elements</data-title>
    <source>GitHub</source>, available from 
    <ext-link ext-link-type='uri' 
      xlink:href='https://github.com/JATS4R/elements'
      >https://github.com/JATS4R/elements</ext-link>.
  </element-citation>
</ref>
```
