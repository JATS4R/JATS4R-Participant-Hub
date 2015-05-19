# `<contrib>` attributes

Authorship

## eLife

Examples of contrib tag with attributes

```xml
<contrib-group>
  <contrib contrib-type="author" equal-contrib="yes" id="author-23">
....
<contrib contrib-type="author" id="author-3">
...
 <contrib contrib-type="author" deceased="yes" id="author-5">
...
<contrib contrib-type="author" corresp="yes" id="author-7">
  ```

Group author:

```xml
<contrib-group>
...
  <contrib contrib-type="author" corresp="yes">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
                    <collab>NISC Comparative Sequencing Program</collab>
  </contrib>
</contrib-group>
...
<contrib-group>
                <contrib contrib-type="author non-byline">
                    <contrib-id contrib-id-type="group-author-key">group-author-id1</contrib-id>
...
</contrib-group>
```

Reviewing editor:

```xml
 <contrib-group content-type="section">
                <contrib contrib-type="editor" id="author-10">
                  ...
                </contrib>
</contrib-group>
```

## PMC

Collaborative author with expanded list of individual names:

From Lupus Sci Med. 2014; 1(1): e000037; 10.1136/lupus-2014-000037

```xml
    <contrib contrib-type="collab" id="collab1">
      <collab>APPLE investigators
        <contrib-group>
          <contrib contrib-type="collab">
            <name>
              <surname>Ardoin</surname>
              <given-names>Stacy</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Dewitt</surname>
              <given-names>Esi Morgan</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Rabinovich</surname>
              <given-names>C Egla</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Ellis</surname>
              <given-names>Janet</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Mieszkalski</surname>
              <given-names>Kelly</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Wootton</surname>
              <given-names>Janet</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Chira</surname>
              <given-names>Peter</given-names>
            </name>
          </contrib>
          <contrib contrib-type="collab">
            <name>
              <surname>Hsu</surname>
              <given-names>Joyce</given-names>
            </name>
          </contrib>
          ...
        </contrib-group>
      </collab>
    </contrib>
```
