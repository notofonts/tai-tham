## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] NotoSansTaiTham[wght].ttf</summary>
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
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni1A28.blwf2

- uni1A31.blwf

- uni1A32.blwf

- uni1A3A.blwf

- uni1A40.blwf

- uni1A421A55

- uni1A421A551A6E

- uni1A421A551A6F

- uni1A421A551A70

- uni1A421A551A71

- uni1A421A551A72

- uni1A421A6E

- uni1A421A6F

- uni1A421A70

- uni1A421A71

- uni1A421A72

- uni1A441A55

- uni1A441A551A6E

- uni1A441A551A6F

- uni1A441A551A70

- uni1A441A551A71

- uni1A441A551A72

- uni1A441A6E

- uni1A441A6F

- uni1A441A70

- uni1A441A71

- uni1A441A72

- uni1A45.blwf

- uni1A461A551A6E

- uni1A461A551A6F

- uni1A461A551A70

- uni1A461A551A71

- uni1A461A551A72

- uni1A4B.blwf

- uni1A58.alt

- uni1A58.blwf

- uni1A69.blwf

- uni1A75.blwf
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansTaiTham/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, malayalam, todhri, old-permic, coptic, hebrew, duployan, syriac, tai-le, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>tai-tham</code></p>
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







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Dutch (Latn, 31,709,104 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Kaska (Latn, 125 speakers), Vute (Latn, 21,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Nzakara (Latn, 50,000 speakers), Cicipu (Latn, 44,000 speakers), Ekpeye (Latn, 226,000 speakers), Avokaya (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Han (Latn, 6 speakers), Heiltsuk (Latn, 300 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Fur (Latn, 1,230,163 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dan (Latn, 1,099,244 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Basaa (Latn, 332,940 speakers), Southern Kisi (Latn, 360,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Ngbaka (Latn, 1,020,000 speakers), Makaa (Latn, 221,000 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- uni1A20 + uni1A6E

- uni1A20 + uni1A6F

- uni1A20 + uni1A70

- uni1A20 + uni1A71

- uni1A20 + uni1A72

- uni1A32.blwf1 + uni1A45.blwf1

- uni1A45 + uni1A60

- uni1A55 + uni1A20

- uni1A60 + uni1A3F

- uni1A60 + uni1A45

- uni1A62 + uni1A75

- uni1A62 + uni1A76

- uni1A65 + uni1A58

- uni1A65 + uni1A74

- uni1A6B + uni1A62

- uni1A6B + uni1A75

- uni1A73 + uni1A75

- uni1A74 + uni1A62

- uni1A74 + uni1A75

- uni1A76 + uni1A75

- uni1AA8 + uni1AA8
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- taHigh.watham
- uni1A451A3F
- uni1A621A62
- uni1A621A75
- uni1A651A58
- uni1A651A74
- uni1A6B1A62.blwf1
- uni1A6B1A75.blwf1
- uni1A731A75.blwf1
- uni1A741A62.blwf1
- uni1A741A75.blwf1
- uni1AA9</p>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



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
| 0 | 0 | 2 | 9 | 95 | 7 | 138 | 0 | 
| 0% | 0% | 1% | 4% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
