# Author Contributions

## PeerJ

```xml
<fn-group content-type="author-contributions">
  <title>Author Contributions</title>
  <fn id="contribution-1" fn-type="con">
    <p><xref ref-type="contrib" rid="author-1">Mike Stock</xref> and <xref ref-type="contrib" rid="author-2">Matt Aitken</xref> conceived and designed the experiments, performed the experiments, analyzed the data, contributed reagents/materials/analysis tools, wrote the paper, prepared figures and/or tables, reviewed drafts of the paper.</p>
  </fn>
  <fn id="contribution-2" fn-type="con">
    <p><xref ref-type="contrib" rid="author-3">Pete Waterman</xref> conceived and designed the experiments, performed the experiments, analyzed the data, contributed reagents/materials/analysis tools, wrote the paper, reviewed drafts of the paper.</p>
  </fn>
</fn-group>
```

## eLife

Examples of contrib tag with attributes

```xml
<contrib-group>
  <contrib contrib-type="author" equal-contrib="yes" id="author-23">
....
<contrib contrib-type="author" id="author-3">
...
 <contrib contrib-type="author" deceased="yes" id="author-5">
...
<contrib contrib-type="author" corresp="yes" id="author-7">
  ```

Group author:

```xml
<contrib-group>
...
  <contrib contrib-type="author" corresp="yes">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
                    <collab>NISC Comparative Sequencing Program</collab>
  </contrib>
</contrib-group>
...
<contrib-group>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
...
</contrib-group>
```

Reviewing editor:

```xml
 <contrib-group content-type="section">
                <contrib contrib-type="editor" id="author-10">
                  ...
                </contrib>
</contrib-group>
```


Example from eLife research content. The first contrib-group contains the authors, second contains the reviewing editor of the article and the third contains individual menmbers of a group author:

```xml
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
                    <xref ref-type="fn" rid="pa1">&#167;</xref>
                    <xref ref-type="other" rid="dataro1"/>
                    <xref ref-type="other" rid="dataro2"/>
                </contrib>
                <contrib contrib-type="author" equal-contrib="yes" id="author-17">
                    <name>
                        <surname>Brown</surname>
                        <given-names>Laura W</given-names>
                    </name>
                    <contrib-id contrib-id-type="orcid">http://orcid.org/0000-0002-7361-560X</contrib-id>
                    <xref ref-type="aff" rid="aff2">2</xref>
                    <xref ref-type="fn" rid="equal-contrib">&#x2020;</xref>
                    <xref ref-type="other" rid="par-1"/>
                    <xref ref-type="other" rid="par-3"/>
                    <xref ref-type="fn" rid="con2"/>
                    <xref ref-type="fn" rid="conf2"/>
                    <xref ref-type="fn" rid="pa2">&#xb6;</xref>
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
                    <xref ref-type="other" rid="pa3">&#x2a;&#x2a;</xref>
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
                    <xref ref-type="fn" rid="fn1">&#x2020;&#x2020;</xref>
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
                <contrib contrib-type="author" corresp="yes">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
                    <collab>NISC Comparative Sequencing Program</collab>
                    <xref ref-type="corresp" rid="cor3">&#x2a;</xref>
                    <xref ref-type="aff" rid="aff3">3</xref>
                    <xref ref-type="fn" rid="con9"/>
                    <xref ref-type="fn" rid="conf2"/>
                    <xref ref-type="other" rid="par-7"/>
                </contrib>
                <contrib contrib-type="author">
                    <contrib-id contrib-id-type="group-author-key">group-author-id2</contrib-id>
                    <collab>eLife staff group</collab>
                </contrib>
                ...
 </contrib-group>
 <contrib-group content-type="section">
                <contrib contrib-type="editor" id="author-10">
                    <name>
                        <surname>Sneden</surname>
                        <given-names>Christopher</given-names>
                    </name>
                    <role>Reviewing editor</role>
                    <aff>
                        <institution>Pediatric Dengue Vaccine Initiative</institution>,
                            <country>United States</country>
                    </aff>
                </contrib>
            </contrib-group>
            <contrib-group>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
                    <name>
                        <surname>Mullikin</surname>
                        <given-names>Jim</given-names>
                    </name>
                    <aff>
                        <institution>Science Exchange, Palo Alto</institution>,
                        <addr-line>
                            <named-content content-type="city">California</named-content>
                        </addr-line>
                    </aff>
                </contrib>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
                    <name>
                        <surname>Mulvany</surname>
                        <given-names>Ian</given-names>
                    </name>
                </contrib>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
                    <name>
                        <surname>Bloggs</surname>
                        <given-names>J</given-names>
                    </name>
                </contrib>
            </contrib-group>
            <contrib-group>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id2</contrib-id>
                    <name>
                        <surname>Dodd</surname>
                        <given-names>Melissa</given-names>
                    </name>
                   </contrib>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id2</contrib-id>
                    <name>
                        <surname>Rogers</surname>
                        <given-names>Fran</given-names>
                    </name>
                </contrib>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id2</contrib-id>
                    <name>
                        <surname>Patterson</surname>
                        <given-names>Mark</given-names>
                    </name>
                </contrib>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id2</contrib-id>
                    <name>
                        <surname>Harrison</surname>
                        <given-names>Melissa</given-names>
                    </name>
                </contrib>
</contrib-group>
```

Example from eLife Editorial content. It is steered by the requirement for the information to be human readable in a string, appearance in the PDF and on html view, and the need for flexibility. Comments and suggestions very welcome!

```xml
<contrib-group>
                <contrib contrib-type="author" corresp="yes" id="author-1057">
                    <name>
                        <surname>Chen</surname>
                        <given-names>Zhijian J</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff1"/>
                    <xref ref-type="fn" rid="conf1"/>
                    <x> is a </x>
                    <role>Reviewing Editor</role>
                    <x>, and is in the </x>
                </contrib>
                <contrib contrib-type="author" id="author-1674">
                    <name>
                        <surname>Ye</surname>
                        <given-names>Jin</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff2"/>
                    <xref ref-type="fn" rid="conf1"/>
                    <x> is in the </x>
                </contrib>
                <aff id="aff1"><institution content-type="dept">Department of Molecular Biology and
                        the Howard Hughes Medical Institute</institution>, <institution>University
                        of Texas Southwestern Medical Center</institution>,
                            <addr-line><named-content content-type="city"
                        >Dallas</named-content></addr-line>, <country>United States</country>
                    <email>zhijian.chen@utsouthwestern.edu</email></aff>
                <aff id="aff2"><institution content-type="dept">Department of Molecular
                        Genetics</institution>, <institution>University of Texas Southwestern
                        Medical Center</institution>, <addr-line><named-content content-type="city"
                            >Dallas</named-content></addr-line>, <country>United States</country>
                    <email>jin.ye@utsouthwestern.edu</email></aff>
</contrib-group>
 ```


## PMC

Collaborative author with expanded list of individual names:

From Lupus Sci Med. 2014; 1(1): e000037; 10.1136/lupus-2014-000037

```xml
    <contrib contrib-type="collab" id="collab1">
      <collab>APPLE investigators
        <contrib-group>
          <contrib contrib-type="collab">
            <name>
              <surname>Ardoin</surname>
              <given-names>Stacy</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Dewitt</surname>
              <given-names>Esi Morgan</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Rabinovich</surname>
              <given-names>C Egla</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Ellis</surname>
              <given-names>Janet</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Mieszkalski</surname>
              <given-names>Kelly</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Wootton</surname>
              <given-names>Janet</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Chira</surname>
              <given-names>Peter</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Hsu</surname>
              <given-names>Joyce</given-names>
            </name>
          </contrib>
          ...
        </contrib-group>
      </collab>
    </contrib>
```
