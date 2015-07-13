# `<funding-group>`

Funding

## eLife

The funding section is cross linked to each author by, for example <xref ref-type="other" rid="par-1"/> contained in the <contrib> element.


```xml
 <funding-group>
                <award-group id="par-1">
                    <funding-source>
                        <institution-wrap>
                            <institution-id institution-id-type="FundRef">dx.doi.org/10.13039/100000011</institution-id>
                            <institution content-type="university">Howard Hughes Medical Institute</institution>
                            </institution-wrap>
                    </funding-source>
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
                    <funding-source>
                        <institution-wrap>
                            <institution-id institution-id-type="FundRef">dx.doi.org/10.13039/100000002</institution-id>
                            <institution content-type="university">National Institutes of Health</institution>
                        </institution-wrap>
                     </funding-source>
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
                    <funding-source>
                        <institution-wrap>
                            <institution-id institution-id-type="FundRef">dx.doi.org/10.13039/100000002</institution-id>
                            <institution content-type="university">National Institutes of Health</institution>
                        </institution-wrap>
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
                    <funding-source>
                        <institution-wrap>
                            <institution-id institution-id-type="FundRef">dx.doi.org/10.13039/100000002</institution-id>
                            <institution content-type="university">National Institutes of Health</institution>
                        </institution-wrap>
                    </funding-source>
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
                    <funding-source>
                        <institution-wrap>
                        <institution-id institution-id-type="FundRef">dx.doi.org/10.13039/100000002</institution-id>
                        <institution content-type="university">National Institutes of Health</institution>
                        </institution-wrap>
                    </funding-source>
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
                    <funding-source><institution-wrap>
                        <institution-id institution-id-type="FundRef">dx.doi.org/10.13039/100000002</institution-id>
                        <institution content-type="university">National Institutes of Health</institution>
                    </institution-wrap></funding-source>
                    <award-id>T32 HG00047</award-id>
                    <principal-award-recipient>
                        <name>
                            <surname>Fairclough</surname>
                            <given-names>Stephen R</given-names>
                        </name>
                    </principal-award-recipient>
                </award-group>
                <award-group id="par-7">
                    <funding-source><institution-wrap>
                        <institution content-type="university">Laura and John Arnold Foundation</institution>
                    </institution-wrap></funding-source>
                    <principal-award-recipient>NISC Comparative Sequencing Program</principal-award-recipient>
                </award-group>
                <funding-statement>The funders had no role in study design; collection, analysis,
                    and interpretation of data; writing the article; and or the decision to submit
                    to the journal.</funding-statement>
            </funding-group>
```


## PLOS


```xml
<funding-group>
<funding-statement>This work was funded by Natural Sciences and Engineering Research Council of Canada, RGPIN-2014-06318, JD <ext-link ext-link-type="uri" xlink:href="http://www.nserc-crsng.gc.ca/index_eng.asp" xlink:type="simple">http://www.nserc-crsng.gc.ca/index_eng.asp</ext-link>; SensoriMotor Rehabilitation Research Team (SMRRT), Canadian Institutes of Health Research, RMF111622, JD <ext-link ext-link-type="uri" xlink:href="http://www.cihr-irsc.gc.ca/e/193.html" xlink:type="simple">http://www.cihr-irsc.gc.ca/e/193.html</ext-link>; and SensoriMotor Rehabilitation Research Team (SMRRT), Canadian Institutes of Health Research, postdoctoral fellowships, SV and OL; <ext-link ext-link-type="uri" xlink:href="http://www.cihr-irsc.gc.ca/e/193.html" xlink:type="simple">http://www.cihr-irsc.gc.ca/e/193.html</ext-link>. The funders had no role in study design, data collection and analysis, decision to publish, or preparation of the manuscript.</funding-statement>
</funding-group>
```


## Aries


 ```<funding-group>
            <!-- the award group ID attribute is a unique ID that Aries assigns. It is not meaningful -->
         <award-group id="ID0EMUAE54">
         <!-- The Author entering the funding source chooses from a drop-down list prepopulated with the FundRef database of funders, or can type in free text. If the funder name is from the FundRef database, the named-content-type content-type attribute is hardcoded as "funder-id" and the FundRef funder ID is included as the value -->
          <funding-source>Directorate for Mathematical and Physical Sciences<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000086</named-content></funding-source>
<!-- the award ID is the grant number as entered by the Author -->          
          <award-id>123456</award-id>
   <!-- the principal-award-recipient is one of the authors, or set to the hardcoded string "Not Applicable" if none of the authors are the grant recipient -->
          <principal-award-recipient>Buzz Aldrin</principal-award-recipient>
        </award-group>
        <award-group id="ID0E4UAE55">
          <funding-source>Division of Physics<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000166</named-content></funding-source>
          <award-id>abcdef</award-id>
          <principal-award-recipient>Not Applicable</principal-award-recipient>
        </award-group>
        <award-group id="ID0EOVAE56">
          <funding-source>Division of Mathematical Sciences<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000121</named-content></funding-source>
          <award-id>rst123</award-id>
          <principal-award-recipient>John Nash</principal-award-recipient>
        </award-group>
        <award-group id="ID0E6VAE57">
          <funding-source>Directorate for Mathematical and Physical Sciences<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000086</named-content></funding-source>
          <award-id>123456</award-id>
          <principal-award-recipient>Buzz Aldrin</principal-award-recipient>
        </award-group>
        <award-group id="ID0EV2AE58">
          <funding-source>Division of Physics<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000166</named-content></funding-source>
          <award-id>abcdef</award-id>
          <principal-award-recipient>Richard Phillips Feynman</principal-award-recipient>
        </award-group>
        <award-group id="ID0EM4AE59">
        <!-- in this example, the funding source was not found in the FundRef database, therefore the <named-content> element is omitted -->
          <funding-source>Division of Mathematical Sciences</funding-source>
          <award-id>rst123</award-id>
          <principal-award-recipient>John Nash</principal-award-recipient>
        </award-group>
        <award-group id="ID0EB6AE60">
          <funding-source>U.S. Nuclear Regulatory Commission<named-content content-type="funder-id">http://dx.doi.org/10.13039/100005187</named-content></funding-source>
          <award-id>asdfasdf</award-id>
          <principal-award-recipient>Buzz Aldrin</principal-award-recipient>
        </award-group>
        <award-group id="ID0EYEAG114">
          <funding-source>National Institute of Environmental Health Sciences (US)<named-content content-type="funder-id">http://dx.doi.org/10.13039/100000066</named-content></funding-source>
          <award-id>5 R01 HL123451-01A2</award-id>
          <principal-award-recipient>John Nash</principal-award-recipient>
        </award-group>
      </funding-group>
      ```