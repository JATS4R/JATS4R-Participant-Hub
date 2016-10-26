# `<aff>`

Affiliations

## eLife

The affiliations are cross linked with authors using the following style within the contrib 
tag:

```xml
<xref ref-type="aff" rid="aff2">2</xref>
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

The reviewing editor contians affliation details within the contrib:

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

And the same for affiliatins of members of a group author group:

```xml
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
</contrib-group>
```

### Present address

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


## PeerJ

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



## Frontiers

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

## BIR

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

## Aries

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

## SciELO


```
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
```

```
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


## Redalyc
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