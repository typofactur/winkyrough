## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[12] WinkyRough-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* dcroat (U+0111): L&lt;&lt;456.0,558.0&gt;--&lt;448.0,559.0&gt;&gt;/L&lt;&lt;448.0,559.0&gt;--&lt;448.0,559.0&gt;&gt; = 7.125016348901757
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* f_f.BRACKET.varAlt01: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt01: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt02: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt02: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt01: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt01: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt02: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt02: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_j.BRACKET.varAlt01: L&lt;&lt;625.0,0.0&gt;--&lt;624.0,500.0&gt;&gt;

* f_f_j.BRACKET.varAlt02: L&lt;&lt;625.0,0.0&gt;--&lt;624.0,500.0&gt;&gt;

* f_j.BRACKET.varAlt01: L&lt;&lt;355.0,0.0&gt;--&lt;354.0,500.0&gt;&gt;

* f_j.BRACKET.varAlt02: L&lt;&lt;355.0,0.0&gt;--&lt;354.0,500.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[12] WinkyRough-SemiBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 584:
plusminus, greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* f_l (U+FB02): L&lt;&lt;344.0,655.0&gt;--&lt;344.0,654.0&gt;&gt;/L&lt;&lt;344.0,654.0&gt;--&lt;346.0,665.0&gt;&gt; = 10.304846468766009

* f_l.BRACKET.varAlt01: L&lt;&lt;344.0,655.0&gt;--&lt;344.0,654.0&gt;&gt;/L&lt;&lt;344.0,654.0&gt;--&lt;346.0,665.0&gt;&gt; = 10.304846468766009

* f_l.BRACKET.varAlt02: L&lt;&lt;344.0,655.0&gt;--&lt;344.0,654.0&gt;&gt;/L&lt;&lt;344.0,654.0&gt;--&lt;346.0,665.0&gt;&gt; = 10.304846468766009

* registered (U+00AE): L&lt;&lt;235.0,541.0&gt;--&lt;220.0,540.0&gt;&gt;/L&lt;&lt;220.0,540.0&gt;--&lt;246.0,539.0&gt;&gt; = 6.016672996056167
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[12] WinkyRough-Medium.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 592:
plusminus, greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Euro (U+20AC): L&lt;&lt;238.0,235.0&gt;--&lt;230.0,236.0&gt;&gt;/L&lt;&lt;230.0,236.0&gt;--&lt;230.0,236.0&gt;&gt; = 7.125016348901757

* W (U+0057): L&lt;&lt;532.0,180.0&gt;--&lt;538.0,166.0&gt;&gt;/L&lt;&lt;538.0,166.0&gt;--&lt;534.0,181.0&gt;&gt; = 8.267173335510634

* Wacute (U+1E82): L&lt;&lt;532.0,180.0&gt;--&lt;538.0,166.0&gt;&gt;/L&lt;&lt;538.0,166.0&gt;--&lt;534.0,181.0&gt;&gt; = 8.267173335510634

* Wcircumflex (U+0174): L&lt;&lt;532.0,180.0&gt;--&lt;538.0,166.0&gt;&gt;/L&lt;&lt;538.0,166.0&gt;--&lt;534.0,181.0&gt;&gt; = 8.267173335510634

* Wdieresis (U+1E84): L&lt;&lt;532.0,180.0&gt;--&lt;538.0,166.0&gt;&gt;/L&lt;&lt;538.0,166.0&gt;--&lt;534.0,181.0&gt;&gt; = 8.267173335510634

* Wgrave (U+1E80): L&lt;&lt;532.0,180.0&gt;--&lt;538.0,166.0&gt;&gt;/L&lt;&lt;538.0,166.0&gt;--&lt;534.0,181.0&gt;&gt; = 8.267173335510634

* numbersign (U+0023): L&lt;&lt;420.0,15.0&gt;--&lt;399.0,0.0&gt;&gt;/L&lt;&lt;399.0,0.0&gt;--&lt;400.0,1.0&gt;&gt; = 9.462322208025574

* ogonek (U+02DB): L&lt;&lt;429.0,-1.0&gt;--&lt;443.0,1.0&gt;&gt;/L&lt;&lt;443.0,1.0&gt;--&lt;431.0,-3.0&gt;&gt; = 10.304846468766044

* onequarter (U+00BC): L&lt;&lt;538.0,267.0&gt;--&lt;541.0,269.0&gt;&gt;/L&lt;&lt;541.0,269.0&gt;--&lt;524.0,263.0&gt;&gt; = 14.250032697803595

* registered (U+00AE): L&lt;&lt;247.0,535.0&gt;--&lt;242.0,536.0&gt;&gt;/L&lt;&lt;242.0,536.0&gt;--&lt;260.0,529.0&gt;&gt; = 9.940573033113024
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[11] WinkyRough-ExtraBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 568:
plusminus, greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[11] WinkyRough-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 576:
plusminus, greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[13] WinkyRough-Black.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 560:
plusminus, greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;275.0,509.0&gt;--&lt;275.0,509.0&gt;&gt;/L&lt;&lt;275.0,509.0&gt;--&lt;268.0,510.0&gt;&gt; = 8.13010235415596

* lslash (U+0142): L&lt;&lt;54.0,191.0&gt;--&lt;54.0,191.0&gt;&gt;/L&lt;&lt;54.0,191.0&gt;--&lt;28.0,196.0&gt;&gt; = 10.88552705465871

* uni006A0301: L&lt;&lt;138.0,773.0&gt;--&lt;132.0,771.0&gt;&gt;/L&lt;&lt;132.0,771.0&gt;--&lt;140.0,773.0&gt;&gt; = 4.398705354995591
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* f_f (U+FB00): L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f (U+FB00): L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt02: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt02: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_i (U+FB03): L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f_i (U+FB03): L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt02: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt02: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_j.BRACKET.varAlt02: L&lt;&lt;625.0,0.0&gt;--&lt;624.0,500.0&gt;&gt;

* f_f_j: L&lt;&lt;625.0,0.0&gt;--&lt;624.0,500.0&gt;&gt;

* f_j.BRACKET.varAlt01: L&lt;&lt;355.0,0.0&gt;--&lt;354.0,500.0&gt;&gt;

* f_j: L&lt;&lt;355.0,0.0&gt;--&lt;354.0,500.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[13] WinkyRough-Light.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 560:
plusminus, greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove

- f_f.BRACKET.varAlt01

- f_f.BRACKET.varAlt02

- f_f_i.BRACKET.varAlt01

- f_f_i.BRACKET.varAlt02

- f_f_j.BRACKET.varAlt01

- f_f_j.BRACKET.varAlt02

- f_f_l.BRACKET.varAlt01

- f_f_l.BRACKET.varAlt02

- f_i.BRACKET.varAlt01

- f_i.BRACKET.varAlt02

- f_j.BRACKET.varAlt01

- f_j.BRACKET.varAlt02

- f_l.BRACKET.varAlt01

- f_l.BRACKET.varAlt02
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, hebrew, math, tai-le, tifinagh, duployan, old-permic, coptic, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, hatran, syriac, oriya, khmer, kayah-li, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: old-hungarian, rejang, yi, hebrew, takri, newa, bengali, grantha, gujarati, myanmar, tifinagh, modi, duployan, avestan, mongolian, phags-pa, warang-citi, masaram-gondi, tai-tham, thaana, psalter-pahlavi, sinhala, chakma, kaithi, manichaean, tai-viet, saurashtra, new-tai-lue, arabic, buhid, lao, sharada, khojki, nko, tibetan, khudawadi, hanunoo, buginese, gurmukhi, kannada, dogra, cham, pahawh-hmong, lepcha, bhaiksuki, sundanese, tagalog, zanabazar-square, siddham, gunjala-gondi, tamil, thai, telugu, javanese, tirhuta, balinese, syloti-nagri, mahajani, hanifi-rohingya, malayalam, limbu, tai-le, mandaic, brahmi, meetei-mayek, sogdian, batak, devanagari, kharoshthi, syriac, tagbanwa, oriya, khmer, kayah-li</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, arabic, nko, phags-pa, syriac, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, nko, phags-pa, syriac, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, nushu, japanese, chinese-simplified, chinese-traditional, chinese-hongkong, phags-pa</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Han (Latn, 6 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Zapotec (Latn, 490,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* braceleft (U+007B): L&lt;&lt;172.0,341.0&gt;--&lt;140.0,336.0&gt;&gt;/L&lt;&lt;140.0,336.0&gt;--&lt;166.0,336.0&gt;&gt; = 8.880659150520234

* braceright (U+007D): L&lt;&lt;241.0,336.0&gt;--&lt;267.0,336.0&gt;&gt;/L&lt;&lt;267.0,336.0&gt;--&lt;235.0,341.0&gt;&gt; = 8.880659150520234
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* f_f.BRACKET.varAlt01: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt01: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt02: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f.BRACKET.varAlt02: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt01: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt01: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt02: L&lt;&lt;175.0,430.0&gt;--&lt;176.0,0.0&gt;&gt;

* f_f_i.BRACKET.varAlt02: L&lt;&lt;445.0,430.0&gt;--&lt;446.0,0.0&gt;&gt;

* f_f_j.BRACKET.varAlt01: L&lt;&lt;625.0,0.0&gt;--&lt;624.0,500.0&gt;&gt;

* f_f_j.BRACKET.varAlt02: L&lt;&lt;625.0,0.0&gt;--&lt;624.0,500.0&gt;&gt;

* f_j.BRACKET.varAlt01: L&lt;&lt;355.0,0.0&gt;--&lt;354.0,500.0&gt;&gt;

* f_j.BRACKET.varAlt02: L&lt;&lt;355.0,0.0&gt;--&lt;354.0,500.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 7 | 77 | 794 | 43 | 728 | 0 | 
| 0% | 0% | 0% | 5% | 48% | 3% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
