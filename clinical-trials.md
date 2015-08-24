# `<fn>`??

Clincal trials 



## eLife

Currently publish within a footnote group with other ethical information

```xml
<fn-group content-type="ethics-information">
                <title>Ethics</title>
                <fn fn-type="other">
                    <p>Clinical trial registration CB7778886452342</p>
                </fn>
                <fn fn-type="other">
                    <p>Human subjects: Participants were recruited and sampled using methods
                        approved by the Institutional Review Board at the University of Colorado
                        (Protocol#: 0409.13). Informed consent and consent to publish was obtained
                        from all subjects. The Helsinki guidelines were followed.</p>
                </fn>
                ...
<fn-group>           
```

## NIHR

This information is currently included as free text within a long-form abstract. For future structured markup we are considering co-opting the related-object element:

```xml
<related-object id="trial1" content-type="clinical-trial" link-type="post-result" source-id="ISRCTN69423238" source-id-type="ISRCTN">
   <source>Spontaneous Urinary Stone Passage ENabled by Drugs</source>
   <ext-link ext-link-type="doi" xlink:href="http://dx.doi.org/10.1186/ISRCTN69423238">10.1186/ISRCTN69423238</ext-link>
</related-object>
```

