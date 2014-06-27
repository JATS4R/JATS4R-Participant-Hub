# `<subj-group>` and `<kwd-group>`

Categories in an organised subject taxonomy, or free-text keywords.

## PeerJ

```xml
<!-- subjects from a fixed taxonomy -->
<article-categories>
  <subj-group subj-group-type="categories">
    <subject>Biochemistry</subject>
    <subject>Computational Biology</subject>
    <subject>Computational Science</subject>
  </subj-group>
</article-categories>

<!-- free text keywords entered by the author -->
<kwd-group kwd-group-type="author">
  <kwd>Computational chemistry</kwd>
  <kwd>Proteins</kwd>
  <kwd>Biochemistry</kwd>
  <kwd>Computational biochemistry</kwd>
  <kwd>Molecular modeling</kwd>
</kwd-group>
```

## eLife

```xml
<!-- subjects from a fixed taxonomy of approx 12. Major subject area. Paper can have 1 to 3 -->
<article-categories>
...
<subj-group subj-group-type="heading">
<subject>Cell biology</subject>
</subj-group>
<subj-group subj-group-type="heading">
<subject>Computer science</subject>
</subj-group>
</article-categories>

<!-- Article type -->
<article-categories>
<subj-group subj-group-type="display-channel">
<subject>Research article</subject>
</subj-group>
...
</article-categories>

<!-- free text keywords entered by the author and tidied up by vendor during production (capitalisation) -->
<kwd-group kwd-group-type="author-keywords">
<title>Author keywords</title>
<kwd>
<italic>Salpingoeca rosetta</italic>
</kwd>
<kwd>Algoriphagus</kwd>
<kwd>bacterial sulfonolipid</kwd>
<kwd>multicellular development</kwd>
</kwd-group>

<!-- Research organism - can contain "Other" which is suppressed on HW site but is in the xml and displayed elsewhwere, eg PMC-->
<kwd-group kwd-group-type="research-organism">
<title>Research organism</title>
<kwd>Mouse</kwd>
<kwd>
<italic>C. elegans</italic>
</kwd>
<kwd>Other</kwd>
</kwd-group>

