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

## Present address

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
