## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[5] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansTamil/googlefonts/ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Tamil Black: 870
Noto Sans Tamil Bold: 870
Noto Sans Tamil ExtraBold: 870
Noto Sans Tamil ExtraLight: 870
Noto Sans Tamil Light: 870
Noto Sans Tamil Medium: 870
Noto Sans Tamil: 870
Noto Sans Tamil SemiBold: 870
Noto Sans Tamil Thin: 870
Noto Sans Tamil UI Black: 1069
Noto Sans Tamil UI Bold: 1069
Noto Sans Tamil UI ExtraBold: 1069
Noto Sans Tamil UI ExtraLight: 1069
Noto Sans Tamil UI Light: 1069
Noto Sans Tamil UI Medium: 1069
Noto Sans Tamil UI: 1069
Noto Sans Tamil UI SemiBold: 1069
Noto Sans Tamil UI Thin: 1069 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Noto Sans Tamil Black: -370
Noto Sans Tamil Bold: -370
Noto Sans Tamil ExtraBold: -370
Noto Sans Tamil ExtraLight: -370
Noto Sans Tamil Light: -370
Noto Sans Tamil Medium: -370
Noto Sans Tamil: -370
Noto Sans Tamil SemiBold: -370
Noto Sans Tamil Thin: -370
Noto Sans Tamil UI Black: -293
Noto Sans Tamil UI Bold: -293
Noto Sans Tamil UI ExtraBold: -293
Noto Sans Tamil UI ExtraLight: -293
Noto Sans Tamil UI Light: -293
Noto Sans Tamil UI Medium: -293
Noto Sans Tamil UI: -293
Noto Sans Tamil UI SemiBold: -293
Noto Sans Tamil UI Thin: -293 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Noto Sans Tamil Black: 870
Noto Sans Tamil Bold: 870
Noto Sans Tamil ExtraBold: 870
Noto Sans Tamil ExtraLight: 870
Noto Sans Tamil Light: 870
Noto Sans Tamil Medium: 870
Noto Sans Tamil: 870
Noto Sans Tamil SemiBold: 870
Noto Sans Tamil Thin: 870
Noto Sans Tamil UI Black: 1069
Noto Sans Tamil UI Bold: 1069
Noto Sans Tamil UI ExtraBold: 1069
Noto Sans Tamil UI ExtraLight: 1069
Noto Sans Tamil UI Light: 1069
Noto Sans Tamil UI Medium: 1069
Noto Sans Tamil UI: 1069
Noto Sans Tamil UI SemiBold: 1069
Noto Sans Tamil UI Thin: 1069 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Noto Sans Tamil Black: 370
Noto Sans Tamil Bold: 370
Noto Sans Tamil ExtraBold: 370
Noto Sans Tamil ExtraLight: 370
Noto Sans Tamil Light: 370
Noto Sans Tamil Medium: 370
Noto Sans Tamil: 370
Noto Sans Tamil SemiBold: 370
Noto Sans Tamil Thin: 370
Noto Sans Tamil UI Black: 293
Noto Sans Tamil UI Bold: 293
Noto Sans Tamil UI ExtraBold: 293
Noto Sans Tamil UI ExtraLight: 293
Noto Sans Tamil UI Light: 293
Noto Sans Tamil UI Medium: 293
Noto Sans Tamil UI: 293
Noto Sans Tamil UI SemiBold: 293
Noto Sans Tamil UI Thin: 293 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Noto Sans Tamil Black: 870
Noto Sans Tamil Bold: 870
Noto Sans Tamil ExtraBold: 870
Noto Sans Tamil ExtraLight: 870
Noto Sans Tamil Light: 870
Noto Sans Tamil Medium: 870
Noto Sans Tamil: 870
Noto Sans Tamil SemiBold: 870
Noto Sans Tamil Thin: 870
Noto Sans Tamil UI Black: 1069
Noto Sans Tamil UI Bold: 1069
Noto Sans Tamil UI ExtraBold: 1069
Noto Sans Tamil UI ExtraLight: 1069
Noto Sans Tamil UI Light: 1069
Noto Sans Tamil UI Medium: 1069
Noto Sans Tamil UI: 1069
Noto Sans Tamil UI SemiBold: 1069
Noto Sans Tamil UI Thin: 1069 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Noto Sans Tamil Black: -370
Noto Sans Tamil Bold: -370
Noto Sans Tamil ExtraBold: -370
Noto Sans Tamil ExtraLight: -370
Noto Sans Tamil Light: -370
Noto Sans Tamil Medium: -370
Noto Sans Tamil: -370
Noto Sans Tamil SemiBold: -370
Noto Sans Tamil Thin: -370
Noto Sans Tamil UI Black: -293
Noto Sans Tamil UI Bold: -293
Noto Sans Tamil UI ExtraBold: -293
Noto Sans Tamil UI ExtraLight: -293
Noto Sans Tamil UI Light: -293
Noto Sans Tamil UI Medium: -293
Noto Sans Tamil UI: -293
Noto Sans Tamil UI SemiBold: -293
Noto Sans Tamil UI Thin: -293 [code: descent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Tamil' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[14] NotoSansTamil-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aatamil
	* aivowelsigntamil
	* asabovesigntamil
	* atamil
	* aulengthmarktamil
	* autamil
	* auvowelsigntamil
	* caiivowelsigntamil
	* caprehalftamil
	* catamil and 118 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<372.0,0.0>--<373.0,480.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansTamil-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aatamil
	* aivowelsigntamil
	* asabovesigntamil
	* atamil
	* aulengthmarktamil
	* autamil
	* auvowelsigntamil
	* caiivowelsigntamil
	* caprehalftamil
	* catamil and 110 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign.tamil (U+0023): X=246.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.tamil (U+0023): X=353.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.tamil (U+0023): X=450.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.tamil (U+0023): X=555.0,Y=713.0 (should be at cap-height 714?)

	* six.tamil (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

	* seven.tamil (U+0037): X=27.0,Y=713.0 (should be at cap-height 714?)

	* seven.tamil (U+0037): X=539.0,Y=713.0 (should be at cap-height 714?)

	* question.tamil (U+003F): X=133.0,Y=712.5 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?) 

	* 63 more.

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

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<80.0,0.0>--<79.0,360.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansTamil-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aatamil
	* aivowelsigntamil
	* asabovesigntamil
	* atamil
	* aulengthmarktamil
	* autamil
	* auvowelsigntamil
	* caiivowelsigntamil
	* caprehalftamil
	* catamil and 117 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357 

	* Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<371.0,0.0>--<372.0,483.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansTamil-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tchaiivowelsigntamil
	* tchaprehalftamil and tchatamil
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[12] NotoSansTamil-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* asabovesigntamil
	* itamil
	* kauuvowelsigntamil
	* nnaiivowelsigntamil
	* nnauuvowelsigntamil
	* nnauvowelsigntamil
	* nnnauuvowelsigntamil
	* nnnauvowelsigntamil
	* nyauuvowelsigntamil
	* nyauvowelsigntamil and 8 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[13] NotoSansTamil-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aatamil
	* aivowelsigntamil
	* asabovesigntamil
	* atamil
	* autamil
	* auvowelsigntamil
	* caiivowelsigntamil
	* caprehalftamil
	* catamil
	* cauuvowelsigntamil and 72 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<86.0,0.0>--<85.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansTamil-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/tamil.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf);}
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

<h4>qa/shaping_tests/tamil.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஙாஂஎ²ஸ𑌁</span> (Added by SIESTA)</li>


<pre>Expected: ngatamil=0+1044|aavowelsigntamil=0+609|anusvaratamil=0@-1307,0+0|etamil=3+826|uni00B2=4+312|satamil=5+1285|u11301=5@-365,235+0</pre>



<pre>Got     : ngatamil=0+1044|aavowelsigntamil=0+640|anusvaratamil=0@-1338,0+0|etamil=3+826|uni00B2=4+312|satamil=5+1285|u11301=5@-365,235+0</pre>



<pre>                                               +                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4107 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M88.0,0.0L88.0,554.0L604.0,554.0L604.0,482.0L430.0,482.0L430.0,324.0Q450.0,336.0 482.0,349.0Q514.0,362.0 558.0,362.0Q633.0,362.0 675.5,319.5Q718.0,277.0 718.0,201.0Q718.0,165.0 708.0,132.0Q698.0,99.0 682.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,0.0L344.0,0.0L344.0,72.0L595.0,72.0Q612.0,97.0 622.0,127.5Q632.0,158.0 632.0,192.0Q632.0,245.0 607.0,267.0Q582.0,289.0 543.0,289.0Q511.0,289.0 481.5,276.0Q452.0,263.0 430.0,246.0L430.0,144.0L344.0,144.0L344.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(0, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(1044, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(346, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1684, 870)"/>
<path d="M15.0,369.0L15.0,423.0L130.0,535.0Q170.0,574.0 191.0,598.5Q212.0,623.0 219.5,642.5Q227.0,662.0 227.0,684.0Q227.0,716.0 208.5,732.0Q190.0,748.0 160.0,748.0Q130.0,748.0 105.5,736.5Q81.0,725.0 55.0,705.0L20.0,751.0Q49.0,776.0 83.5,791.0Q118.0,806.0 161.0,806.0Q225.0,806.0 261.5,774.5Q298.0,743.0 298.0,688.0Q298.0,639.0 268.5,600.0Q239.0,561.0 183.0,508.0L102.0,431.0L297.0,431.0L297.0,369.0L15.0,369.0Z" transform="translate(2510, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(2822, 870)"/>
<path d="M-278.0,660.0Q-362.0,660.0 -407.0,700.5Q-452.0,741.0 -452.0,815.0Q-452.0,844.0 -444.0,870.0L-376.0,856.0Q-379.0,846.0 -380.0,835.5Q-381.0,825.0 -381.0,817.0Q-381.0,781.0 -366.5,761.0Q-352.0,741.0 -328.0,733.0Q-304.0,725.0 -278.0,725.0Q-237.0,725.0 -206.0,746.0Q-175.0,767.0 -175.0,819.0Q-175.0,827.0 -176.0,836.5Q-177.0,846.0 -180.0,856.0L-111.0,870.0Q-108.0,858.0 -106.0,843.0Q-104.0,828.0 -104.0,815.0Q-104.0,742.0 -150.5,701.0Q-197.0,660.0 -278.0,660.0ZM-279.0,767.0Q-301.0,767.0 -315.0,781.0Q-329.0,795.0 -329.0,818.0Q-329.0,839.0 -315.0,853.5Q-301.0,868.0 -279.0,868.0Q-257.0,868.0 -242.5,853.5Q-228.0,839.0 -228.0,818.0Q-228.0,795.0 -242.5,781.0Q-257.0,767.0 -279.0,767.0Z" transform="translate(3742, 1105)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4076 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M88.0,0.0L88.0,554.0L604.0,554.0L604.0,482.0L430.0,482.0L430.0,324.0Q450.0,336.0 482.0,349.0Q514.0,362.0 558.0,362.0Q633.0,362.0 675.5,319.5Q718.0,277.0 718.0,201.0Q718.0,165.0 708.0,132.0Q698.0,99.0 682.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,0.0L344.0,0.0L344.0,72.0L595.0,72.0Q612.0,97.0 622.0,127.5Q632.0,158.0 632.0,192.0Q632.0,245.0 607.0,267.0Q582.0,289.0 543.0,289.0Q511.0,289.0 481.5,276.0Q452.0,263.0 430.0,246.0L430.0,144.0L344.0,144.0L344.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(0, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(1044, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(346, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1653, 870)"/>
<path d="M15.0,369.0L15.0,423.0L130.0,535.0Q170.0,574.0 191.0,598.5Q212.0,623.0 219.5,642.5Q227.0,662.0 227.0,684.0Q227.0,716.0 208.5,732.0Q190.0,748.0 160.0,748.0Q130.0,748.0 105.5,736.5Q81.0,725.0 55.0,705.0L20.0,751.0Q49.0,776.0 83.5,791.0Q118.0,806.0 161.0,806.0Q225.0,806.0 261.5,774.5Q298.0,743.0 298.0,688.0Q298.0,639.0 268.5,600.0Q239.0,561.0 183.0,508.0L102.0,431.0L297.0,431.0L297.0,369.0L15.0,369.0Z" transform="translate(2479, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(2791, 870)"/>
<path d="M-278.0,660.0Q-362.0,660.0 -407.0,700.5Q-452.0,741.0 -452.0,815.0Q-452.0,844.0 -444.0,870.0L-376.0,856.0Q-379.0,846.0 -380.0,835.5Q-381.0,825.0 -381.0,817.0Q-381.0,781.0 -366.5,761.0Q-352.0,741.0 -328.0,733.0Q-304.0,725.0 -278.0,725.0Q-237.0,725.0 -206.0,746.0Q-175.0,767.0 -175.0,819.0Q-175.0,827.0 -176.0,836.5Q-177.0,846.0 -180.0,856.0L-111.0,870.0Q-108.0,858.0 -106.0,843.0Q-104.0,828.0 -104.0,815.0Q-104.0,742.0 -150.5,701.0Q-197.0,660.0 -278.0,660.0ZM-279.0,767.0Q-301.0,767.0 -315.0,781.0Q-329.0,795.0 -329.0,818.0Q-329.0,839.0 -315.0,853.5Q-301.0,868.0 -279.0,868.0Q-257.0,868.0 -242.5,853.5Q-228.0,839.0 -228.0,818.0Q-228.0,795.0 -242.5,781.0Q-257.0,767.0 -279.0,767.0Z" transform="translate(3711, 1105)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌻ணஂ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+562|u1133B=0+0|nnatamil=1+1648|anusvaratamil=1@-1000,0+0</pre>



<pre>Got     : uni25CC=0+562|u1133B=0@46,-54+0|nnatamil=1+1648|anusvaratamil=1@-1000,0+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2210 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(0, 870)"/>
<path d="M-278.0,-210.0Q-306.0,-210.0 -324.0,-192.0Q-342.0,-174.0 -342.0,-146.0Q-342.0,-119.0 -324.0,-100.5Q-306.0,-82.0 -278.0,-82.0Q-250.0,-82.0 -232.0,-100.5Q-214.0,-119.0 -214.0,-146.0Q-214.0,-174.0 -232.5,-192.0Q-251.0,-210.0 -278.0,-210.0Z" transform="translate(608, 816)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q477.0,566.0 536.5,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q930.0,566.0 981.0,550.0Q1032.0,534.0 1077.0,502.0Q1105.0,518.0 1138.5,529.5Q1172.0,541.0 1218.5,547.5Q1265.0,554.0 1333.0,554.0L1631.0,554.0L1631.0,482.0L1461.0,482.0L1461.0,0.0L1375.0,0.0L1375.0,482.0L1310.0,482.0Q1257.0,482.0 1215.5,476.5Q1174.0,471.0 1135.0,452.0Q1184.0,403.0 1212.0,336.0Q1240.0,269.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,262.0 936.0,328.5Q960.0,395.0 1016.0,454.0Q980.0,475.0 942.5,484.0Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.0,88.0Q1038.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,255.0 1130.5,314.5Q1106.0,374.0 1071.0,410.0Q1034.0,374.0 1015.0,314.5Q996.0,255.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(562, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1210, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2210 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(0, 870)"/>
<path d="M-278.0,-210.0Q-306.0,-210.0 -324.0,-192.0Q-342.0,-174.0 -342.0,-146.0Q-342.0,-119.0 -324.0,-100.5Q-306.0,-82.0 -278.0,-82.0Q-250.0,-82.0 -232.0,-100.5Q-214.0,-119.0 -214.0,-146.0Q-214.0,-174.0 -232.5,-192.0Q-251.0,-210.0 -278.0,-210.0Z" transform="translate(562, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q477.0,566.0 536.5,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q930.0,566.0 981.0,550.0Q1032.0,534.0 1077.0,502.0Q1105.0,518.0 1138.5,529.5Q1172.0,541.0 1218.5,547.5Q1265.0,554.0 1333.0,554.0L1631.0,554.0L1631.0,482.0L1461.0,482.0L1461.0,0.0L1375.0,0.0L1375.0,482.0L1310.0,482.0Q1257.0,482.0 1215.5,476.5Q1174.0,471.0 1135.0,452.0Q1184.0,403.0 1212.0,336.0Q1240.0,269.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,262.0 936.0,328.5Q960.0,395.0 1016.0,454.0Q980.0,475.0 942.5,484.0Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.0,88.0Q1038.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,255.0 1130.5,314.5Q1106.0,374.0 1071.0,410.0Q1034.0,374.0 1015.0,314.5Q996.0,255.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(562, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1210, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஸஂஊௗஂசாஂஔஃ</span> (Added by SIESTA)</li>


<pre>Expected: satamil=0+1285|anusvaratamil=0@-819,0+0|uutamil=2+1540|aulengthmarktamil=2+1025|anusvaratamil=2@-1971,0+0|catamil=5+723|aavowelsigntamil=5+617|anusvaratamil=5@-1155,0+0|autamil=8+1992|visargatamil=9+896</pre>



<pre>Got     : satamil=0+1285|anusvaratamil=0@-819,0+0|uutamil=2+1540|aulengthmarktamil=2+1070|anusvaratamil=2@-2016,0+0|catamil=5+723|aavowelsigntamil=5+640|anusvaratamil=5@-1178,0+0|autamil=8+1992|visargatamil=9+896</pre>



<pre>                                                                                       ^^                  ^^^^                                       ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8146 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(466, 870)"/>
<path d="M298.0,566.0Q405.0,566.0 472.0,536.5Q539.0,507.0 570.5,457.5Q602.0,408.0 602.0,349.0Q602.0,271.0 565.0,228.0Q528.0,185.0 462.0,164.5Q396.0,144.0 309.0,135.0L229.0,127.0Q193.0,124.0 175.5,119.5Q158.0,115.0 152.5,109.5Q147.0,104.0 147.0,95.0Q147.0,83.0 155.0,77.5Q163.0,72.0 182.0,72.0L1494.0,72.0L1494.0,0.0L191.0,0.0Q121.0,0.0 91.5,27.0Q62.0,54.0 62.0,94.0Q62.0,139.0 98.5,164.0Q135.0,189.0 226.0,198.0L298.0,205.0Q368.0,212.0 411.0,226.0Q454.0,240.0 477.0,259.5Q500.0,279.0 508.0,302.0Q516.0,325.0 516.0,349.0Q516.0,408.0 472.5,448.0Q429.0,488.0 348.0,495.0Q364.0,474.0 373.5,448.0Q383.0,422.0 383.0,392.0Q383.0,327.0 341.0,285.5Q299.0,244.0 220.0,244.0Q175.0,244.0 138.0,263.0Q101.0,282.0 79.0,317.0Q57.0,352.0 57.0,398.0Q57.0,455.0 88.0,492.5Q119.0,530.0 173.5,548.0Q228.0,566.0 298.0,566.0ZM858.0,132.0Q815.0,132.0 777.5,152.0Q740.0,172.0 717.5,215.0Q695.0,258.0 695.0,325.0Q695.0,409.0 729.0,462.0Q763.0,515.0 817.0,540.5Q871.0,566.0 931.0,566.0Q985.0,566.0 1022.5,552.5Q1060.0,539.0 1090.0,516.0L1090.0,554.0L1494.0,554.0L1494.0,486.0L1376.0,486.0L1376.0,144.0L1294.0,144.0L1294.0,486.0L1159.0,486.0L1159.0,144.0L1077.0,144.0L1077.0,429.0Q1052.0,458.0 1020.0,477.0Q988.0,496.0 937.0,496.0Q869.0,496.0 825.5,459.5Q782.0,423.0 772.0,362.0Q793.0,379.0 817.5,388.5Q842.0,398.0 867.0,398.0Q926.0,398.0 961.5,363.0Q997.0,328.0 997.0,270.0Q997.0,206.0 960.0,169.0Q923.0,132.0 858.0,132.0ZM136.0,399.0Q136.0,362.0 158.5,337.0Q181.0,312.0 222.0,312.0Q259.0,312.0 282.0,335.5Q305.0,359.0 305.0,402.0Q305.0,427.0 297.0,451.0Q289.0,475.0 270.0,497.0L263.0,497.0Q209.0,497.0 172.5,473.0Q136.0,449.0 136.0,399.0ZM850.0,333.0Q808.0,333.0 770.0,292.0Q776.0,239.0 800.0,217.5Q824.0,196.0 858.0,196.0Q886.0,196.0 904.0,213.5Q922.0,231.0 922.0,263.0Q922.0,296.0 902.0,314.5Q882.0,333.0 850.0,333.0Z" transform="translate(1285, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(2825, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1879, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,152.0Q49.0,204.0 75.5,242.5Q102.0,281.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0L683.0,328.0L683.0,258.0L496.0,258.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Z" transform="translate(3895, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(4618, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4080, 870)"/>
<path d="M409.0,-321.0Q355.0,-321.0 309.0,-302.5Q263.0,-284.0 235.5,-245.0Q208.0,-206.0 208.0,-145.0Q208.0,-105.0 222.5,-62.0Q237.0,-19.0 268.0,19.0L342.0,-17.0Q317.0,-54.0 306.0,-83.0Q295.0,-112.0 295.0,-144.0Q295.0,-185.0 312.5,-208.0Q330.0,-231.0 357.5,-239.5Q385.0,-248.0 416.0,-248.0Q483.0,-248.0 522.5,-214.0Q562.0,-180.0 593.0,-128.0Q599.0,-118.0 607.0,-105.5Q615.0,-93.0 622.0,-83.0Q535.0,-51.0 500.5,5.0Q466.0,61.0 466.0,126.0Q466.0,199.0 509.5,259.5Q553.0,320.0 627.0,358.0L708.0,319.0Q696.0,294.0 689.5,271.5Q683.0,249.0 683.0,221.0Q683.0,186.0 699.5,160.5Q716.0,135.0 765.0,135.0Q806.0,135.0 827.0,166.5Q848.0,198.0 848.0,245.0Q848.0,322.0 805.0,377.0Q762.0,432.0 684.5,461.0Q607.0,490.0 503.0,490.0Q367.0,490.0 276.0,454.0Q185.0,418.0 149.0,352.0Q171.0,366.0 198.0,374.0Q225.0,382.0 250.0,382.0Q316.0,382.0 357.0,342.5Q398.0,303.0 398.0,229.0Q398.0,152.0 354.5,108.0Q311.0,64.0 234.0,64.0Q187.0,64.0 145.0,87.5Q103.0,111.0 77.5,156.5Q52.0,202.0 52.0,269.0Q52.0,335.0 81.5,387.0Q111.0,439.0 158.0,475.0Q225.0,526.0 310.5,546.0Q396.0,566.0 502.0,566.0Q629.0,566.0 719.5,531.5Q810.0,497.0 866.0,435.0Q901.0,398.0 917.0,350.5Q933.0,303.0 933.0,256.0Q933.0,223.0 925.5,189.0Q918.0,155.0 899.0,126.5Q880.0,98.0 848.0,81.0Q816.0,64.0 766.0,64.0Q724.0,64.0 688.5,78.0Q653.0,92.0 632.0,123.0Q611.0,154.0 611.0,203.0Q611.0,221.0 614.5,241.5Q618.0,262.0 626.0,279.0Q586.0,251.0 566.5,214.0Q547.0,177.0 547.0,134.0Q547.0,98.0 557.0,70.5Q567.0,43.0 586.0,23.0Q616.0,-9.0 663.5,-23.0Q711.0,-37.0 796.0,-37.0L876.0,-37.0L876.0,-108.0L790.0,-108.0Q763.0,-108.0 742.5,-107.0Q722.0,-106.0 706.0,-104.0Q697.0,-115.0 688.5,-129.0Q680.0,-143.0 674.0,-153.0Q633.0,-233.0 572.5,-277.0Q512.0,-321.0 409.0,-321.0ZM230.0,312.0Q203.0,312.0 178.0,300.0Q153.0,288.0 131.0,268.0Q131.0,199.0 162.0,165.5Q193.0,132.0 239.0,132.0Q274.0,132.0 295.0,155.0Q316.0,178.0 316.0,221.0Q316.0,265.0 292.5,288.5Q269.0,312.0 230.0,312.0ZM1230.0,-12.0Q1177.0,-12.0 1133.0,14.5Q1089.0,41.0 1063.5,97.0Q1038.0,153.0 1038.0,243.0Q1038.0,325.0 1062.5,385.5Q1087.0,446.0 1130.0,486.0Q1173.0,526.0 1227.0,546.0Q1281.0,566.0 1339.0,566.0Q1402.0,566.0 1447.5,548.5Q1493.0,531.0 1530.0,502.0L1530.0,554.0L2034.0,554.0L2034.0,482.0L1864.0,482.0L1864.0,0.0L1778.0,0.0L1778.0,482.0L1604.0,482.0L1604.0,0.0L1518.0,0.0L1518.0,407.0Q1484.0,448.0 1440.5,470.0Q1397.0,492.0 1336.0,492.0Q1248.0,492.0 1191.0,435.5Q1134.0,379.0 1121.0,290.0Q1147.0,307.0 1178.0,317.5Q1209.0,328.0 1242.0,328.0Q1314.0,328.0 1358.5,284.0Q1403.0,240.0 1403.0,165.0Q1403.0,82.0 1356.5,35.0Q1310.0,-12.0 1230.0,-12.0ZM1228.0,258.0Q1198.0,258.0 1170.0,245.5Q1142.0,233.0 1118.0,212.0Q1122.0,126.0 1155.0,91.0Q1188.0,56.0 1234.0,56.0Q1275.0,56.0 1298.0,81.5Q1321.0,107.0 1321.0,155.0Q1321.0,205.0 1295.0,231.5Q1269.0,258.0 1228.0,258.0Z" transform="translate(5258, 870)"/>
<path d="M450.0,477.0Q369.0,477.0 321.0,527.0Q273.0,577.0 273.0,661.0Q273.0,744.0 322.0,793.5Q371.0,843.0 448.0,843.0Q526.0,843.0 574.0,793.5Q622.0,744.0 622.0,661.0Q622.0,605.0 600.0,563.5Q578.0,522.0 539.0,499.5Q500.0,477.0 450.0,477.0ZM449.0,548.0Q487.0,548.0 513.5,576.5Q540.0,605.0 540.0,662.0Q540.0,718.0 513.0,745.0Q486.0,772.0 448.0,772.0Q408.0,772.0 381.5,744.0Q355.0,716.0 355.0,660.0Q355.0,603.0 382.0,575.5Q409.0,548.0 449.0,548.0ZM222.0,-11.0Q140.0,-11.0 92.5,39.5Q45.0,90.0 45.0,173.0Q45.0,256.0 94.0,305.5Q143.0,355.0 220.0,355.0Q298.0,355.0 346.0,305.5Q394.0,256.0 394.0,173.0Q394.0,117.0 372.0,75.5Q350.0,34.0 311.0,11.5Q272.0,-11.0 222.0,-11.0ZM679.0,-11.0Q598.0,-11.0 550.0,39.0Q502.0,89.0 502.0,173.0Q502.0,256.0 551.0,305.5Q600.0,355.0 677.0,355.0Q755.0,355.0 803.0,305.5Q851.0,256.0 851.0,173.0Q851.0,117.0 829.0,75.5Q807.0,34.0 768.0,11.5Q729.0,-11.0 679.0,-11.0ZM221.0,60.0Q259.0,60.0 285.5,88.5Q312.0,117.0 312.0,174.0Q312.0,230.0 285.0,257.0Q258.0,284.0 220.0,284.0Q180.0,284.0 153.5,256.0Q127.0,228.0 127.0,172.0Q127.0,115.0 154.0,87.5Q181.0,60.0 221.0,60.0ZM678.0,60.0Q716.0,60.0 742.5,88.5Q769.0,117.0 769.0,174.0Q769.0,230.0 741.5,257.0Q714.0,284.0 677.0,284.0Q637.0,284.0 610.5,256.0Q584.0,228.0 584.0,172.0Q584.0,115.0 611.0,87.5Q638.0,60.0 678.0,60.0Z" transform="translate(7250, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8078 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(466, 870)"/>
<path d="M298.0,566.0Q405.0,566.0 472.0,536.5Q539.0,507.0 570.5,457.5Q602.0,408.0 602.0,349.0Q602.0,271.0 565.0,228.0Q528.0,185.0 462.0,164.5Q396.0,144.0 309.0,135.0L229.0,127.0Q193.0,124.0 175.5,119.5Q158.0,115.0 152.5,109.5Q147.0,104.0 147.0,95.0Q147.0,83.0 155.0,77.5Q163.0,72.0 182.0,72.0L1494.0,72.0L1494.0,0.0L191.0,0.0Q121.0,0.0 91.5,27.0Q62.0,54.0 62.0,94.0Q62.0,139.0 98.5,164.0Q135.0,189.0 226.0,198.0L298.0,205.0Q368.0,212.0 411.0,226.0Q454.0,240.0 477.0,259.5Q500.0,279.0 508.0,302.0Q516.0,325.0 516.0,349.0Q516.0,408.0 472.5,448.0Q429.0,488.0 348.0,495.0Q364.0,474.0 373.5,448.0Q383.0,422.0 383.0,392.0Q383.0,327.0 341.0,285.5Q299.0,244.0 220.0,244.0Q175.0,244.0 138.0,263.0Q101.0,282.0 79.0,317.0Q57.0,352.0 57.0,398.0Q57.0,455.0 88.0,492.5Q119.0,530.0 173.5,548.0Q228.0,566.0 298.0,566.0ZM858.0,132.0Q815.0,132.0 777.5,152.0Q740.0,172.0 717.5,215.0Q695.0,258.0 695.0,325.0Q695.0,409.0 729.0,462.0Q763.0,515.0 817.0,540.5Q871.0,566.0 931.0,566.0Q985.0,566.0 1022.5,552.5Q1060.0,539.0 1090.0,516.0L1090.0,554.0L1494.0,554.0L1494.0,486.0L1376.0,486.0L1376.0,144.0L1294.0,144.0L1294.0,486.0L1159.0,486.0L1159.0,144.0L1077.0,144.0L1077.0,429.0Q1052.0,458.0 1020.0,477.0Q988.0,496.0 937.0,496.0Q869.0,496.0 825.5,459.5Q782.0,423.0 772.0,362.0Q793.0,379.0 817.5,388.5Q842.0,398.0 867.0,398.0Q926.0,398.0 961.5,363.0Q997.0,328.0 997.0,270.0Q997.0,206.0 960.0,169.0Q923.0,132.0 858.0,132.0ZM136.0,399.0Q136.0,362.0 158.5,337.0Q181.0,312.0 222.0,312.0Q259.0,312.0 282.0,335.5Q305.0,359.0 305.0,402.0Q305.0,427.0 297.0,451.0Q289.0,475.0 270.0,497.0L263.0,497.0Q209.0,497.0 172.5,473.0Q136.0,449.0 136.0,399.0ZM850.0,333.0Q808.0,333.0 770.0,292.0Q776.0,239.0 800.0,217.5Q824.0,196.0 858.0,196.0Q886.0,196.0 904.0,213.5Q922.0,231.0 922.0,263.0Q922.0,296.0 902.0,314.5Q882.0,333.0 850.0,333.0Z" transform="translate(1285, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(2825, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1879, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,152.0Q49.0,204.0 75.5,242.5Q102.0,281.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0L683.0,328.0L683.0,258.0L496.0,258.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Z" transform="translate(3850, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(4573, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4035, 870)"/>
<path d="M409.0,-321.0Q355.0,-321.0 309.0,-302.5Q263.0,-284.0 235.5,-245.0Q208.0,-206.0 208.0,-145.0Q208.0,-105.0 222.5,-62.0Q237.0,-19.0 268.0,19.0L342.0,-17.0Q317.0,-54.0 306.0,-83.0Q295.0,-112.0 295.0,-144.0Q295.0,-185.0 312.5,-208.0Q330.0,-231.0 357.5,-239.5Q385.0,-248.0 416.0,-248.0Q483.0,-248.0 522.5,-214.0Q562.0,-180.0 593.0,-128.0Q599.0,-118.0 607.0,-105.5Q615.0,-93.0 622.0,-83.0Q535.0,-51.0 500.5,5.0Q466.0,61.0 466.0,126.0Q466.0,199.0 509.5,259.5Q553.0,320.0 627.0,358.0L708.0,319.0Q696.0,294.0 689.5,271.5Q683.0,249.0 683.0,221.0Q683.0,186.0 699.5,160.5Q716.0,135.0 765.0,135.0Q806.0,135.0 827.0,166.5Q848.0,198.0 848.0,245.0Q848.0,322.0 805.0,377.0Q762.0,432.0 684.5,461.0Q607.0,490.0 503.0,490.0Q367.0,490.0 276.0,454.0Q185.0,418.0 149.0,352.0Q171.0,366.0 198.0,374.0Q225.0,382.0 250.0,382.0Q316.0,382.0 357.0,342.5Q398.0,303.0 398.0,229.0Q398.0,152.0 354.5,108.0Q311.0,64.0 234.0,64.0Q187.0,64.0 145.0,87.5Q103.0,111.0 77.5,156.5Q52.0,202.0 52.0,269.0Q52.0,335.0 81.5,387.0Q111.0,439.0 158.0,475.0Q225.0,526.0 310.5,546.0Q396.0,566.0 502.0,566.0Q629.0,566.0 719.5,531.5Q810.0,497.0 866.0,435.0Q901.0,398.0 917.0,350.5Q933.0,303.0 933.0,256.0Q933.0,223.0 925.5,189.0Q918.0,155.0 899.0,126.5Q880.0,98.0 848.0,81.0Q816.0,64.0 766.0,64.0Q724.0,64.0 688.5,78.0Q653.0,92.0 632.0,123.0Q611.0,154.0 611.0,203.0Q611.0,221.0 614.5,241.5Q618.0,262.0 626.0,279.0Q586.0,251.0 566.5,214.0Q547.0,177.0 547.0,134.0Q547.0,98.0 557.0,70.5Q567.0,43.0 586.0,23.0Q616.0,-9.0 663.5,-23.0Q711.0,-37.0 796.0,-37.0L876.0,-37.0L876.0,-108.0L790.0,-108.0Q763.0,-108.0 742.5,-107.0Q722.0,-106.0 706.0,-104.0Q697.0,-115.0 688.5,-129.0Q680.0,-143.0 674.0,-153.0Q633.0,-233.0 572.5,-277.0Q512.0,-321.0 409.0,-321.0ZM230.0,312.0Q203.0,312.0 178.0,300.0Q153.0,288.0 131.0,268.0Q131.0,199.0 162.0,165.5Q193.0,132.0 239.0,132.0Q274.0,132.0 295.0,155.0Q316.0,178.0 316.0,221.0Q316.0,265.0 292.5,288.5Q269.0,312.0 230.0,312.0ZM1230.0,-12.0Q1177.0,-12.0 1133.0,14.5Q1089.0,41.0 1063.5,97.0Q1038.0,153.0 1038.0,243.0Q1038.0,325.0 1062.5,385.5Q1087.0,446.0 1130.0,486.0Q1173.0,526.0 1227.0,546.0Q1281.0,566.0 1339.0,566.0Q1402.0,566.0 1447.5,548.5Q1493.0,531.0 1530.0,502.0L1530.0,554.0L2034.0,554.0L2034.0,482.0L1864.0,482.0L1864.0,0.0L1778.0,0.0L1778.0,482.0L1604.0,482.0L1604.0,0.0L1518.0,0.0L1518.0,407.0Q1484.0,448.0 1440.5,470.0Q1397.0,492.0 1336.0,492.0Q1248.0,492.0 1191.0,435.5Q1134.0,379.0 1121.0,290.0Q1147.0,307.0 1178.0,317.5Q1209.0,328.0 1242.0,328.0Q1314.0,328.0 1358.5,284.0Q1403.0,240.0 1403.0,165.0Q1403.0,82.0 1356.5,35.0Q1310.0,-12.0 1230.0,-12.0ZM1228.0,258.0Q1198.0,258.0 1170.0,245.5Q1142.0,233.0 1118.0,212.0Q1122.0,126.0 1155.0,91.0Q1188.0,56.0 1234.0,56.0Q1275.0,56.0 1298.0,81.5Q1321.0,107.0 1321.0,155.0Q1321.0,205.0 1295.0,231.5Q1269.0,258.0 1228.0,258.0Z" transform="translate(5190, 870)"/>
<path d="M450.0,477.0Q369.0,477.0 321.0,527.0Q273.0,577.0 273.0,661.0Q273.0,744.0 322.0,793.5Q371.0,843.0 448.0,843.0Q526.0,843.0 574.0,793.5Q622.0,744.0 622.0,661.0Q622.0,605.0 600.0,563.5Q578.0,522.0 539.0,499.5Q500.0,477.0 450.0,477.0ZM449.0,548.0Q487.0,548.0 513.5,576.5Q540.0,605.0 540.0,662.0Q540.0,718.0 513.0,745.0Q486.0,772.0 448.0,772.0Q408.0,772.0 381.5,744.0Q355.0,716.0 355.0,660.0Q355.0,603.0 382.0,575.5Q409.0,548.0 449.0,548.0ZM222.0,-11.0Q140.0,-11.0 92.5,39.5Q45.0,90.0 45.0,173.0Q45.0,256.0 94.0,305.5Q143.0,355.0 220.0,355.0Q298.0,355.0 346.0,305.5Q394.0,256.0 394.0,173.0Q394.0,117.0 372.0,75.5Q350.0,34.0 311.0,11.5Q272.0,-11.0 222.0,-11.0ZM679.0,-11.0Q598.0,-11.0 550.0,39.0Q502.0,89.0 502.0,173.0Q502.0,256.0 551.0,305.5Q600.0,355.0 677.0,355.0Q755.0,355.0 803.0,305.5Q851.0,256.0 851.0,173.0Q851.0,117.0 829.0,75.5Q807.0,34.0 768.0,11.5Q729.0,-11.0 679.0,-11.0ZM221.0,60.0Q259.0,60.0 285.5,88.5Q312.0,117.0 312.0,174.0Q312.0,230.0 285.0,257.0Q258.0,284.0 220.0,284.0Q180.0,284.0 153.5,256.0Q127.0,228.0 127.0,172.0Q127.0,115.0 154.0,87.5Q181.0,60.0 221.0,60.0ZM678.0,60.0Q716.0,60.0 742.5,88.5Q769.0,117.0 769.0,174.0Q769.0,230.0 741.5,257.0Q714.0,284.0 677.0,284.0Q637.0,284.0 610.5,256.0Q584.0,228.0 584.0,172.0Q584.0,115.0 611.0,87.5Q638.0,60.0 678.0,60.0Z" transform="translate(7182, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ணைடுஂஸாஂஹௗஂ</span> (Added by SIESTA)</li>


<pre>Expected: aivowelsigntamil=0+1160|nnatamil=0+1633|ttauvowelsigntamil=2+1015|anusvaratamil=2@-88,0+264|satamil=5+1285|aavowelsigntamil=5+609|anusvaratamil=5@-1428,0+0|hatamil=8+1619|aulengthmarktamil=8+1070|anusvaratamil=8@-2053,0+0</pre>



<pre>Got     : aivowelsigntamil=0+1160|nnatamil=0+1633|ttauvowelsigntamil=2+1015|anusvaratamil=2+352|satamil=5+1285|aavowelsigntamil=5+640|anusvaratamil=5@-1459,0+0|hatamil=8+1619|aulengthmarktamil=8+1070|anusvaratamil=8@-2053,0+0</pre>



<pre>                                                                                           ^^^^^^^^^^                                    ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8774 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 222.5,526.5Q301.0,566.0 408.0,566.0Q476.0,566.0 535.0,551.0Q594.0,536.0 648.0,504.0Q686.0,534.0 731.5,550.0Q777.0,566.0 828.0,566.0Q922.0,566.0 981.0,526.5Q1040.0,487.0 1068.0,422.0Q1096.0,357.0 1096.0,280.0Q1096.0,211.0 1082.5,157.5Q1069.0,104.0 1048.5,62.5Q1028.0,21.0 1005.0,-12.0L933.0,32.0Q965.0,77.0 986.5,134.5Q1008.0,192.0 1008.0,276.0Q1008.0,374.0 959.0,433.0Q910.0,492.0 821.0,492.0Q752.0,492.0 702.0,460.0Q762.0,409.0 793.5,338.5Q825.0,268.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,272.0 523.0,336.0Q549.0,400.0 592.0,451.0Q549.0,474.0 500.5,483.0Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,252.0 716.5,309.0Q693.0,366.0 648.0,410.0Q613.0,364.0 597.0,308.5Q581.0,253.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 254.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q477.0,566.0 536.5,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q930.0,566.0 981.0,550.0Q1032.0,534.0 1077.0,502.0Q1105.0,518.0 1138.5,529.5Q1172.0,541.0 1218.5,547.5Q1265.0,554.0 1333.0,554.0L1631.0,554.0L1631.0,482.0L1461.0,482.0L1461.0,0.0L1375.0,0.0L1375.0,482.0L1310.0,482.0Q1257.0,482.0 1215.5,476.5Q1174.0,471.0 1135.0,452.0Q1184.0,403.0 1212.0,336.0Q1240.0,269.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,262.0 936.0,328.5Q960.0,395.0 1016.0,454.0Q980.0,475.0 942.5,484.0Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.0,88.0Q1038.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,255.0 1130.5,314.5Q1106.0,374.0 1071.0,410.0Q1034.0,374.0 1015.0,314.5Q996.0,255.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1160, 870)"/>
<path d="M355.0,0.0L355.0,554.0L442.0,554.0L442.0,285.0Q460.0,297.0 488.5,308.0Q517.0,319.0 553.0,319.0Q634.0,319.0 685.0,257.5Q736.0,196.0 736.0,62.0Q736.0,-39.0 712.5,-108.0Q689.0,-177.0 646.5,-218.5Q604.0,-260.0 547.5,-278.5Q491.0,-297.0 424.0,-297.0Q315.0,-297.0 235.5,-237.0Q156.0,-177.0 113.5,-63.0Q71.0,51.0 71.0,214.0L71.0,242.0Q71.0,393.0 108.5,506.0Q146.0,619.0 212.0,693.5Q278.0,768.0 366.5,805.5Q455.0,843.0 557.0,843.0Q639.0,843.0 699.5,822.0Q760.0,801.0 804.0,763.0Q874.0,705.0 901.0,612.5Q928.0,520.0 928.0,377.0L928.0,0.0L842.0,0.0L842.0,334.0Q842.0,418.0 834.0,491.5Q826.0,565.0 802.0,623.0Q778.0,681.0 730.0,717.0Q699.0,741.0 655.5,754.5Q612.0,768.0 554.0,768.0Q479.0,768.0 408.0,738.5Q337.0,709.0 280.5,645.0Q224.0,581.0 190.5,478.0Q157.0,375.0 157.0,229.0Q157.0,-6.0 227.5,-114.0Q298.0,-222.0 421.0,-222.0Q539.0,-222.0 593.5,-151.0Q648.0,-80.0 648.0,53.0Q648.0,163.0 619.0,205.0Q590.0,247.0 538.0,247.0Q510.0,247.0 486.0,236.0Q462.0,225.0 442.0,211.0L442.0,0.0L355.0,0.0Z" transform="translate(2793, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(3808, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(4160, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(5445, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4626, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L836.0,72.0L836.0,341.0Q836.0,414.0 847.0,453.5Q858.0,493.0 889.0,524.0Q931.0,566.0 1005.0,566.0Q1105.0,566.0 1149.0,472.0Q1170.0,513.0 1212.5,539.5Q1255.0,566.0 1320.0,566.0Q1434.0,566.0 1494.5,482.0Q1555.0,398.0 1555.0,244.0Q1555.0,122.0 1524.0,44.5Q1493.0,-33.0 1440.0,-77.0Q1382.0,-124.0 1304.0,-140.0Q1226.0,-156.0 1138.0,-156.0L272.0,-156.0Q230.0,-156.0 207.0,-162.0Q184.0,-168.0 167.0,-179.0Q151.0,-190.0 142.0,-210.0Q133.0,-230.0 133.0,-263.0Q133.0,-293.0 136.0,-317.0L54.0,-321.0Q51.0,-303.0 49.0,-281.5Q47.0,-260.0 47.0,-243.0Q47.0,-199.0 63.0,-168.5Q79.0,-138.0 104.0,-119.0Q130.0,-100.0 162.5,-92.0Q195.0,-84.0 245.0,-84.0L1116.0,-84.0Q1209.0,-84.0 1275.0,-70.5Q1341.0,-57.0 1383.5,-22.0Q1426.0,13.0 1446.0,78.5Q1466.0,144.0 1466.0,247.0Q1466.0,338.0 1446.5,392.0Q1427.0,446.0 1392.5,470.0Q1358.0,494.0 1314.0,494.0Q1287.0,494.0 1264.0,485.5Q1241.0,477.0 1224.0,458.0Q1204.0,435.0 1196.0,404.0Q1188.0,373.0 1188.0,319.0L1188.0,0.0L1102.0,0.0L1102.0,321.0Q1102.0,370.0 1097.0,404.5Q1092.0,439.0 1077.0,461.0Q1067.0,476.0 1051.0,485.0Q1035.0,494.0 1012.0,494.0Q989.0,494.0 973.5,485.5Q958.0,477.0 947.0,463.0Q931.0,441.0 926.5,406.5Q922.0,372.0 922.0,328.0L922.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(6085, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(7704, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(6721, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8655 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 222.5,526.5Q301.0,566.0 408.0,566.0Q476.0,566.0 535.0,551.0Q594.0,536.0 648.0,504.0Q686.0,534.0 731.5,550.0Q777.0,566.0 828.0,566.0Q922.0,566.0 981.0,526.5Q1040.0,487.0 1068.0,422.0Q1096.0,357.0 1096.0,280.0Q1096.0,211.0 1082.5,157.5Q1069.0,104.0 1048.5,62.5Q1028.0,21.0 1005.0,-12.0L933.0,32.0Q965.0,77.0 986.5,134.5Q1008.0,192.0 1008.0,276.0Q1008.0,374.0 959.0,433.0Q910.0,492.0 821.0,492.0Q752.0,492.0 702.0,460.0Q762.0,409.0 793.5,338.5Q825.0,268.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,272.0 523.0,336.0Q549.0,400.0 592.0,451.0Q549.0,474.0 500.5,483.0Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,252.0 716.5,309.0Q693.0,366.0 648.0,410.0Q613.0,364.0 597.0,308.5Q581.0,253.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 254.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q477.0,566.0 536.5,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q930.0,566.0 981.0,550.0Q1032.0,534.0 1077.0,502.0Q1105.0,518.0 1138.5,529.5Q1172.0,541.0 1218.5,547.5Q1265.0,554.0 1333.0,554.0L1631.0,554.0L1631.0,482.0L1461.0,482.0L1461.0,0.0L1375.0,0.0L1375.0,482.0L1310.0,482.0Q1257.0,482.0 1215.5,476.5Q1174.0,471.0 1135.0,452.0Q1184.0,403.0 1212.0,336.0Q1240.0,269.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,262.0 936.0,328.5Q960.0,395.0 1016.0,454.0Q980.0,475.0 942.5,484.0Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.0,88.0Q1038.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,255.0 1130.5,314.5Q1106.0,374.0 1071.0,410.0Q1034.0,374.0 1015.0,314.5Q996.0,255.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1160, 870)"/>
<path d="M355.0,0.0L355.0,554.0L442.0,554.0L442.0,285.0Q460.0,297.0 488.5,308.0Q517.0,319.0 553.0,319.0Q634.0,319.0 685.0,257.5Q736.0,196.0 736.0,62.0Q736.0,-39.0 712.5,-108.0Q689.0,-177.0 646.5,-218.5Q604.0,-260.0 547.5,-278.5Q491.0,-297.0 424.0,-297.0Q315.0,-297.0 235.5,-237.0Q156.0,-177.0 113.5,-63.0Q71.0,51.0 71.0,214.0L71.0,242.0Q71.0,393.0 108.5,506.0Q146.0,619.0 212.0,693.5Q278.0,768.0 366.5,805.5Q455.0,843.0 557.0,843.0Q639.0,843.0 699.5,822.0Q760.0,801.0 804.0,763.0Q874.0,705.0 901.0,612.5Q928.0,520.0 928.0,377.0L928.0,0.0L842.0,0.0L842.0,334.0Q842.0,418.0 834.0,491.5Q826.0,565.0 802.0,623.0Q778.0,681.0 730.0,717.0Q699.0,741.0 655.5,754.5Q612.0,768.0 554.0,768.0Q479.0,768.0 408.0,738.5Q337.0,709.0 280.5,645.0Q224.0,581.0 190.5,478.0Q157.0,375.0 157.0,229.0Q157.0,-6.0 227.5,-114.0Q298.0,-222.0 421.0,-222.0Q539.0,-222.0 593.5,-151.0Q648.0,-80.0 648.0,53.0Q648.0,163.0 619.0,205.0Q590.0,247.0 538.0,247.0Q510.0,247.0 486.0,236.0Q462.0,225.0 442.0,211.0L442.0,0.0L355.0,0.0Z" transform="translate(2793, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(3720, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(4072, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(5357, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4538, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L836.0,72.0L836.0,341.0Q836.0,414.0 847.0,453.5Q858.0,493.0 889.0,524.0Q931.0,566.0 1005.0,566.0Q1105.0,566.0 1149.0,472.0Q1170.0,513.0 1212.5,539.5Q1255.0,566.0 1320.0,566.0Q1434.0,566.0 1494.5,482.0Q1555.0,398.0 1555.0,244.0Q1555.0,122.0 1524.0,44.5Q1493.0,-33.0 1440.0,-77.0Q1382.0,-124.0 1304.0,-140.0Q1226.0,-156.0 1138.0,-156.0L272.0,-156.0Q230.0,-156.0 207.0,-162.0Q184.0,-168.0 167.0,-179.0Q151.0,-190.0 142.0,-210.0Q133.0,-230.0 133.0,-263.0Q133.0,-293.0 136.0,-317.0L54.0,-321.0Q51.0,-303.0 49.0,-281.5Q47.0,-260.0 47.0,-243.0Q47.0,-199.0 63.0,-168.5Q79.0,-138.0 104.0,-119.0Q130.0,-100.0 162.5,-92.0Q195.0,-84.0 245.0,-84.0L1116.0,-84.0Q1209.0,-84.0 1275.0,-70.5Q1341.0,-57.0 1383.5,-22.0Q1426.0,13.0 1446.0,78.5Q1466.0,144.0 1466.0,247.0Q1466.0,338.0 1446.5,392.0Q1427.0,446.0 1392.5,470.0Q1358.0,494.0 1314.0,494.0Q1287.0,494.0 1264.0,485.5Q1241.0,477.0 1224.0,458.0Q1204.0,435.0 1196.0,404.0Q1188.0,373.0 1188.0,319.0L1188.0,0.0L1102.0,0.0L1102.0,321.0Q1102.0,370.0 1097.0,404.5Q1092.0,439.0 1077.0,461.0Q1067.0,476.0 1051.0,485.0Q1035.0,494.0 1012.0,494.0Q989.0,494.0 973.5,485.5Q958.0,477.0 947.0,463.0Q931.0,441.0 926.5,406.5Q922.0,372.0 922.0,328.0L922.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(5966, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(7585, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(6602, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ழாஂலூஂ</span> (Added by SIESTA)</li>


<pre>Expected: lllatamil=0+858|aavowelsigntamil=0+609|anusvaratamil=0@-1214,0+0|lauuvowelsigntamil=3+1624|anusvaratamil=3@-988,0+0</pre>



<pre>Got     : lllatamil=0+858|aavowelsigntamil=0+640|anusvaratamil=0@-1245,0+0|lauuvowelsigntamil=3+1624|anusvaratamil=3@-988,0+0</pre>



<pre>                                               +                    +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3122 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M220.0,-61.0Q237.0,-61.0 255.5,-62.5Q274.0,-64.0 290.0,-66.0L282.0,-133.0Q261.0,-130.0 233.0,-130.0Q196.0,-130.0 172.5,-142.5Q149.0,-155.0 149.0,-185.0Q149.0,-212.0 168.5,-226.5Q188.0,-241.0 217.5,-246.0Q247.0,-251.0 276.0,-251.0L301.0,-251.0Q378.0,-251.0 417.5,-224.5Q457.0,-198.0 479.0,-152.0Q482.0,-146.0 485.0,-142.0Q448.0,-125.0 425.0,-91.0Q402.0,-57.0 400.0,0.0L88.0,0.0L88.0,554.0L174.0,554.0L174.0,72.0L400.0,72.0L400.0,355.0Q400.0,417.0 411.5,453.5Q423.0,490.0 445.0,515.0Q468.0,540.0 500.0,553.0Q532.0,566.0 580.0,566.0Q655.0,566.0 703.0,527.5Q751.0,489.0 774.0,420.5Q797.0,352.0 797.0,262.0Q797.0,192.0 782.0,142.0Q767.0,92.0 734.0,60.0Q699.0,26.0 648.5,13.0Q598.0,0.0 512.0,0.0L485.0,0.0Q486.0,-29.0 495.5,-49.5Q505.0,-70.0 527.0,-81.0Q541.0,-87.0 560.5,-90.5Q580.0,-94.0 611.0,-94.0L739.0,-94.0L739.0,-166.0L560.0,-166.0Q556.0,-173.0 552.0,-182.0Q530.0,-224.0 499.5,-255.5Q469.0,-287.0 420.5,-304.0Q372.0,-321.0 294.0,-321.0L269.0,-321.0Q223.0,-321.0 180.0,-310.5Q137.0,-300.0 111.0,-282.0Q92.0,-268.0 77.5,-244.0Q63.0,-220.0 63.0,-186.0Q63.0,-128.0 106.5,-94.5Q150.0,-61.0 220.0,-61.0ZM578.0,494.0Q561.0,494.0 545.0,488.5Q529.0,483.0 518.0,471.0Q502.0,453.0 494.0,426.5Q486.0,400.0 486.0,338.0L486.0,72.0L533.0,72.0Q601.0,72.0 639.0,91.0Q677.0,110.0 693.0,153.0Q709.0,196.0 709.0,267.0Q709.0,331.0 695.5,382.0Q682.0,433.0 653.5,463.5Q625.0,494.0 578.0,494.0Z" transform="translate(0, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(858, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(253, 870)"/>
<path d="M38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.5,-88.5Q122.0,-84.0 165.0,-84.0L653.0,-84.0Q676.0,-47.0 686.0,-5.0Q631.0,5.0 597.0,38.0Q531.0,99.0 530.0,250.0Q530.0,286.0 526.0,324.0Q522.0,362.0 510.0,396.5Q498.0,431.0 472.0,455.0Q452.0,473.0 424.0,482.5Q396.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q407.0,566.0 457.0,553.0Q507.0,540.0 545.0,502.0Q587.0,461.0 602.0,402.0Q617.0,343.0 617.0,252.0Q617.0,200.0 625.0,160.5Q633.0,121.0 658.0,95.0Q688.0,62.0 744.0,62.0Q777.0,62.0 804.0,78.0Q831.0,94.0 847.0,132.0Q863.0,170.0 863.0,237.0Q863.0,336.0 827.5,412.5Q792.0,489.0 738.0,547.0L816.0,600.0Q878.0,521.0 914.0,434.0Q950.0,347.0 950.0,244.0Q950.0,129.0 906.0,67.0Q862.0,5.0 777.0,-6.0Q767.0,-47.0 751.0,-84.0L1086.0,-84.0L1086.0,554.0L1607.0,554.0L1607.0,482.0L1433.0,482.0L1433.0,-156.0L1347.0,-156.0L1347.0,482.0L1172.0,482.0L1172.0,-156.0L711.0,-156.0Q588.0,-321.0 304.0,-321.0L284.0,-321.0Q223.0,-321.0 166.5,-305.5Q110.0,-290.0 74.0,-256.0Q38.0,-222.0 38.0,-167.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM306.0,-248.0Q396.0,-248.0 473.5,-228.0Q551.0,-208.0 608.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-209.0 165.0,-228.5Q209.0,-248.0 293.0,-248.0L306.0,-248.0Z" transform="translate(1498, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2134, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3091 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M220.0,-61.0Q237.0,-61.0 255.5,-62.5Q274.0,-64.0 290.0,-66.0L282.0,-133.0Q261.0,-130.0 233.0,-130.0Q196.0,-130.0 172.5,-142.5Q149.0,-155.0 149.0,-185.0Q149.0,-212.0 168.5,-226.5Q188.0,-241.0 217.5,-246.0Q247.0,-251.0 276.0,-251.0L301.0,-251.0Q378.0,-251.0 417.5,-224.5Q457.0,-198.0 479.0,-152.0Q482.0,-146.0 485.0,-142.0Q448.0,-125.0 425.0,-91.0Q402.0,-57.0 400.0,0.0L88.0,0.0L88.0,554.0L174.0,554.0L174.0,72.0L400.0,72.0L400.0,355.0Q400.0,417.0 411.5,453.5Q423.0,490.0 445.0,515.0Q468.0,540.0 500.0,553.0Q532.0,566.0 580.0,566.0Q655.0,566.0 703.0,527.5Q751.0,489.0 774.0,420.5Q797.0,352.0 797.0,262.0Q797.0,192.0 782.0,142.0Q767.0,92.0 734.0,60.0Q699.0,26.0 648.5,13.0Q598.0,0.0 512.0,0.0L485.0,0.0Q486.0,-29.0 495.5,-49.5Q505.0,-70.0 527.0,-81.0Q541.0,-87.0 560.5,-90.5Q580.0,-94.0 611.0,-94.0L739.0,-94.0L739.0,-166.0L560.0,-166.0Q556.0,-173.0 552.0,-182.0Q530.0,-224.0 499.5,-255.5Q469.0,-287.0 420.5,-304.0Q372.0,-321.0 294.0,-321.0L269.0,-321.0Q223.0,-321.0 180.0,-310.5Q137.0,-300.0 111.0,-282.0Q92.0,-268.0 77.5,-244.0Q63.0,-220.0 63.0,-186.0Q63.0,-128.0 106.5,-94.5Q150.0,-61.0 220.0,-61.0ZM578.0,494.0Q561.0,494.0 545.0,488.5Q529.0,483.0 518.0,471.0Q502.0,453.0 494.0,426.5Q486.0,400.0 486.0,338.0L486.0,72.0L533.0,72.0Q601.0,72.0 639.0,91.0Q677.0,110.0 693.0,153.0Q709.0,196.0 709.0,267.0Q709.0,331.0 695.5,382.0Q682.0,433.0 653.5,463.5Q625.0,494.0 578.0,494.0Z" transform="translate(0, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(858, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(253, 870)"/>
<path d="M38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.5,-88.5Q122.0,-84.0 165.0,-84.0L653.0,-84.0Q676.0,-47.0 686.0,-5.0Q631.0,5.0 597.0,38.0Q531.0,99.0 530.0,250.0Q530.0,286.0 526.0,324.0Q522.0,362.0 510.0,396.5Q498.0,431.0 472.0,455.0Q452.0,473.0 424.0,482.5Q396.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q407.0,566.0 457.0,553.0Q507.0,540.0 545.0,502.0Q587.0,461.0 602.0,402.0Q617.0,343.0 617.0,252.0Q617.0,200.0 625.0,160.5Q633.0,121.0 658.0,95.0Q688.0,62.0 744.0,62.0Q777.0,62.0 804.0,78.0Q831.0,94.0 847.0,132.0Q863.0,170.0 863.0,237.0Q863.0,336.0 827.5,412.5Q792.0,489.0 738.0,547.0L816.0,600.0Q878.0,521.0 914.0,434.0Q950.0,347.0 950.0,244.0Q950.0,129.0 906.0,67.0Q862.0,5.0 777.0,-6.0Q767.0,-47.0 751.0,-84.0L1086.0,-84.0L1086.0,554.0L1607.0,554.0L1607.0,482.0L1433.0,482.0L1433.0,-156.0L1347.0,-156.0L1347.0,482.0L1172.0,482.0L1172.0,-156.0L711.0,-156.0Q588.0,-321.0 304.0,-321.0L284.0,-321.0Q223.0,-321.0 166.5,-305.5Q110.0,-290.0 74.0,-256.0Q38.0,-222.0 38.0,-167.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM306.0,-248.0Q396.0,-248.0 473.5,-228.0Q551.0,-208.0 608.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-209.0 165.0,-228.5Q209.0,-248.0 293.0,-248.0L306.0,-248.0Z" transform="translate(1467, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2103, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ரஃிஂயாஂஉூஂ</span> (Added by SIESTA)</li>


<pre>Expected: ratamil=0+581|visargatamil=1+896|uni25CC=1+562|ivowelsigntamil=1+262|anusvaratamil=1@-88,0+264|yatamil=4+963|aavowelsigntamil=4+640|anusvaratamil=4@-1298,0+0|utamil=7+1067|uuvowelsigntamil=7+844|anusvaratamil=7@-1554,0+0</pre>



<pre>Got     : ratamil=0+581|visargatamil=1+896|uni25CC=1+562|ivowelsigntamil=1+262|anusvaratamil=1@-688,0+352|yatamil=4+963|aavowelsigntamil=4+640|anusvaratamil=4@-1298,0+0|utamil=7+1067|uuvowelsigntamil=7+844|anusvaratamil=7@-1554,0+0</pre>



<pre>                                                                                                     ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6167 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M231.0,-212.0L174.0,-159.0L367.0,24.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L231.0,-212.0Z" transform="translate(0, 870)"/>
<path d="M450.0,477.0Q369.0,477.0 321.0,527.0Q273.0,577.0 273.0,661.0Q273.0,744.0 322.0,793.5Q371.0,843.0 448.0,843.0Q526.0,843.0 574.0,793.5Q622.0,744.0 622.0,661.0Q622.0,605.0 600.0,563.5Q578.0,522.0 539.0,499.5Q500.0,477.0 450.0,477.0ZM449.0,548.0Q487.0,548.0 513.5,576.5Q540.0,605.0 540.0,662.0Q540.0,718.0 513.0,745.0Q486.0,772.0 448.0,772.0Q408.0,772.0 381.5,744.0Q355.0,716.0 355.0,660.0Q355.0,603.0 382.0,575.5Q409.0,548.0 449.0,548.0ZM222.0,-11.0Q140.0,-11.0 92.5,39.5Q45.0,90.0 45.0,173.0Q45.0,256.0 94.0,305.5Q143.0,355.0 220.0,355.0Q298.0,355.0 346.0,305.5Q394.0,256.0 394.0,173.0Q394.0,117.0 372.0,75.5Q350.0,34.0 311.0,11.5Q272.0,-11.0 222.0,-11.0ZM679.0,-11.0Q598.0,-11.0 550.0,39.0Q502.0,89.0 502.0,173.0Q502.0,256.0 551.0,305.5Q600.0,355.0 677.0,355.0Q755.0,355.0 803.0,305.5Q851.0,256.0 851.0,173.0Q851.0,117.0 829.0,75.5Q807.0,34.0 768.0,11.5Q729.0,-11.0 679.0,-11.0ZM221.0,60.0Q259.0,60.0 285.5,88.5Q312.0,117.0 312.0,174.0Q312.0,230.0 285.0,257.0Q258.0,284.0 220.0,284.0Q180.0,284.0 153.5,256.0Q127.0,228.0 127.0,172.0Q127.0,115.0 154.0,87.5Q181.0,60.0 221.0,60.0ZM678.0,60.0Q716.0,60.0 742.5,88.5Q769.0,117.0 769.0,174.0Q769.0,230.0 741.5,257.0Q714.0,284.0 677.0,284.0Q637.0,284.0 610.5,256.0Q584.0,228.0 584.0,172.0Q584.0,115.0 611.0,87.5Q638.0,60.0 678.0,60.0Z" transform="translate(581, 870)"/>
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(1477, 870)"/>
<path d="M-79.0,843.0Q30.0,843.0 98.0,773.0Q121.0,750.0 138.0,715.5Q155.0,681.0 164.5,626.5Q174.0,572.0 174.0,489.0L174.0,0.0L88.0,0.0L88.0,471.0Q88.0,543.0 81.5,590.0Q75.0,637.0 63.0,667.5Q51.0,698.0 34.0,718.0Q13.0,744.0 -16.5,756.0Q-46.0,768.0 -81.0,768.0Q-146.0,768.0 -180.5,731.5Q-215.0,695.0 -215.0,637.0Q-215.0,609.0 -207.0,576.5Q-199.0,544.0 -182.0,515.0L-273.0,515.0Q-286.0,545.0 -293.5,575.0Q-301.0,605.0 -301.0,636.0Q-301.0,708.0 -270.0,753.5Q-239.0,799.0 -188.5,821.0Q-138.0,843.0 -79.0,843.0Z" transform="translate(2039, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1613, 870)"/>
<path d="M240.0,-11.0Q168.0,-11.0 129.0,36.0Q118.0,51.0 108.5,70.0Q99.0,89.0 93.5,120.0Q88.0,151.0 88.0,202.0L88.0,554.0L174.0,554.0L174.0,223.0Q174.0,177.0 178.0,139.5Q182.0,102.0 202.0,82.0Q212.0,72.0 225.5,66.5Q239.0,61.0 258.0,61.0Q285.0,61.0 309.0,74.0Q333.0,87.0 354.0,116.0L354.0,554.0L440.0,554.0L440.0,72.0L789.0,72.0L789.0,554.0L875.0,554.0L875.0,0.0L354.0,0.0L354.0,35.0Q335.0,17.0 307.0,3.0Q279.0,-11.0 240.0,-11.0Z" transform="translate(2653, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(3616, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2958, 870)"/>
<path d="M298.0,566.0Q405.0,566.0 472.0,536.5Q539.0,507.0 570.5,457.5Q602.0,408.0 602.0,349.0Q602.0,271.0 565.0,228.0Q528.0,185.0 462.0,164.5Q396.0,144.0 309.0,135.0L229.0,127.0Q174.0,122.0 160.0,115.0Q146.0,108.0 146.0,95.0Q146.0,72.0 182.0,72.0L1050.0,72.0L1050.0,0.0L191.0,0.0Q121.0,0.0 91.5,27.0Q62.0,54.0 62.0,94.0Q62.0,139.0 98.5,164.0Q135.0,189.0 226.0,198.0L303.0,205.0Q394.0,214.0 439.5,235.5Q485.0,257.0 500.5,287.0Q516.0,317.0 516.0,349.0Q516.0,408.0 472.5,448.0Q429.0,488.0 348.0,495.0Q364.0,474.0 373.5,448.0Q383.0,422.0 383.0,392.0Q383.0,327.0 341.5,285.5Q300.0,244.0 220.0,244.0Q148.0,244.0 102.5,286.0Q57.0,328.0 57.0,398.0Q57.0,455.0 88.0,492.5Q119.0,530.0 173.5,548.0Q228.0,566.0 298.0,566.0ZM136.0,399.0Q136.0,362.0 157.0,337.0Q178.0,312.0 222.0,312.0Q260.0,312.0 282.5,335.5Q305.0,359.0 305.0,402.0Q305.0,427.0 297.0,451.0Q289.0,475.0 270.0,497.0L263.0,497.0Q209.0,497.0 172.5,473.0Q136.0,449.0 136.0,399.0Z" transform="translate(4256, 870)"/>
<path d="M402.0,13.0Q298.0,13.0 214.5,40.5Q131.0,68.0 78.0,105.0L120.0,174.0Q166.0,140.0 235.5,113.0Q305.0,86.0 399.0,86.0Q485.0,86.0 553.0,117.0Q621.0,148.0 660.5,218.5Q700.0,289.0 700.0,408.0Q700.0,490.0 671.5,553.0Q643.0,616.0 587.5,652.5Q532.0,689.0 450.0,689.0Q363.0,689.0 307.0,650.0Q251.0,611.0 227.0,554.0L248.0,554.0Q316.0,554.0 356.5,543.0Q397.0,532.0 425.0,509.0Q451.0,487.0 467.0,455.5Q483.0,424.0 483.0,378.0Q483.0,304.0 435.5,260.5Q388.0,217.0 314.0,217.0Q244.0,217.0 202.0,246.5Q160.0,276.0 141.0,323.5Q122.0,371.0 122.0,424.0Q122.0,453.0 127.0,482.0L-219.0,482.0L-219.0,554.0L138.0,554.0Q159.0,615.0 201.5,662.5Q244.0,710.0 307.0,737.0Q370.0,764.0 453.0,764.0Q559.0,764.0 633.5,719.0Q708.0,674.0 747.5,594.0Q787.0,514.0 787.0,408.0Q787.0,266.0 736.5,179.0Q686.0,92.0 599.0,52.5Q512.0,13.0 402.0,13.0ZM207.0,419.0Q207.0,352.0 234.0,321.0Q261.0,290.0 310.0,290.0Q354.0,290.0 376.0,315.5Q398.0,341.0 398.0,379.0Q398.0,404.0 389.0,422.5Q380.0,441.0 364.0,454.0Q348.0,468.0 321.0,475.0Q294.0,482.0 230.0,482.0L212.0,482.0Q207.0,451.0 207.0,419.0Z" transform="translate(5323, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4613, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6079 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M231.0,-212.0L174.0,-159.0L367.0,24.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L231.0,-212.0Z" transform="translate(0, 870)"/>
<path d="M450.0,477.0Q369.0,477.0 321.0,527.0Q273.0,577.0 273.0,661.0Q273.0,744.0 322.0,793.5Q371.0,843.0 448.0,843.0Q526.0,843.0 574.0,793.5Q622.0,744.0 622.0,661.0Q622.0,605.0 600.0,563.5Q578.0,522.0 539.0,499.5Q500.0,477.0 450.0,477.0ZM449.0,548.0Q487.0,548.0 513.5,576.5Q540.0,605.0 540.0,662.0Q540.0,718.0 513.0,745.0Q486.0,772.0 448.0,772.0Q408.0,772.0 381.5,744.0Q355.0,716.0 355.0,660.0Q355.0,603.0 382.0,575.5Q409.0,548.0 449.0,548.0ZM222.0,-11.0Q140.0,-11.0 92.5,39.5Q45.0,90.0 45.0,173.0Q45.0,256.0 94.0,305.5Q143.0,355.0 220.0,355.0Q298.0,355.0 346.0,305.5Q394.0,256.0 394.0,173.0Q394.0,117.0 372.0,75.5Q350.0,34.0 311.0,11.5Q272.0,-11.0 222.0,-11.0ZM679.0,-11.0Q598.0,-11.0 550.0,39.0Q502.0,89.0 502.0,173.0Q502.0,256.0 551.0,305.5Q600.0,355.0 677.0,355.0Q755.0,355.0 803.0,305.5Q851.0,256.0 851.0,173.0Q851.0,117.0 829.0,75.5Q807.0,34.0 768.0,11.5Q729.0,-11.0 679.0,-11.0ZM221.0,60.0Q259.0,60.0 285.5,88.5Q312.0,117.0 312.0,174.0Q312.0,230.0 285.0,257.0Q258.0,284.0 220.0,284.0Q180.0,284.0 153.5,256.0Q127.0,228.0 127.0,172.0Q127.0,115.0 154.0,87.5Q181.0,60.0 221.0,60.0ZM678.0,60.0Q716.0,60.0 742.5,88.5Q769.0,117.0 769.0,174.0Q769.0,230.0 741.5,257.0Q714.0,284.0 677.0,284.0Q637.0,284.0 610.5,256.0Q584.0,228.0 584.0,172.0Q584.0,115.0 611.0,87.5Q638.0,60.0 678.0,60.0Z" transform="translate(581, 870)"/>
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(1477, 870)"/>
<path d="M-79.0,843.0Q30.0,843.0 98.0,773.0Q121.0,750.0 138.0,715.5Q155.0,681.0 164.5,626.5Q174.0,572.0 174.0,489.0L174.0,0.0L88.0,0.0L88.0,471.0Q88.0,543.0 81.5,590.0Q75.0,637.0 63.0,667.5Q51.0,698.0 34.0,718.0Q13.0,744.0 -16.5,756.0Q-46.0,768.0 -81.0,768.0Q-146.0,768.0 -180.5,731.5Q-215.0,695.0 -215.0,637.0Q-215.0,609.0 -207.0,576.5Q-199.0,544.0 -182.0,515.0L-273.0,515.0Q-286.0,545.0 -293.5,575.0Q-301.0,605.0 -301.0,636.0Q-301.0,708.0 -270.0,753.5Q-239.0,799.0 -188.5,821.0Q-138.0,843.0 -79.0,843.0Z" transform="translate(2039, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2213, 870)"/>
<path d="M240.0,-11.0Q168.0,-11.0 129.0,36.0Q118.0,51.0 108.5,70.0Q99.0,89.0 93.5,120.0Q88.0,151.0 88.0,202.0L88.0,554.0L174.0,554.0L174.0,223.0Q174.0,177.0 178.0,139.5Q182.0,102.0 202.0,82.0Q212.0,72.0 225.5,66.5Q239.0,61.0 258.0,61.0Q285.0,61.0 309.0,74.0Q333.0,87.0 354.0,116.0L354.0,554.0L440.0,554.0L440.0,72.0L789.0,72.0L789.0,554.0L875.0,554.0L875.0,0.0L354.0,0.0L354.0,35.0Q335.0,17.0 307.0,3.0Q279.0,-11.0 240.0,-11.0Z" transform="translate(2565, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(3528, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2870, 870)"/>
<path d="M298.0,566.0Q405.0,566.0 472.0,536.5Q539.0,507.0 570.5,457.5Q602.0,408.0 602.0,349.0Q602.0,271.0 565.0,228.0Q528.0,185.0 462.0,164.5Q396.0,144.0 309.0,135.0L229.0,127.0Q174.0,122.0 160.0,115.0Q146.0,108.0 146.0,95.0Q146.0,72.0 182.0,72.0L1050.0,72.0L1050.0,0.0L191.0,0.0Q121.0,0.0 91.5,27.0Q62.0,54.0 62.0,94.0Q62.0,139.0 98.5,164.0Q135.0,189.0 226.0,198.0L303.0,205.0Q394.0,214.0 439.5,235.5Q485.0,257.0 500.5,287.0Q516.0,317.0 516.0,349.0Q516.0,408.0 472.5,448.0Q429.0,488.0 348.0,495.0Q364.0,474.0 373.5,448.0Q383.0,422.0 383.0,392.0Q383.0,327.0 341.5,285.5Q300.0,244.0 220.0,244.0Q148.0,244.0 102.5,286.0Q57.0,328.0 57.0,398.0Q57.0,455.0 88.0,492.5Q119.0,530.0 173.5,548.0Q228.0,566.0 298.0,566.0ZM136.0,399.0Q136.0,362.0 157.0,337.0Q178.0,312.0 222.0,312.0Q260.0,312.0 282.5,335.5Q305.0,359.0 305.0,402.0Q305.0,427.0 297.0,451.0Q289.0,475.0 270.0,497.0L263.0,497.0Q209.0,497.0 172.5,473.0Q136.0,449.0 136.0,399.0Z" transform="translate(4168, 870)"/>
<path d="M402.0,13.0Q298.0,13.0 214.5,40.5Q131.0,68.0 78.0,105.0L120.0,174.0Q166.0,140.0 235.5,113.0Q305.0,86.0 399.0,86.0Q485.0,86.0 553.0,117.0Q621.0,148.0 660.5,218.5Q700.0,289.0 700.0,408.0Q700.0,490.0 671.5,553.0Q643.0,616.0 587.5,652.5Q532.0,689.0 450.0,689.0Q363.0,689.0 307.0,650.0Q251.0,611.0 227.0,554.0L248.0,554.0Q316.0,554.0 356.5,543.0Q397.0,532.0 425.0,509.0Q451.0,487.0 467.0,455.5Q483.0,424.0 483.0,378.0Q483.0,304.0 435.5,260.5Q388.0,217.0 314.0,217.0Q244.0,217.0 202.0,246.5Q160.0,276.0 141.0,323.5Q122.0,371.0 122.0,424.0Q122.0,453.0 127.0,482.0L-219.0,482.0L-219.0,554.0L138.0,554.0Q159.0,615.0 201.5,662.5Q244.0,710.0 307.0,737.0Q370.0,764.0 453.0,764.0Q559.0,764.0 633.5,719.0Q708.0,674.0 747.5,594.0Q787.0,514.0 787.0,408.0Q787.0,266.0 736.5,179.0Q686.0,92.0 599.0,52.5Q512.0,13.0 402.0,13.0ZM207.0,419.0Q207.0,352.0 234.0,321.0Q261.0,290.0 310.0,290.0Q354.0,290.0 376.0,315.5Q398.0,341.0 398.0,379.0Q398.0,404.0 389.0,422.5Q380.0,441.0 364.0,454.0Q348.0,468.0 321.0,475.0Q294.0,482.0 230.0,482.0L212.0,482.0Q207.0,451.0 207.0,419.0Z" transform="translate(5235, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4525, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ௗஞறாஂஸணு</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+562|aulengthmarktamil=0+1041|nyatamil=1+1210|rratamil=2+869|aavowelsigntamil=2+609|anusvaratamil=2@-1220,0+0|satamil=5+1285|nnauvowelsigntamil=6+1841</pre>



<pre>Got     : uni25CC=0+562|aulengthmarktamil=0+1041|nyatamil=1+1210|rratamil=2+869|aavowelsigntamil=2+640|anusvaratamil=2@-1251,0+0|satamil=5+1285|nnauvowelsigntamil=6+1841</pre>



<pre>                                                                                                     +                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7448 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(562, 870)"/>
<path d="M503.0,-12.0Q450.0,-12.0 406.5,14.0Q363.0,40.0 337.0,95.5Q311.0,151.0 311.0,239.0Q311.0,316.0 336.0,373.0Q361.0,430.0 404.0,468.0Q451.0,511.0 522.0,532.5Q593.0,554.0 705.0,554.0L1038.0,554.0L1038.0,482.0L868.0,482.0L868.0,284.0Q887.0,297.0 915.5,308.0Q944.0,319.0 980.0,319.0Q1061.0,319.0 1111.5,257.5Q1162.0,196.0 1162.0,83.0Q1162.0,-28.0 1119.0,-105.5Q1076.0,-183.0 1002.0,-230.5Q928.0,-278.0 834.5,-299.5Q741.0,-321.0 640.0,-321.0L613.0,-321.0Q489.0,-321.0 397.5,-295.0Q306.0,-269.0 242.5,-223.0Q179.0,-177.0 141.0,-117.0Q103.0,-57.0 85.5,11.0Q68.0,79.0 68.0,149.0L68.0,170.0Q68.0,239.0 86.5,308.5Q105.0,378.0 135.0,441.0Q165.0,504.0 199.0,554.0L273.0,510.0Q216.0,425.0 185.0,337.5Q154.0,250.0 154.0,163.0L154.0,150.0Q154.0,66.0 181.0,-5.5Q208.0,-77.0 264.5,-130.5Q321.0,-184.0 409.5,-214.0Q498.0,-244.0 622.0,-244.0L635.0,-244.0Q763.0,-244.0 862.0,-209.0Q961.0,-174.0 1017.5,-101.5Q1074.0,-29.0 1074.0,84.0Q1074.0,164.0 1045.5,205.5Q1017.0,247.0 964.0,247.0Q936.0,247.0 912.0,236.0Q888.0,225.0 868.0,211.0L868.0,0.0L782.0,0.0L782.0,482.0L693.0,482.0Q629.0,482.0 586.0,474.5Q543.0,467.0 515.5,454.0Q488.0,441.0 468.0,423.0Q410.0,372.0 395.0,291.0Q421.0,308.0 451.5,318.0Q482.0,328.0 514.0,328.0Q587.0,328.0 631.5,284.0Q676.0,240.0 676.0,165.0Q676.0,82.0 629.5,35.0Q583.0,-12.0 503.0,-12.0ZM500.0,258.0Q470.0,258.0 442.5,245.5Q415.0,233.0 390.0,212.0Q394.0,129.0 426.5,92.5Q459.0,56.0 508.0,56.0Q546.0,56.0 570.0,81.5Q594.0,107.0 594.0,155.0Q594.0,205.0 567.5,231.5Q541.0,258.0 500.0,258.0Z" transform="translate(1603, 870)"/>
<path d="M570.0,566.0Q684.0,566.0 744.5,482.0Q805.0,398.0 805.0,244.0Q805.0,122.0 774.0,44.5Q743.0,-33.0 690.0,-77.0Q632.0,-124.0 554.0,-140.0Q476.0,-156.0 388.0,-156.0L270.0,-156.0Q228.0,-156.0 205.0,-162.0Q182.0,-168.0 165.0,-179.0Q149.0,-190.0 140.0,-210.0Q131.0,-230.0 131.0,-263.0Q131.0,-293.0 134.0,-317.0L52.0,-321.0Q49.0,-303.0 47.0,-281.5Q45.0,-260.0 45.0,-243.0Q45.0,-199.0 61.0,-168.5Q77.0,-138.0 102.0,-119.0Q128.0,-100.0 160.5,-92.0Q193.0,-84.0 243.0,-84.0L366.0,-84.0Q459.0,-84.0 525.0,-70.5Q591.0,-57.0 633.5,-22.0Q676.0,13.0 696.0,78.5Q716.0,144.0 716.0,247.0Q716.0,338.0 696.5,392.0Q677.0,446.0 642.5,470.0Q608.0,494.0 563.0,494.0Q537.0,494.0 514.0,485.5Q491.0,477.0 474.0,458.0Q454.0,435.0 446.0,404.0Q438.0,373.0 438.0,319.0L438.0,0.0L352.0,0.0L352.0,321.0Q352.0,370.0 347.0,404.5Q342.0,439.0 327.0,461.0Q317.0,476.0 301.0,485.0Q285.0,494.0 262.0,494.0Q239.0,494.0 223.5,485.5Q208.0,477.0 197.0,463.0Q181.0,441.0 176.5,406.0Q172.0,371.0 172.0,327.0L172.0,0.0L86.0,0.0L86.0,341.0Q86.0,414.0 97.0,453.5Q108.0,493.0 139.0,524.0Q181.0,566.0 255.0,566.0Q355.0,566.0 399.0,472.0Q420.0,513.0 462.5,539.5Q505.0,566.0 570.0,566.0Z" transform="translate(2813, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(3682, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(3071, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(4322, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q476.0,566.0 536.0,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q927.0,566.0 976.0,551.5Q1025.0,537.0 1068.0,508.0Q1145.0,566.0 1242.0,566.0Q1373.0,566.0 1442.0,478.5Q1511.0,391.0 1511.0,226.0Q1511.0,131.0 1486.5,54.0Q1462.0,-23.0 1419.0,-84.0L1667.0,-84.0L1667.0,554.0L1753.0,554.0L1753.0,-156.0L1362.0,-156.0Q1309.0,-198.0 1247.5,-229.5Q1186.0,-261.0 1104.5,-281.0Q1023.0,-301.0 909.0,-311.0Q795.0,-321.0 637.0,-321.0L465.0,-321.0Q308.0,-321.0 214.0,-305.0Q120.0,-289.0 79.0,-255.0Q38.0,-221.0 38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.0,-88.5Q121.0,-84.0 164.0,-84.0L1313.0,-84.0Q1366.0,-25.0 1394.5,52.5Q1423.0,130.0 1423.0,223.0Q1423.0,320.0 1398.5,379.0Q1374.0,438.0 1332.0,465.0Q1290.0,492.0 1238.0,492.0Q1211.0,492.0 1182.0,485.5Q1153.0,479.0 1125.0,462.0Q1182.0,408.0 1211.0,338.0Q1240.0,268.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,260.0 936.5,329.0Q961.0,398.0 1013.0,456.0Q978.0,476.0 941.5,484.5Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.5,88.0Q1039.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,257.0 1129.5,317.5Q1104.0,378.0 1068.0,414.0Q1031.0,369.0 1013.5,312.5Q996.0,256.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM593.0,-248.0Q723.0,-248.0 821.5,-242.5Q920.0,-237.0 994.5,-226.0Q1069.0,-215.0 1126.0,-197.5Q1183.0,-180.0 1232.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-195.0 139.0,-207.5Q157.0,-220.0 203.0,-229.0Q249.0,-238.0 330.5,-243.0Q412.0,-248.0 539.0,-248.0L593.0,-248.0Z" transform="translate(5607, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7417 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(562, 870)"/>
<path d="M503.0,-12.0Q450.0,-12.0 406.5,14.0Q363.0,40.0 337.0,95.5Q311.0,151.0 311.0,239.0Q311.0,316.0 336.0,373.0Q361.0,430.0 404.0,468.0Q451.0,511.0 522.0,532.5Q593.0,554.0 705.0,554.0L1038.0,554.0L1038.0,482.0L868.0,482.0L868.0,284.0Q887.0,297.0 915.5,308.0Q944.0,319.0 980.0,319.0Q1061.0,319.0 1111.5,257.5Q1162.0,196.0 1162.0,83.0Q1162.0,-28.0 1119.0,-105.5Q1076.0,-183.0 1002.0,-230.5Q928.0,-278.0 834.5,-299.5Q741.0,-321.0 640.0,-321.0L613.0,-321.0Q489.0,-321.0 397.5,-295.0Q306.0,-269.0 242.5,-223.0Q179.0,-177.0 141.0,-117.0Q103.0,-57.0 85.5,11.0Q68.0,79.0 68.0,149.0L68.0,170.0Q68.0,239.0 86.5,308.5Q105.0,378.0 135.0,441.0Q165.0,504.0 199.0,554.0L273.0,510.0Q216.0,425.0 185.0,337.5Q154.0,250.0 154.0,163.0L154.0,150.0Q154.0,66.0 181.0,-5.5Q208.0,-77.0 264.5,-130.5Q321.0,-184.0 409.5,-214.0Q498.0,-244.0 622.0,-244.0L635.0,-244.0Q763.0,-244.0 862.0,-209.0Q961.0,-174.0 1017.5,-101.5Q1074.0,-29.0 1074.0,84.0Q1074.0,164.0 1045.5,205.5Q1017.0,247.0 964.0,247.0Q936.0,247.0 912.0,236.0Q888.0,225.0 868.0,211.0L868.0,0.0L782.0,0.0L782.0,482.0L693.0,482.0Q629.0,482.0 586.0,474.5Q543.0,467.0 515.5,454.0Q488.0,441.0 468.0,423.0Q410.0,372.0 395.0,291.0Q421.0,308.0 451.5,318.0Q482.0,328.0 514.0,328.0Q587.0,328.0 631.5,284.0Q676.0,240.0 676.0,165.0Q676.0,82.0 629.5,35.0Q583.0,-12.0 503.0,-12.0ZM500.0,258.0Q470.0,258.0 442.5,245.5Q415.0,233.0 390.0,212.0Q394.0,129.0 426.5,92.5Q459.0,56.0 508.0,56.0Q546.0,56.0 570.0,81.5Q594.0,107.0 594.0,155.0Q594.0,205.0 567.5,231.5Q541.0,258.0 500.0,258.0Z" transform="translate(1603, 870)"/>
<path d="M570.0,566.0Q684.0,566.0 744.5,482.0Q805.0,398.0 805.0,244.0Q805.0,122.0 774.0,44.5Q743.0,-33.0 690.0,-77.0Q632.0,-124.0 554.0,-140.0Q476.0,-156.0 388.0,-156.0L270.0,-156.0Q228.0,-156.0 205.0,-162.0Q182.0,-168.0 165.0,-179.0Q149.0,-190.0 140.0,-210.0Q131.0,-230.0 131.0,-263.0Q131.0,-293.0 134.0,-317.0L52.0,-321.0Q49.0,-303.0 47.0,-281.5Q45.0,-260.0 45.0,-243.0Q45.0,-199.0 61.0,-168.5Q77.0,-138.0 102.0,-119.0Q128.0,-100.0 160.5,-92.0Q193.0,-84.0 243.0,-84.0L366.0,-84.0Q459.0,-84.0 525.0,-70.5Q591.0,-57.0 633.5,-22.0Q676.0,13.0 696.0,78.5Q716.0,144.0 716.0,247.0Q716.0,338.0 696.5,392.0Q677.0,446.0 642.5,470.0Q608.0,494.0 563.0,494.0Q537.0,494.0 514.0,485.5Q491.0,477.0 474.0,458.0Q454.0,435.0 446.0,404.0Q438.0,373.0 438.0,319.0L438.0,0.0L352.0,0.0L352.0,321.0Q352.0,370.0 347.0,404.5Q342.0,439.0 327.0,461.0Q317.0,476.0 301.0,485.0Q285.0,494.0 262.0,494.0Q239.0,494.0 223.5,485.5Q208.0,477.0 197.0,463.0Q181.0,441.0 176.5,406.0Q172.0,371.0 172.0,327.0L172.0,0.0L86.0,0.0L86.0,341.0Q86.0,414.0 97.0,453.5Q108.0,493.0 139.0,524.0Q181.0,566.0 255.0,566.0Q355.0,566.0 399.0,472.0Q420.0,513.0 462.5,539.5Q505.0,566.0 570.0,566.0Z" transform="translate(2813, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(3682, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(3071, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(4291, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q476.0,566.0 536.0,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q927.0,566.0 976.0,551.5Q1025.0,537.0 1068.0,508.0Q1145.0,566.0 1242.0,566.0Q1373.0,566.0 1442.0,478.5Q1511.0,391.0 1511.0,226.0Q1511.0,131.0 1486.5,54.0Q1462.0,-23.0 1419.0,-84.0L1667.0,-84.0L1667.0,554.0L1753.0,554.0L1753.0,-156.0L1362.0,-156.0Q1309.0,-198.0 1247.5,-229.5Q1186.0,-261.0 1104.5,-281.0Q1023.0,-301.0 909.0,-311.0Q795.0,-321.0 637.0,-321.0L465.0,-321.0Q308.0,-321.0 214.0,-305.0Q120.0,-289.0 79.0,-255.0Q38.0,-221.0 38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.0,-88.5Q121.0,-84.0 164.0,-84.0L1313.0,-84.0Q1366.0,-25.0 1394.5,52.5Q1423.0,130.0 1423.0,223.0Q1423.0,320.0 1398.5,379.0Q1374.0,438.0 1332.0,465.0Q1290.0,492.0 1238.0,492.0Q1211.0,492.0 1182.0,485.5Q1153.0,479.0 1125.0,462.0Q1182.0,408.0 1211.0,338.0Q1240.0,268.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,260.0 936.5,329.0Q961.0,398.0 1013.0,456.0Q978.0,476.0 941.5,484.5Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.5,88.0Q1039.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,257.0 1129.5,317.5Q1104.0,378.0 1068.0,414.0Q1031.0,369.0 1013.5,312.5Q996.0,256.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM593.0,-248.0Q723.0,-248.0 821.5,-242.5Q920.0,-237.0 994.5,-226.0Q1069.0,-215.0 1126.0,-197.5Q1183.0,-180.0 1232.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-195.0 139.0,-207.5Q157.0,-220.0 203.0,-229.0Q249.0,-238.0 330.5,-243.0Q412.0,-248.0 539.0,-248.0L593.0,-248.0Z" transform="translate(5576, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ளீஎௗஂன்ஈாஂறஆ</span> (Added by SIESTA)</li>


<pre>Expected: llaiivowelsigntamil=0+1039|etamil=2+770|aulengthmarktamil=2+1039|anusvaratamil=2@-1585,0+0|nnnaprehalftamil=5+1234|iitamil=7+707|aavowelsigntamil=7+618|anusvaratamil=7@-1148,0+0|rratamil=10+840|aatamil=11+1313</pre>



<pre>Got     : llaiivowelsigntamil=0+1039|etamil=2+770|aulengthmarktamil=2+1070|anusvaratamil=2@-1616,0+0|nnnaprehalftamil=5+1234|iitamil=7+707|aavowelsigntamil=7+640|anusvaratamil=7@-1170,0+0|rratamil=10+840|aatamil=11+1313</pre>



<pre>                                                                        ^^                   ^^^                                                               ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7613 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM955.0,843.0Q1041.0,843.0 1086.0,808.5Q1131.0,774.0 1131.0,718.0Q1131.0,655.0 1093.0,624.5Q1055.0,594.0 1000.0,594.0Q942.0,594.0 907.0,623.5Q872.0,653.0 872.0,705.0Q872.0,719.0 875.0,736.5Q878.0,754.0 886.0,772.0Q828.0,756.0 800.5,716.5Q773.0,677.0 773.0,626.0Q773.0,598.0 780.0,575.5Q787.0,553.0 799.0,535.0L715.0,529.0Q706.0,549.0 701.0,573.0Q696.0,597.0 696.0,624.0Q696.0,683.0 723.5,732.5Q751.0,782.0 808.5,812.5Q866.0,843.0 955.0,843.0ZM938.0,719.0Q938.0,685.0 955.5,670.5Q973.0,656.0 1000.0,656.0Q1029.0,656.0 1045.0,672.0Q1061.0,688.0 1061.0,713.0Q1061.0,748.0 1033.0,764.0Q1005.0,780.0 961.0,780.0Q959.0,780.0 957.0,780.0Q947.0,765.0 942.5,749.5Q938.0,734.0 938.0,719.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1039, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1809, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1263, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q478.0,566.0 538.5,550.0Q599.0,534.0 656.0,499.0Q685.0,515.0 718.5,527.5Q752.0,540.0 800.0,547.0Q848.0,554.0 918.0,554.0L1217.0,554.0L1217.0,482.0L1047.0,482.0L1047.0,0.0L961.0,0.0L961.0,482.0L895.0,482.0Q840.0,482.0 796.0,475.5Q752.0,469.0 713.0,449.0Q764.0,402.0 794.5,335.5Q825.0,269.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,340.0 595.0,449.0Q552.0,473.0 502.5,482.5Q453.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,317.0 652.0,406.0Q617.0,368.0 599.0,309.0Q581.0,250.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM618.0,678.0Q589.0,678.0 570.0,696.5Q551.0,715.0 551.0,745.0Q551.0,774.0 570.0,793.0Q589.0,812.0 618.0,812.0Q647.0,812.0 666.0,793.0Q685.0,774.0 685.0,745.0Q685.0,715.0 666.0,696.5Q647.0,678.0 618.0,678.0Z" transform="translate(2879, 870)"/>
<path d="M88.0,0.0L88.0,554.0L682.0,554.0L682.0,482.0L483.0,482.0L483.0,0.0L397.0,0.0L397.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0ZM286.0,214.0Q259.0,214.0 240.5,232.0Q222.0,250.0 222.0,278.0Q222.0,305.0 240.0,323.0Q258.0,341.0 286.0,341.0Q313.0,341.0 331.0,323.0Q349.0,305.0 349.0,278.0Q349.0,250.0 331.0,232.0Q313.0,214.0 286.0,214.0ZM594.0,214.0Q567.0,214.0 548.5,232.0Q530.0,250.0 530.0,278.0Q530.0,305.0 548.0,323.0Q566.0,341.0 594.0,341.0Q621.0,341.0 639.0,323.0Q657.0,305.0 657.0,278.0Q657.0,250.0 639.0,232.0Q621.0,214.0 594.0,214.0Z" transform="translate(4113, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(4820, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4290, 870)"/>
<path d="M570.0,566.0Q684.0,566.0 744.5,482.0Q805.0,398.0 805.0,244.0Q805.0,122.0 774.0,44.5Q743.0,-33.0 690.0,-77.0Q632.0,-124.0 554.0,-140.0Q476.0,-156.0 388.0,-156.0L270.0,-156.0Q228.0,-156.0 205.0,-162.0Q182.0,-168.0 165.0,-179.0Q149.0,-190.0 140.0,-210.0Q131.0,-230.0 131.0,-263.0Q131.0,-293.0 134.0,-317.0L52.0,-321.0Q49.0,-303.0 47.0,-281.5Q45.0,-260.0 45.0,-243.0Q45.0,-199.0 61.0,-168.5Q77.0,-138.0 102.0,-119.0Q128.0,-100.0 160.5,-92.0Q193.0,-84.0 243.0,-84.0L366.0,-84.0Q459.0,-84.0 525.0,-70.5Q591.0,-57.0 633.5,-22.0Q676.0,13.0 696.0,78.5Q716.0,144.0 716.0,247.0Q716.0,338.0 696.5,392.0Q677.0,446.0 642.5,470.0Q608.0,494.0 563.0,494.0Q537.0,494.0 514.0,485.5Q491.0,477.0 474.0,458.0Q454.0,435.0 446.0,404.0Q438.0,373.0 438.0,319.0L438.0,0.0L352.0,0.0L352.0,321.0Q352.0,370.0 347.0,404.5Q342.0,439.0 327.0,461.0Q317.0,476.0 301.0,485.0Q285.0,494.0 262.0,494.0Q239.0,494.0 223.5,485.5Q208.0,477.0 197.0,463.0Q181.0,441.0 176.5,406.0Q172.0,371.0 172.0,327.0L172.0,0.0L86.0,0.0L86.0,341.0Q86.0,414.0 97.0,453.5Q108.0,493.0 139.0,524.0Q181.0,566.0 255.0,566.0Q355.0,566.0 399.0,472.0Q420.0,513.0 462.5,539.5Q505.0,566.0 570.0,566.0Z" transform="translate(5460, 870)"/>
<path d="M379.0,397.0Q379.0,360.0 401.5,334.5Q424.0,309.0 465.0,309.0Q503.0,309.0 525.5,332.5Q548.0,356.0 548.0,400.0Q548.0,428.0 540.5,451.5Q533.0,475.0 514.0,496.0Q504.0,497.0 493.0,497.0Q446.0,497.0 412.5,472.0Q379.0,447.0 379.0,397.0ZM344.0,-51.0Q482.0,-51.0 568.0,-7.5Q654.0,36.0 695.0,104.0L217.0,104.0Q186.0,104.0 169.5,103.0Q153.0,102.0 145.0,99.0Q137.0,96.0 129.0,90.0Q114.0,78.0 114.0,56.0Q114.0,7.0 167.0,-22.0Q220.0,-51.0 327.0,-51.0L344.0,-51.0ZM321.0,-124.0Q176.0,-124.0 102.5,-72.5Q29.0,-21.0 29.0,60.0Q29.0,85.0 40.0,109.0Q51.0,133.0 74.0,149.0Q87.0,158.0 102.0,164.0Q117.0,170.0 141.5,173.0Q166.0,176.0 206.0,176.0L721.0,176.0Q730.0,211.0 730.0,251.0Q730.0,323.0 699.0,385.5Q668.0,448.0 601.0,477.0Q612.0,459.0 619.0,438.5Q626.0,418.0 626.0,396.0Q626.0,326.0 584.0,283.5Q542.0,241.0 463.0,241.0Q395.0,241.0 347.5,279.0Q300.0,317.0 300.0,393.0Q300.0,455.0 329.0,493.0Q358.0,531.0 404.5,548.5Q451.0,566.0 503.0,566.0Q580.0,566.0 638.5,540.0Q697.0,514.0 736.5,469.0Q776.0,424.0 796.0,368.0Q816.0,312.0 816.0,252.0Q816.0,212.0 810.0,176.0L947.0,176.0L947.0,554.0L1033.0,554.0L1033.0,70.0Q1053.0,82.0 1080.0,91.0Q1107.0,100.0 1145.0,100.0Q1186.0,100.0 1223.5,82.0Q1261.0,64.0 1285.0,27.5Q1309.0,-9.0 1309.0,-65.0Q1309.0,-141.0 1263.0,-199.0Q1217.0,-257.0 1131.5,-289.0Q1046.0,-321.0 928.0,-321.0L922.0,-321.0Q792.0,-321.0 720.0,-277.5Q648.0,-234.0 648.0,-154.0Q648.0,-125.0 662.5,-99.5Q677.0,-74.0 707.5,-57.5Q738.0,-41.0 784.0,-41.0Q810.0,-41.0 838.0,-46.5Q866.0,-52.0 891.0,-62.0L877.0,-127.0Q855.0,-120.0 832.5,-115.0Q810.0,-110.0 790.0,-110.0Q759.0,-110.0 742.0,-122.0Q725.0,-134.0 725.0,-157.0Q725.0,-181.0 743.5,-202.0Q762.0,-223.0 806.0,-236.0Q850.0,-249.0 926.0,-249.0L933.0,-249.0Q1019.0,-249.0 1084.5,-227.5Q1150.0,-206.0 1187.5,-164.0Q1225.0,-122.0 1225.0,-63.0Q1225.0,-19.0 1200.0,6.0Q1175.0,31.0 1131.0,31.0Q1099.0,31.0 1074.5,22.5Q1050.0,14.0 1033.0,1.0L1033.0,-124.0L947.0,-124.0L947.0,104.0L789.0,104.0Q756.0,30.0 691.0,-21.0Q626.0,-72.0 537.0,-98.0Q448.0,-124.0 342.0,-124.0L321.0,-124.0Z" transform="translate(6300, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7560 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM955.0,843.0Q1041.0,843.0 1086.0,808.5Q1131.0,774.0 1131.0,718.0Q1131.0,655.0 1093.0,624.5Q1055.0,594.0 1000.0,594.0Q942.0,594.0 907.0,623.5Q872.0,653.0 872.0,705.0Q872.0,719.0 875.0,736.5Q878.0,754.0 886.0,772.0Q828.0,756.0 800.5,716.5Q773.0,677.0 773.0,626.0Q773.0,598.0 780.0,575.5Q787.0,553.0 799.0,535.0L715.0,529.0Q706.0,549.0 701.0,573.0Q696.0,597.0 696.0,624.0Q696.0,683.0 723.5,732.5Q751.0,782.0 808.5,812.5Q866.0,843.0 955.0,843.0ZM938.0,719.0Q938.0,685.0 955.5,670.5Q973.0,656.0 1000.0,656.0Q1029.0,656.0 1045.0,672.0Q1061.0,688.0 1061.0,713.0Q1061.0,748.0 1033.0,764.0Q1005.0,780.0 961.0,780.0Q959.0,780.0 957.0,780.0Q947.0,765.0 942.5,749.5Q938.0,734.0 938.0,719.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1039, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1809, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1263, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q478.0,566.0 538.5,550.0Q599.0,534.0 656.0,499.0Q685.0,515.0 718.5,527.5Q752.0,540.0 800.0,547.0Q848.0,554.0 918.0,554.0L1217.0,554.0L1217.0,482.0L1047.0,482.0L1047.0,0.0L961.0,0.0L961.0,482.0L895.0,482.0Q840.0,482.0 796.0,475.5Q752.0,469.0 713.0,449.0Q764.0,402.0 794.5,335.5Q825.0,269.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,340.0 595.0,449.0Q552.0,473.0 502.5,482.5Q453.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,317.0 652.0,406.0Q617.0,368.0 599.0,309.0Q581.0,250.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM618.0,678.0Q589.0,678.0 570.0,696.5Q551.0,715.0 551.0,745.0Q551.0,774.0 570.0,793.0Q589.0,812.0 618.0,812.0Q647.0,812.0 666.0,793.0Q685.0,774.0 685.0,745.0Q685.0,715.0 666.0,696.5Q647.0,678.0 618.0,678.0Z" transform="translate(2848, 870)"/>
<path d="M88.0,0.0L88.0,554.0L682.0,554.0L682.0,482.0L483.0,482.0L483.0,0.0L397.0,0.0L397.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0ZM286.0,214.0Q259.0,214.0 240.5,232.0Q222.0,250.0 222.0,278.0Q222.0,305.0 240.0,323.0Q258.0,341.0 286.0,341.0Q313.0,341.0 331.0,323.0Q349.0,305.0 349.0,278.0Q349.0,250.0 331.0,232.0Q313.0,214.0 286.0,214.0ZM594.0,214.0Q567.0,214.0 548.5,232.0Q530.0,250.0 530.0,278.0Q530.0,305.0 548.0,323.0Q566.0,341.0 594.0,341.0Q621.0,341.0 639.0,323.0Q657.0,305.0 657.0,278.0Q657.0,250.0 639.0,232.0Q621.0,214.0 594.0,214.0Z" transform="translate(4082, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z" transform="translate(4789, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4259, 870)"/>
<path d="M570.0,566.0Q684.0,566.0 744.5,482.0Q805.0,398.0 805.0,244.0Q805.0,122.0 774.0,44.5Q743.0,-33.0 690.0,-77.0Q632.0,-124.0 554.0,-140.0Q476.0,-156.0 388.0,-156.0L270.0,-156.0Q228.0,-156.0 205.0,-162.0Q182.0,-168.0 165.0,-179.0Q149.0,-190.0 140.0,-210.0Q131.0,-230.0 131.0,-263.0Q131.0,-293.0 134.0,-317.0L52.0,-321.0Q49.0,-303.0 47.0,-281.5Q45.0,-260.0 45.0,-243.0Q45.0,-199.0 61.0,-168.5Q77.0,-138.0 102.0,-119.0Q128.0,-100.0 160.5,-92.0Q193.0,-84.0 243.0,-84.0L366.0,-84.0Q459.0,-84.0 525.0,-70.5Q591.0,-57.0 633.5,-22.0Q676.0,13.0 696.0,78.5Q716.0,144.0 716.0,247.0Q716.0,338.0 696.5,392.0Q677.0,446.0 642.5,470.0Q608.0,494.0 563.0,494.0Q537.0,494.0 514.0,485.5Q491.0,477.0 474.0,458.0Q454.0,435.0 446.0,404.0Q438.0,373.0 438.0,319.0L438.0,0.0L352.0,0.0L352.0,321.0Q352.0,370.0 347.0,404.5Q342.0,439.0 327.0,461.0Q317.0,476.0 301.0,485.0Q285.0,494.0 262.0,494.0Q239.0,494.0 223.5,485.5Q208.0,477.0 197.0,463.0Q181.0,441.0 176.5,406.0Q172.0,371.0 172.0,327.0L172.0,0.0L86.0,0.0L86.0,341.0Q86.0,414.0 97.0,453.5Q108.0,493.0 139.0,524.0Q181.0,566.0 255.0,566.0Q355.0,566.0 399.0,472.0Q420.0,513.0 462.5,539.5Q505.0,566.0 570.0,566.0Z" transform="translate(5407, 870)"/>
<path d="M379.0,397.0Q379.0,360.0 401.5,334.5Q424.0,309.0 465.0,309.0Q503.0,309.0 525.5,332.5Q548.0,356.0 548.0,400.0Q548.0,428.0 540.5,451.5Q533.0,475.0 514.0,496.0Q504.0,497.0 493.0,497.0Q446.0,497.0 412.5,472.0Q379.0,447.0 379.0,397.0ZM344.0,-51.0Q482.0,-51.0 568.0,-7.5Q654.0,36.0 695.0,104.0L217.0,104.0Q186.0,104.0 169.5,103.0Q153.0,102.0 145.0,99.0Q137.0,96.0 129.0,90.0Q114.0,78.0 114.0,56.0Q114.0,7.0 167.0,-22.0Q220.0,-51.0 327.0,-51.0L344.0,-51.0ZM321.0,-124.0Q176.0,-124.0 102.5,-72.5Q29.0,-21.0 29.0,60.0Q29.0,85.0 40.0,109.0Q51.0,133.0 74.0,149.0Q87.0,158.0 102.0,164.0Q117.0,170.0 141.5,173.0Q166.0,176.0 206.0,176.0L721.0,176.0Q730.0,211.0 730.0,251.0Q730.0,323.0 699.0,385.5Q668.0,448.0 601.0,477.0Q612.0,459.0 619.0,438.5Q626.0,418.0 626.0,396.0Q626.0,326.0 584.0,283.5Q542.0,241.0 463.0,241.0Q395.0,241.0 347.5,279.0Q300.0,317.0 300.0,393.0Q300.0,455.0 329.0,493.0Q358.0,531.0 404.5,548.5Q451.0,566.0 503.0,566.0Q580.0,566.0 638.5,540.0Q697.0,514.0 736.5,469.0Q776.0,424.0 796.0,368.0Q816.0,312.0 816.0,252.0Q816.0,212.0 810.0,176.0L947.0,176.0L947.0,554.0L1033.0,554.0L1033.0,70.0Q1053.0,82.0 1080.0,91.0Q1107.0,100.0 1145.0,100.0Q1186.0,100.0 1223.5,82.0Q1261.0,64.0 1285.0,27.5Q1309.0,-9.0 1309.0,-65.0Q1309.0,-141.0 1263.0,-199.0Q1217.0,-257.0 1131.5,-289.0Q1046.0,-321.0 928.0,-321.0L922.0,-321.0Q792.0,-321.0 720.0,-277.5Q648.0,-234.0 648.0,-154.0Q648.0,-125.0 662.5,-99.5Q677.0,-74.0 707.5,-57.5Q738.0,-41.0 784.0,-41.0Q810.0,-41.0 838.0,-46.5Q866.0,-52.0 891.0,-62.0L877.0,-127.0Q855.0,-120.0 832.5,-115.0Q810.0,-110.0 790.0,-110.0Q759.0,-110.0 742.0,-122.0Q725.0,-134.0 725.0,-157.0Q725.0,-181.0 743.5,-202.0Q762.0,-223.0 806.0,-236.0Q850.0,-249.0 926.0,-249.0L933.0,-249.0Q1019.0,-249.0 1084.5,-227.5Q1150.0,-206.0 1187.5,-164.0Q1225.0,-122.0 1225.0,-63.0Q1225.0,-19.0 1200.0,6.0Q1175.0,31.0 1131.0,31.0Q1099.0,31.0 1074.5,22.5Q1050.0,14.0 1033.0,1.0L1033.0,-124.0L947.0,-124.0L947.0,104.0L789.0,104.0Q756.0,30.0 691.0,-21.0Q626.0,-72.0 537.0,-98.0Q448.0,-124.0 342.0,-124.0L321.0,-124.0Z" transform="translate(6247, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஐௗஂ𑌁᳚றௗஂஷூஂணௗஂ</span> (Added by SIESTA)</li>


<pre>Expected: aitamil=0+1022|aulengthmarktamil=0+1048|anusvaratamil=0@-1735,0+0|candrabindu_1CDA_tamil=0@-1281,235+0|rratamil=5+869|aulengthmarktamil=5+1039|anusvaratamil=5@-1650,0+0|ssatamil=8+1345|uuvowelsignalttamil=8+830|anusvaratamil=8@-1678,0+0|nnatamil=11+1617|aulengthmarktamil=11+1070|anusvaratamil=11@-2039,0+0</pre>



<pre>Got     : aitamil=0+1022|aulengthmarktamil=0+1070|anusvaratamil=0@-1757,0+0|candrabindu_1CDA_tamil=0@-1303,235+0|rratamil=5+869|aulengthmarktamil=5+1070|anusvaratamil=5@-1681,0+0|ssatamil=8+1345|uuvowelsignalttamil=8+830|anusvaratamil=8@-1678,0+0|nnatamil=11+1617|aulengthmarktamil=11+1070|anusvaratamil=11@-2039,0+0</pre>



<pre>                                               +++++++++++++++++++++ ^^                                ^^^                                            ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8893 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M338.0,-321.0Q246.0,-321.0 185.0,-290.0Q124.0,-259.0 93.5,-207.5Q63.0,-156.0 63.0,-95.0Q63.0,-40.0 81.5,-0.5Q100.0,39.0 131.0,65.0Q183.0,109.0 262.5,122.0Q342.0,135.0 432.0,135.0L521.0,135.0Q634.0,135.0 708.5,147.5Q783.0,160.0 823.0,196.0Q871.0,241.0 871.0,334.0Q871.0,413.0 829.5,453.0Q788.0,493.0 726.0,493.0Q667.0,493.0 635.0,457.0Q616.0,434.0 608.0,403.5Q600.0,373.0 600.0,319.0L600.0,205.0L513.0,205.0L513.0,297.0Q513.0,357.0 496.5,402.0Q480.0,447.0 441.5,471.5Q403.0,496.0 337.0,496.0Q314.0,496.0 299.5,494.5Q285.0,493.0 271.0,490.0Q329.0,478.0 366.5,439.5Q404.0,401.0 404.0,342.0Q404.0,270.0 357.5,227.0Q311.0,184.0 235.0,184.0Q150.0,184.0 106.5,230.5Q63.0,277.0 63.0,345.0Q63.0,415.0 100.0,464.5Q137.0,514.0 198.5,540.0Q260.0,566.0 331.0,566.0Q397.0,566.0 440.5,550.0Q484.0,534.0 510.0,508.5Q536.0,483.0 551.0,455.0Q575.0,508.0 619.5,537.0Q664.0,566.0 729.0,566.0Q804.0,566.0 855.0,536.5Q906.0,507.0 932.5,455.0Q959.0,403.0 959.0,335.0Q959.0,268.0 939.0,221.0Q919.0,174.0 883.0,143.0Q845.0,110.0 791.5,93.0Q738.0,76.0 674.5,69.5Q611.0,63.0 542.0,63.0L448.0,63.0Q348.0,63.0 285.0,53.0Q222.0,43.0 187.0,8.0Q168.0,-11.0 159.5,-36.0Q151.0,-61.0 151.0,-93.0Q151.0,-147.0 176.5,-181.0Q202.0,-215.0 245.0,-231.5Q288.0,-248.0 340.0,-248.0Q382.0,-248.0 413.5,-239.5Q445.0,-231.0 467.0,-212.0Q493.0,-189.0 503.0,-158.0Q513.0,-127.0 513.0,-73.0L513.0,-11.0L600.0,-11.0L600.0,-47.0Q600.0,-87.0 605.0,-120.0Q610.0,-153.0 622.0,-178.0Q639.0,-212.0 669.5,-230.0Q700.0,-248.0 749.0,-248.0Q781.0,-248.0 809.0,-234.5Q837.0,-221.0 854.5,-190.0Q872.0,-159.0 872.0,-105.0Q872.0,-77.0 865.0,-42.0Q858.0,-7.0 847.0,16.0L932.0,45.0Q945.0,11.0 952.0,-24.0Q959.0,-59.0 959.0,-108.0Q959.0,-177.0 931.5,-224.5Q904.0,-272.0 856.5,-296.5Q809.0,-321.0 750.0,-321.0Q692.0,-321.0 653.5,-305.0Q615.0,-289.0 591.5,-263.5Q568.0,-238.0 556.0,-210.0Q527.0,-264.0 471.5,-292.5Q416.0,-321.0 338.0,-321.0ZM142.0,348.0Q142.0,305.0 163.5,278.5Q185.0,252.0 234.0,252.0Q273.0,252.0 297.5,274.0Q322.0,296.0 322.0,335.0Q322.0,386.0 283.0,416.0Q244.0,446.0 185.0,448.0Q162.0,427.0 152.0,401.5Q142.0,376.0 142.0,348.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1022, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(335, 870)"/>
<path d="M-412.0,660.0Q-496.0,660.0 -541.0,700.5Q-586.0,741.0 -586.0,815.0Q-586.0,844.0 -578.0,870.0L-510.0,856.0Q-513.0,846.0 -514.0,835.5Q-515.0,825.0 -515.0,817.0Q-515.0,781.0 -500.5,761.0Q-486.0,741.0 -462.0,733.0Q-438.0,725.0 -412.0,725.0Q-371.0,725.0 -340.0,746.0Q-309.0,767.0 -309.0,819.0Q-309.0,827.0 -310.0,836.5Q-311.0,846.0 -314.0,856.0L-245.0,870.0Q-242.0,858.0 -240.0,843.0Q-238.0,828.0 -238.0,815.0Q-238.0,742.0 -284.5,701.0Q-331.0,660.0 -412.0,660.0ZM-413.0,767.0Q-435.0,767.0 -449.0,781.0Q-463.0,795.0 -463.0,818.0Q-463.0,839.0 -449.0,853.5Q-435.0,868.0 -413.0,868.0Q-391.0,868.0 -376.5,853.5Q-362.0,839.0 -362.0,818.0Q-362.0,795.0 -376.5,781.0Q-391.0,767.0 -413.0,767.0ZM-171.0,870.0L-103.0,870.0L-103.0,659.0L-171.0,659.0L-171.0,870.0ZM-41.0,870.0L27.0,870.0L27.0,659.0L-41.0,659.0L-41.0,870.0Z" transform="translate(789, 1105)"/>
<path d="M570.0,566.0Q684.0,566.0 744.5,482.0Q805.0,398.0 805.0,244.0Q805.0,122.0 774.0,44.5Q743.0,-33.0 690.0,-77.0Q632.0,-124.0 554.0,-140.0Q476.0,-156.0 388.0,-156.0L270.0,-156.0Q228.0,-156.0 205.0,-162.0Q182.0,-168.0 165.0,-179.0Q149.0,-190.0 140.0,-210.0Q131.0,-230.0 131.0,-263.0Q131.0,-293.0 134.0,-317.0L52.0,-321.0Q49.0,-303.0 47.0,-281.5Q45.0,-260.0 45.0,-243.0Q45.0,-199.0 61.0,-168.5Q77.0,-138.0 102.0,-119.0Q128.0,-100.0 160.5,-92.0Q193.0,-84.0 243.0,-84.0L366.0,-84.0Q459.0,-84.0 525.0,-70.5Q591.0,-57.0 633.5,-22.0Q676.0,13.0 696.0,78.5Q716.0,144.0 716.0,247.0Q716.0,338.0 696.5,392.0Q677.0,446.0 642.5,470.0Q608.0,494.0 563.0,494.0Q537.0,494.0 514.0,485.5Q491.0,477.0 474.0,458.0Q454.0,435.0 446.0,404.0Q438.0,373.0 438.0,319.0L438.0,0.0L352.0,0.0L352.0,321.0Q352.0,370.0 347.0,404.5Q342.0,439.0 327.0,461.0Q317.0,476.0 301.0,485.0Q285.0,494.0 262.0,494.0Q239.0,494.0 223.5,485.5Q208.0,477.0 197.0,463.0Q181.0,441.0 176.5,406.0Q172.0,371.0 172.0,327.0L172.0,0.0L86.0,0.0L86.0,341.0Q86.0,414.0 97.0,453.5Q108.0,493.0 139.0,524.0Q181.0,566.0 255.0,566.0Q355.0,566.0 399.0,472.0Q420.0,513.0 462.5,539.5Q505.0,566.0 570.0,566.0Z" transform="translate(2092, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(2961, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2350, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L917.0,72.0L945.0,184.0Q853.0,192.0 794.0,241.0Q735.0,290.0 735.0,384.0Q735.0,435.0 755.5,476.0Q776.0,517.0 815.0,541.5Q854.0,566.0 909.0,566.0Q966.0,566.0 1001.5,544.0Q1037.0,522.0 1053.0,485.5Q1069.0,449.0 1069.0,406.0Q1069.0,371.0 1063.5,334.0Q1058.0,297.0 1048.0,256.0Q1098.0,264.0 1132.0,285.5Q1166.0,307.0 1188.0,328.0L1269.0,328.0L1269.0,0.0L984.0,0.0L912.0,-284.0L833.0,-262.0L899.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,285.5Q422.0,243.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM818.0,382.0Q818.0,319.0 858.0,288.0Q898.0,257.0 962.0,253.0Q982.0,340.0 982.0,403.0Q982.0,447.0 963.0,470.5Q944.0,494.0 909.0,494.0Q868.0,494.0 843.0,466.0Q818.0,438.0 818.0,382.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM1192.0,247.0Q1166.0,225.0 1125.0,206.5Q1084.0,188.0 1030.0,183.0L1002.0,72.0L1188.0,72.0L1188.0,153.0Q1188.0,176.0 1189.0,201.0Q1190.0,226.0 1192.0,247.0Z" transform="translate(4031, 870)"/>
<path d="M388.0,13.0Q284.0,13.0 200.5,40.5Q117.0,68.0 64.0,105.0L106.0,174.0Q152.0,140.0 221.5,113.0Q291.0,86.0 385.0,86.0Q471.0,86.0 539.0,117.0Q607.0,148.0 646.5,218.5Q686.0,289.0 686.0,408.0Q686.0,490.0 657.5,553.0Q629.0,616.0 573.5,652.5Q518.0,689.0 436.0,689.0Q349.0,689.0 293.0,650.0Q237.0,611.0 213.0,554.0L234.0,554.0Q302.0,554.0 342.5,543.0Q383.0,532.0 411.0,509.0Q437.0,487.0 453.0,455.5Q469.0,424.0 469.0,378.0Q469.0,304.0 421.5,260.5Q374.0,217.0 300.0,217.0Q230.0,217.0 188.0,246.5Q146.0,276.0 127.0,323.5Q108.0,371.0 108.0,424.0Q108.0,453.0 113.0,482.0L-365.0,482.0L-365.0,554.0L124.0,554.0Q145.0,615.0 187.5,662.5Q230.0,710.0 293.0,737.0Q356.0,764.0 439.0,764.0Q545.0,764.0 619.5,719.0Q694.0,674.0 733.5,594.0Q773.0,514.0 773.0,408.0Q773.0,266.0 722.5,179.0Q672.0,92.0 585.0,52.5Q498.0,13.0 388.0,13.0ZM193.0,419.0Q193.0,352.0 220.0,321.0Q247.0,290.0 296.0,290.0Q340.0,290.0 362.0,315.5Q384.0,341.0 384.0,379.0Q384.0,404.0 375.0,422.5Q366.0,441.0 350.0,454.0Q334.0,468.0 307.0,475.0Q280.0,482.0 216.0,482.0L198.0,482.0Q193.0,451.0 193.0,419.0Z" transform="translate(5376, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4528, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q477.0,566.0 536.5,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q930.0,566.0 981.0,550.0Q1032.0,534.0 1077.0,502.0Q1105.0,518.0 1138.5,529.5Q1172.0,541.0 1218.5,547.5Q1265.0,554.0 1333.0,554.0L1631.0,554.0L1631.0,482.0L1461.0,482.0L1461.0,0.0L1375.0,0.0L1375.0,482.0L1310.0,482.0Q1257.0,482.0 1215.5,476.5Q1174.0,471.0 1135.0,452.0Q1184.0,403.0 1212.0,336.0Q1240.0,269.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,262.0 936.0,328.5Q960.0,395.0 1016.0,454.0Q980.0,475.0 942.5,484.0Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.0,88.0Q1038.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,255.0 1130.5,314.5Q1106.0,374.0 1071.0,410.0Q1034.0,374.0 1015.0,314.5Q996.0,255.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(6206, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(7823, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(6854, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8840 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M338.0,-321.0Q246.0,-321.0 185.0,-290.0Q124.0,-259.0 93.5,-207.5Q63.0,-156.0 63.0,-95.0Q63.0,-40.0 81.5,-0.5Q100.0,39.0 131.0,65.0Q183.0,109.0 262.5,122.0Q342.0,135.0 432.0,135.0L521.0,135.0Q634.0,135.0 708.5,147.5Q783.0,160.0 823.0,196.0Q871.0,241.0 871.0,334.0Q871.0,413.0 829.5,453.0Q788.0,493.0 726.0,493.0Q667.0,493.0 635.0,457.0Q616.0,434.0 608.0,403.5Q600.0,373.0 600.0,319.0L600.0,205.0L513.0,205.0L513.0,297.0Q513.0,357.0 496.5,402.0Q480.0,447.0 441.5,471.5Q403.0,496.0 337.0,496.0Q314.0,496.0 299.5,494.5Q285.0,493.0 271.0,490.0Q329.0,478.0 366.5,439.5Q404.0,401.0 404.0,342.0Q404.0,270.0 357.5,227.0Q311.0,184.0 235.0,184.0Q150.0,184.0 106.5,230.5Q63.0,277.0 63.0,345.0Q63.0,415.0 100.0,464.5Q137.0,514.0 198.5,540.0Q260.0,566.0 331.0,566.0Q397.0,566.0 440.5,550.0Q484.0,534.0 510.0,508.5Q536.0,483.0 551.0,455.0Q575.0,508.0 619.5,537.0Q664.0,566.0 729.0,566.0Q804.0,566.0 855.0,536.5Q906.0,507.0 932.5,455.0Q959.0,403.0 959.0,335.0Q959.0,268.0 939.0,221.0Q919.0,174.0 883.0,143.0Q845.0,110.0 791.5,93.0Q738.0,76.0 674.5,69.5Q611.0,63.0 542.0,63.0L448.0,63.0Q348.0,63.0 285.0,53.0Q222.0,43.0 187.0,8.0Q168.0,-11.0 159.5,-36.0Q151.0,-61.0 151.0,-93.0Q151.0,-147.0 176.5,-181.0Q202.0,-215.0 245.0,-231.5Q288.0,-248.0 340.0,-248.0Q382.0,-248.0 413.5,-239.5Q445.0,-231.0 467.0,-212.0Q493.0,-189.0 503.0,-158.0Q513.0,-127.0 513.0,-73.0L513.0,-11.0L600.0,-11.0L600.0,-47.0Q600.0,-87.0 605.0,-120.0Q610.0,-153.0 622.0,-178.0Q639.0,-212.0 669.5,-230.0Q700.0,-248.0 749.0,-248.0Q781.0,-248.0 809.0,-234.5Q837.0,-221.0 854.5,-190.0Q872.0,-159.0 872.0,-105.0Q872.0,-77.0 865.0,-42.0Q858.0,-7.0 847.0,16.0L932.0,45.0Q945.0,11.0 952.0,-24.0Q959.0,-59.0 959.0,-108.0Q959.0,-177.0 931.5,-224.5Q904.0,-272.0 856.5,-296.5Q809.0,-321.0 750.0,-321.0Q692.0,-321.0 653.5,-305.0Q615.0,-289.0 591.5,-263.5Q568.0,-238.0 556.0,-210.0Q527.0,-264.0 471.5,-292.5Q416.0,-321.0 338.0,-321.0ZM142.0,348.0Q142.0,305.0 163.5,278.5Q185.0,252.0 234.0,252.0Q273.0,252.0 297.5,274.0Q322.0,296.0 322.0,335.0Q322.0,386.0 283.0,416.0Q244.0,446.0 185.0,448.0Q162.0,427.0 152.0,401.5Q142.0,376.0 142.0,348.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1022, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(335, 870)"/>
<path d="M-412.0,660.0Q-496.0,660.0 -541.0,700.5Q-586.0,741.0 -586.0,815.0Q-586.0,844.0 -578.0,870.0L-510.0,856.0Q-513.0,846.0 -514.0,835.5Q-515.0,825.0 -515.0,817.0Q-515.0,781.0 -500.5,761.0Q-486.0,741.0 -462.0,733.0Q-438.0,725.0 -412.0,725.0Q-371.0,725.0 -340.0,746.0Q-309.0,767.0 -309.0,819.0Q-309.0,827.0 -310.0,836.5Q-311.0,846.0 -314.0,856.0L-245.0,870.0Q-242.0,858.0 -240.0,843.0Q-238.0,828.0 -238.0,815.0Q-238.0,742.0 -284.5,701.0Q-331.0,660.0 -412.0,660.0ZM-413.0,767.0Q-435.0,767.0 -449.0,781.0Q-463.0,795.0 -463.0,818.0Q-463.0,839.0 -449.0,853.5Q-435.0,868.0 -413.0,868.0Q-391.0,868.0 -376.5,853.5Q-362.0,839.0 -362.0,818.0Q-362.0,795.0 -376.5,781.0Q-391.0,767.0 -413.0,767.0ZM-171.0,870.0L-103.0,870.0L-103.0,659.0L-171.0,659.0L-171.0,870.0ZM-41.0,870.0L27.0,870.0L27.0,659.0L-41.0,659.0L-41.0,870.0Z" transform="translate(789, 1105)"/>
<path d="M570.0,566.0Q684.0,566.0 744.5,482.0Q805.0,398.0 805.0,244.0Q805.0,122.0 774.0,44.5Q743.0,-33.0 690.0,-77.0Q632.0,-124.0 554.0,-140.0Q476.0,-156.0 388.0,-156.0L270.0,-156.0Q228.0,-156.0 205.0,-162.0Q182.0,-168.0 165.0,-179.0Q149.0,-190.0 140.0,-210.0Q131.0,-230.0 131.0,-263.0Q131.0,-293.0 134.0,-317.0L52.0,-321.0Q49.0,-303.0 47.0,-281.5Q45.0,-260.0 45.0,-243.0Q45.0,-199.0 61.0,-168.5Q77.0,-138.0 102.0,-119.0Q128.0,-100.0 160.5,-92.0Q193.0,-84.0 243.0,-84.0L366.0,-84.0Q459.0,-84.0 525.0,-70.5Q591.0,-57.0 633.5,-22.0Q676.0,13.0 696.0,78.5Q716.0,144.0 716.0,247.0Q716.0,338.0 696.5,392.0Q677.0,446.0 642.5,470.0Q608.0,494.0 563.0,494.0Q537.0,494.0 514.0,485.5Q491.0,477.0 474.0,458.0Q454.0,435.0 446.0,404.0Q438.0,373.0 438.0,319.0L438.0,0.0L352.0,0.0L352.0,321.0Q352.0,370.0 347.0,404.5Q342.0,439.0 327.0,461.0Q317.0,476.0 301.0,485.0Q285.0,494.0 262.0,494.0Q239.0,494.0 223.5,485.5Q208.0,477.0 197.0,463.0Q181.0,441.0 176.5,406.0Q172.0,371.0 172.0,327.0L172.0,0.0L86.0,0.0L86.0,341.0Q86.0,414.0 97.0,453.5Q108.0,493.0 139.0,524.0Q181.0,566.0 255.0,566.0Q355.0,566.0 399.0,472.0Q420.0,513.0 462.5,539.5Q505.0,566.0 570.0,566.0Z" transform="translate(2070, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(2939, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(2328, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L917.0,72.0L945.0,184.0Q853.0,192.0 794.0,241.0Q735.0,290.0 735.0,384.0Q735.0,435.0 755.5,476.0Q776.0,517.0 815.0,541.5Q854.0,566.0 909.0,566.0Q966.0,566.0 1001.5,544.0Q1037.0,522.0 1053.0,485.5Q1069.0,449.0 1069.0,406.0Q1069.0,371.0 1063.5,334.0Q1058.0,297.0 1048.0,256.0Q1098.0,264.0 1132.0,285.5Q1166.0,307.0 1188.0,328.0L1269.0,328.0L1269.0,0.0L984.0,0.0L912.0,-284.0L833.0,-262.0L899.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,285.5Q422.0,243.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM818.0,382.0Q818.0,319.0 858.0,288.0Q898.0,257.0 962.0,253.0Q982.0,340.0 982.0,403.0Q982.0,447.0 963.0,470.5Q944.0,494.0 909.0,494.0Q868.0,494.0 843.0,466.0Q818.0,438.0 818.0,382.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM1192.0,247.0Q1166.0,225.0 1125.0,206.5Q1084.0,188.0 1030.0,183.0L1002.0,72.0L1188.0,72.0L1188.0,153.0Q1188.0,176.0 1189.0,201.0Q1190.0,226.0 1192.0,247.0Z" transform="translate(3978, 870)"/>
<path d="M388.0,13.0Q284.0,13.0 200.5,40.5Q117.0,68.0 64.0,105.0L106.0,174.0Q152.0,140.0 221.5,113.0Q291.0,86.0 385.0,86.0Q471.0,86.0 539.0,117.0Q607.0,148.0 646.5,218.5Q686.0,289.0 686.0,408.0Q686.0,490.0 657.5,553.0Q629.0,616.0 573.5,652.5Q518.0,689.0 436.0,689.0Q349.0,689.0 293.0,650.0Q237.0,611.0 213.0,554.0L234.0,554.0Q302.0,554.0 342.5,543.0Q383.0,532.0 411.0,509.0Q437.0,487.0 453.0,455.5Q469.0,424.0 469.0,378.0Q469.0,304.0 421.5,260.5Q374.0,217.0 300.0,217.0Q230.0,217.0 188.0,246.5Q146.0,276.0 127.0,323.5Q108.0,371.0 108.0,424.0Q108.0,453.0 113.0,482.0L-365.0,482.0L-365.0,554.0L124.0,554.0Q145.0,615.0 187.5,662.5Q230.0,710.0 293.0,737.0Q356.0,764.0 439.0,764.0Q545.0,764.0 619.5,719.0Q694.0,674.0 733.5,594.0Q773.0,514.0 773.0,408.0Q773.0,266.0 722.5,179.0Q672.0,92.0 585.0,52.5Q498.0,13.0 388.0,13.0ZM193.0,419.0Q193.0,352.0 220.0,321.0Q247.0,290.0 296.0,290.0Q340.0,290.0 362.0,315.5Q384.0,341.0 384.0,379.0Q384.0,404.0 375.0,422.5Q366.0,441.0 350.0,454.0Q334.0,468.0 307.0,475.0Q280.0,482.0 216.0,482.0L198.0,482.0Q193.0,451.0 193.0,419.0Z" transform="translate(5323, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(4475, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,342.0 100.5,414.5Q144.0,487.0 223.0,526.5Q302.0,566.0 408.0,566.0Q477.0,566.0 536.5,550.5Q596.0,535.0 652.0,501.0Q743.0,566.0 866.0,566.0Q930.0,566.0 981.0,550.0Q1032.0,534.0 1077.0,502.0Q1105.0,518.0 1138.5,529.5Q1172.0,541.0 1218.5,547.5Q1265.0,554.0 1333.0,554.0L1631.0,554.0L1631.0,482.0L1461.0,482.0L1461.0,0.0L1375.0,0.0L1375.0,482.0L1310.0,482.0Q1257.0,482.0 1215.5,476.5Q1174.0,471.0 1135.0,452.0Q1184.0,403.0 1212.0,336.0Q1240.0,269.0 1240.0,189.0Q1240.0,89.0 1196.5,38.5Q1153.0,-12.0 1077.0,-12.0Q1020.0,-12.0 983.5,14.0Q947.0,40.0 929.5,84.5Q912.0,129.0 912.0,186.0Q912.0,262.0 936.0,328.5Q960.0,395.0 1016.0,454.0Q980.0,475.0 942.5,484.0Q905.0,493.0 868.0,493.0Q823.0,493.0 784.0,484.5Q745.0,476.0 708.0,454.0Q763.0,403.0 794.0,336.5Q825.0,270.0 825.0,189.0Q825.0,89.0 781.5,38.5Q738.0,-12.0 663.0,-12.0Q605.0,-12.0 568.5,14.0Q532.0,40.0 514.5,84.5Q497.0,129.0 497.0,186.0Q497.0,265.0 521.0,333.0Q545.0,401.0 593.0,450.0Q550.0,473.0 501.0,482.5Q452.0,492.0 398.0,492.0Q288.0,492.0 222.0,435.5Q156.0,379.0 140.0,290.0Q166.0,308.0 197.0,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM996.0,189.0Q996.0,120.0 1017.0,88.0Q1038.0,56.0 1074.0,56.0Q1106.0,56.0 1123.5,75.0Q1141.0,94.0 1148.0,123.0Q1155.0,152.0 1155.0,182.0Q1155.0,255.0 1130.5,314.5Q1106.0,374.0 1071.0,410.0Q1034.0,374.0 1015.0,314.5Q996.0,255.0 996.0,189.0ZM581.0,189.0Q581.0,120.0 602.0,88.0Q623.0,56.0 660.0,56.0Q691.0,56.0 708.5,75.0Q726.0,94.0 733.0,123.0Q740.0,152.0 740.0,182.0Q740.0,251.0 717.0,307.5Q694.0,364.0 650.0,407.0Q612.0,364.0 596.5,305.5Q581.0,247.0 581.0,189.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q141.0,126.0 173.5,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(6153, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(7770, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(6801, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஞூஂவஂ</span> (Added by SIESTA)</li>


<pre>Expected: nyauuvowelsigntamil=0+1558|anusvaratamil=0@-940,0+0|vatamil=3+1044|anusvaratamil=3@-698,0+0</pre>



<pre>Got     : nyauuvowelsigntamil=0+1589|anusvaratamil=0@-971,0+0|vatamil=3+1044|anusvaratamil=3@-698,0+0</pre>



<pre>                                  +                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2633 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.5,14.0Q109.0,40.0 83.0,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,284.0Q633.0,297.0 661.5,308.0Q690.0,319.0 726.0,319.0Q807.0,319.0 857.5,259.0Q908.0,199.0 908.0,89.0Q908.0,39.0 897.5,-4.0Q887.0,-47.0 866.0,-84.0L1052.0,-84.0L1052.0,554.0L1572.0,554.0L1572.0,481.0L1398.0,481.0L1398.0,-156.0L1312.0,-156.0L1312.0,481.0L1138.0,481.0L1138.0,-156.0L822.0,-156.0Q770.0,-214.0 694.0,-250.5Q618.0,-287.0 528.0,-304.0Q438.0,-321.0 342.0,-321.0L320.0,-321.0Q266.0,-321.0 215.5,-312.5Q165.0,-304.0 125.0,-285.5Q85.0,-267.0 61.5,-237.5Q38.0,-208.0 38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.5,-88.5Q122.0,-84.0 165.0,-84.0L770.0,-84.0Q820.0,-14.0 820.0,93.0Q820.0,167.0 791.5,207.0Q763.0,247.0 710.0,247.0Q682.0,247.0 658.0,236.0Q634.0,225.0 614.0,211.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,285.5Q422.0,243.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 136.0,212.0Q140.0,129.0 172.5,92.5Q205.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM343.0,-249.0Q463.0,-249.0 553.5,-226.5Q644.0,-204.0 712.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-209.0 173.5,-229.0Q226.0,-249.0 327.0,-249.0L343.0,-249.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(618, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1589, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1935, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2602 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.5,14.0Q109.0,40.0 83.0,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,284.0Q633.0,297.0 661.5,308.0Q690.0,319.0 726.0,319.0Q807.0,319.0 857.5,259.0Q908.0,199.0 908.0,89.0Q908.0,39.0 897.5,-4.0Q887.0,-47.0 866.0,-84.0L1052.0,-84.0L1052.0,554.0L1572.0,554.0L1572.0,481.0L1398.0,481.0L1398.0,-156.0L1312.0,-156.0L1312.0,481.0L1138.0,481.0L1138.0,-156.0L822.0,-156.0Q770.0,-214.0 694.0,-250.5Q618.0,-287.0 528.0,-304.0Q438.0,-321.0 342.0,-321.0L320.0,-321.0Q266.0,-321.0 215.5,-312.5Q165.0,-304.0 125.0,-285.5Q85.0,-267.0 61.5,-237.5Q38.0,-208.0 38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.5,-88.5Q122.0,-84.0 165.0,-84.0L770.0,-84.0Q820.0,-14.0 820.0,93.0Q820.0,167.0 791.5,207.0Q763.0,247.0 710.0,247.0Q682.0,247.0 658.0,236.0Q634.0,225.0 614.0,211.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,285.5Q422.0,243.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 136.0,212.0Q140.0,129.0 172.5,92.5Q205.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM343.0,-249.0Q463.0,-249.0 553.5,-226.5Q644.0,-204.0 712.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-209.0 173.5,-229.0Q226.0,-249.0 327.0,-249.0L343.0,-249.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(618, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1558, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(1904, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">பௗஂஎஷஸ்ரீஆ॒</span> (Added by SIESTA)</li>


<pre>Expected: patamil=0+778|aulengthmarktamil=0+1039|anusvaratamil=0@-1604,0+0|etamil=3+770|ssatamil=4+1345|shritamil=5+1514|aatamil=9+1313|uni0952=9@-378,-317+0</pre>



<pre>Got     : patamil=0+778|aulengthmarktamil=0+1070|anusvaratamil=0@-1635,0+0|etamil=3+770|ssatamil=4+1345|shritamil=5+1514|aatamil=9+1313|uni0952=9@-378,-317+0</pre>



<pre>                                              ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6790 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M88.0,0.0L88.0,554.0L174.0,554.0L174.0,72.0L604.0,72.0L604.0,554.0L690.0,554.0L690.0,0.0L88.0,0.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(778, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(213, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1848, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L917.0,72.0L945.0,184.0Q853.0,192.0 794.0,241.0Q735.0,290.0 735.0,384.0Q735.0,435.0 755.5,476.0Q776.0,517.0 815.0,541.5Q854.0,566.0 909.0,566.0Q966.0,566.0 1001.5,544.0Q1037.0,522.0 1053.0,485.5Q1069.0,449.0 1069.0,406.0Q1069.0,371.0 1063.5,334.0Q1058.0,297.0 1048.0,256.0Q1098.0,264.0 1132.0,285.5Q1166.0,307.0 1188.0,328.0L1269.0,328.0L1269.0,0.0L984.0,0.0L912.0,-284.0L833.0,-262.0L899.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,285.5Q422.0,243.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM818.0,382.0Q818.0,319.0 858.0,288.0Q898.0,257.0 962.0,253.0Q982.0,340.0 982.0,403.0Q982.0,447.0 963.0,470.5Q944.0,494.0 909.0,494.0Q868.0,494.0 843.0,466.0Q818.0,438.0 818.0,382.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM1192.0,247.0Q1166.0,225.0 1125.0,206.5Q1084.0,188.0 1030.0,183.0L1002.0,72.0L1188.0,72.0L1188.0,153.0Q1188.0,176.0 1189.0,201.0Q1190.0,226.0 1192.0,247.0Z" transform="translate(2618, 870)"/>
<path d="M88.0,0.0L88.0,554.0L174.0,554.0L174.0,72.0L546.0,72.0L546.0,342.0Q546.0,414.0 557.0,453.5Q568.0,493.0 599.0,524.0Q641.0,566.0 715.0,566.0Q752.0,566.0 778.5,552.5Q805.0,539.0 827.0,510.0L827.0,554.0L1077.0,554.0Q1067.0,586.0 1067.0,623.0Q1067.0,682.0 1094.5,732.0Q1122.0,782.0 1179.5,812.5Q1237.0,843.0 1326.0,843.0Q1412.0,843.0 1457.0,808.5Q1502.0,774.0 1502.0,718.0Q1502.0,655.0 1464.0,624.5Q1426.0,594.0 1372.0,594.0Q1313.0,594.0 1278.0,623.5Q1243.0,653.0 1243.0,705.0Q1243.0,719.0 1246.0,736.5Q1249.0,754.0 1257.0,772.0Q1199.0,756.0 1171.5,716.5Q1144.0,677.0 1144.0,626.0Q1144.0,605.0 1148.0,587.0Q1152.0,569.0 1159.0,554.0L1334.0,554.0L1334.0,482.0L1159.0,482.0L1159.0,323.0Q1184.0,339.0 1212.0,350.5Q1240.0,362.0 1284.0,362.0Q1334.0,362.0 1375.0,337.0Q1416.0,312.0 1440.5,262.5Q1465.0,213.0 1465.0,141.0Q1465.0,15.0 1403.0,-77.5Q1341.0,-170.0 1225.0,-228.0Q1131.0,-274.0 1005.5,-297.5Q880.0,-321.0 728.0,-321.0L619.0,-321.0Q456.0,-321.0 359.0,-307.5Q262.0,-294.0 209.0,-269.0Q169.0,-249.0 152.0,-224.0Q135.0,-199.0 135.0,-168.0Q135.0,-140.0 151.5,-115.0Q168.0,-90.0 206.0,-74.0Q244.0,-58.0 309.0,-58.0Q357.0,-58.0 397.0,-64.0Q437.0,-70.0 471.0,-78.0L456.0,-150.0Q424.0,-142.0 386.5,-135.5Q349.0,-129.0 314.0,-129.0Q262.0,-129.0 241.5,-139.5Q221.0,-150.0 221.0,-170.0Q221.0,-184.0 238.5,-198.0Q256.0,-212.0 301.5,-223.5Q347.0,-235.0 431.5,-241.5Q516.0,-248.0 650.0,-248.0L694.0,-248.0Q831.0,-248.0 942.0,-232.0Q1053.0,-216.0 1137.0,-182.0Q1254.0,-135.0 1315.5,-54.5Q1377.0,26.0 1377.0,141.0Q1377.0,219.0 1346.0,254.0Q1315.0,289.0 1269.0,289.0Q1234.0,289.0 1207.5,276.0Q1181.0,263.0 1159.0,246.0L1159.0,0.0L1073.0,0.0L1073.0,482.0L898.0,482.0L898.0,0.0L812.0,0.0L812.0,336.0Q812.0,373.0 806.0,409.0Q800.0,445.0 781.0,469.5Q762.0,494.0 722.0,494.0Q699.0,494.0 683.5,485.5Q668.0,477.0 657.0,463.0Q641.0,441.0 636.5,406.0Q632.0,371.0 632.0,327.0L632.0,0.0L88.0,0.0ZM1309.0,719.0Q1309.0,685.0 1327.0,670.5Q1345.0,656.0 1372.0,656.0Q1401.0,656.0 1416.5,672.0Q1432.0,688.0 1432.0,713.0Q1432.0,748.0 1404.0,764.0Q1376.0,780.0 1332.0,780.0Q1330.0,780.0 1328.0,780.0Q1318.0,765.0 1313.5,749.5Q1309.0,734.0 1309.0,719.0Z" transform="translate(3963, 870)"/>
<path d="M379.0,397.0Q379.0,360.0 401.5,334.5Q424.0,309.0 465.0,309.0Q503.0,309.0 525.5,332.5Q548.0,356.0 548.0,400.0Q548.0,428.0 540.5,451.5Q533.0,475.0 514.0,496.0Q504.0,497.0 493.0,497.0Q446.0,497.0 412.5,472.0Q379.0,447.0 379.0,397.0ZM344.0,-51.0Q482.0,-51.0 568.0,-7.5Q654.0,36.0 695.0,104.0L217.0,104.0Q186.0,104.0 169.5,103.0Q153.0,102.0 145.0,99.0Q137.0,96.0 129.0,90.0Q114.0,78.0 114.0,56.0Q114.0,7.0 167.0,-22.0Q220.0,-51.0 327.0,-51.0L344.0,-51.0ZM321.0,-124.0Q176.0,-124.0 102.5,-72.5Q29.0,-21.0 29.0,60.0Q29.0,85.0 40.0,109.0Q51.0,133.0 74.0,149.0Q87.0,158.0 102.0,164.0Q117.0,170.0 141.5,173.0Q166.0,176.0 206.0,176.0L721.0,176.0Q730.0,211.0 730.0,251.0Q730.0,323.0 699.0,385.5Q668.0,448.0 601.0,477.0Q612.0,459.0 619.0,438.5Q626.0,418.0 626.0,396.0Q626.0,326.0 584.0,283.5Q542.0,241.0 463.0,241.0Q395.0,241.0 347.5,279.0Q300.0,317.0 300.0,393.0Q300.0,455.0 329.0,493.0Q358.0,531.0 404.5,548.5Q451.0,566.0 503.0,566.0Q580.0,566.0 638.5,540.0Q697.0,514.0 736.5,469.0Q776.0,424.0 796.0,368.0Q816.0,312.0 816.0,252.0Q816.0,212.0 810.0,176.0L947.0,176.0L947.0,554.0L1033.0,554.0L1033.0,70.0Q1053.0,82.0 1080.0,91.0Q1107.0,100.0 1145.0,100.0Q1186.0,100.0 1223.5,82.0Q1261.0,64.0 1285.0,27.5Q1309.0,-9.0 1309.0,-65.0Q1309.0,-141.0 1263.0,-199.0Q1217.0,-257.0 1131.5,-289.0Q1046.0,-321.0 928.0,-321.0L922.0,-321.0Q792.0,-321.0 720.0,-277.5Q648.0,-234.0 648.0,-154.0Q648.0,-125.0 662.5,-99.5Q677.0,-74.0 707.5,-57.5Q738.0,-41.0 784.0,-41.0Q810.0,-41.0 838.0,-46.5Q866.0,-52.0 891.0,-62.0L877.0,-127.0Q855.0,-120.0 832.5,-115.0Q810.0,-110.0 790.0,-110.0Q759.0,-110.0 742.0,-122.0Q725.0,-134.0 725.0,-157.0Q725.0,-181.0 743.5,-202.0Q762.0,-223.0 806.0,-236.0Q850.0,-249.0 926.0,-249.0L933.0,-249.0Q1019.0,-249.0 1084.5,-227.5Q1150.0,-206.0 1187.5,-164.0Q1225.0,-122.0 1225.0,-63.0Q1225.0,-19.0 1200.0,6.0Q1175.0,31.0 1131.0,31.0Q1099.0,31.0 1074.5,22.5Q1050.0,14.0 1033.0,1.0L1033.0,-124.0L947.0,-124.0L947.0,104.0L789.0,104.0Q756.0,30.0 691.0,-21.0Q626.0,-72.0 537.0,-98.0Q448.0,-124.0 342.0,-124.0L321.0,-124.0Z" transform="translate(5477, 870)"/>
<path d="M-65.0,-182.0L-491.0,-182.0L-491.0,-111.0L-65.0,-111.0L-65.0,-182.0Z" transform="translate(6412, 553)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6759 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M88.0,0.0L88.0,554.0L174.0,554.0L174.0,72.0L604.0,72.0L604.0,554.0L690.0,554.0L690.0,0.0L88.0,0.0Z" transform="translate(0, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,325.0 81.5,385.5Q106.0,446.0 149.0,486.0Q192.0,526.0 246.0,546.0Q300.0,566.0 358.0,566.0Q421.0,566.0 466.5,548.5Q512.0,531.0 549.0,502.0L549.0,554.0L1053.0,554.0L1053.0,482.0L883.0,482.0L883.0,0.0L797.0,0.0L797.0,482.0L623.0,482.0L623.0,0.0L537.0,0.0L537.0,407.0Q503.0,448.0 459.5,470.0Q416.0,492.0 355.0,492.0Q267.0,492.0 210.0,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(778, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(213, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(1817, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L917.0,72.0L945.0,184.0Q853.0,192.0 794.0,241.0Q735.0,290.0 735.0,384.0Q735.0,435.0 755.5,476.0Q776.0,517.0 815.0,541.5Q854.0,566.0 909.0,566.0Q966.0,566.0 1001.5,544.0Q1037.0,522.0 1053.0,485.5Q1069.0,449.0 1069.0,406.0Q1069.0,371.0 1063.5,334.0Q1058.0,297.0 1048.0,256.0Q1098.0,264.0 1132.0,285.5Q1166.0,307.0 1188.0,328.0L1269.0,328.0L1269.0,0.0L984.0,0.0L912.0,-284.0L833.0,-262.0L899.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,285.5Q422.0,243.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM818.0,382.0Q818.0,319.0 858.0,288.0Q898.0,257.0 962.0,253.0Q982.0,340.0 982.0,403.0Q982.0,447.0 963.0,470.5Q944.0,494.0 909.0,494.0Q868.0,494.0 843.0,466.0Q818.0,438.0 818.0,382.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0ZM1192.0,247.0Q1166.0,225.0 1125.0,206.5Q1084.0,188.0 1030.0,183.0L1002.0,72.0L1188.0,72.0L1188.0,153.0Q1188.0,176.0 1189.0,201.0Q1190.0,226.0 1192.0,247.0Z" transform="translate(2587, 870)"/>
<path d="M88.0,0.0L88.0,554.0L174.0,554.0L174.0,72.0L546.0,72.0L546.0,342.0Q546.0,414.0 557.0,453.5Q568.0,493.0 599.0,524.0Q641.0,566.0 715.0,566.0Q752.0,566.0 778.5,552.5Q805.0,539.0 827.0,510.0L827.0,554.0L1077.0,554.0Q1067.0,586.0 1067.0,623.0Q1067.0,682.0 1094.5,732.0Q1122.0,782.0 1179.5,812.5Q1237.0,843.0 1326.0,843.0Q1412.0,843.0 1457.0,808.5Q1502.0,774.0 1502.0,718.0Q1502.0,655.0 1464.0,624.5Q1426.0,594.0 1372.0,594.0Q1313.0,594.0 1278.0,623.5Q1243.0,653.0 1243.0,705.0Q1243.0,719.0 1246.0,736.5Q1249.0,754.0 1257.0,772.0Q1199.0,756.0 1171.5,716.5Q1144.0,677.0 1144.0,626.0Q1144.0,605.0 1148.0,587.0Q1152.0,569.0 1159.0,554.0L1334.0,554.0L1334.0,482.0L1159.0,482.0L1159.0,323.0Q1184.0,339.0 1212.0,350.5Q1240.0,362.0 1284.0,362.0Q1334.0,362.0 1375.0,337.0Q1416.0,312.0 1440.5,262.5Q1465.0,213.0 1465.0,141.0Q1465.0,15.0 1403.0,-77.5Q1341.0,-170.0 1225.0,-228.0Q1131.0,-274.0 1005.5,-297.5Q880.0,-321.0 728.0,-321.0L619.0,-321.0Q456.0,-321.0 359.0,-307.5Q262.0,-294.0 209.0,-269.0Q169.0,-249.0 152.0,-224.0Q135.0,-199.0 135.0,-168.0Q135.0,-140.0 151.5,-115.0Q168.0,-90.0 206.0,-74.0Q244.0,-58.0 309.0,-58.0Q357.0,-58.0 397.0,-64.0Q437.0,-70.0 471.0,-78.0L456.0,-150.0Q424.0,-142.0 386.5,-135.5Q349.0,-129.0 314.0,-129.0Q262.0,-129.0 241.5,-139.5Q221.0,-150.0 221.0,-170.0Q221.0,-184.0 238.5,-198.0Q256.0,-212.0 301.5,-223.5Q347.0,-235.0 431.5,-241.5Q516.0,-248.0 650.0,-248.0L694.0,-248.0Q831.0,-248.0 942.0,-232.0Q1053.0,-216.0 1137.0,-182.0Q1254.0,-135.0 1315.5,-54.5Q1377.0,26.0 1377.0,141.0Q1377.0,219.0 1346.0,254.0Q1315.0,289.0 1269.0,289.0Q1234.0,289.0 1207.5,276.0Q1181.0,263.0 1159.0,246.0L1159.0,0.0L1073.0,0.0L1073.0,482.0L898.0,482.0L898.0,0.0L812.0,0.0L812.0,336.0Q812.0,373.0 806.0,409.0Q800.0,445.0 781.0,469.5Q762.0,494.0 722.0,494.0Q699.0,494.0 683.5,485.5Q668.0,477.0 657.0,463.0Q641.0,441.0 636.5,406.0Q632.0,371.0 632.0,327.0L632.0,0.0L88.0,0.0ZM1309.0,719.0Q1309.0,685.0 1327.0,670.5Q1345.0,656.0 1372.0,656.0Q1401.0,656.0 1416.5,672.0Q1432.0,688.0 1432.0,713.0Q1432.0,748.0 1404.0,764.0Q1376.0,780.0 1332.0,780.0Q1330.0,780.0 1328.0,780.0Q1318.0,765.0 1313.5,749.5Q1309.0,734.0 1309.0,719.0Z" transform="translate(3932, 870)"/>
<path d="M379.0,397.0Q379.0,360.0 401.5,334.5Q424.0,309.0 465.0,309.0Q503.0,309.0 525.5,332.5Q548.0,356.0 548.0,400.0Q548.0,428.0 540.5,451.5Q533.0,475.0 514.0,496.0Q504.0,497.0 493.0,497.0Q446.0,497.0 412.5,472.0Q379.0,447.0 379.0,397.0ZM344.0,-51.0Q482.0,-51.0 568.0,-7.5Q654.0,36.0 695.0,104.0L217.0,104.0Q186.0,104.0 169.5,103.0Q153.0,102.0 145.0,99.0Q137.0,96.0 129.0,90.0Q114.0,78.0 114.0,56.0Q114.0,7.0 167.0,-22.0Q220.0,-51.0 327.0,-51.0L344.0,-51.0ZM321.0,-124.0Q176.0,-124.0 102.5,-72.5Q29.0,-21.0 29.0,60.0Q29.0,85.0 40.0,109.0Q51.0,133.0 74.0,149.0Q87.0,158.0 102.0,164.0Q117.0,170.0 141.5,173.0Q166.0,176.0 206.0,176.0L721.0,176.0Q730.0,211.0 730.0,251.0Q730.0,323.0 699.0,385.5Q668.0,448.0 601.0,477.0Q612.0,459.0 619.0,438.5Q626.0,418.0 626.0,396.0Q626.0,326.0 584.0,283.5Q542.0,241.0 463.0,241.0Q395.0,241.0 347.5,279.0Q300.0,317.0 300.0,393.0Q300.0,455.0 329.0,493.0Q358.0,531.0 404.5,548.5Q451.0,566.0 503.0,566.0Q580.0,566.0 638.5,540.0Q697.0,514.0 736.5,469.0Q776.0,424.0 796.0,368.0Q816.0,312.0 816.0,252.0Q816.0,212.0 810.0,176.0L947.0,176.0L947.0,554.0L1033.0,554.0L1033.0,70.0Q1053.0,82.0 1080.0,91.0Q1107.0,100.0 1145.0,100.0Q1186.0,100.0 1223.5,82.0Q1261.0,64.0 1285.0,27.5Q1309.0,-9.0 1309.0,-65.0Q1309.0,-141.0 1263.0,-199.0Q1217.0,-257.0 1131.5,-289.0Q1046.0,-321.0 928.0,-321.0L922.0,-321.0Q792.0,-321.0 720.0,-277.5Q648.0,-234.0 648.0,-154.0Q648.0,-125.0 662.5,-99.5Q677.0,-74.0 707.5,-57.5Q738.0,-41.0 784.0,-41.0Q810.0,-41.0 838.0,-46.5Q866.0,-52.0 891.0,-62.0L877.0,-127.0Q855.0,-120.0 832.5,-115.0Q810.0,-110.0 790.0,-110.0Q759.0,-110.0 742.0,-122.0Q725.0,-134.0 725.0,-157.0Q725.0,-181.0 743.5,-202.0Q762.0,-223.0 806.0,-236.0Q850.0,-249.0 926.0,-249.0L933.0,-249.0Q1019.0,-249.0 1084.5,-227.5Q1150.0,-206.0 1187.5,-164.0Q1225.0,-122.0 1225.0,-63.0Q1225.0,-19.0 1200.0,6.0Q1175.0,31.0 1131.0,31.0Q1099.0,31.0 1074.5,22.5Q1050.0,14.0 1033.0,1.0L1033.0,-124.0L947.0,-124.0L947.0,104.0L789.0,104.0Q756.0,30.0 691.0,-21.0Q626.0,-72.0 537.0,-98.0Q448.0,-124.0 342.0,-124.0L321.0,-124.0Z" transform="translate(5446, 870)"/>
<path d="M-65.0,-182.0L-491.0,-182.0L-491.0,-111.0L-65.0,-111.0L-65.0,-182.0Z" transform="translate(6381, 553)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">வூஂ𑌼த²</span> (Added by SIESTA)</li>


<pre>Expected: vauuvowelsigntamil=0+1214|anusvaratamil=0@-784,0+0|uni25CC=0+562|u1133C=0+0|tatamil=4+752|uni00B2=5+312</pre>



<pre>Got     : vauuvowelsigntamil=0+1214|anusvaratamil=0@-784,0+0|uni25CC=0+562|u1133C=0@46,-54+0|tatamil=4+752|uni00B2=5+312</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2840 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,72.0Q975.0,85.0 1000.5,93.0Q1026.0,101.0 1058.0,101.0Q1098.0,101.0 1132.5,85.0Q1167.0,69.0 1188.0,35.5Q1209.0,2.0 1209.0,-49.0Q1209.0,-116.0 1177.0,-164.0Q1145.0,-212.0 1083.0,-244.0Q1004.0,-285.0 881.0,-303.0Q758.0,-321.0 596.0,-321.0L545.0,-321.0Q401.0,-321.0 309.0,-308.5Q217.0,-296.0 165.0,-274.0Q120.0,-254.0 101.5,-227.5Q83.0,-201.0 83.0,-168.0Q83.0,-140.0 99.5,-115.0Q116.0,-90.0 154.5,-74.0Q193.0,-58.0 258.0,-58.0Q305.0,-58.0 345.0,-64.0Q385.0,-70.0 419.0,-78.0L404.0,-150.0Q372.0,-142.0 334.5,-135.5Q297.0,-129.0 262.0,-129.0Q210.0,-129.0 189.5,-139.5Q169.0,-150.0 169.0,-170.0Q169.0,-184.0 186.0,-198.0Q203.0,-212.0 247.0,-223.5Q291.0,-235.0 370.0,-241.5Q449.0,-248.0 572.0,-248.0L585.0,-248.0Q882.0,-248.0 1013.0,-192.0Q1125.0,-144.0 1125.0,-51.0Q1125.0,-7.0 1103.0,12.0Q1081.0,31.0 1042.0,31.0Q1016.0,31.0 993.5,21.0Q971.0,11.0 956.0,-1.0L956.0,-148.0L870.0,-148.0L870.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(430, 870)"/>
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(1214, 870)"/>
<path d="M-430.0,-146.0Q-430.0,-120.0 -413.0,-102.5Q-396.0,-85.0 -373.0,-85.0Q-349.0,-85.0 -332.0,-102.5Q-315.0,-120.0 -315.0,-146.0Q-315.0,-171.0 -332.0,-188.5Q-349.0,-206.0 -373.0,-206.0Q-396.0,-206.0 -413.0,-188.5Q-430.0,-171.0 -430.0,-146.0ZM-242.0,-146.0Q-242.0,-120.0 -225.0,-102.5Q-208.0,-85.0 -185.0,-85.0Q-161.0,-85.0 -144.0,-102.5Q-127.0,-120.0 -127.0,-146.0Q-127.0,-171.0 -144.0,-188.5Q-161.0,-206.0 -185.0,-206.0Q-208.0,-206.0 -225.0,-188.5Q-242.0,-171.0 -242.0,-146.0Z" transform="translate(1822, 816)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,152.0Q49.0,204.0 75.5,243.0Q102.0,282.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0Q578.0,326.0 641.5,303.5Q705.0,281.0 741.0,231.0Q777.0,181.0 777.0,98.0Q777.0,31.0 752.0,-14.5Q727.0,-60.0 681.0,-94.0Q632.0,-129.0 562.5,-142.5Q493.0,-156.0 385.0,-156.0L272.0,-156.0Q230.0,-156.0 207.0,-162.0Q184.0,-168.0 167.0,-179.0Q151.0,-190.0 142.0,-210.0Q133.0,-230.0 133.0,-263.0Q133.0,-293.0 136.0,-317.0L54.0,-321.0Q51.0,-303.0 49.0,-281.5Q47.0,-260.0 47.0,-243.0Q47.0,-199.0 63.0,-168.5Q79.0,-138.0 104.0,-119.0Q130.0,-100.0 162.5,-92.0Q195.0,-84.0 245.0,-84.0L354.0,-84.0Q443.0,-84.0 500.0,-76.5Q557.0,-69.0 592.0,-53.5Q627.0,-38.0 650.0,-13.0Q691.0,31.0 691.0,105.0Q691.0,164.0 663.0,196.5Q635.0,229.0 590.0,242.0Q545.0,255.0 496.0,257.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0Z" transform="translate(1776, 870)"/>
<path d="M15.0,369.0L15.0,423.0L130.0,535.0Q170.0,574.0 191.0,598.5Q212.0,623.0 219.5,642.5Q227.0,662.0 227.0,684.0Q227.0,716.0 208.5,732.0Q190.0,748.0 160.0,748.0Q130.0,748.0 105.5,736.5Q81.0,725.0 55.0,705.0L20.0,751.0Q49.0,776.0 83.5,791.0Q118.0,806.0 161.0,806.0Q225.0,806.0 261.5,774.5Q298.0,743.0 298.0,688.0Q298.0,639.0 268.5,600.0Q239.0,561.0 183.0,508.0L102.0,431.0L297.0,431.0L297.0,369.0L15.0,369.0Z" transform="translate(2528, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2840 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.5Q108.0,41.0 82.5,97.0Q57.0,153.0 57.0,243.0Q57.0,350.0 99.5,422.0Q142.0,494.0 212.0,530.0Q282.0,566.0 364.0,566.0Q466.0,566.0 529.0,527.0Q592.0,488.0 621.5,423.5Q651.0,359.0 651.0,280.0Q651.0,216.0 637.0,166.0Q623.0,116.0 603.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,72.0Q975.0,85.0 1000.5,93.0Q1026.0,101.0 1058.0,101.0Q1098.0,101.0 1132.5,85.0Q1167.0,69.0 1188.0,35.5Q1209.0,2.0 1209.0,-49.0Q1209.0,-116.0 1177.0,-164.0Q1145.0,-212.0 1083.0,-244.0Q1004.0,-285.0 881.0,-303.0Q758.0,-321.0 596.0,-321.0L545.0,-321.0Q401.0,-321.0 309.0,-308.5Q217.0,-296.0 165.0,-274.0Q120.0,-254.0 101.5,-227.5Q83.0,-201.0 83.0,-168.0Q83.0,-140.0 99.5,-115.0Q116.0,-90.0 154.5,-74.0Q193.0,-58.0 258.0,-58.0Q305.0,-58.0 345.0,-64.0Q385.0,-70.0 419.0,-78.0L404.0,-150.0Q372.0,-142.0 334.5,-135.5Q297.0,-129.0 262.0,-129.0Q210.0,-129.0 189.5,-139.5Q169.0,-150.0 169.0,-170.0Q169.0,-184.0 186.0,-198.0Q203.0,-212.0 247.0,-223.5Q291.0,-235.0 370.0,-241.5Q449.0,-248.0 572.0,-248.0L585.0,-248.0Q882.0,-248.0 1013.0,-192.0Q1125.0,-144.0 1125.0,-51.0Q1125.0,-7.0 1103.0,12.0Q1081.0,31.0 1042.0,31.0Q1016.0,31.0 993.5,21.0Q971.0,11.0 956.0,-1.0L956.0,-148.0L870.0,-148.0L870.0,0.0L515.0,0.0L511.0,63.0Q534.0,98.0 548.5,149.5Q563.0,201.0 563.0,269.0Q563.0,376.0 508.0,434.0Q453.0,492.0 360.0,492.0Q268.0,492.0 210.5,435.5Q153.0,379.0 140.0,290.0Q166.0,307.0 197.0,317.5Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q217.0,258.0 189.0,245.5Q161.0,233.0 137.0,212.0Q141.0,126.0 174.0,91.0Q207.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(430, 870)"/>
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(1214, 870)"/>
<path d="M-430.0,-146.0Q-430.0,-120.0 -413.0,-102.5Q-396.0,-85.0 -373.0,-85.0Q-349.0,-85.0 -332.0,-102.5Q-315.0,-120.0 -315.0,-146.0Q-315.0,-171.0 -332.0,-188.5Q-349.0,-206.0 -373.0,-206.0Q-396.0,-206.0 -413.0,-188.5Q-430.0,-171.0 -430.0,-146.0ZM-242.0,-146.0Q-242.0,-120.0 -225.0,-102.5Q-208.0,-85.0 -185.0,-85.0Q-161.0,-85.0 -144.0,-102.5Q-127.0,-120.0 -127.0,-146.0Q-127.0,-171.0 -144.0,-188.5Q-161.0,-206.0 -185.0,-206.0Q-208.0,-206.0 -225.0,-188.5Q-242.0,-171.0 -242.0,-146.0Z" transform="translate(1776, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,152.0Q49.0,204.0 75.5,243.0Q102.0,282.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0Q578.0,326.0 641.5,303.5Q705.0,281.0 741.0,231.0Q777.0,181.0 777.0,98.0Q777.0,31.0 752.0,-14.5Q727.0,-60.0 681.0,-94.0Q632.0,-129.0 562.5,-142.5Q493.0,-156.0 385.0,-156.0L272.0,-156.0Q230.0,-156.0 207.0,-162.0Q184.0,-168.0 167.0,-179.0Q151.0,-190.0 142.0,-210.0Q133.0,-230.0 133.0,-263.0Q133.0,-293.0 136.0,-317.0L54.0,-321.0Q51.0,-303.0 49.0,-281.5Q47.0,-260.0 47.0,-243.0Q47.0,-199.0 63.0,-168.5Q79.0,-138.0 104.0,-119.0Q130.0,-100.0 162.5,-92.0Q195.0,-84.0 245.0,-84.0L354.0,-84.0Q443.0,-84.0 500.0,-76.5Q557.0,-69.0 592.0,-53.5Q627.0,-38.0 650.0,-13.0Q691.0,31.0 691.0,105.0Q691.0,164.0 663.0,196.5Q635.0,229.0 590.0,242.0Q545.0,255.0 496.0,257.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0Z" transform="translate(1776, 870)"/>
<path d="M15.0,369.0L15.0,423.0L130.0,535.0Q170.0,574.0 191.0,598.5Q212.0,623.0 219.5,642.5Q227.0,662.0 227.0,684.0Q227.0,716.0 208.5,732.0Q190.0,748.0 160.0,748.0Q130.0,748.0 105.5,736.5Q81.0,725.0 55.0,705.0L20.0,751.0Q49.0,776.0 83.5,791.0Q118.0,806.0 161.0,806.0Q225.0,806.0 261.5,774.5Q298.0,743.0 298.0,688.0Q298.0,639.0 268.5,600.0Q239.0,561.0 183.0,508.0L102.0,431.0L297.0,431.0L297.0,369.0L15.0,369.0Z" transform="translate(2528, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஏஂதுஔஆதஂ</span> (Added by SIESTA)</li>


<pre>Expected: eetamil=0+756|anusvaratamil=0@-532,0+0|tauvowelsigntamil=2+1091|autamil=4+1955|aatamil=5+1304|tatamil=6+825|anusvaratamil=6@-589,0+0</pre>



<pre>Got     : eetamil=0+801|anusvaratamil=0@-577,0+0|tauvowelsigntamil=2+1091|autamil=4+1955|aatamil=5+1304|tatamil=6+825|anusvaratamil=6@-589,0+0</pre>



<pre>                    ^^^                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5976 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L392.0,-212.0L335.0,-159.0L528.0,24.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,129.0 173.0,92.5Q206.0,56.0 254.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(224, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,153.0Q49.0,204.0 75.5,242.5Q102.0,281.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0Q626.0,325.0 701.0,255.5Q776.0,186.0 776.0,58.0Q776.0,18.0 767.5,-18.0Q759.0,-54.0 745.0,-84.0L917.0,-84.0L917.0,554.0L1003.0,554.0L1003.0,-156.0L713.0,-156.0Q656.0,-236.0 555.5,-278.5Q455.0,-321.0 313.0,-321.0L300.0,-321.0Q230.0,-321.0 170.0,-305.5Q110.0,-290.0 74.0,-256.0Q38.0,-222.0 38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.0,-88.5Q121.0,-84.0 164.0,-84.0L655.0,-84.0Q687.0,-24.0 687.0,55.0Q687.0,153.0 635.5,202.5Q584.0,252.0 496.0,257.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0ZM310.0,-248.0Q416.0,-248.0 490.0,-224.5Q564.0,-201.0 613.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-209.0 164.5,-228.5Q208.0,-248.0 297.0,-248.0L310.0,-248.0Z" transform="translate(801, 870)"/>
<path d="M409.0,-321.0Q355.0,-321.0 309.0,-302.5Q263.0,-284.0 235.5,-245.0Q208.0,-206.0 208.0,-145.0Q208.0,-105.0 222.5,-62.0Q237.0,-19.0 268.0,19.0L342.0,-17.0Q317.0,-54.0 306.0,-83.0Q295.0,-112.0 295.0,-144.0Q295.0,-185.0 312.5,-208.0Q330.0,-231.0 357.5,-239.5Q385.0,-248.0 416.0,-248.0Q483.0,-248.0 522.5,-214.0Q562.0,-180.0 593.0,-128.0Q599.0,-118.0 607.0,-105.5Q615.0,-93.0 622.0,-83.0Q535.0,-51.0 500.5,5.0Q466.0,61.0 466.0,126.0Q466.0,199.0 509.5,259.5Q553.0,320.0 627.0,358.0L708.0,319.0Q696.0,294.0 689.5,271.5Q683.0,249.0 683.0,221.0Q683.0,186.0 699.5,160.5Q716.0,135.0 765.0,135.0Q806.0,135.0 827.0,166.5Q848.0,198.0 848.0,245.0Q848.0,322.0 805.0,377.0Q762.0,432.0 684.5,461.0Q607.0,490.0 503.0,490.0Q367.0,490.0 276.0,454.0Q185.0,418.0 149.0,352.0Q171.0,366.0 198.0,374.0Q225.0,382.0 250.0,382.0Q316.0,382.0 357.0,342.5Q398.0,303.0 398.0,229.0Q398.0,152.0 354.5,108.0Q311.0,64.0 234.0,64.0Q187.0,64.0 145.0,87.5Q103.0,111.0 77.5,156.5Q52.0,202.0 52.0,269.0Q52.0,335.0 81.5,387.0Q111.0,439.0 158.0,475.0Q225.0,526.0 310.5,546.0Q396.0,566.0 502.0,566.0Q629.0,566.0 719.5,531.5Q810.0,497.0 866.0,435.0Q901.0,398.0 917.0,350.5Q933.0,303.0 933.0,256.0Q933.0,223.0 925.5,189.0Q918.0,155.0 899.0,126.5Q880.0,98.0 848.0,81.0Q816.0,64.0 766.0,64.0Q724.0,64.0 688.5,78.0Q653.0,92.0 632.0,123.0Q611.0,154.0 611.0,203.0Q611.0,221.0 614.5,241.5Q618.0,262.0 626.0,279.0Q586.0,251.0 566.5,214.0Q547.0,177.0 547.0,134.0Q547.0,98.0 557.0,70.5Q567.0,43.0 586.0,23.0Q616.0,-9.0 663.5,-23.0Q711.0,-37.0 796.0,-37.0L876.0,-37.0L876.0,-108.0L790.0,-108.0Q763.0,-108.0 742.5,-107.0Q722.0,-106.0 706.0,-104.0Q697.0,-115.0 688.5,-129.0Q680.0,-143.0 674.0,-153.0Q633.0,-233.0 572.5,-277.0Q512.0,-321.0 409.0,-321.0ZM230.0,312.0Q203.0,312.0 178.0,300.0Q153.0,288.0 131.0,268.0Q131.0,199.0 162.0,165.5Q193.0,132.0 239.0,132.0Q274.0,132.0 295.0,155.0Q316.0,178.0 316.0,221.0Q316.0,265.0 292.5,288.5Q269.0,312.0 230.0,312.0ZM1230.0,-12.0Q1177.0,-12.0 1133.0,14.5Q1089.0,41.0 1063.5,97.0Q1038.0,153.0 1038.0,243.0Q1038.0,325.0 1062.5,385.5Q1087.0,446.0 1130.0,486.0Q1173.0,526.0 1227.0,546.0Q1281.0,566.0 1339.0,566.0Q1402.0,566.0 1447.5,548.5Q1493.0,531.0 1530.0,502.0L1530.0,554.0L2034.0,554.0L2034.0,482.0L1864.0,482.0L1864.0,0.0L1778.0,0.0L1778.0,482.0L1604.0,482.0L1604.0,0.0L1518.0,0.0L1518.0,407.0Q1484.0,448.0 1440.5,470.0Q1397.0,492.0 1336.0,492.0Q1248.0,492.0 1191.0,435.5Q1134.0,379.0 1121.0,290.0Q1147.0,307.0 1178.0,317.5Q1209.0,328.0 1242.0,328.0Q1314.0,328.0 1358.5,284.0Q1403.0,240.0 1403.0,165.0Q1403.0,82.0 1356.5,35.0Q1310.0,-12.0 1230.0,-12.0ZM1228.0,258.0Q1198.0,258.0 1170.0,245.5Q1142.0,233.0 1118.0,212.0Q1122.0,126.0 1155.0,91.0Q1188.0,56.0 1234.0,56.0Q1275.0,56.0 1298.0,81.5Q1321.0,107.0 1321.0,155.0Q1321.0,205.0 1295.0,231.5Q1269.0,258.0 1228.0,258.0Z" transform="translate(1892, 870)"/>
<path d="M379.0,397.0Q379.0,360.0 401.5,334.5Q424.0,309.0 465.0,309.0Q503.0,309.0 525.5,332.5Q548.0,356.0 548.0,400.0Q548.0,428.0 540.5,451.5Q533.0,475.0 514.0,496.0Q504.0,497.0 493.0,497.0Q446.0,497.0 412.5,472.0Q379.0,447.0 379.0,397.0ZM344.0,-51.0Q482.0,-51.0 568.0,-7.5Q654.0,36.0 695.0,104.0L217.0,104.0Q186.0,104.0 169.5,103.0Q153.0,102.0 145.0,99.0Q137.0,96.0 129.0,90.0Q114.0,78.0 114.0,56.0Q114.0,7.0 167.0,-22.0Q220.0,-51.0 327.0,-51.0L344.0,-51.0ZM321.0,-124.0Q176.0,-124.0 102.5,-72.5Q29.0,-21.0 29.0,60.0Q29.0,85.0 40.0,109.0Q51.0,133.0 74.0,149.0Q87.0,158.0 102.0,164.0Q117.0,170.0 141.5,173.0Q166.0,176.0 206.0,176.0L721.0,176.0Q730.0,211.0 730.0,251.0Q730.0,323.0 699.0,385.5Q668.0,448.0 601.0,477.0Q612.0,459.0 619.0,438.5Q626.0,418.0 626.0,396.0Q626.0,326.0 584.0,283.5Q542.0,241.0 463.0,241.0Q395.0,241.0 347.5,279.0Q300.0,317.0 300.0,393.0Q300.0,455.0 329.0,493.0Q358.0,531.0 404.5,548.5Q451.0,566.0 503.0,566.0Q580.0,566.0 638.5,540.0Q697.0,514.0 736.5,469.0Q776.0,424.0 796.0,368.0Q816.0,312.0 816.0,252.0Q816.0,212.0 810.0,176.0L947.0,176.0L947.0,554.0L1033.0,554.0L1033.0,70.0Q1053.0,82.0 1080.0,91.0Q1107.0,100.0 1145.0,100.0Q1186.0,100.0 1223.5,82.0Q1261.0,64.0 1285.0,27.5Q1309.0,-9.0 1309.0,-65.0Q1309.0,-141.0 1263.0,-199.0Q1217.0,-257.0 1131.5,-289.0Q1046.0,-321.0 928.0,-321.0L922.0,-321.0Q792.0,-321.0 720.0,-277.5Q648.0,-234.0 648.0,-154.0Q648.0,-125.0 662.5,-99.5Q677.0,-74.0 707.5,-57.5Q738.0,-41.0 784.0,-41.0Q810.0,-41.0 838.0,-46.5Q866.0,-52.0 891.0,-62.0L877.0,-127.0Q855.0,-120.0 832.5,-115.0Q810.0,-110.0 790.0,-110.0Q759.0,-110.0 742.0,-122.0Q725.0,-134.0 725.0,-157.0Q725.0,-181.0 743.5,-202.0Q762.0,-223.0 806.0,-236.0Q850.0,-249.0 926.0,-249.0L933.0,-249.0Q1019.0,-249.0 1084.5,-227.5Q1150.0,-206.0 1187.5,-164.0Q1225.0,-122.0 1225.0,-63.0Q1225.0,-19.0 1200.0,6.0Q1175.0,31.0 1131.0,31.0Q1099.0,31.0 1074.5,22.5Q1050.0,14.0 1033.0,1.0L1033.0,-124.0L947.0,-124.0L947.0,104.0L789.0,104.0Q756.0,30.0 691.0,-21.0Q626.0,-72.0 537.0,-98.0Q448.0,-124.0 342.0,-124.0L321.0,-124.0Z" transform="translate(3847, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,152.0Q49.0,204.0 75.5,243.0Q102.0,282.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0Q578.0,326.0 641.5,303.5Q705.0,281.0 741.0,231.0Q777.0,181.0 777.0,98.0Q777.0,31.0 752.0,-14.5Q727.0,-60.0 681.0,-94.0Q632.0,-129.0 562.5,-142.5Q493.0,-156.0 385.0,-156.0L272.0,-156.0Q230.0,-156.0 207.0,-162.0Q184.0,-168.0 167.0,-179.0Q151.0,-190.0 142.0,-210.0Q133.0,-230.0 133.0,-263.0Q133.0,-293.0 136.0,-317.0L54.0,-321.0Q51.0,-303.0 49.0,-281.5Q47.0,-260.0 47.0,-243.0Q47.0,-199.0 63.0,-168.5Q79.0,-138.0 104.0,-119.0Q130.0,-100.0 162.5,-92.0Q195.0,-84.0 245.0,-84.0L354.0,-84.0Q443.0,-84.0 500.0,-76.5Q557.0,-69.0 592.0,-53.5Q627.0,-38.0 650.0,-13.0Q691.0,31.0 691.0,105.0Q691.0,164.0 663.0,196.5Q635.0,229.0 590.0,242.0Q545.0,255.0 496.0,257.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0Z" transform="translate(5151, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(5387, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5931 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L392.0,-212.0L335.0,-159.0L528.0,24.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,129.0 173.0,92.5Q206.0,56.0 254.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z" transform="translate(0, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(224, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,153.0Q49.0,204.0 75.5,242.5Q102.0,281.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0Q626.0,325.0 701.0,255.5Q776.0,186.0 776.0,58.0Q776.0,18.0 767.5,-18.0Q759.0,-54.0 745.0,-84.0L917.0,-84.0L917.0,554.0L1003.0,554.0L1003.0,-156.0L713.0,-156.0Q656.0,-236.0 555.5,-278.5Q455.0,-321.0 313.0,-321.0L300.0,-321.0Q230.0,-321.0 170.0,-305.5Q110.0,-290.0 74.0,-256.0Q38.0,-222.0 38.0,-167.0Q38.0,-123.0 69.0,-103.0Q83.0,-93.0 102.0,-88.5Q121.0,-84.0 164.0,-84.0L655.0,-84.0Q687.0,-24.0 687.0,55.0Q687.0,153.0 635.5,202.5Q584.0,252.0 496.0,257.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0ZM310.0,-248.0Q416.0,-248.0 490.0,-224.5Q564.0,-201.0 613.0,-156.0L156.0,-156.0Q144.0,-156.0 132.5,-159.5Q121.0,-163.0 121.0,-180.0Q121.0,-209.0 164.5,-228.5Q208.0,-248.0 297.0,-248.0L310.0,-248.0Z" transform="translate(756, 870)"/>
<path d="M409.0,-321.0Q355.0,-321.0 309.0,-302.5Q263.0,-284.0 235.5,-245.0Q208.0,-206.0 208.0,-145.0Q208.0,-105.0 222.5,-62.0Q237.0,-19.0 268.0,19.0L342.0,-17.0Q317.0,-54.0 306.0,-83.0Q295.0,-112.0 295.0,-144.0Q295.0,-185.0 312.5,-208.0Q330.0,-231.0 357.5,-239.5Q385.0,-248.0 416.0,-248.0Q483.0,-248.0 522.5,-214.0Q562.0,-180.0 593.0,-128.0Q599.0,-118.0 607.0,-105.5Q615.0,-93.0 622.0,-83.0Q535.0,-51.0 500.5,5.0Q466.0,61.0 466.0,126.0Q466.0,199.0 509.5,259.5Q553.0,320.0 627.0,358.0L708.0,319.0Q696.0,294.0 689.5,271.5Q683.0,249.0 683.0,221.0Q683.0,186.0 699.5,160.5Q716.0,135.0 765.0,135.0Q806.0,135.0 827.0,166.5Q848.0,198.0 848.0,245.0Q848.0,322.0 805.0,377.0Q762.0,432.0 684.5,461.0Q607.0,490.0 503.0,490.0Q367.0,490.0 276.0,454.0Q185.0,418.0 149.0,352.0Q171.0,366.0 198.0,374.0Q225.0,382.0 250.0,382.0Q316.0,382.0 357.0,342.5Q398.0,303.0 398.0,229.0Q398.0,152.0 354.5,108.0Q311.0,64.0 234.0,64.0Q187.0,64.0 145.0,87.5Q103.0,111.0 77.5,156.5Q52.0,202.0 52.0,269.0Q52.0,335.0 81.5,387.0Q111.0,439.0 158.0,475.0Q225.0,526.0 310.5,546.0Q396.0,566.0 502.0,566.0Q629.0,566.0 719.5,531.5Q810.0,497.0 866.0,435.0Q901.0,398.0 917.0,350.5Q933.0,303.0 933.0,256.0Q933.0,223.0 925.5,189.0Q918.0,155.0 899.0,126.5Q880.0,98.0 848.0,81.0Q816.0,64.0 766.0,64.0Q724.0,64.0 688.5,78.0Q653.0,92.0 632.0,123.0Q611.0,154.0 611.0,203.0Q611.0,221.0 614.5,241.5Q618.0,262.0 626.0,279.0Q586.0,251.0 566.5,214.0Q547.0,177.0 547.0,134.0Q547.0,98.0 557.0,70.5Q567.0,43.0 586.0,23.0Q616.0,-9.0 663.5,-23.0Q711.0,-37.0 796.0,-37.0L876.0,-37.0L876.0,-108.0L790.0,-108.0Q763.0,-108.0 742.5,-107.0Q722.0,-106.0 706.0,-104.0Q697.0,-115.0 688.5,-129.0Q680.0,-143.0 674.0,-153.0Q633.0,-233.0 572.5,-277.0Q512.0,-321.0 409.0,-321.0ZM230.0,312.0Q203.0,312.0 178.0,300.0Q153.0,288.0 131.0,268.0Q131.0,199.0 162.0,165.5Q193.0,132.0 239.0,132.0Q274.0,132.0 295.0,155.0Q316.0,178.0 316.0,221.0Q316.0,265.0 292.5,288.5Q269.0,312.0 230.0,312.0ZM1230.0,-12.0Q1177.0,-12.0 1133.0,14.5Q1089.0,41.0 1063.5,97.0Q1038.0,153.0 1038.0,243.0Q1038.0,325.0 1062.5,385.5Q1087.0,446.0 1130.0,486.0Q1173.0,526.0 1227.0,546.0Q1281.0,566.0 1339.0,566.0Q1402.0,566.0 1447.5,548.5Q1493.0,531.0 1530.0,502.0L1530.0,554.0L2034.0,554.0L2034.0,482.0L1864.0,482.0L1864.0,0.0L1778.0,0.0L1778.0,482.0L1604.0,482.0L1604.0,0.0L1518.0,0.0L1518.0,407.0Q1484.0,448.0 1440.5,470.0Q1397.0,492.0 1336.0,492.0Q1248.0,492.0 1191.0,435.5Q1134.0,379.0 1121.0,290.0Q1147.0,307.0 1178.0,317.5Q1209.0,328.0 1242.0,328.0Q1314.0,328.0 1358.5,284.0Q1403.0,240.0 1403.0,165.0Q1403.0,82.0 1356.5,35.0Q1310.0,-12.0 1230.0,-12.0ZM1228.0,258.0Q1198.0,258.0 1170.0,245.5Q1142.0,233.0 1118.0,212.0Q1122.0,126.0 1155.0,91.0Q1188.0,56.0 1234.0,56.0Q1275.0,56.0 1298.0,81.5Q1321.0,107.0 1321.0,155.0Q1321.0,205.0 1295.0,231.5Q1269.0,258.0 1228.0,258.0Z" transform="translate(1847, 870)"/>
<path d="M379.0,397.0Q379.0,360.0 401.5,334.5Q424.0,309.0 465.0,309.0Q503.0,309.0 525.5,332.5Q548.0,356.0 548.0,400.0Q548.0,428.0 540.5,451.5Q533.0,475.0 514.0,496.0Q504.0,497.0 493.0,497.0Q446.0,497.0 412.5,472.0Q379.0,447.0 379.0,397.0ZM344.0,-51.0Q482.0,-51.0 568.0,-7.5Q654.0,36.0 695.0,104.0L217.0,104.0Q186.0,104.0 169.5,103.0Q153.0,102.0 145.0,99.0Q137.0,96.0 129.0,90.0Q114.0,78.0 114.0,56.0Q114.0,7.0 167.0,-22.0Q220.0,-51.0 327.0,-51.0L344.0,-51.0ZM321.0,-124.0Q176.0,-124.0 102.5,-72.5Q29.0,-21.0 29.0,60.0Q29.0,85.0 40.0,109.0Q51.0,133.0 74.0,149.0Q87.0,158.0 102.0,164.0Q117.0,170.0 141.5,173.0Q166.0,176.0 206.0,176.0L721.0,176.0Q730.0,211.0 730.0,251.0Q730.0,323.0 699.0,385.5Q668.0,448.0 601.0,477.0Q612.0,459.0 619.0,438.5Q626.0,418.0 626.0,396.0Q626.0,326.0 584.0,283.5Q542.0,241.0 463.0,241.0Q395.0,241.0 347.5,279.0Q300.0,317.0 300.0,393.0Q300.0,455.0 329.0,493.0Q358.0,531.0 404.5,548.5Q451.0,566.0 503.0,566.0Q580.0,566.0 638.5,540.0Q697.0,514.0 736.5,469.0Q776.0,424.0 796.0,368.0Q816.0,312.0 816.0,252.0Q816.0,212.0 810.0,176.0L947.0,176.0L947.0,554.0L1033.0,554.0L1033.0,70.0Q1053.0,82.0 1080.0,91.0Q1107.0,100.0 1145.0,100.0Q1186.0,100.0 1223.5,82.0Q1261.0,64.0 1285.0,27.5Q1309.0,-9.0 1309.0,-65.0Q1309.0,-141.0 1263.0,-199.0Q1217.0,-257.0 1131.5,-289.0Q1046.0,-321.0 928.0,-321.0L922.0,-321.0Q792.0,-321.0 720.0,-277.5Q648.0,-234.0 648.0,-154.0Q648.0,-125.0 662.5,-99.5Q677.0,-74.0 707.5,-57.5Q738.0,-41.0 784.0,-41.0Q810.0,-41.0 838.0,-46.5Q866.0,-52.0 891.0,-62.0L877.0,-127.0Q855.0,-120.0 832.5,-115.0Q810.0,-110.0 790.0,-110.0Q759.0,-110.0 742.0,-122.0Q725.0,-134.0 725.0,-157.0Q725.0,-181.0 743.5,-202.0Q762.0,-223.0 806.0,-236.0Q850.0,-249.0 926.0,-249.0L933.0,-249.0Q1019.0,-249.0 1084.5,-227.5Q1150.0,-206.0 1187.5,-164.0Q1225.0,-122.0 1225.0,-63.0Q1225.0,-19.0 1200.0,6.0Q1175.0,31.0 1131.0,31.0Q1099.0,31.0 1074.5,22.5Q1050.0,14.0 1033.0,1.0L1033.0,-124.0L947.0,-124.0L947.0,104.0L789.0,104.0Q756.0,30.0 691.0,-21.0Q626.0,-72.0 537.0,-98.0Q448.0,-124.0 342.0,-124.0L321.0,-124.0Z" transform="translate(3802, 870)"/>
<path d="M261.0,-12.0Q201.0,-12.0 153.0,7.0Q105.0,26.0 77.0,63.0Q49.0,100.0 49.0,152.0Q49.0,204.0 75.5,243.0Q102.0,282.0 160.0,303.0L160.0,554.0L683.0,554.0L683.0,482.0L496.0,482.0L496.0,328.0Q578.0,326.0 641.5,303.5Q705.0,281.0 741.0,231.0Q777.0,181.0 777.0,98.0Q777.0,31.0 752.0,-14.5Q727.0,-60.0 681.0,-94.0Q632.0,-129.0 562.5,-142.5Q493.0,-156.0 385.0,-156.0L272.0,-156.0Q230.0,-156.0 207.0,-162.0Q184.0,-168.0 167.0,-179.0Q151.0,-190.0 142.0,-210.0Q133.0,-230.0 133.0,-263.0Q133.0,-293.0 136.0,-317.0L54.0,-321.0Q51.0,-303.0 49.0,-281.5Q47.0,-260.0 47.0,-243.0Q47.0,-199.0 63.0,-168.5Q79.0,-138.0 104.0,-119.0Q130.0,-100.0 162.5,-92.0Q195.0,-84.0 245.0,-84.0L354.0,-84.0Q443.0,-84.0 500.0,-76.5Q557.0,-69.0 592.0,-53.5Q627.0,-38.0 650.0,-13.0Q691.0,31.0 691.0,105.0Q691.0,164.0 663.0,196.5Q635.0,229.0 590.0,242.0Q545.0,255.0 496.0,257.0L496.0,226.0Q496.0,159.0 484.5,121.0Q473.0,83.0 452.0,57.0Q421.0,19.0 372.5,3.5Q324.0,-12.0 261.0,-12.0ZM239.0,482.0L239.0,322.0Q281.0,328.0 332.0,328.0L411.0,328.0L411.0,482.0L239.0,482.0ZM135.0,153.0Q135.0,107.0 173.0,83.5Q211.0,60.0 269.0,60.0Q313.0,60.0 344.5,73.5Q376.0,87.0 393.5,120.5Q411.0,154.0 411.0,213.0L411.0,258.0L325.0,258.0Q274.0,258.0 238.5,252.0Q203.0,246.0 178.0,232.0Q135.0,207.0 135.0,153.0Z" transform="translate(5106, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(5342, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ுஃஜ॒ிஂ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+562|uvowelsigntamil=0+483|visargatamil=1+896|jatamil=2+1022|uni0952=2@-233,-317+0|uni25CC=2+562|ivowelsigntamil=2+262|anusvaratamil=2@-88,0+264</pre>



<pre>Got     : uni25CC=0+562|uvowelsigntamil=0+483|visargatamil=1+896|jatamil=2+1022|uni0952=2@-233,-317+0|uni25CC=2+562|ivowelsigntamil=2+262|anusvaratamil=2@-688,0+352</pre>



<pre>                                                                                                                                                                 ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4139 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(0, 870)"/>
<path d="M294.0,217.0Q236.0,217.0 198.5,235.5Q161.0,254.0 140.0,283.5Q119.0,313.0 110.5,348.0Q102.0,383.0 102.0,416.0Q102.0,435.0 103.0,451.5Q104.0,468.0 106.0,482.0L-219.0,482.0L-219.0,554.0L228.0,554.0Q296.0,554.0 336.5,543.0Q377.0,532.0 405.0,509.0Q431.0,487.0 447.0,455.5Q463.0,424.0 463.0,378.0Q463.0,304.0 415.5,260.5Q368.0,217.0 294.0,217.0ZM187.0,419.0Q187.0,361.0 211.0,325.5Q235.0,290.0 290.0,290.0Q334.0,290.0 356.0,315.5Q378.0,341.0 378.0,379.0Q378.0,404.0 369.0,422.5Q360.0,441.0 344.0,454.0Q328.0,468.0 301.0,475.0Q274.0,482.0 210.0,482.0L192.0,482.0Q189.0,469.0 188.0,453.5Q187.0,438.0 187.0,419.0Z" transform="translate(562, 870)"/>
<path d="M450.0,477.0Q369.0,477.0 321.0,527.0Q273.0,577.0 273.0,661.0Q273.0,744.0 322.0,793.5Q371.0,843.0 448.0,843.0Q526.0,843.0 574.0,793.5Q622.0,744.0 622.0,661.0Q622.0,605.0 600.0,563.5Q578.0,522.0 539.0,499.5Q500.0,477.0 450.0,477.0ZM449.0,548.0Q487.0,548.0 513.5,576.5Q540.0,605.0 540.0,662.0Q540.0,718.0 513.0,745.0Q486.0,772.0 448.0,772.0Q408.0,772.0 381.5,744.0Q355.0,716.0 355.0,660.0Q355.0,603.0 382.0,575.5Q409.0,548.0 449.0,548.0ZM222.0,-11.0Q140.0,-11.0 92.5,39.5Q45.0,90.0 45.0,173.0Q45.0,256.0 94.0,305.5Q143.0,355.0 220.0,355.0Q298.0,355.0 346.0,305.5Q394.0,256.0 394.0,173.0Q394.0,117.0 372.0,75.5Q350.0,34.0 311.0,11.5Q272.0,-11.0 222.0,-11.0ZM679.0,-11.0Q598.0,-11.0 550.0,39.0Q502.0,89.0 502.0,173.0Q502.0,256.0 551.0,305.5Q600.0,355.0 677.0,355.0Q755.0,355.0 803.0,305.5Q851.0,256.0 851.0,173.0Q851.0,117.0 829.0,75.5Q807.0,34.0 768.0,11.5Q729.0,-11.0 679.0,-11.0ZM221.0,60.0Q259.0,60.0 285.5,88.5Q312.0,117.0 312.0,174.0Q312.0,230.0 285.0,257.0Q258.0,284.0 220.0,284.0Q180.0,284.0 153.5,256.0Q127.0,228.0 127.0,172.0Q127.0,115.0 154.0,87.5Q181.0,60.0 221.0,60.0ZM678.0,60.0Q716.0,60.0 742.5,88.5Q769.0,117.0 769.0,174.0Q769.0,230.0 741.5,257.0Q714.0,284.0 677.0,284.0Q637.0,284.0 610.5,256.0Q584.0,228.0 584.0,172.0Q584.0,115.0 611.0,87.5Q638.0,60.0 678.0,60.0Z" transform="translate(1045, 870)"/>
<path d="M331.0,566.0Q397.0,566.0 440.5,550.0Q484.0,534.0 510.0,508.5Q536.0,483.0 551.0,455.0Q575.0,508.0 619.5,537.0Q664.0,566.0 729.0,566.0Q804.0,566.0 855.0,536.5Q906.0,507.0 932.5,455.0Q959.0,403.0 959.0,335.0Q959.0,268.0 939.0,221.0Q919.0,174.0 883.0,143.0Q845.0,110.0 791.5,93.0Q738.0,76.0 674.5,69.5Q611.0,63.0 542.0,63.0L448.0,63.0Q348.0,63.0 285.0,53.0Q222.0,43.0 187.0,8.0Q168.0,-11.0 159.5,-36.0Q151.0,-61.0 151.0,-93.0Q151.0,-151.0 173.0,-185.0Q195.0,-219.0 227.5,-233.5Q260.0,-248.0 292.0,-248.0Q336.0,-248.0 368.0,-235.5Q400.0,-223.0 426.0,-200.0Q452.0,-177.0 478.0,-148.0Q520.0,-101.0 558.0,-70.0Q596.0,-39.0 641.5,-23.0Q687.0,-7.0 751.0,-7.0Q799.0,-7.0 843.5,-24.5Q888.0,-42.0 917.0,-78.5Q946.0,-115.0 946.0,-174.0Q946.0,-241.0 901.0,-281.0Q856.0,-321.0 787.0,-321.0Q730.0,-321.0 694.5,-300.0Q659.0,-279.0 642.0,-247.0Q625.0,-215.0 625.0,-181.0Q625.0,-153.0 633.5,-131.0Q642.0,-109.0 656.0,-90.0Q627.0,-103.0 600.5,-128.0Q574.0,-153.0 549.0,-184.0Q499.0,-245.0 441.5,-283.0Q384.0,-321.0 297.0,-321.0Q215.0,-321.0 163.0,-289.5Q111.0,-258.0 87.0,-206.0Q63.0,-154.0 63.0,-95.0Q63.0,-40.0 81.5,-0.5Q100.0,39.0 131.0,65.0Q183.0,109.0 262.5,122.0Q342.0,135.0 432.0,135.0L521.0,135.0Q634.0,135.0 709.0,147.0Q784.0,159.0 823.0,196.0Q871.0,241.0 871.0,334.0Q871.0,413.0 829.5,453.0Q788.0,493.0 726.0,493.0Q667.0,493.0 635.0,457.0Q616.0,434.0 608.0,403.5Q600.0,373.0 600.0,319.0L600.0,205.0L513.0,205.0L513.0,293.0Q513.0,390.0 473.5,443.0Q434.0,496.0 337.0,496.0Q314.0,496.0 299.5,494.5Q285.0,493.0 271.0,490.0Q329.0,478.0 366.5,439.5Q404.0,401.0 404.0,342.0Q404.0,270.0 357.5,227.0Q311.0,184.0 235.0,184.0Q150.0,184.0 106.5,230.5Q63.0,277.0 63.0,345.0Q63.0,415.0 100.0,464.5Q137.0,514.0 198.5,540.0Q260.0,566.0 331.0,566.0ZM142.0,348.0Q142.0,305.0 163.5,278.5Q185.0,252.0 234.0,252.0Q273.0,252.0 297.5,274.0Q322.0,296.0 322.0,335.0Q322.0,386.0 283.0,416.0Q244.0,446.0 185.0,448.0Q162.0,427.0 152.0,401.5Q142.0,376.0 142.0,348.0ZM707.0,-168.0Q707.0,-202.0 725.5,-227.0Q744.0,-252.0 789.0,-252.0Q815.0,-252.0 840.0,-235.0Q865.0,-218.0 865.0,-173.0Q865.0,-136.0 847.0,-116.0Q829.0,-96.0 801.5,-87.5Q774.0,-79.0 746.0,-77.0Q707.0,-117.0 707.0,-168.0Z" transform="translate(1941, 870)"/>
<path d="M-65.0,-182.0L-491.0,-182.0L-491.0,-111.0L-65.0,-111.0L-65.0,-182.0Z" transform="translate(2730, 553)"/>
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(2963, 870)"/>
<path d="M-79.0,843.0Q30.0,843.0 98.0,773.0Q121.0,750.0 138.0,715.5Q155.0,681.0 164.5,626.5Q174.0,572.0 174.0,489.0L174.0,0.0L88.0,0.0L88.0,471.0Q88.0,543.0 81.5,590.0Q75.0,637.0 63.0,667.5Q51.0,698.0 34.0,718.0Q13.0,744.0 -16.5,756.0Q-46.0,768.0 -81.0,768.0Q-146.0,768.0 -180.5,731.5Q-215.0,695.0 -215.0,637.0Q-215.0,609.0 -207.0,576.5Q-199.0,544.0 -182.0,515.0L-273.0,515.0Q-286.0,545.0 -293.5,575.0Q-301.0,605.0 -301.0,636.0Q-301.0,708.0 -270.0,753.5Q-239.0,799.0 -188.5,821.0Q-138.0,843.0 -79.0,843.0Z" transform="translate(3525, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(3099, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4051 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(0, 870)"/>
<path d="M294.0,217.0Q236.0,217.0 198.5,235.5Q161.0,254.0 140.0,283.5Q119.0,313.0 110.5,348.0Q102.0,383.0 102.0,416.0Q102.0,435.0 103.0,451.5Q104.0,468.0 106.0,482.0L-219.0,482.0L-219.0,554.0L228.0,554.0Q296.0,554.0 336.5,543.0Q377.0,532.0 405.0,509.0Q431.0,487.0 447.0,455.5Q463.0,424.0 463.0,378.0Q463.0,304.0 415.5,260.5Q368.0,217.0 294.0,217.0ZM187.0,419.0Q187.0,361.0 211.0,325.5Q235.0,290.0 290.0,290.0Q334.0,290.0 356.0,315.5Q378.0,341.0 378.0,379.0Q378.0,404.0 369.0,422.5Q360.0,441.0 344.0,454.0Q328.0,468.0 301.0,475.0Q274.0,482.0 210.0,482.0L192.0,482.0Q189.0,469.0 188.0,453.5Q187.0,438.0 187.0,419.0Z" transform="translate(562, 870)"/>
<path d="M450.0,477.0Q369.0,477.0 321.0,527.0Q273.0,577.0 273.0,661.0Q273.0,744.0 322.0,793.5Q371.0,843.0 448.0,843.0Q526.0,843.0 574.0,793.5Q622.0,744.0 622.0,661.0Q622.0,605.0 600.0,563.5Q578.0,522.0 539.0,499.5Q500.0,477.0 450.0,477.0ZM449.0,548.0Q487.0,548.0 513.5,576.5Q540.0,605.0 540.0,662.0Q540.0,718.0 513.0,745.0Q486.0,772.0 448.0,772.0Q408.0,772.0 381.5,744.0Q355.0,716.0 355.0,660.0Q355.0,603.0 382.0,575.5Q409.0,548.0 449.0,548.0ZM222.0,-11.0Q140.0,-11.0 92.5,39.5Q45.0,90.0 45.0,173.0Q45.0,256.0 94.0,305.5Q143.0,355.0 220.0,355.0Q298.0,355.0 346.0,305.5Q394.0,256.0 394.0,173.0Q394.0,117.0 372.0,75.5Q350.0,34.0 311.0,11.5Q272.0,-11.0 222.0,-11.0ZM679.0,-11.0Q598.0,-11.0 550.0,39.0Q502.0,89.0 502.0,173.0Q502.0,256.0 551.0,305.5Q600.0,355.0 677.0,355.0Q755.0,355.0 803.0,305.5Q851.0,256.0 851.0,173.0Q851.0,117.0 829.0,75.5Q807.0,34.0 768.0,11.5Q729.0,-11.0 679.0,-11.0ZM221.0,60.0Q259.0,60.0 285.5,88.5Q312.0,117.0 312.0,174.0Q312.0,230.0 285.0,257.0Q258.0,284.0 220.0,284.0Q180.0,284.0 153.5,256.0Q127.0,228.0 127.0,172.0Q127.0,115.0 154.0,87.5Q181.0,60.0 221.0,60.0ZM678.0,60.0Q716.0,60.0 742.5,88.5Q769.0,117.0 769.0,174.0Q769.0,230.0 741.5,257.0Q714.0,284.0 677.0,284.0Q637.0,284.0 610.5,256.0Q584.0,228.0 584.0,172.0Q584.0,115.0 611.0,87.5Q638.0,60.0 678.0,60.0Z" transform="translate(1045, 870)"/>
<path d="M331.0,566.0Q397.0,566.0 440.5,550.0Q484.0,534.0 510.0,508.5Q536.0,483.0 551.0,455.0Q575.0,508.0 619.5,537.0Q664.0,566.0 729.0,566.0Q804.0,566.0 855.0,536.5Q906.0,507.0 932.5,455.0Q959.0,403.0 959.0,335.0Q959.0,268.0 939.0,221.0Q919.0,174.0 883.0,143.0Q845.0,110.0 791.5,93.0Q738.0,76.0 674.5,69.5Q611.0,63.0 542.0,63.0L448.0,63.0Q348.0,63.0 285.0,53.0Q222.0,43.0 187.0,8.0Q168.0,-11.0 159.5,-36.0Q151.0,-61.0 151.0,-93.0Q151.0,-151.0 173.0,-185.0Q195.0,-219.0 227.5,-233.5Q260.0,-248.0 292.0,-248.0Q336.0,-248.0 368.0,-235.5Q400.0,-223.0 426.0,-200.0Q452.0,-177.0 478.0,-148.0Q520.0,-101.0 558.0,-70.0Q596.0,-39.0 641.5,-23.0Q687.0,-7.0 751.0,-7.0Q799.0,-7.0 843.5,-24.5Q888.0,-42.0 917.0,-78.5Q946.0,-115.0 946.0,-174.0Q946.0,-241.0 901.0,-281.0Q856.0,-321.0 787.0,-321.0Q730.0,-321.0 694.5,-300.0Q659.0,-279.0 642.0,-247.0Q625.0,-215.0 625.0,-181.0Q625.0,-153.0 633.5,-131.0Q642.0,-109.0 656.0,-90.0Q627.0,-103.0 600.5,-128.0Q574.0,-153.0 549.0,-184.0Q499.0,-245.0 441.5,-283.0Q384.0,-321.0 297.0,-321.0Q215.0,-321.0 163.0,-289.5Q111.0,-258.0 87.0,-206.0Q63.0,-154.0 63.0,-95.0Q63.0,-40.0 81.5,-0.5Q100.0,39.0 131.0,65.0Q183.0,109.0 262.5,122.0Q342.0,135.0 432.0,135.0L521.0,135.0Q634.0,135.0 709.0,147.0Q784.0,159.0 823.0,196.0Q871.0,241.0 871.0,334.0Q871.0,413.0 829.5,453.0Q788.0,493.0 726.0,493.0Q667.0,493.0 635.0,457.0Q616.0,434.0 608.0,403.5Q600.0,373.0 600.0,319.0L600.0,205.0L513.0,205.0L513.0,293.0Q513.0,390.0 473.5,443.0Q434.0,496.0 337.0,496.0Q314.0,496.0 299.5,494.5Q285.0,493.0 271.0,490.0Q329.0,478.0 366.5,439.5Q404.0,401.0 404.0,342.0Q404.0,270.0 357.5,227.0Q311.0,184.0 235.0,184.0Q150.0,184.0 106.5,230.5Q63.0,277.0 63.0,345.0Q63.0,415.0 100.0,464.5Q137.0,514.0 198.5,540.0Q260.0,566.0 331.0,566.0ZM142.0,348.0Q142.0,305.0 163.5,278.5Q185.0,252.0 234.0,252.0Q273.0,252.0 297.5,274.0Q322.0,296.0 322.0,335.0Q322.0,386.0 283.0,416.0Q244.0,446.0 185.0,448.0Q162.0,427.0 152.0,401.5Q142.0,376.0 142.0,348.0ZM707.0,-168.0Q707.0,-202.0 725.5,-227.0Q744.0,-252.0 789.0,-252.0Q815.0,-252.0 840.0,-235.0Q865.0,-218.0 865.0,-173.0Q865.0,-136.0 847.0,-116.0Q829.0,-96.0 801.5,-87.5Q774.0,-79.0 746.0,-77.0Q707.0,-117.0 707.0,-168.0Z" transform="translate(1941, 870)"/>
<path d="M-65.0,-182.0L-491.0,-182.0L-491.0,-111.0L-65.0,-111.0L-65.0,-182.0Z" transform="translate(2730, 553)"/>
<path d="M281.0,424.0Q249.0,424.0 249.0,456.0Q249.0,487.0 281.0,487.0Q312.0,487.0 312.0,456.0Q312.0,424.0 281.0,424.0ZM138.0,369.0Q106.0,369.0 106.0,401.0Q106.0,432.0 138.0,432.0Q169.0,432.0 169.0,401.0Q169.0,369.0 138.0,369.0ZM423.0,369.0Q391.0,369.0 391.0,401.0Q391.0,432.0 423.0,432.0Q455.0,432.0 455.0,401.0Q455.0,369.0 423.0,369.0ZM89.0,231.0Q57.0,231.0 57.0,264.0Q57.0,295.0 89.0,295.0Q121.0,295.0 121.0,264.0Q121.0,231.0 89.0,231.0ZM472.0,231.0Q441.0,231.0 441.0,264.0Q441.0,295.0 472.0,295.0Q504.0,295.0 504.0,264.0Q504.0,231.0 472.0,231.0ZM138.0,95.0Q106.0,95.0 106.0,127.0Q106.0,158.0 138.0,158.0Q169.0,158.0 169.0,127.0Q169.0,95.0 138.0,95.0ZM423.0,95.0Q391.0,95.0 391.0,127.0Q391.0,158.0 423.0,158.0Q455.0,158.0 455.0,127.0Q455.0,95.0 423.0,95.0ZM281.0,40.0Q249.0,40.0 249.0,72.0Q249.0,104.0 281.0,104.0Q312.0,104.0 312.0,72.0Q312.0,40.0 281.0,40.0Z" transform="translate(2963, 870)"/>
<path d="M-79.0,843.0Q30.0,843.0 98.0,773.0Q121.0,750.0 138.0,715.5Q155.0,681.0 164.5,626.5Q174.0,572.0 174.0,489.0L174.0,0.0L88.0,0.0L88.0,471.0Q88.0,543.0 81.5,590.0Q75.0,637.0 63.0,667.5Q51.0,698.0 34.0,718.0Q13.0,744.0 -16.5,756.0Q-46.0,768.0 -81.0,768.0Q-146.0,768.0 -180.5,731.5Q-215.0,695.0 -215.0,637.0Q-215.0,609.0 -207.0,576.5Q-199.0,544.0 -182.0,515.0L-273.0,515.0Q-286.0,545.0 -293.5,575.0Q-301.0,605.0 -301.0,636.0Q-301.0,708.0 -270.0,753.5Q-239.0,799.0 -188.5,821.0Q-138.0,843.0 -79.0,843.0Z" transform="translate(3525, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z" transform="translate(3699, 870)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aatamil
	* aivowelsigntamil
	* asabovesigntamil
	* atamil
	* caiivowelsigntamil
	* caprehalftamil
	* catamil
	* cauuvowelsigntamil
	* cauvowelsigntamil
	* creditsigntamil and 48 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[15] NotoSansTamil-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aatamil
	* aivowelsigntamil
	* asabovesigntamil
	* atamil
	* aulengthmarktamil
	* autamil
	* auvowelsigntamil
	* caiivowelsigntamil
	* caprehalftamil
	* catamil and 89 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign.tamil (U+0023): X=247.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.tamil (U+0023): X=341.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.tamil (U+0023): X=455.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.tamil (U+0023): X=547.0,Y=713.0 (should be at cap-height 714?)

	* four.tamil (U+0034): X=340.0,Y=716.0 (should be at cap-height 714?)

	* four.tamil (U+0034): X=461.0,Y=716.0 (should be at cap-height 714?)

	* five.tamil (U+0035): X=138.0,Y=-1.0 (should be at baseline 0?)

	* six.tamil (U+0036): X=481.0,Y=715.0 (should be at cap-height 714?)

	* seven.tamil (U+0037): X=33.0,Y=713.0 (should be at cap-height 714?)

	* seven.tamil (U+0037): X=533.0,Y=713.0 (should be at cap-height 714?) 

	* 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* ohmsigntamil (U+0BD0): B<<351.0,461.5>-<241.0,435.0>-<189.0,388.0>>/B<<189.0,388.0>-<207.0,398.0>-<228.5,403.5>> = 13.054126304702278 

	* rupeesigntamil (U+0BF9): B<<551.5,763.5>-<528.0,757.0>-<511.0,748.0>>/B<<511.0,748.0>-<515.0,749.0>-<519.0,749.0>> = 13.861027563021121 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<83.0,0.0>--<82.0,357.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansTamil-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.tamil (U+0021): L<<105.0,174.0>--<103.0,714.0>>

	* exclam.tamil (U+0021): L<<131.0,714.0>--<129.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansTamilUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,287.0>-<346.0,255.0>-<347.0,235.0>>/B<<347.0,235.0>-<349.0,255.0>-<354.5,286.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,262.5>-<313.0,236.0>-<315.0,218.0>>/B<<315.0,218.0>-<319.0,248.0>-<325.5,287.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,493.0>-<523.0,519.0>-<521.0,537.0>>/B<<521.0,537.0>-<519.0,519.0>-<514.5,493.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,286.0>-<721.0,247.0>-<724.0,218.0>>/B<<724.0,218.0>-<727.0,243.0>-<734.0,280.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,262.5>-<313.0,236.0>-<315.0,218.0>>/B<<315.0,218.0>-<319.0,248.0>-<325.5,287.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,493.0>-<523.0,519.0>-<521.0,537.0>>/B<<521.0,537.0>-<519.0,519.0>-<514.5,493.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,286.0>-<721.0,247.0>-<724.0,218.0>>/B<<724.0,218.0>-<727.0,243.0>-<734.0,280.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,262.5>-<313.0,236.0>-<315.0,218.0>>/B<<315.0,218.0>-<319.0,248.0>-<325.5,287.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,493.0>-<523.0,519.0>-<521.0,537.0>>/B<<521.0,537.0>-<519.0,519.0>-<514.5,493.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,286.0>-<721.0,247.0>-<724.0,218.0>>/B<<724.0,218.0>-<727.0,243.0>-<734.0,280.0>> = 12.748914526401432 

	* 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<372.0,51.0>--<373.0,531.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansTamilUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* R (U+0052): X=513.5,Y=712.0 (should be at cap-height 714?)

	* grave (U+0060): X=284.5,Y=714.5 (should be at cap-height 714?)

	* a (U+0061): X=470.5,Y=560.5 (should be at x-height 562?)

	* s (U+0073): X=453.0,Y=564.0 (should be at x-height 562?)

	* t (U+0074): X=148.0,Y=713.0 (should be at cap-height 714?)

	* t (U+0074): X=243.0,Y=713.0 (should be at cap-height 714?)

	* braceleft.tamil (U+007B): X=275.0,Y=1.0 (should be at baseline 0?)

	* braceright.tamil (U+007D): X=109.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=196.0,Y=712.0 (should be at cap-height 714?)

	* copyright (U+00A9): X=416.0,Y=712.0 (should be at cap-height 714?) 

	* 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,247.0>-<272.0,212.0>-<275.0,188.0>>/B<<275.0,188.0>-<278.0,213.0>-<284.0,247.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,556.5>-<485.0,580.0>-<483.0,593.0>>/B<<483.0,593.0>-<482.0,580.0>-<477.5,556.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,247.0>-<689.0,212.0>-<692.0,188.0>>/B<<692.0,188.0>-<695.0,213.0>-<701.0,247.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,247.0>-<272.0,212.0>-<275.0,188.0>>/B<<275.0,188.0>-<278.0,213.0>-<284.0,247.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,556.5>-<485.0,580.0>-<483.0,593.0>>/B<<483.0,593.0>-<482.0,580.0>-<477.5,556.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,247.0>-<689.0,212.0>-<692.0,188.0>>/B<<692.0,188.0>-<695.0,213.0>-<701.0,247.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,247.0>-<272.0,212.0>-<275.0,188.0>>/B<<275.0,188.0>-<278.0,213.0>-<284.0,247.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,556.5>-<485.0,580.0>-<483.0,593.0>>/B<<483.0,593.0>-<482.0,580.0>-<477.5,556.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,247.0>-<689.0,212.0>-<692.0,188.0>>/B<<692.0,188.0>-<695.0,213.0>-<701.0,247.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,247.0>-<272.0,212.0>-<275.0,188.0>>/B<<275.0,188.0>-<278.0,213.0>-<284.0,247.5>> = 13.967789761532726 

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<80.0,51.0>--<79.0,411.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansTamilUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.tamil (U+002C): X=184.5,Y=-1.0 (should be at baseline 0?)

	* semicolon.tamil (U+003B): X=184.5,Y=-1.0 (should be at baseline 0?)

	* grave (U+0060): X=309.5,Y=714.5 (should be at cap-height 714?)

	* j (U+006A): X=241.0,Y=-2.0 (should be at baseline 0?)

	* braceleft.tamil (U+007B): X=305.5,Y=712.0 (should be at cap-height 714?)

	* braceleft.tamil (U+007B): X=287.0,Y=2.0 (should be at baseline 0?)

	* braceright.tamil (U+007D): X=118.0,Y=2.0 (should be at baseline 0?)

	* braceright.tamil (U+007D): X=100.0,Y=712.0 (should be at cap-height 714?)

	* acute (U+00B4): X=79.0,Y=714.5 (should be at cap-height 714?)

	* questiondown (U+00BF): X=261.0,Y=2.0 (should be at baseline 0?) 

	* 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,260.5>-<333.0,228.0>-<335.0,207.0>>/B<<335.0,207.0>-<338.0,228.0>-<344.5,260.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,262.5>-<290.0,226.0>-<293.0,202.0>>/B<<293.0,202.0>-<297.0,234.0>-<305.0,277.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,526.5>-<502.0,551.0>-<501.0,567.0>>/B<<501.0,567.0>-<499.0,551.0>-<494.5,526.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,262.5>-<290.0,226.0>-<293.0,202.0>>/B<<293.0,202.0>-<297.0,234.0>-<305.0,277.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,526.5>-<502.0,551.0>-<501.0,567.0>>/B<<501.0,567.0>-<499.0,551.0>-<494.5,526.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,262.5>-<290.0,226.0>-<293.0,202.0>>/B<<293.0,202.0>-<297.0,234.0>-<305.0,277.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,526.5>-<502.0,551.0>-<501.0,567.0>>/B<<501.0,567.0>-<499.0,551.0>-<494.5,526.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,262.5>-<290.0,226.0>-<293.0,202.0>>/B<<293.0,202.0>-<297.0,234.0>-<305.0,277.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,526.5>-<502.0,551.0>-<501.0,567.0>>/B<<501.0,567.0>-<499.0,551.0>-<494.5,526.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,262.5>-<290.0,226.0>-<293.0,202.0>>/B<<293.0,202.0>-<297.0,234.0>-<305.0,277.5>> = 14.25003269780357 

	* Wgrave (U+1E80): B<<506.5,526.5>-<502.0,551.0>-<501.0,567.0>>/B<<501.0,567.0>-<499.0,551.0>-<494.5,526.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<371.0,51.0>--<372.0,534.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansTamilUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=450.0,Y=712.0 (should be at cap-height 714?)

	* dollar (U+0024): X=285.0,Y=713.0 (should be at cap-height 714?)

	* dollar (U+0024): X=253.0,Y=713.0 (should be at cap-height 714?)

	* comma.tamil (U+002C): X=59.5,Y=1.0 (should be at baseline 0?)

	* semicolon.tamil (U+003B): X=60.5,Y=1.5 (should be at baseline 0?)

	* at (U+0040): X=223.0,Y=-0.5 (should be at baseline 0?)

	* at (U+0040): X=660.5,Y=715.5 (should be at cap-height 714?)

	* W (U+0057): X=437.0,Y=713.0 (should be at cap-height 714?)

	* a (U+0061): X=99.0,Y=549.0 (should be at x-height 548?)

	* c (U+0063): X=374.5,Y=549.0 (should be at x-height 548?) 

	* 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[11] NotoSansTamilUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[13] NotoSansTamilUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=417.0,Y=715.0 (should be at cap-height 714?)

	* asterisk.tamil (U+002A): X=498.0,Y=716.0 (should be at cap-height 714?)

	* asterisk.tamil (U+002A): X=54.0,Y=716.0 (should be at cap-height 714?)

	* a (U+0061): X=443.5,Y=555.5 (should be at x-height 556?)

	* f (U+0066): X=373.0,Y=716.0 (should be at cap-height 714?)

	* h (U+0068): X=187.0,Y=557.5 (should be at x-height 556?)

	* t (U+0074): X=18.0,Y=557.0 (should be at x-height 556?)

	* ordmasculine (U+00BA): X=190.0,Y=712.0 (should be at cap-height 714?)

	* Aring (U+00C5): X=325.0,Y=713.0 (should be at cap-height 714?)

	* Aring (U+00C5): X=325.0,Y=713.0 (should be at cap-height 714?) 

	* 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<86.0,51.0>--<85.0,405.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansTamilUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent.tamil (U+0025): X=195.0,Y=713.0 (should be at cap-height 714?)

	* asterisk.tamil (U+002A): X=496.0,Y=713.0 (should be at cap-height 714?)

	* asterisk.tamil (U+002A): X=54.0,Y=713.0 (should be at cap-height 714?)

	* I (U+0049): X=40.0,Y=713.0 (should be at cap-height 714?)

	* I (U+0049): X=298.0,Y=713.0 (should be at cap-height 714?)

	* R (U+0052): X=490.5,Y=714.5 (should be at cap-height 714?)

	* a (U+0061): X=433.0,Y=553.0 (should be at x-height 554?)

	* f (U+0066): X=218.5,Y=714.5 (should be at cap-height 714?)

	* section (U+00A7): X=411.0,Y=715.0 (should be at cap-height 714?)

	* ordfeminine (U+00AA): X=122.0,Y=713.5 (should be at cap-height 714?) 

	* 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[14] NotoSansTamilUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* R (U+0052): X=504.5,Y=713.0 (should be at cap-height 714?)

	* a (U+0061): X=456.5,Y=557.0 (should be at x-height 559?)

	* f (U+0066): X=18.0,Y=558.0 (should be at x-height 559?)

	* f (U+0066): X=301.0,Y=715.0 (should be at cap-height 714?)

	* t (U+0074): X=140.0,Y=712.0 (should be at cap-height 714?)

	* t (U+0074): X=219.0,Y=712.0 (should be at cap-height 714?)

	* copyright (U+00A9): X=416.0,Y=716.0 (should be at cap-height 714?)

	* registered (U+00AE): X=416.0,Y=716.0 (should be at cap-height 714?)

	* germandbls (U+00DF): X=332.0,Y=716.0 (should be at cap-height 714?)

	* eth (U+00F0): X=218.0,Y=716.0 (should be at cap-height 714?) 

	* 34 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,233.5>-<263.0,201.0>-<266.0,177.0>>/B<<266.0,177.0>-<269.0,202.0>-<275.0,235.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,233.0>-<684.0,201.0>-<687.0,177.0>>/B<<687.0,177.0>-<690.0,202.0>-<695.5,234.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,233.5>-<263.0,201.0>-<266.0,177.0>>/B<<266.0,177.0>-<269.0,202.0>-<275.0,235.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,233.0>-<684.0,201.0>-<687.0,177.0>>/B<<687.0,177.0>-<690.0,202.0>-<695.5,234.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,233.5>-<263.0,201.0>-<266.0,177.0>>/B<<266.0,177.0>-<269.0,202.0>-<275.0,235.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,233.0>-<684.0,201.0>-<687.0,177.0>>/B<<687.0,177.0>-<690.0,202.0>-<695.5,234.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,233.5>-<263.0,201.0>-<266.0,177.0>>/B<<266.0,177.0>-<269.0,202.0>-<275.0,235.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,233.0>-<684.0,201.0>-<687.0,177.0>>/B<<687.0,177.0>-<690.0,202.0>-<695.5,234.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,233.5>-<263.0,201.0>-<266.0,177.0>>/B<<266.0,177.0>-<269.0,202.0>-<275.0,235.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,233.0>-<684.0,201.0>-<687.0,177.0>>/B<<687.0,177.0>-<690.0,202.0>-<695.5,234.0>> = 13.967789761532726

	* ohmsigntamil (U+0BD0): B<<351.0,512.5>-<241.0,486.0>-<189.0,439.0>>/B<<189.0,439.0>-<207.0,449.0>-<228.5,454.5>> = 13.054126304702278 

	* rupeesigntamil (U+0BF9): B<<551.5,814.5>-<528.0,808.0>-<511.0,799.0>>/B<<511.0,799.0>-<515.0,800.0>-<519.0,800.0>> = 13.861027563021121 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<83.0,51.0>--<82.0,408.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansTamilUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=171.5,Y=712.0 (should be at cap-height 714?)

	* three.tamil (U+0033): X=392.0,Y=713.0 (should be at cap-height 714?)

	* six.tamil (U+0036): X=235.0,Y=715.5 (should be at cap-height 714?)

	* eight.tamil (U+0038): X=409.5,Y=715.5 (should be at cap-height 714?)

	* eight.tamil (U+0038): X=164.0,Y=713.5 (should be at cap-height 714?)

	* semicolon.tamil (U+003B): X=63.5,Y=0.5 (should be at baseline 0?)

	* question.tamil (U+003F): X=49.0,Y=713.0 (should be at cap-height 714?)

	* at (U+0040): X=221.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=659.0,Y=713.5 (should be at cap-height 714?)

	* C (U+0043): X=573.0,Y=713.0 (should be at cap-height 714?) 

	* 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.tamil (U+0021): L<<105.0,225.0>--<103.0,765.0>>

	* exclam.tamil (U+0021): L<<131.0,765.0>--<129.0,225.0>>

	* exclamdown (U+00A1): L<<122.0,405.0>--<124.0,-135.0>> 

	* exclamdown (U+00A1): L<<96.0,-135.0>--<98.0,405.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansTamil[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 82 | 163 | 2154 | 116 | 1792 | 0 |
| 0% | 2% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
