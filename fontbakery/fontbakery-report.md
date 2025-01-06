## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[6] WinkyRough-BoldItalic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



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

<details><summary>[6] WinkyRough-BlackItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;304.0,509.0&gt;--&lt;304.0,509.0&gt;&gt;/L&lt;&lt;304.0,509.0&gt;--&lt;297.0,510.0&gt;&gt; = 8.13010235415596
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-Regular.ttf</summary>
<div>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Aogonek (U+0104): L&lt;&lt;474.0,11.0&gt;--&lt;497.0,10.0&gt;&gt;/L&lt;&lt;497.0,10.0&gt;--&lt;495.0,10.0&gt;&gt; = 2.4895529219991284

* Eogonek (U+0118): L&lt;&lt;420.0,11.0&gt;--&lt;443.0,10.0&gt;&gt;/L&lt;&lt;443.0,10.0&gt;--&lt;441.0,10.0&gt;&gt; = 2.4895529219991284

* Iogonek (U+012E): L&lt;&lt;236.0,11.0&gt;--&lt;259.0,10.0&gt;&gt;/L&lt;&lt;259.0,10.0&gt;--&lt;257.0,10.0&gt;&gt; = 2.4895529219991284

* Uogonek (U+0172): L&lt;&lt;346.0,11.0&gt;--&lt;369.0,10.0&gt;&gt;/L&lt;&lt;369.0,10.0&gt;--&lt;367.0,10.0&gt;&gt; = 2.4895529219991284

* aogonek (U+0105): L&lt;&lt;424.0,21.0&gt;--&lt;447.0,20.0&gt;&gt;/L&lt;&lt;447.0,20.0&gt;--&lt;445.0,20.0&gt;&gt; = 2.4895529219991284

* dcroat (U+0111): L&lt;&lt;456.0,558.0&gt;--&lt;447.0,559.0&gt;&gt;/L&lt;&lt;447.0,559.0&gt;--&lt;447.0,559.0&gt;&gt; = 6.340191745909908

* eogonek (U+0119): L&lt;&lt;374.0,20.0&gt;--&lt;397.0,19.0&gt;&gt;/L&lt;&lt;397.0,19.0&gt;--&lt;395.0,19.0&gt;&gt; = 2.4895529219991284

* iogonek (U+012F): L&lt;&lt;152.0,1.0&gt;--&lt;175.0,0.0&gt;&gt;/L&lt;&lt;175.0,0.0&gt;--&lt;173.0,0.0&gt;&gt; = 2.4895529219991284

* uni0328 (U+0328): L&lt;&lt;419.0,1.0&gt;--&lt;442.0,0.0&gt;&gt;/L&lt;&lt;442.0,0.0&gt;--&lt;440.0,0.0&gt;&gt; = 2.4895529219991284

* uogonek (U+0173): L&lt;&lt;455.0,11.0&gt;--&lt;478.0,10.0&gt;&gt;/L&lt;&lt;478.0,10.0&gt;--&lt;476.0,10.0&gt;&gt; = 2.4895529219991284
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-SemiBoldItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* registered (U+00AE): L&lt;&lt;277.0,541.0&gt;--&lt;262.0,540.0&gt;&gt;/L&lt;&lt;262.0,540.0&gt;--&lt;287.0,539.0&gt;&gt; = 6.104684876928853

* uni0E3F (U+0E3F): L&lt;&lt;176.0,-9.0&gt;--&lt;176.0,-9.0&gt;&gt;/L&lt;&lt;176.0,-9.0&gt;--&lt;162.0,-8.0&gt;&gt; = 4.085616779974888
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-SemiBold.ttf</summary>
<div>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* registered (U+00AE): L&lt;&lt;230.0,541.0&gt;--&lt;215.0,540.0&gt;&gt;/L&lt;&lt;215.0,540.0&gt;--&lt;241.0,539.0&gt;&gt; = 6.016672996056167
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-Medium.ttf</summary>
<div>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): L&lt;&lt;542.0,180.0&gt;--&lt;548.0,166.0&gt;&gt;/L&lt;&lt;548.0,166.0&gt;--&lt;544.0,181.0&gt;&gt; = 8.267173335510634

* Wacute (U+1E82): L&lt;&lt;542.0,180.0&gt;--&lt;548.0,166.0&gt;&gt;/L&lt;&lt;548.0,166.0&gt;--&lt;544.0,181.0&gt;&gt; = 8.267173335510634

* Wcircumflex (U+0174): L&lt;&lt;542.0,180.0&gt;--&lt;548.0,166.0&gt;&gt;/L&lt;&lt;548.0,166.0&gt;--&lt;544.0,181.0&gt;&gt; = 8.267173335510634

* Wdieresis (U+1E84): L&lt;&lt;542.0,180.0&gt;--&lt;548.0,166.0&gt;&gt;/L&lt;&lt;548.0,166.0&gt;--&lt;544.0,181.0&gt;&gt; = 8.267173335510634

* Wgrave (U+1E80): L&lt;&lt;542.0,180.0&gt;--&lt;548.0,166.0&gt;&gt;/L&lt;&lt;548.0,166.0&gt;--&lt;544.0,181.0&gt;&gt; = 8.267173335510634

* numbersign (U+0023): L&lt;&lt;418.0,15.0&gt;--&lt;397.0,0.0&gt;&gt;/L&lt;&lt;397.0,0.0&gt;--&lt;398.0,1.0&gt;&gt; = 9.462322208025574

* ogonek (U+02DB): L&lt;&lt;429.0,-1.0&gt;--&lt;443.0,1.0&gt;&gt;/L&lt;&lt;443.0,1.0&gt;--&lt;431.0,-3.0&gt;&gt; = 10.304846468766044

* onequarter (U+00BC): L&lt;&lt;542.0,267.0&gt;--&lt;545.0,269.0&gt;&gt;/L&lt;&lt;545.0,269.0&gt;--&lt;528.0,263.0&gt;&gt; = 14.250032697803595

* registered (U+00AE): L&lt;&lt;250.0,535.0&gt;--&lt;245.0,536.0&gt;&gt;/L&lt;&lt;245.0,536.0&gt;--&lt;263.0,529.0&gt;&gt; = 9.940573033113024
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-ExtraBoldItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* paragraph (U+00B6): L&lt;&lt;486.0,551.0&gt;--&lt;486.0,553.0&gt;&gt;/L&lt;&lt;486.0,553.0&gt;--&lt;485.0,532.0&gt;&gt; = 2.726310993906212

* quotedblleft (U+201C): L&lt;&lt;194.0,389.0&gt;--&lt;171.0,394.0&gt;&gt;/L&lt;&lt;171.0,394.0&gt;--&lt;171.0,394.0&gt;&gt; = 12.2647737278924

* quotedblleft (U+201C): L&lt;&lt;389.0,389.0&gt;--&lt;366.0,394.0&gt;&gt;/L&lt;&lt;366.0,394.0&gt;--&lt;366.0,394.0&gt;&gt; = 12.2647737278924

* quoteleft (U+2018): L&lt;&lt;194.0,389.0&gt;--&lt;171.0,394.0&gt;&gt;/L&lt;&lt;171.0,394.0&gt;--&lt;171.0,394.0&gt;&gt; = 12.2647737278924

* sterling (U+00A3): L&lt;&lt;253.0,256.0&gt;--&lt;241.0,253.0&gt;&gt;/L&lt;&lt;241.0,253.0&gt;--&lt;241.0,253.0&gt;&gt; = 14.036243467926484

* uni0123 (U+0123): L&lt;&lt;310.0,533.0&gt;--&lt;287.0,538.0&gt;&gt;/L&lt;&lt;287.0,538.0&gt;--&lt;287.0,538.0&gt;&gt; = 12.2647737278924

* uni0312 (U+0312): L&lt;&lt;217.0,533.0&gt;--&lt;194.0,538.0&gt;&gt;/L&lt;&lt;194.0,538.0&gt;--&lt;194.0,538.0&gt;&gt; = 12.2647737278924

* yen (U+00A5): L&lt;&lt;121.0,115.0&gt;--&lt;121.0,115.0&gt;&gt;/L&lt;&lt;121.0,115.0&gt;--&lt;112.0,114.0&gt;&gt; = 6.340191745909908
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-MediumItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: quotedblright	Contours detected: 1	Expected: 2

- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): L&lt;&lt;517.0,180.0&gt;--&lt;521.0,166.0&gt;&gt;/L&lt;&lt;521.0,166.0&gt;--&lt;519.0,181.0&gt;&gt; = 8.350752532331416

* Wacute (U+1E82): L&lt;&lt;517.0,180.0&gt;--&lt;521.0,166.0&gt;&gt;/L&lt;&lt;521.0,166.0&gt;--&lt;519.0,181.0&gt;&gt; = 8.350752532331416

* Wcircumflex (U+0174): L&lt;&lt;517.0,180.0&gt;--&lt;521.0,166.0&gt;&gt;/L&lt;&lt;521.0,166.0&gt;--&lt;519.0,181.0&gt;&gt; = 8.350752532331416

* Wdieresis (U+1E84): L&lt;&lt;517.0,180.0&gt;--&lt;521.0,166.0&gt;&gt;/L&lt;&lt;521.0,166.0&gt;--&lt;519.0,181.0&gt;&gt; = 8.350752532331416

* Wgrave (U+1E80): L&lt;&lt;517.0,180.0&gt;--&lt;521.0,166.0&gt;&gt;/L&lt;&lt;521.0,166.0&gt;--&lt;519.0,181.0&gt;&gt; = 8.350752532331416

* numbersign (U+0023): L&lt;&lt;409.0,15.0&gt;--&lt;386.0,0.0&gt;&gt;/L&lt;&lt;386.0,0.0&gt;--&lt;387.0,1.0&gt;&gt; = 11.888658039627998

* ogonek (U+02DB): L&lt;&lt;442.0,-1.0&gt;--&lt;456.0,1.0&gt;&gt;/L&lt;&lt;456.0,1.0&gt;--&lt;444.0,-3.0&gt;&gt; = 10.304846468766044

* onequarter (U+00BC): L&lt;&lt;544.0,267.0&gt;--&lt;548.0,269.0&gt;&gt;/L&lt;&lt;548.0,269.0&gt;--&lt;530.0,263.0&gt;&gt; = 8.130102354155916

* paragraph (U+00B6): L&lt;&lt;434.0,611.0&gt;--&lt;434.0,614.0&gt;&gt;/L&lt;&lt;434.0,614.0&gt;--&lt;429.0,585.0&gt;&gt; = 9.782407031807285

* registered (U+00AE): L&lt;&lt;295.0,535.0&gt;--&lt;290.0,536.0&gt;&gt;/L&lt;&lt;290.0,536.0&gt;--&lt;307.0,529.0&gt;&gt; = 11.070202577939344

* threequarters (U+00BE): L&lt;&lt;245.0,315.0&gt;--&lt;247.0,316.0&gt;&gt;/L&lt;&lt;247.0,316.0&gt;--&lt;230.0,312.0&gt;&gt; = 13.324531261890783
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-Italic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: OE	Contours detected: 4	Expected: 2

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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Aogonek (U+0104): L&lt;&lt;422.0,11.0&gt;--&lt;445.0,10.0&gt;&gt;/L&lt;&lt;445.0,10.0&gt;--&lt;443.0,10.0&gt;&gt; = 2.4895529219991284

* Eogonek (U+0118): L&lt;&lt;395.0,11.0&gt;--&lt;418.0,10.0&gt;&gt;/L&lt;&lt;418.0,10.0&gt;--&lt;416.0,10.0&gt;&gt; = 2.4895529219991284

* Iogonek (U+012E): L&lt;&lt;185.0,11.0&gt;--&lt;208.0,10.0&gt;&gt;/L&lt;&lt;208.0,10.0&gt;--&lt;206.0,10.0&gt;&gt; = 2.4895529219991284

* Uogonek (U+0172): L&lt;&lt;295.0,11.0&gt;--&lt;318.0,10.0&gt;&gt;/L&lt;&lt;318.0,10.0&gt;--&lt;316.0,10.0&gt;&gt; = 2.4895529219991284

* aogonek (U+0105): L&lt;&lt;388.0,21.0&gt;--&lt;411.0,20.0&gt;&gt;/L&lt;&lt;411.0,20.0&gt;--&lt;409.0,20.0&gt;&gt; = 2.4895529219991284

* eogonek (U+0119): L&lt;&lt;338.0,20.0&gt;--&lt;361.0,19.0&gt;&gt;/L&lt;&lt;361.0,19.0&gt;--&lt;359.0,19.0&gt;&gt; = 2.4895529219991284

* iogonek (U+012F): L&lt;&lt;113.0,1.0&gt;--&lt;136.0,0.0&gt;&gt;/L&lt;&lt;136.0,0.0&gt;--&lt;134.0,0.0&gt;&gt; = 2.4895529219991284

* notequal (U+2260): L&lt;&lt;372.0,289.0&gt;--&lt;360.0,292.0&gt;&gt;/L&lt;&lt;360.0,292.0&gt;--&lt;360.0,292.0&gt;&gt; = 14.036243467926484

* threequarters (U+00BE): L&lt;&lt;280.0,361.0&gt;--&lt;280.0,365.0&gt;&gt;/L&lt;&lt;280.0,365.0&gt;--&lt;278.0,357.0&gt;&gt; = 14.036243467926484

* threequarters (U+00BE): L&lt;&lt;280.0,365.0&gt;--&lt;278.0,357.0&gt;&gt;/L&lt;&lt;278.0,357.0&gt;--&lt;280.0,361.0&gt;&gt; = 12.528807709151522

* uni0328 (U+0328): L&lt;&lt;432.0,1.0&gt;--&lt;455.0,0.0&gt;&gt;/L&lt;&lt;455.0,0.0&gt;--&lt;453.0,0.0&gt;&gt; = 2.4895529219991284

* uogonek (U+0173): L&lt;&lt;417.0,11.0&gt;--&lt;440.0,10.0&gt;&gt;/L&lt;&lt;440.0,10.0&gt;--&lt;438.0,10.0&gt;&gt; = 2.4895529219991284

* yen (U+00A5): L&lt;&lt;363.0,349.0&gt;--&lt;346.0,335.0&gt;&gt;/L&lt;&lt;346.0,335.0&gt;--&lt;350.0,337.0&gt;&gt; = 12.90740867126582
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-LightItalic.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Lslash (U+0141): L&lt;&lt;112.0,257.0&gt;--&lt;113.0,258.0&gt;&gt;/L&lt;&lt;113.0,258.0&gt;--&lt;110.0,256.0&gt;&gt; = 11.309932474020227

* Oslash (U+00D8): L&lt;&lt;135.0,162.0&gt;--&lt;136.0,171.0&gt;&gt;/L&lt;&lt;136.0,171.0&gt;--&lt;132.0,160.0&gt;&gt; = 13.642914775990052

* braceleft (U+007B): L&lt;&lt;183.0,341.0&gt;--&lt;150.0,336.0&gt;&gt;/L&lt;&lt;150.0,336.0&gt;--&lt;176.0,336.0&gt;&gt; = 8.615648184164108

* braceright (U+007D): L&lt;&lt;252.0,340.0&gt;--&lt;285.0,345.0&gt;&gt;/L&lt;&lt;285.0,345.0&gt;--&lt;259.0,345.0&gt;&gt; = 8.615648184164108
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[5] WinkyRough-ExtraBold.ttf</summary>
<div>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



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

<details><summary>[5] WinkyRough-Bold.ttf</summary>
<div>
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

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: Oslash	Contours detected: 4	Expected: 2 or 3

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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



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

<details><summary>[6] WinkyRough-Black.ttf</summary>
<div>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;275.0,509.0&gt;--&lt;275.0,509.0&gt;&gt;/L&lt;&lt;275.0,509.0&gt;--&lt;268.0,510.0&gt;&gt; = 8.13010235415596
</code></pre>
 [code: found-jaggy-segments]



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

<details><summary>[6] WinkyRough-Light.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, hebrew, math, coptic, old-permic, tifinagh, todhri, tai-le, malayalam, syriac, canadian-aboriginal</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, hatran, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, brahmi, kaithi, newa, myanmar, dogra, zanabazar-square, hanunoo, devanagari, meetei-mayek, pahawh-hmong, malayalam, warang-citi, avestan, tai-viet, cham, takri, siddham, syriac, saurashtra, tibetan, tamil, balinese, tai-tham, tirhuta, hebrew, new-tai-lue, nko, javanese, arabic, khojki, kharoshthi, limbu, sogdian, telugu, gunjala-gondi, batak, tagalog, thaana, bhaiksuki, buginese, chakma, grantha, masaram-gondi, gurmukhi, khmer, tai-le, buhid, gujarati, bengali, rejang, mahajani, oriya, yi, tagbanwa, mongolian, duployan, psalter-pahlavi, tifinagh, sundanese, old-hungarian, lao, syloti-nagri, kayah-li, lepcha, modi, kannada, hanifi-rohingya, manichaean, sharada, khudawadi, phags-pa, mandaic, thai</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, syriac, phags-pa, nko</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: zanabazar-square, pahawh-hmong, cham, takri, siddham, tibetan, hebrew, kharoshthi, limbu, mende-kikakui, elbasan, bhaiksuki, marchen, gujarati, mahajani, duployan, tifinagh, kayah-li, lepcha, kaithi, newa, old-permic, meetei-mayek, warang-citi, syriac, tai-tham, tirhuta, miao, coptic, javanese, sogdian, telugu, batak, thaana, osage, grantha, gurmukhi, khmer, tai-le, buhid, rejang, oriya, mongolian, syloti-nagri, modi, hanifi-rohingya, manichaean, sharada, phags-pa, nko, masaram-gondi, ahom, sinhala, myanmar, bassa-vah, music, tai-viet, math, new-tai-lue, gunjala-gondi, chakma, yi, tagbanwa, khudawadi, saurashtra, brahmi, dogra, hanunoo, devanagari, malayalam, armenian, tamil, balinese, soyombo, khojki, symbols, tagalog, buginese, bengali, caucasian-albanian, adlam, psalter-pahlavi, sundanese, wancho, lao, kannada, canadian-aboriginal, mandaic, thai</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, chinese-hongkong, japanese, phags-pa, yi, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ į̆ į̇ į̈ į̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kaska (Latn, 125 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
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
| 0 | 0 | 1 | 81 | 1613 | 85 | 1500 | 0 | 
| 0% | 0% | 0% | 2% | 49% | 3% | 46% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
