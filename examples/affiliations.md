#Affiliations
N.B. See samples of author and affiliation relationhsips in [authors_affililations.md] (https://github.com/JATS4R/JATS4R-Participant-Hub/blob/master/examples/authors_affiliations.md)


[American Society for Microbiology](#asm)<br>
[Aries](#aries)<br>
[BIR](#bir)<br>
[de Gruyter](#degruyter)<br>
[eLife](#eLife)<br>
[Frontiers](#frontiers)<br>
[PeerJ](#peerj)<br>
[Redalyc](#redalyc)<br>
[SciELO](#scielo)

## American Society for Microbiology <a name="asm"></a>

```xml

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
            
```



## Aries <a name="aries"></a>

```xml
   <aff id="aff1">
           <institution-wrap>
          <institution>University of Massachusetts</institution>
          <institution-id institution-id-type="Ringgold">14707</institution-id>
          </institution-wrap>
          <institution content-type="position">Director</institution>
          <institution content-type="dept">Admissions</institution>
          <addr-line content-type="addrline1">110 Thatcher Rd</addr-line>
          <addr-line content-type="addrline2">Administration Building</addr-line>
          <addr-line content-type="addrline3">Suite 204</addr-line>
          <addr-line content-type="addrline4">Mail Drop 1501</addr-line>
          <country>UNITED STATES</country>
          <addr-line content-type="city">Amherst</addr-line>
          <addr-line content-type="state">MA</addr-line>
          <addr-line content-type="zipcode">01003</addr-line>
          <fax>978-975-6813</fax>
          <phone content-type="primary">978-975-7570</phone>
</aff>
```
## BIR <a name="bir"></a>

```xml
<aff id="AF0001"><sup>1</sup>The Harley Street Clinic, London, UK</aff>
<aff id="AF0002"><sup>2</sup>Department of Surgery and Cancer, Imperial College London, London, UK</aff>
```
## de Gruyter <a name="degruyter"></a>
```
<aff id="j_hsz-2013-0008_aff_002">
  <institution>Cancer Research UK Cell Signalling Group and Weatherall</institution>,
  <institution content-type="dept">Institute of Molecular Medicine</institution>,
  <city>Oxford</city>,
  <addr-line>OX3 9DS</addr-line>,
  <country country="GB">United Kingdom</country>.
</aff>
```
Hidden Country Information
```
<aff id="j_med-2017-0001_aff_002">
    <institution content-type="dept">Department of General and Endocrynology Surgery
        Medical</institution>
    <institution>University of Warsaw</institution>, <city>Warsaw</city>.<country country="PL"/>
</aff>
```
Using Ringgold
```xml
<aff id="j_cclm-2015-0154_aff_001">
    <institution-wrap>
        <institution-id institution-id-type="Ringgold">1812</institution-id>
        <institution content-type="university">Université Catholique de Louvain</institution>
        <institution content-type="dept">Université Catholique de Louvain</institution>
    </institution-wrap>, <city>Louvain la Neuve</city>, <country country="BE">Belgium</country>
</aff>
```
Any affiliation information that is not institution, city or country shall be tagged using <addr-line>. Punctuation must be preserved.


## eLife <a name="eLife"></a>

```xml
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


## Frontiers <a name="frontiers"></a>

```xml
<aff id="aff1"><sup>1</sup><institution>School of Biological Sciences, University of 
  Nebraska-Lincoln</institution>, <addr-line>Lincoln, NE</addr-line>, 
  <country>USA</country></aff>
<aff id="aff2"><sup>2</sup><institution>Nebraska Center for Virology, University of 
  Nebraska-Lincoln</institution>, <addr-line>Lincoln, NE</addr-line>, 
  <country>USA</country></aff>
```
## PeerJ <a name="peerj"></a>
Each affiliation has some level of granularity in the address:

```xml
<aff id="aff-1"><institution>Department of Physiology and Biophysics, The Weill Cornell 
  Medical College</institution>, <addr-line>New York, NY</addr-line>, 
  <country>United States of America</country></aff>
```
## Redalyc <a name="redalyc"></a>
```xml
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
## PeerJ <a name="peerj"></a>

Each affiliation has some level of granularity in the address:

```xml
<aff id="aff-1"><institution>Department of Physiology and Biophysics, The Weill Cornell 
  Medical College</institution>, <addr-line>New York, NY</addr-line>, 
  <country>United States of America</country></aff>
```
## Redalyc <a name="redalyc"></a>
```xml
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
```xml
 <aff id="aff2">
    <label>2</label>
    <institution content-type="normalized">University School of Physical Education in Wroclaw</institution>
    <institution content-type="orgname">Univ. School of Physical Educ. in Wroclaw</institution>
    <institution content-type="orgdiv1">Faculty of Physiotherapy</institution>
    <institution content-type="orgdiv2">Department of Physiotherapy in Internal Diseases</institution>   
    <addr-line>
        <named-content content-type="state">Wroclaw</named-content>
    </addr-line>
    <country country="PL">Poland</country>
    <institution content-type="original">Department of Physiotherapy in Internal Diseases, Faculty of Physiotherapy, Univ. School of Physical Educ. in Wroclaw, Wroclaw, Poland</institution>
                </aff>
<aff id="aff3">
    <label>3</label>
    <institution content-type="normalized">Universidade de São Paulo</institution>
    <institution content-type="orgname">USP</institution>
    <institution content-type="orgdiv1">Faculdade de Medicina de Ribeirão Preto</institution>
    <institution content-type="orgdiv2">Departamento de Cirurgia e Anatomia</institution>   
    <addr-line>
        <named-content content-type="city">Ribeirão Preto</named-content>
        <named-content content-type="state">SP</named-content>
    </addr-line>
    <country country="BR">Brasil</country>
    <institution content-type="original">Departamento de Cirurgia e Anatomia, Faculdade de Medicina de Ribeirão Preto, USP, Ribeirão Preto, SP, Brasil</institution>
</aff>
```
                
