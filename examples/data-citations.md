# `<element-citation publication-type="data">`

These examples of how to tag data references are taken from the eLife kitchen sink XML. They use element citation.


####Data reference: NCBI Gene Expression Omnibus: pub-id-type="accession" assigning-authority="NCBI"


```xml

...
	<ref id="bib1">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Bouveret</surname>
                    <given-names>R</given-names>
                </name>
                <name>
                    <surname>Waardenberg</surname>
                    <given-names>AJ</given-names>
                </name>
                <name>
                    <surname>Schonrock</surname>
                    <given-names>N</given-names>
                </name>
                <name>
                    <surname>Ramialison</surname>
                    <given-names>M</given-names>
                </name>
                <name>
                    <surname>Doan</surname>
                    <given-names>T</given-names>
                </name>
                <name>
                    <surname>de Jong</surname>
                    <given-names>D</given-names>
                </name>
                <name>
                    <surname>Bondue</surname>
                    <given-names>A</given-names>
                </name>
                <name>
                    <surname>Kaur</surname>
                    <given-names>G</given-names>
                </name>
                <name>
                    <surname>Mohamed</surname>
                    <given-names>S</given-names>
                </name>
                <name>
                    <surname>Fonoudi</surname>
                    <given-names>H</given-names>
                </name>
                <name>
                    <surname>Chen</surname>
                    <given-names>C</given-names>
                </name>
                <name>
                    <surname>Wouters</surname>
                    <given-names>M</given-names>
                </name>
                <name>
                    <surname>Bhattacharya</surname>
                    <given-names>S</given-names>
                </name>
                <name>
                    <surname> Plachta</surname>
                    <given-names>N</given-names>
                </name>
                <name>
                    <surname>Dunwoodie</surname>
                    <given-names>SL</given-names>
                </name>
                <name>
                    <surname>Chapman</surname>
                    <given-names>G</given-names>
                </name>
                <name>
                    <surname>Blanpain</surname>
                    <given-names>C</given-names>
                </name>
                <name>
                    <surname>Harvey</surname>
                    <given-names>RP</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2015">2015</year>
            <data-title>NKX2-5 mutations causative for congenital heart disease retain
                functionality and are directed to hundreds of targets</data-title>
            <source>NCBI Gene Expression Omnibus</source>
            <pub-id pub-id-type="accession" assigning-authority="NCBI"
                xlink:href="https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE44902"
                >GSE44902</pub-id>
        </element-citation>
    </ref>
...

```

####Data reference: RCSB Protein Data Bank 

```
...
<ref id="bib2">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Du</surname>
                    <given-names>J</given-names>
                </name>
                <name>
                    <surname>Johnson</surname>
                    <given-names>LM</given-names>
                </name>
                <name>
                    <surname>Groth</surname>
                    <given-names>M</given-names>
                </name>
                <name>
                    <surname>Feng</surname>
                    <given-names>S</given-names>
                </name>
                <name>
                    <surname>Hale</surname>
                    <given-names>CJ</given-names>
                </name>
                <name>
                    <surname>Li</surname>
                    <given-names>S</given-names>
                </name>
                <name>
                    <surname>Vashisht</surname>
                    <given-names>AA</given-names>
                </name>
                <name>
                    <surname>Gallego-Bartolome</surname>
                    <given-names>J</given-names>
                </name>
                <name>
                    <surname>Wohlschlegel</surname>
                    <given-names>JA</given-names>
                </name>
                <name>
                    <surname>Patel</surname>
                    <given-names>DJ</given-names>
                </name>
                <name>
                    <surname>Jacobsen</surname>
                    <given-names>SE</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2014">2014</year>
            <data-title>Crystal structure of KRYPTONITE in complex with mCHH DNA and
                SAH</data-title>
            <source>RCSB Protein Data Bank</source>
            <pub-id pub-id-type="doi" assigning-authority="RCSB Protein Data Bank">10.2210/pdb4qen/pdb</pub-id>
        </element-citation>
    </ref>
    ...

```

####Generic data citation

```
...
    <ref id="bib3">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Ferry</surname>
                    <given-names>Q</given-names>
                </name>
                <name>
                    <surname>Steinberg</surname>
                    <given-names>J</given-names>
                </name>
                <name>
                    <surname>Webber</surname>
                    <given-names>C</given-names>
                </name>
                <name>
                    <surname>FitzPatrick</surname>
                    <given-names>DR</given-names>
                </name>
                <name>
                    <surname>Ponting</surname>
                    <given-names>CP</given-names>
                </name>
                <name>
                    <surname>Zisserman</surname>
                    <given-names>A</given-names>
                </name>
                <name>
                    <surname>Nellåker</surname>
                    <given-names>C</given-names>
                </name>
            </person-group>   
            <year iso-8601-date="2014">2014</year>
            <data-title>Diagnostically relevant facial gestalt information from ordinary photos database</data-title>
            <source>Division of Clinical Neurology, University of Oxford</source>
            <ext-link ext-link-type="uri" xlink:href="https://github.com/ChristofferNellaker/Clinical_Face_Phenotype_Space_Pipeline">
                https://github.com/ChristofferNellaker/Clinical_Face_Phenotype_Space_Pipeline
            </ext-link>
        </element-citation>
    </ref>
...

```

####Data reference: NCBI Nucleotide: pub-id-type="accession" assigning-authority="NCBI" contains version detail
```
...
    <ref id="bib4">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Gavrilov</surname>
                    <given-names>S</given-names>
                </name>
                <name>
                    <surname>Harvey</surname>
                    <given-names>RP</given-names>
                </name>
                <name>
                    <surname>Papaioannou</surname>
                    <given-names>VE</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2014">2014</year>
            <data-title>Mus musculus T-box 2 (Tbx2), mRNA</data-title>
            <source>NCBI Nucleotide</source>
            <pub-id pub-id-type="accession" assigning-authority="NCBI"
                xlink:href="http://www.ncbi.nlm.nih.gov/nuccore/120407038"
                >NM_009324</pub-id>
            <version designator="NM_009324.2">NM_009324.2</version>
        </element-citation>
    </ref>
...

```

####Data reference: NCBI Gene Expression Omnibus (GEO): pub-id-type="accession" assigning-authority="NCBI"
```
...
     <ref id="bib5">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Hoang</surname>
                    <given-names>C</given-names>
                </name>
                <name>
                    <surname>Swift</surname>
                    <given-names>GH</given-names>
                </name>
                <name>
                    <surname>Azevedo-Pouly</surname>
                    <given-names>A</given-names>
                </name>
                <name>
                    <surname>MacDonald</surname>
                    <given-names>RJ</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2015">2015</year>
            <data-title>Effects on the transcriptome of adult mouse pancreas (principally
                acinar cells) by the inactivation of the Ptf1a gene in vivo</data-title>
            <source>NCBI Gene Expression Omnibus</source>
            <pub-id pub-id-type="accession" assigning-authority="NCBI"
                xlink:href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE70542"
                >GSE70542</pub-id>
        </element-citation>
    </ref>
...

```

####Data reference: Dryad dataset
```
...
    <ref id="bib6">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Kok</surname>
                    <given-names>K</given-names>
                </name>
                <name>
                    <surname>Ay</surname>
                    <given-names>A</given-names>
                </name>
                <name>
                    <surname>Li</surname>
                    <given-names>L</given-names>
                </name>
                <name>
                    <surname>Arnosti</surname>
                    <given-names>DN</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2015">2015</year>
            <data-title>Data from: Genome-wide errant targeting by Hairy</data-title>
            <source>Dryad Digital Repository</source>
            <pub-id pub-id-type="doi" assigning-authority="Dryad Digital Repository">10.5061/dryad.cv323</pub-id>
        </element-citation>
    </ref>
...

```


####Data reference: ProteomeXchange: pub-id-type="archive" - not clear what this number is, so default option
```
...
    <ref id="bib7">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Radoshevich</surname>
                    <given-names>L</given-names>
                </name>
                <name>
                    <surname>Impens</surname>
                    <given-names>F</given-names>
                </name>
                <name>
                    <surname>Ribet</surname>
                    <given-names>D</given-names>
                </name>
                <name>
                    <surname>Quereda</surname>
                    <given-names>JJ</given-names>
                </name>
                <name>
                    <surname>Nam Tham</surname>
                    <given-names>T</given-names>
                </name>
                <name>
                    <surname>Nahori</surname>
                    <given-names>MA</given-names>
                </name>
                <name>
                    <surname>Bierne</surname>
                    <given-names>H</given-names>
                </name>
                <name>
                    <surname>Dussurget</surname>
                    <given-names>O</given-names>
                </name>
                <name>
                    <surname>Pizarro-Cerdá</surname>
                    <given-names>J</given-names>
                </name>
                <name>
                    <surname>Knobeloch</surname>
                    <given-names>KP</given-names>
                </name>
                <name>
                    <surname>Cossart</surname>
                    <given-names>P</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2015">2015a</year>
            <data-title>ISG15 counteracts <italic>Listeria monocytogenes</italic>
                infection</data-title>
            <source>ProteomeXchange</source>
            <pub-id pub-id-type="archive"
                xlink:href="http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD001805"
                >PXD001805</pub-id>
        </element-citation>
    </ref>
...

```


####Data reference: ArrayExpress: pub-id-type="accession"
```
...

    <ref id="bib8">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Radoshevich</surname>
                    <given-names>L</given-names>
                </name>
                <name>
                    <surname>Impens</surname>
                    <given-names>F</given-names>
                </name>
                <name>
                    <surname>Ribet</surname>
                    <given-names>D</given-names>
                </name>
                <name>
                    <surname>Quereda</surname>
                    <given-names>JJ</given-names>
                </name>
                <name>
                    <surname>Nam Tham</surname>
                    <given-names>T</given-names>
                </name>
                <name>
                    <surname>Nahori</surname>
                    <given-names>MA</given-names>
                </name>
                <name>
                    <surname>Bierne</surname>
                    <given-names>H</given-names>
                </name>
                <name>
                    <surname>Dussurget</surname>
                    <given-names>O</given-names>
                </name>
                <name>
                    <surname>Pizarro-Cerdá</surname>
                    <given-names>J</given-names>
                </name>
                <name>
                    <surname>Knobeloch</surname>
                    <given-names>KP</given-names>
                </name>
                <name>
                    <surname>Cossart</surname>
                    <given-names>P</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2015">2015b</year>
            <data-title>Transcription profiling by high throughput sequencing of LoVo
                cells infected with Listeria for 24 hr compared to uninfected
                cells</data-title>
            <source>ArrayExpress</source>
            <pub-id pub-id-type="accession"
                xlink:href="https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-3649/"
                >E-MTAB-3649</pub-id>
        </element-citation>
    </ref>

...

```








####Data reference: JASPAR
```
...
    <ref id="bib9">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Staab</surname>
                    <given-names>TA</given-names>
                </name>
                <name>
                    <surname>Griffen</surname>
                    <given-names>TC</given-names>
                </name>
                <name>
                    <surname>Corcoran</surname>
                    <given-names>C</given-names>
                </name>
                <name>
                    <surname>Evgrafov</surname>
                    <given-names>O</given-names>
                </name>
                <name>
                    <surname>Knowles</surname>
                    <given-names>JA</given-names>
                </name>
                <name>
                    <surname>Sieburth</surname>
                    <given-names>D</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2013">2013</year>
            <data-title>SKN-1 from the JASPAR CORE database</data-title>
            <source>JASPAR</source>
            <pub-id pub-id-type="archive"
                xlink:href="http://jaspar.genereg.net/cgi-bin/jaspar_db.pl"
                >MA0547.1</pub-id>
        </element-citation>
    </ref>
...

```


####Data reference: NCBI BioProject: author is a collab pub-id-type="accession" assigning-authority="NCBI" example of 3 references with same author/year 
```
...
    <ref id="bib10">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <collab>The <italic>Shigella</italic> Genome Sequencing Consortium</collab>
            </person-group>
            <year iso-8601-date="2015">2015a</year>
            <data-title>Global Diversity of Shigella Species</data-title>
            <source>NCBI BioProject</source>
            <pub-id pub-id-type="accession" assigning-authority="NCBI"
                xlink:href="http://www.ncbi.nlm.nih.gov/bioproject/?term=PRJEB2846"
                >PRJEB2846</pub-id>
        </element-citation>
    </ref>
    <ref id="bib11">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <collab>The <italic>Shigella</italic> Genome Sequencing Consortium</collab>
            </person-group>
            <year iso-8601-date="2015">2015b</year>
            <data-title>Shigella sonnei and flexneri from around the world</data-title>
            <source>NCBI BioProject</source>
            <pub-id pub-id-type="accession" assigning-authority="NCBI"
                xlink:href="http://www.ncbi.nlm.nih.gov/bioproject/204320"
                >PRJEB2460</pub-id>
        </element-citation>
    </ref>
    <ref id="bib12">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <collab>The <italic>Shigella</italic> Genome Sequencing Consortium</collab>
            </person-group>
            <year iso-8601-date="2015">2015c</year>
            <data-title>Shigella flexneri from around the world</data-title>
            <source>NCBI BioProject </source>
            <pub-id pub-id-type="accession" assigning-authority="NCBI"
                xlink:href="http://www.ncbi.nlm.nih.gov/bioproject/?term=PRJEB2542"
                >PRJEB2542</pub-id>
        </element-citation>
    </ref>
...

```


####Data reference
```
...
<ref id="bib13">
        <element-citation publication-type="data">
            <person-group person-group-type="author">
                <name>
                    <surname>Zhang</surname>
                    <given-names>YA</given-names>
                </name>
                <name>
                    <surname>Salinas</surname>
                    <given-names>I</given-names>
                </name>
                <name>
                    <surname>Li</surname>
                <given-names>J</given-names>
                </name>
                <name>
                    <surname>Parra</surname>
                    <given-names>D</given-names>
                </name>
                <name>
                    <surname>Bjork</surname>
                    <given-names>S</given-names>
                </name>
                <name>
                    <surname>Xu</surname>
                    <given-names>Z</given-names>
                </name>
                <name>
                    <surname>LaPatra</surname>
                    <given-names>SE</given-names>
                </name>
                <name>
                    <surname>Bartholomew</surname>
                    <given-names>J</given-names>
                </name>
                <name>
                    <surname>Sunyer</surname>
                    <given-names>JO</given-names>
                </name>
            </person-group>
            <year iso-8601-date="2010">2010</year>
            <data-title>Polymeric immunoglobulin receptor [Oncorhynchus mykiss]</data-title>
            <source>NCBI</source>
            <pub-id assigning-authority="NCBI" pub-id-type="accession" xlink:href="http://www.ncbi.nlm.nih.gov/protein/ADB81776.1">GenBank: ADB81776.1</pub-id>
        </element-citation>
    </ref>
    ...

```

####Data reference: modMine pub-id-type="archive"
```
...
            <ref id="bib14">
                <element-citation publication-type="data">
                    <person-group person-group-type="author">
                        <name>
                            <surname>Zhong</surname>
                            <given-names>M</given-names>
                        </name>
                        <name>
                            <surname>Snyder</surname>
                            <given-names>M</given-names>
                        </name>
                        <name>
                            <surname>Slightam</surname>
                            <given-names>C</given-names>
                        </name>
                        <name>
                            <surname>Kim</surname>
                            <given-names>S</given-names>
                        </name>
                        <name>
                            <surname>Murray</surname>
                            <given-names>J</given-names>
                        </name>
                        <name>
                            <surname>Waterston</surname>
                            <given-names>R</given-names>
                        </name>
                        <name>
                            <surname>Gerstein</surname>
                            <given-names>M</given-names>
                        </name>
                        <name>
                            <surname>Niu</surname>
                            <given-names>W</given-names>
                        </name>
                        <name>
                            <surname>Janette</surname>
                            <given-names>J</given-names>
                        </name>
                        <name>
                            <surname>Raha</surname>
                            <given-names>D</given-names>
                        </name>
                        <name>
                            <surname>Agarwal</surname>
                            <given-names>A</given-names>
                        </name>
                        <name>
                            <surname>Reinke</surname>
                            <given-names>V</given-names>
                        </name>
                        <name>
                            <surname>Sarov</surname>
                            <given-names>M</given-names>
                        </name>
                        <name>
                            <surname>Hyman</surname>
                            <given-names>A</given-names>
                        </name>
                    </person-group>
                    <year iso-8601-date="2013">2013</year>
                    <data-title>ChIP-Seq Identification of C. elegans TF Binding Sites</data-title>
                    <source>modMine</source>
                    <pub-id pub-id-type="archive" xlink:href="http://intermine.modencode.org/release-33/report.do?id=77000379">modENCODE_3369</pub-id>
                </element-citation>
            </ref>
...

```
