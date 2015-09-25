# `<pub-date>` `<history>`

Dates
## eLife

These are the dates we currenlty store in the xml. However, we will be adding more versioning information in due course and want to ensure we do it right.
For example, adding a new date each time a new version is published.

```xml
<pub-date publication-format="electronic" date-type="pub">
                <day>28</day>
                <month>02</month>
                <year>2014</year>
            </pub-date>
            <pub-date pub-type="collection">
                <year>2014</year>
            </pub-date>
            <volume>3</volume>
            <elocation-id>e00013</elocation-id>
            <history>
                <date date-type="received">
                    <day>22</day>
                    <month>06</month>
                    <year>2012</year>
                </date>
                <date date-type="accepted">
                    <day>18</day>
                    <month>07</month>
                    <year>2012</year>
                </date>
```


## PMC

An example with print and electronic dates:

From J Adv Prosthodont. 2015 Apr; 7(2): 93–97; 10.4047/jap.2015.7.2.93

```xml
      <pub-date publication-format="print" date-type="pub">
        <month>4</month>
        <year>2015</year>
      </pub-date>
      <pub-date publication-format="electronic" date-type="pub">
        <day>23</day>
        <month>4</month>
        <year>2015</year>
      </pub-date>
      ...
      <history>
        <date date-type="received">
          <day>03</day>
          <month>4</month>
          <year>2014</year>
        </date>
        <date date-type="rev-recd">
          <day>28</day>
          <month>1</month>
          <year>2015</year>
        </date>
        <date date-type="accepted">
          <day>02</day>
          <month>2</month>
          <year>2015</year>
        </date>
      </history>
```
