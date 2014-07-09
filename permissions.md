# `<permissions>`

Article permissions: copyright details, license URL, license text.


## Open Book Publishers

An example of book-, chapter-, and image-level permission statement
```xml
<book>
  <book-meta>
  ...
    <permissions>
      <copyright-statement>Margaret Harper Mills and Warwick Gould, CC BY-NC-ND</copyright-statement>
      <copyright-year>2013</copyright-year>
      <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by-nc-nd/4.0/"/>
      <license license-type="open-access" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab">
        <license-p>This entire volume is published under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License (CC BY-NC-ND 4.0), which enables you to share, copy, distribute and transmit the work in its entirety for personal and non-commercial use, providing editor and author attribution is clearly stated. However all the text and many of the individual chapters are licenced under the more permissive Creative Commons Attribution 4.0 International Public License (CC BY 4.0). See permissions relating to individual chapters. Please note that illustrations may be issued under separate licenses. See permissions relating to individual images.</license-p>
      </license>
    </permissions>
  </book-meta>
  <front-matter>...</front-matter>
  <book-body>
    <book-part id="ch1" book-part-type="chapter">
      <book-part-meta>
        ...
        <permissions>
          <copyright-statement>Warwick Gould, CC BY-NC-ND 4.0</copyright-statement>
          <copyright-year>2013</copyright-year>
          <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by-nc-nd/4.0/"/>
          <license license-type="open-access" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab">
            <license-p>This chapter is published under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License (CC BY-NC-ND 4.0), which enables you to share, copy, distribute and transmit the work for personal and non-commercial use, providing editor and author attribution is clearly stated. Please note that illustrations may be issued under separate licenses. See permissions relating to individual images.</license-p>
          </license>
        </permissions>
      </book-part-meta>
      <body>
        ...
        <fig id="fig1">
          <label>Fig. 1</label>
          <caption>
            <p>Plaster cast of mask of W. B. Yeats by Kathleen Scott (née Bruce, later Lady Kennet), 1907. 17 1/2 in. (445 mm) high. Photograph courtesy and © The National Portrait Gallery, London.</p>
          </caption>
          <permissions>
            <copyright-statement>The National Portrait Gallery, London. All rights reserved</copyright-statement>
            <copyright-year>2013</copyright-year>
            <license license-type="" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab"/>
          </permissions>
          <graphic xlink:href="images/fig1"/>
        </fig>
        ...
      </body>
    </book-part>
    <book-part id="ch2" book-part-type="chapter">
      <book-part-meta>
      ...
        <permissions>
          <copyright-statement>Alexandra Poulain, CC BY 4.0</copyright-statement>
          <copyright-year>2013</copyright-year>
          <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/4.0/"/>
          <license license-type="open-access" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab">
            <license-p>This chapter is published under a Creative Commons Attribution 4.0 International Public License (CC BY 4.0), which allows you to share, copy, distribute, transmit,adapt, and re-use the material so licenced, even for commercial purposes. Any material copied or adapted in this way must be attributed to the editors and the respective authors (but not in any way that suggests that they endorse you or your use of the work). Please note that illustrations may be issued under separate licenses. See permissions relating to individual images.</license-p>
          </license>
        </permissions>
      </book-part-meta>
      <body>...</body>
    </book-part>
  </book-body>
  <book-back>...</book-back>
</book>
```

***Notes***
* How can we make clear in a machine readable way that it's necessary to go from the particular (individual image license) to the general (whole book)? - which is to say that the permission attached to the whole book excludes individual chapters, and the permission attached to individual chapters excludes images?


## PeerJ

```xml
<permissions>
  <copyright-statement>© 2014 Surname et al.</copyright-statement>
  <copyright-year>2014</copyright-year>
  <copyright-holder>Surname et al.</copyright-holder>
  <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/4.0/">
    <license-p>This is an open access article distributed under the terms of the <ext-link
        ext-link-type="uri" xlink:href="http://creativecommons.org/licenses/by/4.0/">Creative
        Commons Attribution License</ext-link>, which permits unrestricted use, distribution,
      reproduction and adaptation in any medium and for any purpose provided that it is properly
      attributed. For attribution, the original author(s), title, publication source (PeerJ) and
      either DOI or URL of the article must be cited.</license-p>
  </license>
</permissions>
```

## eLife

```xml
<permissions>
  <copyright-statement>Copyright &#xa9; 2012, Alegado et al</copyright-statement>
  <copyright-year>2012</copyright-year>
  <copyright-holder>Alegado et al</copyright-holder>
  <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/4.0/">
    <license-p>This article is distributed under the terms of the <ext-link ext-link-type="uri"
        xlink:href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution
        License</ext-link>, which permits unrestricted use and redistribution provided that the
      original author and source are credited.</license-p>
  </license>
</permissions>
```

## Ubiquity Press

```xml

<permissions>
    <copyright-statement>Copyright: &#x00A9; 2014 The Author(s)</copyright-statement>
    <copyright-year>2014</copyright-year>
    <license license-type="open-access"
        xlink:href="http://creativecommons.org/licenses/by/3.0/">
        <license-p>This is an open-access article distributed under the terms of the
            Creative Commons Attribution 3.0 Unported License (CC-BY 3.0), which permits
            unrestricted use, distribution, and reproduction in any medium, provided the
            original author and source are credited. See <uri
                xlink:href="http://creativecommons.org/licenses/by/3.0/"
                >http://creativecommons.org/licenses/by/3.0/</uri>.</license-p>
    </license>
</permissions>
```

## JATS Tag Library

From [Journal Publishing Tag Library - NISO JATS Draft Version
1.1d1](http://jatspan.org/niso/publishing-1.1d1/#p=elem-license)

```xml
<permissions>
  <copyright-statement>Copyright: &copy; 2004 Eichenberger et al.</copyright-statement>
  <copyright-year>2004</copyright-year>
  <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/2.0/">
    <license-p>This is an open-access article distributed under the terms of the Creative Commons
      Attribution License, which permits unrestricted use, distribution, and reproduction in any
      medium, provided the original work is properly cited.</license-p>
  </license>
</permissions>
```

***Notes***

* Use of character entity references ("\&copy;") should be discouraged (? see [issue
  #1](https://github.com/JATS4R/elements/issues/1))

