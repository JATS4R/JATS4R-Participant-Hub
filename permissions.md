# `<permissions>`

Article permissions: copyright details, license URL, license text.


## Open Book Publishers

An updated example of book-, chapter-, and image-level permission statement

```xml
<book>
  <book-meta>
  ...
    <permissions>
      <copyright-statement>Margaret Harper Mills and Warwick Gould, CC BY-NC-ND</copyright-statement>
      <copyright-year>2013</copyright-year>
      <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by-nc-nd/4.0/"/>
        <license-p>This entire volume is published under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License (CC BY-NC-ND 4.0), which enables you to share, copy, distribute and transmit the work in its entirety for personal and non-commercial use, providing editor and author attribution is clearly stated. However all the text and many of the individual chapters are licenced under the more permissive Creative Commons Attribution 4.0 International Public License (CC BY 4.0). See permissions relating to individual chapters. Please note that illustrations may be issued under separate licenses. See permissions relating to individual images. Detailed information is available at <ext-link ext-link-type="uri" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab">http://www.openbookpublishers.com/product/233#copyright</ext-link>.</license-p>
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
            <license-p>This chapter is published under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License (CC BY-NC-ND 4.0), which enables you to share, copy, distribute and transmit the work for personal and non-commercial use, providing editor and author attribution is clearly stated. Please note that illustrations may be issued under separate licenses. See permissions relating to individual images. Detailed information is available at <ext-link ext-link-type="uri" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab">http://www.openbookpublishers.com/product/233#copyright</ext-link>.</license-p>
          </license>
        </permissions>
      </book-part-meta>

      <body>
        ...
        <fig id="fig1">
          <label>Fig. 1</label>
          <caption>
            <p>Plaster cast of mask of W. B. Yeats by Kathleen Scott (née Bruce, later Lady Kennet),
              1907. 17 1/2 in. (445 mm) high. Photograph courtesy and © The National Portrait Gallery,
              London.</p>
          </caption>
          <permissions>
            <copyright-statement>The National Portrait Gallery, London. All rights
              reserved</copyright-statement>
            <copyright-year>2013</copyright-year>
            <!-- Do we need a license element here? Do we need a URI?-->
            <license license-type="" xlink:href=""/>
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
            <license-p>This chapter is published under a Creative Commons Attribution 4.0 International Public License (CC BY 4.0), which allows you to share, copy, distribute, transmit,adapt, and re-use the material so licenced, even for commercial purposes. Any material copied or adapted in this way must be attributed to the editors and the respective authors (but not in any way that suggests that they endorse you or your use of the work). Please note that illustrations may be issued under separate licenses. See permissions relating to individual images. Detailed information is available at <ext-link ext-link-type="uri" xlink:href="http://www.openbookpublishers.com/isbn/9781783740178#copyrighttab">http://www.openbookpublishers.com/product/233#copyright</ext-link>.</license-p>
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

Updated OBP example:
* the human readable link has been moved inside license-p as suggested in issue #2. It should be ignored by machines;
* all rights reserved image: the license element has been left incomplete. Do we need a license element? And do we want/need a machine readable URI? See issue #8


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

eLife suggested changes based on discussions (tie-in with upgrade from 3.0 to JATS in Oct)
<permissions>
                <copyright-statement>Copyright &#xa9; 2014, Baldwin</copyright-statement>
                <copyright-year>2014</copyright-year>
                <copyright-holder>Baldwin</copyright-holder>
                <license xlink:href="http://creativecommons.org/licenses/by/4.0/">
                    <license-p>This article is distributed under the terms of the <ext-link
                            ext-link-type="uri"
                            xlink:href="http://creativecommons.org/licenses/by/3.0/">Creative
                            Commons Attribution License</ext-link>, which permits unrestricted use
                        and redistribution provided that the original author and source are
                        credited.</license-p>
                </license>
            </permissions>


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
      original author and source are credited. See
      <uri xlink:href="http://creativecommons.org/licenses/by/3.0/"
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





## Examples from PMC Content


### Pretty basic

```xml
<permissions>
  <license>
    <license-p>This is an Open Access article distributed under the terms of the Creative Commons
      Attribution License, (<ext-link ext-link-type="uri"
        xlink:href="http://creativecommons.org/licenses/by/3.0/"
        >http://creativecommons.org/licenses/by/3.0/</ext-link>) which permits unrestricted use,
      distribution, and reproduction in any medium, provided the original work is properly
      cited.</license-p>
  </license>
</permissions>
```

### Pretty basic just wrong

Compare @xlink:href with content of ext-link and text.

```xml
<permissions>
  <license>
    <license-p>This is an Open Access article distributed under the terms of the Creative Commons
      Attribution License, (<ext-link ext-link-type="uri"
        xlink:href="http://creativecommons.org/licenses/by-nc-nd/3.0/"
        >http://creativecommons.org/licenses/by/3.0/</ext-link>) which permits unrestricted use,
      distribution, and reproduction in any medium, provided the original work is properly
      cited.</license-p>
  </license>
</permissions>
```

```xml
<permissions>
  <copyright-statement>© Juan Valdez et al. This is an open-access article distributed under the
    terms of the Creative Commons Attribution License, which permits unrestricted use,
    distribution, and reproduction in any medium, provided the original author and source are
    properly cited. To view a copy of this license, visit <ext-link ext-link-type="uri"
      xlink:href="http://creativecommons.org/licenses/by/3.0/"
      >http://creativecommons.org/licenses/by/3.0/</ext-link></copyright-statement>
  <copyright-year>2013</copyright-year>
  <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/3.0">
    <p>This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0
      Unported License.</p>
  </license>
</permissions>
```

### Entire licence paragraph tagged as an ext-link

```xml
<permissions>
  <copyright-statement>Copyright © 2014 BleepBlip Society</copyright-statement>
  <copyright-year>2014</copyright-year>
  <copyright-holder>BleepBlip Society</copyright-holder>
  <license>
    <license-p>
      <ext-link xmlns:xlink="http://www.w3.org/1999/xlink" ext-link-type="uri"
        xlink:href="http://bleepblip.org/authorchoice_ccby_termsofuse.html">Terms of Use
        CC-BY</ext-link>
    </license-p>
  </license>
</permissions>
```

```xml
<permissions>
  <copyright-statement>Copyright © 2014 BleepBlip Society</copyright-statement>
  <copyright-year>2014</copyright-year>
  <copyright-holder>BleepBlip Society</copyright-holder>
  <license>
    <license-p>
      <ext-link xmlns:xlink="http://www.w3.org/1999/xlink" ext-link-type="uri"
        xlink:href="http://bleepblip.org/authorchoice_termsofuse.html">Terms of Use</ext-link>
    </license-p>
  </license>
</permissions>
```


### URI on \<license>

```xml
<permissions>
  <license license-type="open-access"
    xlink:href="http://creativecommons.org/licenses/by-nc-nd/3.0/">
    <license-p>This is an open access article under the terms of the Creative Commons
      Attribution-NonCommercial-NoDerivs License, which permits use and distribution in any
      medium, provided the original work is properly cited, the use is non-commercial and no
      modifications or adaptations are made.</license-p>
  </license>
</permissions>
```


### Just a statement of when article becomes/became "Open Access"

```xml
<permissions>
  <copyright-statement>Copyright © 2014 BleepBlip Society</copyright-statement>
  <copyright-year>2014</copyright-year>
  <copyright-holder>BleepBlip Society</copyright-holder>
  <license>
    <license-p>Open Access on 05/27/2015</license-p>
  </license>
</permissions>
```

### With an inline image

```xml
<permissions>
  <copyright-statement>© 2014 The authors</copyright-statement>
  <copyright-year>2014</copyright-year>
  <license license-type="license">
    <license-p>
      <inline-graphic xlink:href="88x31.png"/>This work is licensed under a <ext-link
        ext-link-type="uri" xlink:href="http://creativecommons.org/licenses/by/3.0/deed.en_GB"
        >Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported
      License</ext-link>.</license-p>
  </license>
</permissions>
```

### Multiple copyright statements - multiple licenses

```xml
<permissions>
  <copyright-statement content-type="issue-copyright">© 2014 Published by Orange Blossom
    Periodicals, Inc.</copyright-statement>
  <copyright-statement content-type="article-copyright">© 2014 The Authors. <italic>Am Example
      J.</italic> published by Orange Blossom Periodicals, Inc.</copyright-statement>
  <license license-type="creativeCommonsBy">
    <license-p>This is an open access article under the terms of the <ext-link ext-link-type="uri"
        xlink:href="http://creativecommons.org/licenses/by/3.0/">Creative Commons
        Attribution</ext-link> License, which permits use, distribution and reproduction in any
      medium, provided the original work is properly cited.</license-p>
  </license>
  <license license-type="open-access">
    <license-p/>
  </license>
</permissions>
```


### Almost with a subtitle

```xml
<permissions>
  <copyright-statement>© The Author(s) 2014</copyright-statement>
  <license license-type="OpenAccess">
    <license-p>
      <bold>Open Access</bold> This article is distributed under the terms of the Creative Commons
      Attribution License which permits any use, distribution, and reproduction in any medium,
      provided the original author(s) and the source are credited.</license-p>
  </license>
</permissions>
```


### Copyright clearance center

```xml
<license license-type="ccc">
  <license-p>0148-0731/2014/136(08)/081004/7/<price>$0.00</price></license-p>
</license>
```

### Complicated

```xml
<permissions>
  <copyright-statement>&#x00A9; 2014 Spinx <italic>et&#x00A0;al.</italic> This article is
    distributed by The American Society for Pugilistic Endeavors under license from the author(s).
    Two months after publication it is available to the public under an
    Attribution&#x2013;Noncommercial&#x2013;Share Alike 3.0 Unported Creative Commons License
      (<ext-link xmlns:xlink="http://www.w3.org/1999/xlink" ext-link-type="uri"
      xlink:href="http://creativecommons.org/licenses/by-nc-sa/3.0"
      >http://creativecommons.org/licenses/by-nc-sa/3.0</ext-link>).</copyright-statement>
  <copyright-year>2014</copyright-year>
  <license license-type="creative-commons">
    <license-p>&#x201C;ASPE&#x00AE;,&#x201D; &#x201C;The American Society for Pugilistic
      Endeavors&#x00AE;,&#x201D; and &#x201C;American Journal of Pugilism&#x00AE;&#x201D; are
      registered trademarks of The American Society of Cell Biology.</license-p>
  </license>
</permissions>
```


## From PMC Tagging Guidelines

### Multiple license types.

```xml
<permissions>
  <copyright-statement>Copyright &#xA9; 2012 Medical
    Publishing Corp.</copyright-statement>
  <copyright-year>2012</copyright-year>
  <license license-type="open-access"
    xlink:href="http://creativecommons.org/licenses/by-nc/3.0/">
    <license-p>This article is distributed under the terms of the
      Creative Commons Attribution Non-Commercial License, which permits
      unrestricted non-commercial use, distribution, and reproduction in any
      medium, provided the original work is properly cited.</license-p>
  </license>
  <license license-type="ccc">
    <license-p>For permission to reuse copyrighted content from this publication,
      please go to <ext-link ext-link-type="uri"
      xlink:href="http://www.copyright.com">www.copyright.com</ext-link>, or
      contact Copyright Clearance Center, 222 Rosewood Drive, Danvers, MA 01923</license-p>
  </license>
</permissions>
```

### License with URI in the license text.

```xml
<license license-type="open-access">
  <license-p>This article is distributed under the terms of the Creative Commons Attribution License
    (<ext-link ext-link-type="uri" xlink:href="http://creativecommons.org/licenses/by/3.0/">
    http://creativecommons.org/licenses/by/3.0/</ext-link>), which permits unrestricted use and
    redistribution provided that the original author and source are credited.</license-p>
</license>
```

### License with URI not in the license text.

```xml
<license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/3.0/">
  <license-p>This article is distributed under the terms of the Creative Commons Attribution License,
  which permits unrestricted use and redistribution provided that the original author and
  source are credited.</license-p>
</license>
```
