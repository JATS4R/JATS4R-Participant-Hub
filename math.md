# Math equations and formulas

Contained in the `<disp-formula>` and `<inline-formula>` elements.

Formulas and equations

## Tag Library

### &lt;tex-math> example

This example is from the Tag Library, [&lt;tex-math>](http://jatspan.org/niso/publishing-1.1d1/#p=elem-tex-math)
documentation, modified somewhat.

```xml
<disp-formula>
  <tex-math id="M1"><![CDATA[
    \documentclass[12pt]{minimal}

    \usepackage{amsmath}
    \usepackage{amsfonts}
    \usepackage{amssymb}
    \usepackage{amsbsy}
    \usepackage[mathscr]{eucal}
    \usepackage{mathrsfs}

    \begin{document}
      $$
        \mathrm{Acc/Acc: \hspace{.5em}}
        \frac{\mathit{ade2-202}}{\mathit{ADE2}} 
        \hspace{.5em}
        \frac{\mathit{ura3-59}}{\mathit{ura3-59}}
        \hspace{.5em}
        \frac{\mathit{MATa}}{\mathit{MAT{\alpha}}}
      $$
    \end{document}
  ]]></tex-math>
</disp-formula>
```

## PLOS

### Bad example - no math markup, only image

```xml
<disp-formula><graphic xlink:href="pone.0024306.e003"/><label>(3)</label></disp-formula>
```

## eLife

```xml
<disp-formula id="equ2">
  <label>(2)</label>
  <mml:math id="m2">
    <mml:mrow>
      <mml:mi>q</mml:mi>
      <mml:mo>&#x3d;</mml:mo>
      <mml:mfrac>
        <mml:mi>x</mml:mi>
        <mml:mrow>
          <mml:msub>
            <mml:mi>k</mml:mi>
            <mml:mi>d</mml:mi>
          </mml:msub>
          <mml:mo>&#x2b;</mml:mo>
          <mml:mi>x</mml:mi>
        </mml:mrow>
      </mml:mfrac>
      <mml:mo>,</mml:mo>
    </mml:mrow>
  </mml:math>
</disp-formula>

<inline-formula>
  <mml:math id="inf1">
    <mml:mrow>
      <mml:mi mathvariant="bold-italic">&#xa0;I</mml:mi>
      <mml:mrow>
        <mml:mo>(</mml:mo>
        <mml:mi mathvariant="bold-italic">t</mml:mi>
        <mml:mo>)</mml:mo>
      </mml:mrow>
      <mml:mo>&#x3d;</mml:mo>
      <mml:mi mathvariant="bold-italic">A</mml:mi>
      <mml:mo>(</mml:mo>
      <mml:mn mathvariant="bold">1</mml:mn>
      <mml:mo>&#x2212;</mml:mo>
      <mml:msup>
        <mml:mi mathvariant="bold-italic">e</mml:mi>
        <mml:mrow>
          <mml:mo>&#x2212;</mml:mo>
          <mml:mi mathvariant="bold-italic">&#x03C4;t</mml:mi>
        </mml:mrow>
      </mml:msup>
      <mml:mo>)</mml:mo>
    </mml:mrow>
  </mml:math>
</inline-formula>
```

## BIR

```xml
<disp-formula id="ueq1">
	<mml:math id="m1">
		<mml:mrow>
			<mml:mi mathvariant="italic">V</mml:mi>
			<mml:mrow>
				<mml:mo>(</mml:mo>
				<mml:mi mathvariant="italic">p</mml:mi>
				<mml:mo>)</mml:mo>
			</mml:mrow>
			<mml:mo>&#x3d;</mml:mo>
			<mml:mo>&#x2212;</mml:mo>
			<mml:mfrac>
				<mml:mrow>
					<mml:mn>2</mml:mn>
					<mml:mi>&#x3c0;</mml:mi>
					<mml:mi mathvariant="italic">A</mml:mi>
				</mml:mrow>
				<mml:mi mathvariant="italic">P</mml:mi>
			</mml:mfrac>
			<mml:mtext>sin</mml:mtext>
			<mml:mi mathvariant="italic">&#x2009;</mml:mi>
			<mml:mrow>
				<mml:mo>(</mml:mo>
				<mml:mrow>
					<mml:mfrac>
						<mml:mrow>
							<mml:mn>2</mml:mn>
							<mml:mi>&#x3c0;</mml:mi>
						</mml:mrow>
						<mml:mrow>
							<mml:mn>100</mml:mn>
						</mml:mrow>
					</mml:mfrac>
					<mml:mi>p</mml:mi>
				</mml:mrow>
				<mml:mo>)</mml:mo>
			</mml:mrow>
		</mml:mrow>
	</mml:math>
</disp-formula>

<inline-formula>
	<mml:math id="m5">
		<mml:mrow>
			<mml:msubsup>
				<mml:mi>T</mml:mi>
				<mml:mi mathvariant="italic">k</mml:mi>
				<mml:mrow>
					<mml:mo>&#x2212;</mml:mo>
					<mml:mn>1</mml:mn>
				</mml:mrow>
			</mml:msubsup>
		</mml:mrow>
	</mml:math>
</inline-formula>

