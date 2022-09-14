## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[3] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansTaiTham/googlefonts/ttf', 'fonts/NotoSansTaiTham/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[10] NotoSansTaiTham-Bold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_raMedial_signAetham
	* a_raMedial_signAitham
	* a_raMedial_signEtham
	* a_raMedial_signOotham
	* a_raMedial_signThamAitham
	* ba_raMedial_signAetham
	* ba_raMedial_signAitham
	* ba_raMedial_signOotham
	* ba_raMedial_signThamAitham
	* ba_signAetham and 464 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- maiKang_maiSattham.blwf1
	- maiKang_tone1tham.blwf1
	- maiSat_maiSattham
	- maiSat_tone1tham
	- signI_maiKangLaitham
	- signI_maiKangtham
	- signO_maiSattham.blwf1
	- signO_tone1tham.blwf1
	- signOaAbove_tone1tham.blwf1
	- taHigh.watham
	- uni1AA9
	- wa_yaLowtham

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- lue_raMedial_signAetham

	- lue_raMedial_signAitham

	- lue_raMedial_signEtham

	- lue_raMedial_signOotham

	- lue_raMedial_signThamAitham

	- lue_raMedialtham

	- lue_signAetham

	- lue_signAitham

	- lue_signEtham

	- lue_signOotham 

	- And 28 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=413.5,Y=698.5 (should be at cap-height 700?)

	* six (U+0036): X=241.5,Y=698.5 (should be at cap-height 700?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=286.0,Y=532.5 (should be at x-height 534?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* d (U+0064): X=352.0,Y=533.0 (should be at x-height 534?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* p (U+0070): X=286.0,Y=532.0 (should be at x-height 534?) 

	* And 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni1A4F (U+1A4F): L<<199.0,35.0>--<200.0,-124.0>>

	* uni1A4F (U+1A4F): L<<76.0,203.0>--<202.0,204.0>>

	* uni1A4F (U+1A4F): L<<78.0,-86.0>--<76.0,203.0>>

	* uni1A50 (U+1A50): L<<84.0,203.0>--<211.0,204.0>> 

	* And uni1A50 (U+1A50): L<<89.0,385.0>--<87.0,660.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansTaiTham-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_raMedial_signAetham
	* a_raMedial_signAitham
	* a_raMedial_signEtham
	* a_raMedial_signOotham
	* a_raMedial_signThamAitham
	* ba_raMedial_signAetham
	* ba_raMedial_signAitham
	* ba_raMedial_signEtham
	* ba_raMedial_signOotham
	* ba_raMedial_signThamAitham and 574 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- maiKang_maiSattham.blwf1
	- maiKang_tone1tham.blwf1
	- maiSat_maiSattham
	- maiSat_tone1tham
	- signI_maiKangLaitham
	- signI_maiKangtham
	- signO_maiSattham.blwf1
	- signO_tone1tham.blwf1
	- signOaAbove_tone1tham.blwf1
	- taHigh.watham
	- uni1AA9
	- wa_yaLowtham

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tai Tham Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- lue_raMedial_signAetham

	- lue_raMedial_signAitham

	- lue_raMedial_signEtham

	- lue_raMedial_signOotham

	- lue_raMedial_signThamAitham

	- lue_raMedialtham

	- lue_signAetham

	- lue_signAitham

	- lue_signEtham

	- lue_signOotham 

	- And 28 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=149.0,Y=698.0 (should be at cap-height 700?)

	* three (U+0033): X=136.5,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=243.5,Y=699.5 (should be at cap-height 700?)

	* nine (U+0039): X=96.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=552.5,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=534.5,Y=-0.5 (should be at baseline 0?)

	* S (U+0053): X=137.5,Y=-0.5 (should be at baseline 0?)

	* a (U+0061): X=188.5,Y=534.5 (should be at x-height 534?)

	* c (U+0063): X=383.0,Y=-2.0 (should be at baseline 0?)

	* e (U+0065): X=414.5,Y=-1.5 (should be at baseline 0?) 

	* And 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1A3D (U+1A3D): L<<504.0,266.0>--<504.0,266.0>> -> L<<504.0,266.0>--<504.0,266.0>>

	* uni1A47 (U+1A47): L<<493.0,268.0>--<493.0,268.0>> -> L<<493.0,268.0>--<493.0,268.0>>

	* uni1A48 (U+1A48): L<<499.0,268.0>--<499.0,268.0>> -> L<<499.0,268.0>--<499.0,268.0>>

	* uni1A54 (U+1A54): L<<506.0,268.0>--<506.0,268.0>> -> L<<506.0,268.0>--<506.0,268.0>>

	* uni1A54 (U+1A54): L<<902.0,268.0>--<902.0,267.0>> -> L<<902.0,267.0>--<902.0,266.0>> 

	* And uni1AA2 (U+1AA2): L<<506.0,268.0>--<506.0,268.0>> -> L<<506.0,268.0>--<506.0,268.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<474.5,553.0>-<469.0,579.0>-<467.0,591.0>>/B<<467.0,591.0>-<466.0,579.0>-<460.5,553.5>> = 14.22596389875178

	* W (U+0057): B<<667.0,199.5>-<677.0,151.0>-<682.0,116.0>>/B<<682.0,116.0>-<686.0,153.0>-<696.0,200.0>> = 14.300277449185549

	* Wacute (U+1E82): B<<474.5,553.0>-<469.0,579.0>-<467.0,591.0>>/B<<467.0,591.0>-<466.0,579.0>-<460.5,553.5>> = 14.22596389875178

	* Wacute (U+1E82): B<<667.0,199.5>-<677.0,151.0>-<682.0,116.0>>/B<<682.0,116.0>-<686.0,153.0>-<696.0,200.0>> = 14.300277449185549

	* Wcircumflex (U+0174): B<<474.5,553.0>-<469.0,579.0>-<467.0,591.0>>/B<<467.0,591.0>-<466.0,579.0>-<460.5,553.5>> = 14.22596389875178

	* Wcircumflex (U+0174): B<<667.0,199.5>-<677.0,151.0>-<682.0,116.0>>/B<<682.0,116.0>-<686.0,153.0>-<696.0,200.0>> = 14.300277449185549

	* Wdieresis (U+1E84): B<<474.5,553.0>-<469.0,579.0>-<467.0,591.0>>/B<<467.0,591.0>-<466.0,579.0>-<460.5,553.5>> = 14.22596389875178

	* Wdieresis (U+1E84): B<<667.0,199.5>-<677.0,151.0>-<682.0,116.0>>/B<<682.0,116.0>-<686.0,153.0>-<696.0,200.0>> = 14.300277449185549

	* Wgrave (U+1E80): B<<474.5,553.0>-<469.0,579.0>-<467.0,591.0>>/B<<467.0,591.0>-<466.0,579.0>-<460.5,553.5>> = 14.22596389875178 

	* And Wgrave (U+1E80): B<<667.0,199.5>-<677.0,151.0>-<682.0,116.0>>/B<<682.0,116.0>-<686.0,153.0>-<696.0,200.0>> = 14.300277449185549 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni1A2A (U+1A2A): L<<87.0,271.0>--<89.0,636.0>>

	* uni1A4F (U+1A4F): L<<82.0,-86.0>--<80.0,169.0>>

	* uni1A50 (U+1A50): L<<173.0,47.0>--<174.0,-124.0>>

	* uni1A50 (U+1A50): L<<179.0,705.0>--<178.0,490.0>> 

	* And uni1A50 (U+1A50): L<<84.0,-86.0>--<83.0,169.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansTaiTham-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_raMedial_signAitham
	* a_raMedial_signOotham
	* chaHigh_raMedial_signAitham
	* chaHigh_raMedial_signOotham
	* chaHigh_raMedial_signThamAitham
	* chaHigh_signAitham
	* chaHigh_signOotham
	* chaHigh_signThamAitham
	* greatSa_raMedial_signAitham
	* greatSa_raMedial_signOotham and 101 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- maiKang_maiSattham.blwf1
	- maiKang_tone1tham.blwf1
	- maiSat_maiSattham
	- maiSat_tone1tham
	- signI_maiKangLaitham
	- signI_maiKangtham
	- signO_maiSattham.blwf1
	- signO_tone1tham.blwf1
	- signOaAbove_tone1tham.blwf1
	- taHigh.watham
	- uni1AA9
	- wa_yaLowtham

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- lue_raMedial_signAetham

	- lue_raMedial_signAitham

	- lue_raMedial_signEtham

	- lue_raMedial_signOotham

	- lue_raMedial_signThamAitham

	- lue_raMedialtham

	- lue_signAetham

	- lue_signAitham

	- lue_signEtham

	- lue_signOotham 

	- And 28 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1A2C (U+1A2C): L<<518.0,268.0>--<518.0,268.0>> -> L<<518.0,268.0>--<518.0,268.0>>

	* uni1A32 (U+1A32): L<<539.0,266.0>--<539.0,266.0>> -> L<<539.0,266.0>--<539.0,266.0>>

	* uni1A3D (U+1A3D): L<<489.0,266.0>--<489.0,266.0>> -> L<<489.0,266.0>--<489.0,266.0>>

	* uni1A47 (U+1A47): L<<474.0,268.0>--<474.0,268.0>> -> L<<474.0,268.0>--<474.0,268.0>>

	* uni1A48 (U+1A48): L<<482.0,268.0>--<482.0,268.0>> -> L<<482.0,268.0>--<482.0,268.0>>

	* uni1A54 (U+1A54): L<<492.0,268.0>--<492.0,268.0>> -> L<<492.0,268.0>--<492.0,268.0>>

	* uni1A54 (U+1A54): L<<891.0,268.0>--<891.0,268.0>> -> L<<891.0,268.0>--<891.0,268.0>>

	* uni1A93 (U+1A93): L<<539.0,267.0>--<539.0,267.0>> -> L<<539.0,267.0>--<539.0,267.0>> 

	* And uni1AA2 (U+1AA2): L<<491.0,268.0>--<491.0,268.0>> -> L<<491.0,268.0>--<491.0,268.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni1A2A (U+1A2A): L<<88.0,271.0>--<90.0,635.0>>

	* uni1A4F (U+1A4F): L<<157.0,53.0>--<158.0,-124.0>>

	* uni1A4F (U+1A4F): L<<83.0,-86.0>--<81.0,156.0>>

	* uni1A50 (U+1A50): L<<159.0,52.0>--<160.0,-124.0>>

	* uni1A50 (U+1A50): L<<84.0,-86.0>--<82.0,156.0>> 

	* And uni1A50 (U+1A50): L<<86.0,419.0>--<87.0,636.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansTaiTham-SemiBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_raMedial_signAetham
	* a_raMedial_signAitham
	* a_raMedial_signEtham
	* a_raMedial_signOotham
	* a_raMedial_signThamAitham
	* ba_raMedial_signAetham
	* ba_raMedial_signAitham
	* ba_raMedial_signEtham
	* ba_raMedial_signOotham
	* ba_raMedial_signThamAitham and 562 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- maiKang_maiSattham.blwf1
	- maiKang_tone1tham.blwf1
	- maiSat_maiSattham
	- maiSat_tone1tham
	- signI_maiKangLaitham
	- signI_maiKangtham
	- signO_maiSattham.blwf1
	- signO_tone1tham.blwf1
	- signOaAbove_tone1tham.blwf1
	- taHigh.watham
	- uni1AA9
	- wa_yaLowtham

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tai Tham SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- lue_raMedial_signAetham

	- lue_raMedial_signAitham

	- lue_raMedial_signEtham

	- lue_raMedial_signOotham

	- lue_raMedial_signThamAitham

	- lue_raMedialtham

	- lue_signAetham

	- lue_signAitham

	- lue_signEtham

	- lue_signOotham 

	- And 28 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=405.0,Y=699.5 (should be at cap-height 700?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* six (U+0036): X=242.5,Y=699.5 (should be at cap-height 700?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=531.0,Y=0.5 (should be at baseline 0?)

	* c (U+0063): X=388.5,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=423.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=275.5,Y=532.0 (should be at x-height 534?)

	* m (U+006D): X=270.5,Y=532.5 (should be at x-height 534?) 

	* And 64 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<482.5,523.0>-<476.0,553.0>-<475.0,567.0>>/B<<475.0,567.0>-<473.0,553.0>-<467.5,523.5>> = 12.215719134130818

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<482.5,523.0>-<476.0,553.0>-<475.0,567.0>>/B<<475.0,567.0>-<473.0,553.0>-<467.5,523.5>> = 12.215719134130818

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<482.5,523.0>-<476.0,553.0>-<475.0,567.0>>/B<<475.0,567.0>-<473.0,553.0>-<467.5,523.5>> = 12.215719134130818

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni1A2A (U+1A2A): L<<86.0,271.0>--<87.0,638.0>>

	* uni1A4F (U+1A4F): L<<183.0,41.0>--<184.0,-124.0>>

	* uni1A4F (U+1A4F): L<<80.0,-86.0>--<78.0,185.0>>

	* uni1A50 (U+1A50): L<<191.0,42.0>--<192.0,-124.0>>

	* uni1A50 (U+1A50): L<<197.0,706.0>--<196.0,493.0>>

	* uni1A50 (U+1A50): L<<84.0,-86.0>--<83.0,185.0>> 

	* And uni1A50 (U+1A50): L<<88.0,398.0>--<87.0,651.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] NotoSansTaiTham[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni1A55 + uni1A20

	- uni1A20 + uni1A6F

	- uni1A6F + uni1A20

	- uni1A20 + uni1A71

	- uni1A71 + uni1A20

	- uni1A20 + uni1A6E

	- uni1A6E + uni1A20

	- uni1A20 + uni1A70

	- uni1A70 + uni1A20

	- uni1A20 + uni1A72 

	- And 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- lue_raMedial_signAetham

	- lue_raMedial_signAitham

	- lue_raMedial_signEtham

	- lue_raMedial_signOotham

	- lue_raMedial_signThamAitham

	- lue_raMedialtham

	- lue_signAetham

	- lue_signAitham

	- lue_signEtham

	- lue_signOotham 

	- And 28 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1A56 (U+1A56), uni1A58 (U+1A58), uni1A59 (U+1A59), uni1A5A (U+1A5A), uni1A5B (U+1A5B), uni1A5C (U+1A5C), uni1A5D (U+1A5D), uni1A5E (U+1A5E), uni1A60 (U+1A60), uni1A65 (U+1A65) and 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 3 | 49 | 533 | 32 | 455 | 0 |
| 0% | 0% | 5% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
