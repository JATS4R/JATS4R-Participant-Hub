# `<contrib-group>, <contrib>, <aff>`

# Authors and Affiliations<br>

For samples related to affiliation details, see [Affiliations] (#https://github.com/JATS4R/JATS4R-Participant-Hub/blob/master/examples/affiliations.md)


[American Society for Microbiology](#asm)<br>
[Aries](#aries)<br>
[BIR](#bir)<br>
[deGruyter](#degruyter)<br>
[eLife](#eLife)<br>
[Frontiers](#frontiers)<br>
[PeerJ](#peerj)<br>
[Redalyc](#redalyc)<br>
[SciELO](#scielo)

## American Society for Microbiology <a name="asm"></a>

Sample 1 (using addr-line in aff; aff as child of contrib-group)
```xml
<contrib-group content-type="authors">
                <contrib contrib-type="author" corresp="yes">
				<contrib-id contrib-id-type="orcid">http://orcid.org/0000-0002-7881-8027</contrib-id>
                    <name>
                        <surname>Roghmann</surname>
                        <given-names>Mary-Claire</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff1"><sup>a</sup></xref>
                    <xref ref-type="aff" rid="aff2"><sup>b</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Lydecker</surname>
                        <given-names>Alison D.</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff2"><sup>b</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Hittle</surname>
                        <given-names>Lauren</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff3"><sup>c</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>DeBoy</surname>
                        <given-names>Robert T.</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff2"><sup>b</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Nowak</surname>
                        <given-names>Rebecca G.</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff2"><sup>b</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Johnson</surname>
                        <given-names>J. Kristie</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff4"><sup>d</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Mongodin</surname>
                        <given-names>Emmanuel F.</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff3"><sup>c</sup></xref>
                </contrib>
                <aff id="aff1"><label>a</label><addr-line>Geriatrics Research Education and Clinical
                        Center, VA Maryland Health Care System, Baltimore, Maryland,
                    USA</addr-line></aff>
                <aff id="aff2"><label>b</label><addr-line>Department of Epidemiology and Public
                        Health, University of Maryland School of Medicine, Baltimore, Maryland,
                        USA</addr-line></aff>
                <aff id="aff3"><label>c</label><addr-line>Department of Microbiology and Immunology
                        and Institute for Genome Sciences, University of Maryland School of
                        Medicine, Baltimore, Maryland, USA</addr-line></aff>
                <aff id="aff4"><label>d</label><addr-line>Department of Pathology, University of
                        Maryland School of Medicine, Baltimore, Maryland, USA</addr-line></aff>
            </contrib-group>
```
Sample 2 (aff as child of contrib-group [no addr-line])
```xml
 <contrib-group content-type="authors">
                <contrib contrib-type="author" corresp="yes">
                    <name>
                        <surname>Juretschko</surname>
                        <given-names>Stefan</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff1"><sup>a</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Mahony</surname>
                        <given-names>James</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff2"><sup>b</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Buller</surname>
                        <given-names>Richard S.</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff3"><sup>c</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Manji</surname>
                        <given-names>Ryhana</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff1"><sup>a</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Dunbar</surname>
                        <given-names>Sherry</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff4"><sup>d</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Walker</surname>
                        <given-names>Kimberly</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff5"><sup>e</sup></xref>
                </contrib>
                <contrib contrib-type="author">
                    <name>
                        <surname>Rao</surname>
                        <given-names>Arundhati</given-names>
                    </name>
                    <xref ref-type="aff" rid="aff5"><sup>e</sup></xref>
                </contrib>
                <aff id="aff1"><label>a</label>Northwell Health Laboratories, Pathology and
                    Laboratory Medicine, Lake Success, New York, USA</aff>
                <aff id="aff2"><label>b</label>McMaster University, Hamilton, Ontario, Canada</aff>
                <aff id="aff3"><label>c</label>Washington University School of Medicine, Department
                    of Pediatrics, St. Louis, Missouri, USA</aff>
                <aff id="aff4"><label>d</label>Luminex Corporation, Austin, Texas, USA</aff>
                <aff id="aff5"><label>e</label>Scott and White Medical Center, Baylor Scott and
                    White Healthcare, Temple, Texas, USA</aff>
            </contrib-group>
```
Sample 3 (aff as child of contrib)
```xml
<contrib-group content-type="editors">
                <contrib contrib-type="editor">
                    <name>
                        <surname>Mitchell</surname>
                        <given-names>Aaron P.</given-names>
                    </name>
                    <role>Editor</role>
                    <aff>Carnegie Mellon University</aff>
                </contrib>
            </contrib-group>
```
Sample 4 (parsed aff and contrib ids)
```xml
<contrib-group content-type="authors">
    <contrib id="author-1" contrib-type="author" corresp="yes">
        <name>
            <surname>Garcia</surname>
            <given-names>Danilo</given-names>
        </name>
        <email>danilo.garcia@icloud.com</email>
        <xref ref-type="aff" rid="aff-1">1</xref>
        <xref ref-type="aff" rid="aff-2">2</xref>
        <xref ref-type="aff" rid="aff-3">3</xref>
        <xref ref-type="aff" rid="aff-4">4</xref>
    </contrib>
    <contrib id="author-2" contrib-type="author">
        <name>
            <surname>Granjard</surname>
            <given-names>Alexandre</given-names>
        </name>
        <xref ref-type="aff" rid="aff-1">1</xref>
    </contrib>
    <contrib id="author-3" contrib-type="author">
        <name>
            <surname>Lundblad</surname>
            <given-names>Suzanna</given-names>
        </name>
        <xref ref-type="aff" rid="aff-5">5</xref>
    </contrib>
    <contrib id="author-4" contrib-type="author">
        <name>
            <surname>Archer</surname>
            <given-names>Trevor</given-names>
        </name>
        <xref ref-type="aff" rid="aff-2">2</xref>
        <xref ref-type="aff" rid="aff-3">3</xref>
    </contrib>
    <aff id="aff-1">
        <label>1</label>
        <institution>
            Blekinge Centre of Competence, Blekinge County Council
        </institution>
        ,
        <city>Karlskrona</city>
        ,
        <country>Sweden</country>
    </aff>
    <aff id="aff-2">
        <label>2</label>
        <institution>Department of Psychology, University of Gothenburg</institution>
        ,
        <city>Gothenburg</city>
        ,
        <country>Sweden</country>
    </aff>
    <aff id="aff-3">
        <label>3</label>
        <institution>Network for Empowerment and Well-Being</institution>
        ,
        <country>Sweden</country>
    </aff>
    <aff id="aff-4">
        <label>4</label>
        <institution>Department of Psychology, Lund University</institution>
        ,
        <city>Lund</city>
        ,
        <country>Sweden</country>
    </aff>
    <aff id="aff-5">
        <label>5</label>
        <institution>
            Psychiatry Affective, Anorexia & Bulimia Clinic for Adults, Sahlgrenska University Hospital
        </institution>
        ,
        <city>Gothenburg</city>
        ,
        <country>Sweden</country>
    </aff>
</contrib-group>

```
## BIR <a name="bir"></a>

```xml
<contrib contrib-type="author">
  <string-name>
    <given-names>P M</given-names><x> </x>
    <surname>Price</surname>
  </string-name><x> </x><email>PatPrice@patprice.co.uk</email>
  <xref ref-type="aff" rid="AF0001"><sup>1</sup></xref>
  <xref ref-type="aff" rid="AF0002"><sup>2</sup></xref>
</contrib>
...

<aff id="AF0001"><sup>1</sup>The Harley Street Clinic, London, UK</aff>
<aff id="AF0002"><sup>2</sup>Department of Surgery and Cancer, Imperial College London, London, UK</aff>
```
## de Gruyter <a name="degruyter"></a>
```xml
<contrib-group>
  <contrib contrib-type="series_editor">
    <name>
      <surname>Michael</surname>
      <given-names>Miller</given-names>
    </name>
    <email xlink:href="mailto:michael.miller@jatssamples.com">michael.miller@jatssamples.com</email>
    <xref ref-type="aff" rid="j_hsz-2013-0008_aff_001"/>
    <xref ref-type="aff" rid="j_hsz-2013-0008_aff_003"/>
  </contrib>
</contrib-group>
```


## eLife <a name="eLife"></a>

The affiliations are cross linked with authors using the following style within the contrib 
tag:

```xml
<xref ref-type="aff" rid="aff1">1</xref>
```

```xml
<contrib-group>
  ...
  <aff id="aff1">
    <label>1</label>
    <institution content-type="dept">Department of Molecular and Cell Biology</institution>, 
    <institution>University of California, Berkeley</institution>,
    <addr-line>
      <named-content content-type="city">Berkeley</named-content>
    </addr-line>, 
    <country>United States</country>
  </aff>
  <aff id="aff2">
    <label>2</label>
    <institution content-type="dept">Department of Biological Chemistry and Molecular 
      Pharmacology</institution>,
    <institution>Harvard Medical School</institution>, 
    <addr-line>
      <named-content content-type="city">Boston</named-content>
    </addr-line>,
    <country>United States</country>
  </aff>
  <aff id="aff3">
    <label>3</label>
    <institution content-type="dept">Department of Biochemistry</institution>,
    <institution>Stanford University School of Medicine</institution>, 
    <addr-line>
      <named-content content-type="city">Stanford</named-content>
    </addr-line>,
    <country>United States</country>
  </aff>
</contrib-group>

```

The reviewing editor contains affliation details within the contrib:

```xml
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
```

Affiliatins of members of a group author group are contained within contrib for each individual's affiliation, but the group's generif affiliation is dealt with in the same way as for indivudual authors:

```xml
 <contrib contrib-type="author">
                   <collab>eLife Editorial Production Group
                        <contrib-group>                          
                            <role>Writing group</role>
                            <contrib>
                                <name>
                                    <surname>Shearer</surname>
                                    <given-names>Alistair</given-names>
                                </name>
                                <aff>
                                    <institution>eLife</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                            </contrib>
                            <contrib>
                                <name>
                                    <surname>Caton</surname>
                                    <given-names>Hannah</given-names>
                                </name>
                                <aff>
                                    <institution>eLife</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                                <aff>
                                    <institution>eLife Institute</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                            </contrib>
                        </contrib-group>
                        <contrib-group>
                            <role>Editing group</role>
                            <contrib>
                                <name>
                                    <surname>Chan</surname>
                                    <given-names>Wei Mun</given-names>
                                </name>
                                <aff>
                                    <institution>eLife</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                            </contrib>
                            <contrib>
                                <name>
                                    <surname>Drury</surname>
                                    <given-names>Hannah</given-names>
                                </name>
                                <aff>
                                    <institution>eLife</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                            </contrib>
                            <contrib>
                                <name>
                                    <surname>Guerreiro</surname>
                                    <given-names>Maria</given-names>
                                </name>
                                <aff>
                                    <institution>eLife</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                            </contrib>
                            <contrib>
                                <name>
                                    <surname>Richmond</surname>
                                    <given-names>Susanna</given-names>
                                </name>
                                <aff>
                                    <institution>eLife</institution>
                                    <addr-line>
                                        <named-content content-type="city">Cambridge</named-content>
                                    </addr-line>
                                    <country>United Kingdom</country>
                                </aff>
                            </contrib>
                        </contrib-group>
                </collab>
                    <xref ref-type="fn" rid="equal-contrib2">&#x2021;</xref>
                    <xref ref-type="fn" rid="con3"/>
                    <xref ref-type="fn" rid="conf2"/>
                    <xref ref-type="aff" rid="aff1">1</xref>
                </contrib>
                
                ...
  <aff id="aff1">
    <label>1</label>
    <institution content-type="dept">Department of Molecular and Cell Biology</institution>, 
    <institution>University of California, Berkeley</institution>,
    <addr-line>
      <named-content content-type="city">Berkeley</named-content>
    </addr-line>, 
    <country>United States</country>
  </aff>
  <aff id="aff2">
    <label>2</label>
    <institution content-type="dept">Department of Biological Chemistry and Molecular 
      Pharmacology</institution>,
    <institution>Harvard Medical School</institution>, 
    <addr-line>
      <named-content content-type="city">Boston</named-content>
    </addr-line>,
    <country>United States</country>
  </aff>
  <aff id="aff3">
    <label>3</label>
    <institution content-type="dept">Department of Biochemistry</institution>,
    <institution>Stanford University School of Medicine</institution>, 
    <addr-line>
      <named-content content-type="city">Stanford</named-content>
    </addr-line>,
    <country>United States</country>
  </aff>
</contrib-group>
                
```

Present address:

An author with a present address has the following within the contrib tagging:

```xml
<xref ref-type="fn" rid="pa1">&#167;</xref>
```

and the following footnote in author notes:


```xml
<author-notes>
  <fn fn-type="present-address" id="pa1">
    <label>&#167;</label>
    <p>Department of Wellcome Trust, Sanger Institute, London, United Kingdom</p>
  </fn>
</author-notes>
```
## Frontiers <a name="frontiers"></a>

```xml
<contrib contrib-type="author">
  <name>...</name>
  <xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
  <xref ref-type="aff" rid="aff2"><sup>2</sup></xref>
  <uri xlink:href="http://frontiersin.org/people/u/..."/>
</contrib>
...

<aff id="aff1"><sup>1</sup><institution>School of Biological Sciences, University of 
  Nebraska-Lincoln</institution>, <addr-line>Lincoln, NE</addr-line>, 
  <country>USA</country></aff>
<aff id="aff2"><sup>2</sup><institution>Nebraska Center for Virology, University of 
  Nebraska-Lincoln</institution>, <addr-line>Lincoln, NE</addr-line>, 
  <country>USA</country></aff>
```

### Present address

In contrib:

```xml
<contrib contrib-type="author">
  <name><surname>Ren</surname> <given-names>Hongyan</given-names></name>
  <xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
  <xref ref-type="fn" rid="fn003"><sup>&#x02020;</sup></xref>
</contrib>
```

Footnote in author notes:

```xml
<fn fn-type="present-address" id="fn003"><p>&#x02020;Present Address: Hongyan Ren, 
  Shanghai Majorbio Bio-pharm Technology Co., Ltd., Shanghai, China</p></fn>
```
## PeerJ <a name="peerj"></a>

Each author has a reference to one or more affiliations:

```xml
<contrib id="author-1" contrib-type="author">
  …
  <xref ref-type="aff" rid="aff-1">1</xref>
</contrib>
```

Each affiliation has some level of granularity in the address:

```xml
<aff id="aff-1"><institution>Department of Physiology and Biophysics, The Weill Cornell 
  Medical College</institution>, <addr-line>New York, NY</addr-line>, 
  <country>United States of America</country></aff>
```



## Redalyc <a name="redalyc"></a>
```
<contrib-group>
<contrib contrib-type="author" corresp="no">
<name name-style="western">
<surname>Maldonado Rivera</surname>
<given-names>Ivette</given-names>
</name>
<xref ref-type="aff" rid="aff1"/>
<email>ivette.maldonado1@upr.edu</email>
</contrib>
<contrib contrib-type="author" corresp="no">
<name name-style="western">
<surname>Romero</surname>
<given-names>Liz</given-names>
</name>
<xref ref-type="aff" rid="aff2"/>
<email>lisbia@nova.edu</email>
</contrib>
</contrib-group>
<aff id="aff1">
<institution content-type="original">Centro de Recursos para el
Aprendizaje, Universidad de Puerto Rico en Bayamón. ivette.maldonado1@upr.edu</institution>
<institution content-type="orgname">Universidad de Puerto Rico</institution>
</aff>
<aff id="aff2">
<institution content-type="original">Abraham S. Fischler College
of Education, Nova Southeastern University. lisbia@nova.edu</institution>
<institution content-type="orgname">Nova Southeastern University</institution>
</aff>
```


## SciELO <a name="scielo"></a>
Example 1

```xml
 <article-meta>
	<contrib-group>
		<contrib contrib-type="author">
			<name>
				<surname>Couto</surname>
				<given-names>Cláudio Gonçalves</given-names>
			</name>
			<xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
		</contrib>
		<contrib contrib-type="author">
			<name>
				<surname>Lima</surname>
				<given-names>Giovanna de Moura Rocha</given-names>
			</name>
			<xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
		</contrib>
	</contrib-group>
	<aff id="aff1">
		<label>1</label>
		<institution content-type="normalized">Fundação Getúlio Vargas</institution>
		<institution content-type="orgname">Fundação Getulio Vargas</institution>
		<addr-line>
			<named-content content-type="city">São Paulo</named-content>
			<named-content content-type="state">SP</named-content>
		</addr-line>
		<country country="BR">Brasil</country>
		<email>claudio.couto@fgv.br.</email>
		<institution content-type="original">. Fundação Getulio Vargas (FGV), São Paulo, SP, Brasil. E-mail para contato: claudio.couto@fgv.br.</institution>
	</aff>
</article-meta>
```
Example 2

```xml
<article-meta>
	<contrib-group>
		<contrib contrib-type="author">
			<name>
				<surname>Nunes</surname>
				<given-names>Ana Paula</given-names>
			</name>
			<xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
		</contrib>
		<contrib contrib-type="author">
			<name>
				<surname>Mariz</surname>
				<given-names>Cecília</given-names>
			</name>
			<xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
		</contrib>
		<contrib contrib-type="author">
			<name>
				<surname>Faerstein</surname>
				<given-names>Eduardo</given-names>
			</name>
			<xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
		</contrib>
	</contrib-group>
	<aff id="aff1">
		<label>1</label>
		<institution content-type="normalized">Universidade do Estado do Rio de Janeiro</institution>
		<institution content-type="orgname">Universidade do Estado do Rio de Janeiro</institution>
		<addr-line>
			<named-content content-type="city">Rio de Janeiro</named-content>
			<named-content content-type="state">RJ</named-content>
		</addr-line>
		<country country="BR">Brasil</country>
		<email>ceciliamariz@globo.com.</email>
		<institution content-type="original">. Universidade do Estado do Rio de Janeiro (UERJ), Rio de Janeiro, RJ, Brasil. E-mail para contato: ceciliamariz@globo.com.</institution>
	</aff>
</article-meta>
```
Example 3
```xml
<article-meta>
	<contrib-group>
		<contrib contrib-type="author">
			<name>
				<surname>Borges</surname>
				<given-names>Gabriel Mendes</given-names>
			</name>
			<xref ref-type="aff" rid="aff1"><sup>1</sup></xref>
			<xref ref-type="aff" rid="aff2"><sup>2</sup></xref>
			<xref ref-type="corresp" rid="c1">*</xref>
		</contrib>
	</contrib-group>
	<aff id="aff1">
		<label>1</label>
		<institution content-type="original"> Instituto Brasileiro de Geografia e Estatística, Rio de Janeiro, Brasil.</institution>
		<institution content-type="orgname">Instituto Brasileiro de Geografia e Estatística</institution>
		<addr-line>
			<named-content content-type="city">Rio de Janeiro</named-content>
		</addr-line>
		<country country="BR">Brasil</country>
	</aff>
	<aff id="aff2">
		<label>2</label>
		<institution content-type="original"> University of California, Berkeley, U.S.A.</institution>
		<institution content-type="normalized">University of California</institution>
		<institution content-type="orgname">University of California</institution>
		<addr-line>
			<named-content content-type="city">Berkeley</named-content>
		</addr-line>
		<country country="US">USA</country>
	</aff>
	<author-notes>
		<corresp id="c1">* Correspondence G. M. Borges Instituto Brasileiro de Geografia e Estatística. Av. Presidente Antonio Carlos 25, sala 803, Rio de Janeiro, RJ 20020-010, Brasil. <email>gmendesb@hotmail.com</email>
		</corresp>
	</author-notes>
</article-meta>
```
