## FontBakery report

fontbakery version: 0.12.10





## Check results



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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Aogonek (U+0104): L&lt;&lt;474.0,11.0&gt;--&lt;497.0,10.0&gt;&gt;/L&lt;&lt;497.0,10.0&gt;--&lt;495.0,10.0&gt;&gt; = 2.4895529219991284

* Eogonek (U+0118): L&lt;&lt;420.0,11.0&gt;--&lt;443.0,10.0&gt;&gt;/L&lt;&lt;443.0,10.0&gt;--&lt;441.0,10.0&gt;&gt; = 2.4895529219991284

* Iogonek (U+012E): L&lt;&lt;237.0,11.0&gt;--&lt;260.0,10.0&gt;&gt;/L&lt;&lt;260.0,10.0&gt;--&lt;258.0,10.0&gt;&gt; = 2.4895529219991284

* Uogonek (U+0172): L&lt;&lt;351.0,11.0&gt;--&lt;374.0,10.0&gt;&gt;/L&lt;&lt;374.0,10.0&gt;--&lt;372.0,10.0&gt;&gt; = 2.4895529219991284

* aogonek (U+0105): L&lt;&lt;424.0,21.0&gt;--&lt;447.0,20.0&gt;&gt;/L&lt;&lt;447.0,20.0&gt;--&lt;445.0,20.0&gt;&gt; = 2.4895529219991284

* dcroat (U+0111): L&lt;&lt;456.0,558.0&gt;--&lt;448.0,559.0&gt;&gt;/L&lt;&lt;448.0,559.0&gt;--&lt;448.0,559.0&gt;&gt; = 7.125016348901757

* eogonek (U+0119): L&lt;&lt;373.0,20.0&gt;--&lt;396.0,19.0&gt;&gt;/L&lt;&lt;396.0,19.0&gt;--&lt;394.0,19.0&gt;&gt; = 2.4895529219991284

* iogonek (U+012F): L&lt;&lt;153.0,1.0&gt;--&lt;176.0,0.0&gt;&gt;/L&lt;&lt;176.0,0.0&gt;--&lt;174.0,0.0&gt;&gt; = 2.4895529219991284

* uni0328 (U+0328): L&lt;&lt;419.0,1.0&gt;--&lt;442.0,0.0&gt;&gt;/L&lt;&lt;442.0,0.0&gt;--&lt;440.0,0.0&gt;&gt; = 2.4895529219991284

* uogonek (U+0173): L&lt;&lt;453.0,11.0&gt;--&lt;476.0,10.0&gt;&gt;/L&lt;&lt;476.0,10.0&gt;--&lt;474.0,10.0&gt;&gt; = 2.4895529219991284
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* registered (U+00AE): L&lt;&lt;235.0,541.0&gt;--&lt;220.0,540.0&gt;&gt;/L&lt;&lt;220.0,540.0&gt;--&lt;246.0,539.0&gt;&gt; = 6.016672996056167
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Oslash (U+00D8): L&lt;&lt;275.0,509.0&gt;--&lt;275.0,509.0&gt;&gt;/L&lt;&lt;275.0,509.0&gt;--&lt;268.0,510.0&gt;&gt; = 8.13010235415596

* lslash (U+0142): L&lt;&lt;54.0,191.0&gt;--&lt;54.0,191.0&gt;&gt;/L&lt;&lt;54.0,191.0&gt;--&lt;28.0,196.0&gt;&gt; = 10.88552705465871
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

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 3	Expected: 2

- Glyph name: Wacute	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 4	Expected: 3

- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, malayalam, canadian-aboriginal, syriac, todhri, math, duployan, tai-le, tifinagh, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, hatran, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, manichaean, javanese, kaithi, telugu, tifinagh, saurashtra, myanmar, chakma, hanifi-rohingya, syriac, sogdian, bengali, newa, kayah-li, khudawadi, buhid, lao, tagalog, devanagari, old-hungarian, mongolian, sundanese, malayalam, batak, meetei-mayek, limbu, arabic, takri, khojki, tamil, duployan, dogra, buginese, mahajani, masaram-gondi, hebrew, tirhuta, bhaiksuki, brahmi, hanunoo, khmer, oriya, cham, rejang, tai-viet, thai, tagbanwa, modi, warang-citi, lepcha, pahawh-hmong, siddham, syloti-nagri, gurmukhi, kharoshthi, tai-tham, nko, sharada, avestan, new-tai-lue, balinese, gujarati, kannada, mandaic, tai-le, gunjala-gondi, phags-pa, grantha, zanabazar-square, psalter-pahlavi, tibetan, yi, thaana</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, syriac, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: javanese, chakma, math, lao, buhid, sundanese, takri, tamil, music, tirhuta, brahmi, khmer, oriya, adlam, rejang, wancho, modi, syloti-nagri, kharoshthi, nko, gujarati, soyombo, gunjala-gondi, elbasan, old-permic, canadian-aboriginal, kayah-li, khudawadi, mongolian, meetei-mayek, khojki, mahajani, hebrew, bhaiksuki, hanunoo, bassa-vah, thai, miao, lepcha, marchen, phags-pa, grantha, psalter-pahlavi, tibetan, manichaean, saurashtra, myanmar, sogdian, mende-kikakui, tagalog, devanagari, batak, ahom, dogra, caucasian-albanian, tai-viet, cham, warang-citi, pahawh-hmong, coptic, sharada, osage, mandaic, yi, thaana, sinhala, kaithi, telugu, symbols, hanifi-rohingya, syriac, bengali, newa, malayalam, limbu, duployan, buginese, masaram-gondi, tagbanwa, siddham, gurmukhi, tai-tham, new-tai-lue, balinese, kannada, tai-le, zanabazar-square, armenian, tifinagh</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: yi, chinese-simplified, chinese-hongkong, nushu, phags-pa, japanese, chinese-traditional</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
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
| 0 | 0 | 0 | 40 | 808 | 43 | 758 | 0 | 
| 0% | 0% | 0% | 2% | 49% | 3% | 46% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG