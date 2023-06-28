## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[11] NotoSansInscriptionalPahlavi-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** No dotted circle glyph presentand font uses a complex shaper [code: missing-dotted-circle-complex]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/inscriptional-pahlavi.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansInscriptionalPahlavi/googlefonts/ttf/NotoSansInscriptionalPahlavi-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/inscriptional-pahlavi.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐭡𐭤𐭡</span> (Added by SIESTA)</li>


<pre>Expected: u10B61=2+892|u10B64=1+859|u10B61.alt02=0@117,0+467</pre>



<pre>Got     : u10B61=2+892|u10B64=1+859|u10B61.alt02=0+350</pre>



<pre>                                                  ++++++ ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2101 2421" transform="matrix(1 0 0 -1 0 0)">
<path d="M15.0,-144.0L15.0,-70.0L718.0,-70.0L718.0,336.0L807.0,336.0L807.0,-144.0L15.0,-144.0Z" transform="translate(0, 852)"/>
<path d="M572.0,-10.0Q518.0,-10.0 486.0,4.0Q454.0,18.0 440.5,52.0Q427.0,86.0 427.0,146.0L427.0,440.0Q363.0,472.0 311.0,472.0Q232.0,472.0 190.5,427.5Q149.0,383.0 149.0,297.0Q149.0,250.0 160.0,197.5Q171.0,145.0 189.0,94.0Q207.0,43.0 229.0,0.0L139.0,0.0Q117.0,39.0 99.0,91.0Q81.0,143.0 70.5,197.5Q60.0,252.0 60.0,297.0Q60.0,374.0 89.5,429.5Q119.0,485.0 173.0,515.5Q227.0,546.0 299.0,546.0Q352.0,546.0 391.0,535.0Q430.0,524.0 462.0,507.5Q494.0,491.0 525.0,474.0Q556.0,457.0 592.0,446.0Q628.0,435.0 675.0,435.0Q710.0,435.0 730.0,455.5Q750.0,476.0 750.0,507.0Q750.0,524.0 746.0,536.0L835.0,536.0Q837.0,526.0 838.0,518.0Q839.0,510.0 839.0,505.0Q839.0,435.0 793.0,398.0Q747.0,361.0 673.0,361.0Q587.0,361.0 515.0,394.0L515.0,141.0Q515.0,97.0 526.0,80.5Q537.0,64.0 577.0,64.0Q600.0,64.0 625.5,66.5Q651.0,69.0 679.0,74.0L679.0,0.0Q650.0,-4.0 623.5,-7.0Q597.0,-10.0 572.0,-10.0Z" transform="translate(892, 852)"/>
<path d="M-527.0,-144.0L-527.0,-70.0L177.0,-70.0L177.0,336.0L265.0,336.0L265.0,-144.0L-527.0,-144.0Z" transform="translate(1751, 852)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2218 2421" transform="matrix(1 0 0 -1 0 0)">
<path d="M15.0,-144.0L15.0,-70.0L718.0,-70.0L718.0,336.0L807.0,336.0L807.0,-144.0L15.0,-144.0Z" transform="translate(0, 852)"/>
<path d="M572.0,-10.0Q518.0,-10.0 486.0,4.0Q454.0,18.0 440.5,52.0Q427.0,86.0 427.0,146.0L427.0,440.0Q363.0,472.0 311.0,472.0Q232.0,472.0 190.5,427.5Q149.0,383.0 149.0,297.0Q149.0,250.0 160.0,197.5Q171.0,145.0 189.0,94.0Q207.0,43.0 229.0,0.0L139.0,0.0Q117.0,39.0 99.0,91.0Q81.0,143.0 70.5,197.5Q60.0,252.0 60.0,297.0Q60.0,374.0 89.5,429.5Q119.0,485.0 173.0,515.5Q227.0,546.0 299.0,546.0Q352.0,546.0 391.0,535.0Q430.0,524.0 462.0,507.5Q494.0,491.0 525.0,474.0Q556.0,457.0 592.0,446.0Q628.0,435.0 675.0,435.0Q710.0,435.0 730.0,455.5Q750.0,476.0 750.0,507.0Q750.0,524.0 746.0,536.0L835.0,536.0Q837.0,526.0 838.0,518.0Q839.0,510.0 839.0,505.0Q839.0,435.0 793.0,398.0Q747.0,361.0 673.0,361.0Q587.0,361.0 515.0,394.0L515.0,141.0Q515.0,97.0 526.0,80.5Q537.0,64.0 577.0,64.0Q600.0,64.0 625.5,66.5Q651.0,69.0 679.0,74.0L679.0,0.0Q650.0,-4.0 623.5,-7.0Q597.0,-10.0 572.0,-10.0Z" transform="translate(892, 852)"/>
<path d="M-527.0,-144.0L-527.0,-70.0L177.0,-70.0L177.0,336.0L265.0,336.0L265.0,-144.0L-527.0,-144.0Z" transform="translate(1868, 852)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Inscriptional Pahlavi' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* dollar (U+0024): X=253.0,Y=759.0 (should be at cap-height 760?)

	* dollar (U+0024): X=317.0,Y=759.0 (should be at cap-height 760?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?) 

	* 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 4 | 7 | 117 | 7 | 111 | 0 |
| 0% | 2% | 3% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
