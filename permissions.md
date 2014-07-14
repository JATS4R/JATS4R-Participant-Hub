# `<permissions>`

Article permissions: copyright details, license URL, license text.

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





## Examples from PMC Content

```xml
    <!-- pretty basic -->
    <permissions>
        <license>
            <license-p>This is an Open Access article distributed under the terms of the Creative
                Commons Attribution License, (<ext-link ext-link-type="uri"
                    xlink:href="http://creativecommons.org/licenses/by/3.0/"
                    >http://creativecommons.org/licenses/by/3.0/</ext-link>) which permits
                unrestricted use, distribution, and reproduction in any medium, provided the
                original work is properly cited.</license-p>
        </license>
    </permissions>

    <!-- pretty basic just wrong (compare @xlink:href with contnet of ext-link and text)-->
    <permissions>
        <license>
            <license-p>This is an Open Access article distributed under the terms of the Creative
                Commons Attribution License, (<ext-link ext-link-type="uri"
                    xlink:href="http://creativecommons.org/licenses/by-nc-nd/3.0/"
                    >http://creativecommons.org/licenses/by/3.0/</ext-link>) which permits
                unrestricted use, distribution, and reproduction in any medium, provided the
                original work is properly cited.</license-p>
        </license>
    </permissions>

    <permissions>
        <copyright-statement>© Juan Valdez et al. This is an open-access article distributed under
            the terms of the Creative Commons Attribution License, which permits unrestricted use,
            distribution, and reproduction in any medium, provided the original author and source
            are properly cited. To view a copy of this license, visit <ext-link ext-link-type="uri"
                xlink:href="http://creativecommons.org/licenses/by/3.0/"
                >http://creativecommons.org/licenses/by/3.0/</ext-link></copyright-statement>
        <copyright-year>2013</copyright-year>
        <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/3.0">
            <p>This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike
                3.0 Unported License.</p>
        </license>
    </permissions>


    <!-- Entire licence paragraph tagged as an ext-link -->
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

    <permissions>
        <copyright-statement>Copyright © 2014 BleepBlip Society</copyright-statement>
        <copyright-year>2014</copyright-year>
        <copyright-holder>BleepBlip Society</copyright-holder>
        <license>
            <license-p>
                <ext-link xmlns:xlink="http://www.w3.org/1999/xlink" ext-link-type="uri"
                    xlink:href="http://bleepblip.org/authorchoice_termsofuse.html">Terms of
                    Use</ext-link>
            </license-p>
        </license>
    </permissions>

    <!-- URI on <license> -->
    <permissions>
        <license license-type="open-access"
            xlink:href="http://creativecommons.org/licenses/by-nc-nd/3.0/">
            <license-p>This is an open access article under the terms of the Creative Commons
                Attribution-NonCommercial-NoDerivs License, which permits use and distribution in
                any medium, provided the original work is properly cited, the use is non-commercial
                and no modifications or adaptations are made.</license-p>
        </license>
    </permissions>



    <!-- just a statement of when article becomes/became "Open Access" -->
    <permissions>
        <copyright-statement>Copyright © 2014 BleepBlip Society</copyright-statement>
        <copyright-year>2014</copyright-year>
        <copyright-holder>BleepBlip Society</copyright-holder>
        <license>
            <license-p>Open Access on 05/27/2015</license-p>
        </license>
    </permissions>


    <!-- with an inline image -->
    <permissions>
        <copyright-statement>© 2014 The authors</copyright-statement>
        <copyright-year>2014</copyright-year>
        <license license-type="license">
            <license-p>
                <inline-graphic xlink:href="88x31.png"/>This work is licensed under a <ext-link
                    ext-link-type="uri"
                    xlink:href="http://creativecommons.org/licenses/by/3.0/deed.en_GB">Creative
                    Commons Attribution-NonCommercial-NoDerivs 3.0 Unported
                License</ext-link>.</license-p>
        </license>
    </permissions>


    <!-- multiple copyright statements - multiple licenses -->
    <permissions>
        <copyright-statement content-type="issue-copyright">© 2014 Published by Orange Blossom
            Periodicals, Inc.</copyright-statement>
        <copyright-statement content-type="article-copyright">© 2014 The Authors. <italic>Am Example
                J.</italic> published by Orange Blossom Periodicals, Inc.</copyright-statement>
        <license license-type="creativeCommonsBy">
            <license-p>This is an open access article under the terms of the <ext-link
                    ext-link-type="uri" xlink:href="http://creativecommons.org/licenses/by/3.0/"
                    >Creative Commons Attribution</ext-link> License, which permits use,
                distribution and reproduction in any medium, provided the original work is properly
                cited.</license-p>
        </license>
        <license license-type="open-access">
            <license-p/>
        </license>
    </permissions>


    <!-- almost with a subtitle -->
    <permissions>
        <copyright-statement>© The Author(s) 2014</copyright-statement>
        <license license-type="OpenAccess">
            <license-p>
                <bold>Open Access</bold> This article is distributed under the terms of the Creative
                Commons Attribution License which permits any use, distribution, and reproduction in
                any medium, provided the original author(s) and the source are credited.</license-p>
        </license>
    </permissions>


    <!-- copyright clearance center -->
    <license license-type="ccc">
        <license-p>0148-0731/2014/136(08)/081004/7/<price>$0.00</price></license-p>
    </license>

    <!-- complicated -->
    <permissions>
        <copyright-statement>&#x00A9; 2014 Spinx <italic>et&#x00A0;al.</italic> This article is
            distributed by The American Society for Pugilistic Endeavors under license from the
            author(s). Two months after publication it is available to the public under an
            Attribution&#x2013;Noncommercial&#x2013;Share Alike 3.0 Unported Creative Commons
            License (<ext-link xmlns:xlink="http://www.w3.org/1999/xlink" ext-link-type="uri"
                xlink:href="http://creativecommons.org/licenses/by-nc-sa/3.0"
                >http://creativecommons.org/licenses/by-nc-sa/3.0</ext-link>).</copyright-statement>
        <copyright-year>2014</copyright-year>
        <license license-type="creative-commons">
            <license-p>&#x201C;ASPE&#x00AE;,&#x201D; &#x201C;The American Society for Pugilistic
                Endeavors&#x00AE;,&#x201D; and &#x201C;American Journal of Pugilism&#x00AE;&#x201D;
                are registered trademarks of The American Society of Cell Biology.</license-p>
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

###xml License with URI not in the license text.

```xml

<license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/3.0/">
  <license-p>This article is distributed under the terms of the Creative Commons Attribution License, 
  which permits unrestricted use and redistribution provided that the original author and 
  source are credited.</license-p>
</license>

```
