## FontBakery report

fontbakery version: 0.13.1







## Check results



<details><summary>[8] WinkyRough-BoldItalic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Winky Rough Bold</strong></td>
<td align="left"><strong>Winky Rough</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Bold Italic</td>
<td align="left">Bold Italic</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Winky Rough Bold Italic</td>
<td align="left">Winky Rough Bold Italic</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">WinkyRough-BoldItalic</td>
<td align="left">WinkyRough-BoldItalic</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Winky Rough</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Bold Italic</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Euro (U+20AC): L&lt;&lt;242.0,227.0&gt;--&lt;229.0,228.0&gt;&gt;/L&lt;&lt;229.0,228.0&gt;--&lt;229.0,228.0&gt;&gt; = 4.398705354995508

* Hbar (U+0126): L&lt;&lt;288.0,481.0&gt;--&lt;272.0,477.0&gt;&gt;/L&lt;&lt;272.0,477.0&gt;--&lt;272.0,477.0&gt;&gt; = 14.036243467926484

* quotedblright (U+201D): L&lt;&lt;84.0,669.0&gt;--&lt;82.0,656.0&gt;&gt;/L&lt;&lt;82.0,656.0&gt;--&lt;88.0,673.0&gt;&gt; = 10.69387256562099

* quotedblright (U+201D): L&lt;&lt;87.0,624.0&gt;--&lt;83.0,636.0&gt;&gt;/L&lt;&lt;83.0,636.0&gt;--&lt;85.0,622.0&gt;&gt; = 10.304846468766044

* uni0E3F (U+0E3F): L&lt;&lt;334.0,-4.0&gt;--&lt;322.0,-5.0&gt;&gt;/L&lt;&lt;322.0,-5.0&gt;--&lt;322.0,-5.0&gt;&gt; = 4.763641690726143

* yen (U+00A5): L&lt;&lt;353.0,256.0&gt;--&lt;332.0,255.0&gt;&gt;/L&lt;&lt;332.0,255.0&gt;--&lt;332.0,255.0&gt;&gt; = 2.726310993906212
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-BlackItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;304.0,509.0&gt;--&lt;304.0,509.0&gt;&gt;/L&lt;&lt;304.0,509.0&gt;--&lt;296.0,510.0&gt;&gt; = 7.125016348901757

* Oslash (U+00D8): L&lt;&lt;383.0,349.0&gt;--&lt;382.0,357.0&gt;&gt;/L&lt;&lt;382.0,357.0&gt;--&lt;382.0,356.0&gt;&gt; = 7.125016348901757
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[8] WinkyRough-RegularItalic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Winky Rough Regular</strong></td>
<td align="left"><strong>Winky Rough</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Italic</td>
<td align="left">Italic</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left"><strong>Winky Rough Regular Italic</strong></td>
<td align="left"><strong>Winky Rough Italic</strong></td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>WinkyRough-RegularItalic</strong></td>
<td align="left"><strong>WinkyRough-Italic</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Winky Rough</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Regular Italic</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Aogonek (U+0104): L&lt;&lt;422.0,11.0&gt;--&lt;445.0,10.0&gt;&gt;/L&lt;&lt;445.0,10.0&gt;--&lt;443.0,10.0&gt;&gt; = 2.4895529219991284

* Eogonek (U+0118): L&lt;&lt;395.0,11.0&gt;--&lt;418.0,10.0&gt;&gt;/L&lt;&lt;418.0,10.0&gt;--&lt;416.0,10.0&gt;&gt; = 2.4895529219991284

* Iogonek (U+012E): L&lt;&lt;186.0,11.0&gt;--&lt;209.0,10.0&gt;&gt;/L&lt;&lt;209.0,10.0&gt;--&lt;207.0,10.0&gt;&gt; = 2.4895529219991284

* Uogonek (U+0172): L&lt;&lt;295.0,11.0&gt;--&lt;318.0,10.0&gt;&gt;/L&lt;&lt;318.0,10.0&gt;--&lt;316.0,10.0&gt;&gt; = 2.4895529219991284

* aogonek (U+0105): L&lt;&lt;381.0,21.0&gt;--&lt;404.0,20.0&gt;&gt;/L&lt;&lt;404.0,20.0&gt;--&lt;402.0,20.0&gt;&gt; = 2.4895529219991284

* eogonek (U+0119): L&lt;&lt;331.0,20.0&gt;--&lt;354.0,19.0&gt;&gt;/L&lt;&lt;354.0,19.0&gt;--&lt;352.0,19.0&gt;&gt; = 2.4895529219991284

* iogonek (U+012F): L&lt;&lt;87.0,1.0&gt;--&lt;110.0,0.0&gt;&gt;/L&lt;&lt;110.0,0.0&gt;--&lt;108.0,0.0&gt;&gt; = 2.4895529219991284

* notequal (U+2260): L&lt;&lt;372.0,289.0&gt;--&lt;360.0,292.0&gt;&gt;/L&lt;&lt;360.0,292.0&gt;--&lt;360.0,292.0&gt;&gt; = 14.036243467926484

* ogonek (U+02DB): L&lt;&lt;432.0,1.0&gt;--&lt;455.0,0.0&gt;&gt;/L&lt;&lt;455.0,0.0&gt;--&lt;453.0,0.0&gt;&gt; = 2.4895529219991284

* threequarters (U+00BE): L&lt;&lt;280.0,361.0&gt;--&lt;280.0,365.0&gt;&gt;/L&lt;&lt;280.0,365.0&gt;--&lt;278.0,357.0&gt;&gt; = 14.036243467926484

* threequarters (U+00BE): L&lt;&lt;280.0,365.0&gt;--&lt;278.0,357.0&gt;&gt;/L&lt;&lt;278.0,357.0&gt;--&lt;280.0,361.0&gt;&gt; = 12.528807709151522

* uni0328 (U+0328): L&lt;&lt;432.0,1.0&gt;--&lt;455.0,0.0&gt;&gt;/L&lt;&lt;455.0,0.0&gt;--&lt;453.0,0.0&gt;&gt; = 2.4895529219991284

* uogonek (U+0173): L&lt;&lt;410.0,11.0&gt;--&lt;433.0,10.0&gt;&gt;/L&lt;&lt;433.0,10.0&gt;--&lt;431.0,10.0&gt;&gt; = 2.4895529219991284
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Aogonek (U+0104): L&lt;&lt;474.0,11.0&gt;--&lt;497.0,10.0&gt;&gt;/L&lt;&lt;497.0,10.0&gt;--&lt;495.0,10.0&gt;&gt; = 2.4895529219991284

* Eogonek (U+0118): L&lt;&lt;420.0,11.0&gt;--&lt;443.0,10.0&gt;&gt;/L&lt;&lt;443.0,10.0&gt;--&lt;441.0,10.0&gt;&gt; = 2.4895529219991284

* Iogonek (U+012E): L&lt;&lt;236.0,11.0&gt;--&lt;259.0,10.0&gt;&gt;/L&lt;&lt;259.0,10.0&gt;--&lt;257.0,10.0&gt;&gt; = 2.4895529219991284

* Uogonek (U+0172): L&lt;&lt;346.0,11.0&gt;--&lt;369.0,10.0&gt;&gt;/L&lt;&lt;369.0,10.0&gt;--&lt;367.0,10.0&gt;&gt; = 2.4895529219991284

* aogonek (U+0105): L&lt;&lt;424.0,21.0&gt;--&lt;447.0,20.0&gt;&gt;/L&lt;&lt;447.0,20.0&gt;--&lt;445.0,20.0&gt;&gt; = 2.4895529219991284

* eogonek (U+0119): L&lt;&lt;374.0,20.0&gt;--&lt;397.0,19.0&gt;&gt;/L&lt;&lt;397.0,19.0&gt;--&lt;395.0,19.0&gt;&gt; = 2.4895529219991284

* iogonek (U+012F): L&lt;&lt;152.0,1.0&gt;--&lt;175.0,0.0&gt;&gt;/L&lt;&lt;175.0,0.0&gt;--&lt;173.0,0.0&gt;&gt; = 2.4895529219991284

* ogonek (U+02DB): L&lt;&lt;419.0,1.0&gt;--&lt;442.0,0.0&gt;&gt;/L&lt;&lt;442.0,0.0&gt;--&lt;440.0,0.0&gt;&gt; = 2.4895529219991284

* uni0328 (U+0328): L&lt;&lt;419.0,1.0&gt;--&lt;442.0,0.0&gt;&gt;/L&lt;&lt;442.0,0.0&gt;--&lt;440.0,0.0&gt;&gt; = 2.4895529219991284

* uogonek (U+0173): L&lt;&lt;455.0,11.0&gt;--&lt;478.0,10.0&gt;&gt;/L&lt;&lt;478.0,10.0&gt;--&lt;476.0,10.0&gt;&gt; = 2.4895529219991284
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-SemiBoldItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Dcroat (U+0110): L&lt;&lt;201.0,285.0&gt;--&lt;177.0,283.0&gt;&gt;/L&lt;&lt;177.0,283.0&gt;--&lt;177.0,283.0&gt;&gt; = 4.763641690726143

* Eth (U+00D0): L&lt;&lt;201.0,285.0&gt;--&lt;177.0,283.0&gt;&gt;/L&lt;&lt;177.0,283.0&gt;--&lt;177.0,283.0&gt;&gt; = 4.763641690726143

* Euro (U+20AC): L&lt;&lt;99.0,421.0&gt;--&lt;85.0,424.0&gt;&gt;/L&lt;&lt;85.0,424.0&gt;--&lt;100.0,424.0&gt;&gt; = 12.094757077012089

* Hbar (U+0126): L&lt;&lt;457.0,484.0&gt;--&lt;457.0,484.0&gt;&gt;/L&lt;&lt;457.0,484.0&gt;--&lt;445.0,483.0&gt;&gt; = 4.763641690726143
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-SemiBold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Euro (U+20AC): L&lt;&lt;83.0,421.0&gt;--&lt;68.0,424.0&gt;&gt;/L&lt;&lt;68.0,424.0&gt;--&lt;84.0,424.0&gt;&gt; = 11.309932474020195

* Oslash (U+00D8): L&lt;&lt;206.0,-7.0&gt;--&lt;195.0,-8.0&gt;&gt;/L&lt;&lt;195.0,-8.0&gt;--&lt;195.0,-8.0&gt;&gt; = 5.1944289077348

* dcroat (U+0111): L&lt;&lt;467.0,659.0&gt;--&lt;466.0,659.0&gt;&gt;/L&lt;&lt;466.0,659.0&gt;--&lt;479.0,661.0&gt;&gt; = 8.746162262555211

* lslash (U+0142): L&lt;&lt;275.0,485.0&gt;--&lt;271.0,479.0&gt;&gt;/L&lt;&lt;271.0,479.0&gt;--&lt;272.0,480.0&gt;&gt; = 11.309932474020227

* yen (U+00A5): L&lt;&lt;190.0,122.0&gt;--&lt;190.0,122.0&gt;&gt;/L&lt;&lt;190.0,122.0&gt;--&lt;170.0,120.0&gt;&gt; = 5.710593137499633
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[6] WinkyRough-Medium.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-ExtraBoldItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;323.0,524.0&gt;--&lt;323.0,524.0&gt;&gt;/L&lt;&lt;323.0,524.0&gt;--&lt;306.0,526.0&gt;&gt; = 6.709836807756896

* less (U+003C): L&lt;&lt;281.0,278.0&gt;--&lt;266.0,271.0&gt;&gt;/L&lt;&lt;266.0,271.0&gt;--&lt;269.0,273.0&gt;&gt; = 8.673174047879764
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-MediumItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Hbar (U+0126): L&lt;&lt;458.0,482.0&gt;--&lt;458.0,482.0&gt;&gt;/L&lt;&lt;458.0,482.0&gt;--&lt;447.0,484.0&gt;&gt; = 10.304846468766044

* onehalf (U+00BD): L&lt;&lt;283.0,362.0&gt;--&lt;274.0,344.0&gt;&gt;/L&lt;&lt;274.0,344.0&gt;--&lt;283.0,357.0&gt;&gt; = 8.13010235415596

* oslash (U+00F8): L&lt;&lt;479.0,397.0&gt;--&lt;467.0,394.0&gt;&gt;/L&lt;&lt;467.0,394.0&gt;--&lt;467.0,394.0&gt;&gt; = 14.036243467926484
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-LightItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* OE (U+0152): L&lt;&lt;466.0,601.0&gt;--&lt;464.0,590.0&gt;&gt;/L&lt;&lt;464.0,590.0&gt;--&lt;472.0,609.0&gt;&gt; = 12.528807709151522

* braceleft (U+007B): L&lt;&lt;183.0,341.0&gt;--&lt;150.0,336.0&gt;&gt;/L&lt;&lt;150.0,336.0&gt;--&lt;176.0,336.0&gt;&gt; = 8.615648184164108

* braceright (U+007D): L&lt;&lt;151.0,336.0&gt;--&lt;177.0,336.0&gt;&gt;/L&lt;&lt;177.0,336.0&gt;--&lt;144.0,341.0&gt;&gt; = 8.615648184164108

* dollar (U+0024): L&lt;&lt;119.0,-8.0&gt;--&lt;119.0,-8.0&gt;&gt;/L&lt;&lt;119.0,-8.0&gt;--&lt;100.0,-4.0&gt;&gt; = 11.888658039627968

* dollar (U+0024): L&lt;&lt;215.0,-1.0&gt;--&lt;194.0,-5.0&gt;&gt;/L&lt;&lt;194.0,-5.0&gt;--&lt;194.0,-5.0&gt;&gt; = 10.784297867562561
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[6] WinkyRough-ExtraBold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-Bold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Dcroat (U+0110): L&lt;&lt;216.0,271.0&gt;--&lt;210.0,272.0&gt;&gt;/L&lt;&lt;210.0,272.0&gt;--&lt;210.0,272.0&gt;&gt; = 9.462322208025613

* Eth (U+00D0): L&lt;&lt;216.0,271.0&gt;--&lt;210.0,272.0&gt;&gt;/L&lt;&lt;210.0,272.0&gt;--&lt;210.0,272.0&gt;&gt; = 9.462322208025613

* quotedblright (U+201D): L&lt;&lt;217.0,669.0&gt;--&lt;216.0,655.0&gt;&gt;/L&lt;&lt;216.0,655.0&gt;--&lt;220.0,673.0&gt;&gt; = 8.443190929176685

* quotedblright (U+201D): L&lt;&lt;227.0,624.0&gt;--&lt;220.0,639.0&gt;&gt;/L&lt;&lt;220.0,639.0&gt;--&lt;226.0,622.0&gt;&gt; = 5.576858649923835
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-Black.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;275.0,509.0&gt;--&lt;275.0,509.0&gt;&gt;/L&lt;&lt;275.0,509.0&gt;--&lt;268.0,510.0&gt;&gt; = 8.13010235415596

* Oslash (U+00D8): L&lt;&lt;380.0,349.0&gt;--&lt;378.0,358.0&gt;&gt;/L&lt;&lt;378.0,358.0&gt;--&lt;378.0,356.0&gt;&gt; = 12.528807709151492

* ae (U+00E6): L&lt;&lt;279.0,198.0&gt;--&lt;279.0,198.0&gt;&gt;/L&lt;&lt;279.0,198.0&gt;--&lt;274.0,197.0&gt;&gt; = 11.309932474020195
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] WinkyRough-Light.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, todhri, old-permic, malayalam, syriac, tifinagh, canadian-aboriginal, hebrew, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, hatran, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, tagalog, tai-viet, warang-citi, khmer, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tibetan, sharada, javanese, nko, sundanese, phags-pa, arabic, mahajani, masaram-gondi, new-tai-lue, sogdian, tai-le, thai, dogra, sinhala, buhid, brahmi, kharoshthi, khudawadi, tirhuta, buginese, lao, mongolian, bhaiksuki, hanifi-rohingya, devanagari, hanunoo, balinese, grantha, myanmar, old-hungarian, tagalog, tai-viet, khmer, warang-citi, hebrew, thaana, zanabazar-square, mandaic, cham, saurashtra, takri, syloti-nagri, kayah-li, kannada, malayalam, tifinagh, avestan, manichaean, chakma, batak, limbu, oriya, rejang, gunjala-gondi, duployan, gujarati, tamil, siddham, tai-tham, telugu, yi, pahawh-hmong, lepcha, modi, tagbanwa, meetei-mayek, psalter-pahlavi, syriac, gurmukhi, kaithi, newa, khojki, bengali</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, phags-pa, arabic, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, elbasan, buginese, tagalog, zanabazar-square, music, syloti-nagri, kannada, batak, marchen, gunjala-gondi, math, gujarati, symbols, pahawh-hmong, psalter-pahlavi, gurmukhi, lepcha, newa, lao, caucasian-albanian, bassa-vah, mahajani, new-tai-lue, dogra, hanifi-rohingya, tai-viet, myanmar, warang-citi, khmer, mandaic, saurashtra, old-permic, ahom, kayah-li, tifinagh, soyombo, canadian-aboriginal, chakma, oriya, duployan, siddham, telugu, adlam, modi, sogdian, tibetan, sharada, nko, sundanese, phags-pa, masaram-gondi, thai, sinhala, tirhuta, brahmi, kharoshthi, mongolian, bhaiksuki, hanunoo, balinese, grantha, cham, malayalam, mende-kikakui, manichaean, tamil, miao, tai-tham, tagbanwa, kaithi, khojki, bengali, tai-le, osage, buhid, khudawadi, yi, devanagari, hebrew, thaana, wancho, takri, limbu, rejang, armenian, meetei-mayek, syriac, coptic</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, nushu, phags-pa, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Ikwere (Latn, 717,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Longto (Latn, 5,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Northern Tutchone (Latn, 85 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Abua (Latn, 25,000 speakers), Keliko (Latn, 63,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* OE (U+0152): L&lt;&lt;429.0,584.0&gt;--&lt;426.0,586.0&gt;&gt;/L&lt;&lt;426.0,586.0&gt;--&lt;429.0,583.0&gt;&gt; = 11.309932474020227

* braceleft (U+007B): L&lt;&lt;169.0,341.0&gt;--&lt;137.0,336.0&gt;&gt;/L&lt;&lt;137.0,336.0&gt;--&lt;163.0,336.0&gt;&gt; = 8.880659150520234

* braceright (U+007D): L&lt;&lt;244.0,336.0&gt;--&lt;270.0,336.0&gt;&gt;/L&lt;&lt;270.0,336.0&gt;--&lt;238.0,341.0&gt;&gt; = 8.880659150520234

* lslash (U+0142): L&lt;&lt;175.0,446.0&gt;--&lt;175.0,438.0&gt;&gt;/L&lt;&lt;175.0,438.0&gt;--&lt;176.0,443.0&gt;&gt; = 11.309932474020195
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
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
| 0 | 0 | 2 | 96 | 1466 | 71 | 1448 | 0 | 
| 0% | 0% | 0% | 3% | 48% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
