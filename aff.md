# `<aff>`

Affiliations

## eLife

The affiliations are cross linked with authors using the following style within the contrib tag:

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
             </addr-line>, <country>United States</country>
    </aff>
    <aff id="aff2">
         <label>2</label>
              <institution content-type="dept">Department of Biological Chemistry and Molecular Pharmacology</institution>,
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
<aff id="aff-1"><institution>Department of Physiology and Biophysics, The Weill Cornell Medical College</institution>, <addr-line>New York, NY</addr-line>, <country>United States of America</country></aff>
```

# Present address

## eLife
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
```

