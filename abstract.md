# `<abstract>`

Abstracts - multiple

The @specific-use attribute may be used to identify a processing purpose, such as RSS feed or pronunciation.
The optional @abstract-type attribute may be used to identify special types of abstracts, for example, graphical abstracts, stereochemical abstracts, ASCII abstracts for sending to small devices, and Table-of-Contents abstracts that are so short they are inserted as annotations into a Table of Contents. See the attribute page for @abstract-type for a list of suggested types.

See http://jats.nlm.nih.gov/archiving/tag-library/1.1d3/attribute/abstract-type.html for suggested usage of @abstract-type attribute

## eLife

Currently publish two types of abstract. The main abstract does not take an @abstract-type attribute

```xml
<abstract>
                <object-id pub-id-type="doi">10.7554/eLife.00013.001</object-id>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>
                    <bold>DOI:</bold>
                    <ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.001"
                        >http://dx.doi.org/10.7554/eLife.00013.001</ext-link>
                </p>
            </abstract>
            <abstract abstract-type="executive-summary">
                <object-id pub-id-type="doi">10.7554/eLife.00013.002</object-id>
                <title>eLife digest</title>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>text, text, text</p>
                <p>
                    <bold>DOI:</bold>
                    <ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.002"
                        >http://dx.doi.org/10.7554/eLife.00013.002</ext-link>
                </p>
            </abstract>
            </custom-meta-group>
```


