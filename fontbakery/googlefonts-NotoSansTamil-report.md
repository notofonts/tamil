## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf', 'fonts/NotoSansTamil/googlefonts/ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Tamil Regular: 870
Noto Sans Tamil Black: 870
Noto Sans Tamil Bold: 870
Noto Sans Tamil ExtraBold: 870
Noto Sans Tamil ExtraLight: 870
Noto Sans Tamil Light: 870
Noto Sans Tamil Medium: 870
Noto Sans Tamil SemiBold: 870
Noto Sans Tamil Thin: 870
Noto Sans Tamil UI Black: 1069
Noto Sans Tamil UI Bold: 1069
Noto Sans Tamil UI ExtraBold: 1069
Noto Sans Tamil UI ExtraLight: 1069
Noto Sans Tamil UI Light: 1069
Noto Sans Tamil UI Medium: 1069
Noto Sans Tamil UI Regular: 1069
Noto Sans Tamil UI SemiBold: 1069
Noto Sans Tamil UI Thin: 1069 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Noto Sans Tamil Regular: -370
Noto Sans Tamil Black: -370
Noto Sans Tamil Bold: -370
Noto Sans Tamil ExtraBold: -370
Noto Sans Tamil ExtraLight: -370
Noto Sans Tamil Light: -370
Noto Sans Tamil Medium: -370
Noto Sans Tamil SemiBold: -370
Noto Sans Tamil Thin: -370
Noto Sans Tamil UI Black: -293
Noto Sans Tamil UI Bold: -293
Noto Sans Tamil UI ExtraBold: -293
Noto Sans Tamil UI ExtraLight: -293
Noto Sans Tamil UI Light: -293
Noto Sans Tamil UI Medium: -293
Noto Sans Tamil UI Regular: -293
Noto Sans Tamil UI SemiBold: -293
Noto Sans Tamil UI Thin: -293 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Noto Sans Tamil Regular: 870
Noto Sans Tamil Black: 870
Noto Sans Tamil Bold: 870
Noto Sans Tamil ExtraBold: 870
Noto Sans Tamil ExtraLight: 870
Noto Sans Tamil Light: 870
Noto Sans Tamil Medium: 870
Noto Sans Tamil SemiBold: 870
Noto Sans Tamil Thin: 870
Noto Sans Tamil UI Black: 1069
Noto Sans Tamil UI Bold: 1069
Noto Sans Tamil UI ExtraBold: 1069
Noto Sans Tamil UI ExtraLight: 1069
Noto Sans Tamil UI Light: 1069
Noto Sans Tamil UI Medium: 1069
Noto Sans Tamil UI Regular: 1069
Noto Sans Tamil UI SemiBold: 1069
Noto Sans Tamil UI Thin: 1069 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Noto Sans Tamil Regular: 370
Noto Sans Tamil Black: 370
Noto Sans Tamil Bold: 370
Noto Sans Tamil ExtraBold: 370
Noto Sans Tamil ExtraLight: 370
Noto Sans Tamil Light: 370
Noto Sans Tamil Medium: 370
Noto Sans Tamil SemiBold: 370
Noto Sans Tamil Thin: 370
Noto Sans Tamil UI Black: 293
Noto Sans Tamil UI Bold: 293
Noto Sans Tamil UI ExtraBold: 293
Noto Sans Tamil UI ExtraLight: 293
Noto Sans Tamil UI Light: 293
Noto Sans Tamil UI Medium: 293
Noto Sans Tamil UI Regular: 293
Noto Sans Tamil UI SemiBold: 293
Noto Sans Tamil UI Thin: 293 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Noto Sans Tamil Regular: 870
Noto Sans Tamil Black: 870
Noto Sans Tamil Bold: 870
Noto Sans Tamil ExtraBold: 870
Noto Sans Tamil ExtraLight: 870
Noto Sans Tamil Light: 870
Noto Sans Tamil Medium: 870
Noto Sans Tamil SemiBold: 870
Noto Sans Tamil Thin: 870
Noto Sans Tamil UI Black: 1069
Noto Sans Tamil UI Bold: 1069
Noto Sans Tamil UI ExtraBold: 1069
Noto Sans Tamil UI ExtraLight: 1069
Noto Sans Tamil UI Light: 1069
Noto Sans Tamil UI Medium: 1069
Noto Sans Tamil UI Regular: 1069
Noto Sans Tamil UI SemiBold: 1069
Noto Sans Tamil UI Thin: 1069 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Noto Sans Tamil Regular: -370
Noto Sans Tamil Black: -370
Noto Sans Tamil Bold: -370
Noto Sans Tamil ExtraBold: -370
Noto Sans Tamil ExtraLight: -370
Noto Sans Tamil Light: -370
Noto Sans Tamil Medium: -370
Noto Sans Tamil SemiBold: -370
Noto Sans Tamil Thin: -370
Noto Sans Tamil UI Black: -293
Noto Sans Tamil UI Bold: -293
Noto Sans Tamil UI ExtraBold: -293
Noto Sans Tamil UI ExtraLight: -293
Noto Sans Tamil UI Light: -293
Noto Sans Tamil UI Medium: -293
Noto Sans Tamil UI Regular: -293
Noto Sans Tamil UI SemiBold: -293
Noto Sans Tamil UI Thin: -293 [code: descent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[18] NotoSansTamil[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansTamil[wght].ttf' must be renamed to 'NotoSansTamil[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Check variable font instances don't have duplicate names (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont_duplicate_instance_names">com.google.fonts/check/varfont_duplicate_instance_names</a>)</summary><div>


* 🔥 **FAIL** Following instances names are duplicate: 
	- ExtraLight
	- Light
	- Regular
	- Medium
	- SemiBold
	- Bold
 [code: duplicate-instance-names]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 270. [code: invalid-default-instance-postscript-nameid:270]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 279. [code: invalid-default-instance-postscript-nameid:279]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[18] NotoSansTamil-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* taprehalftamil
	* mauvowelsigntamil
	* llauuvowelsigntamil
	* ssaprehalftamil
	* oovowelsigntamil
	* satamil
	* nnnauuvowelsigntamil
	* llauvowelsigntamil
	* caiivowelsigntamil and 118 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<372.0,0.0>--<373.0,480.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] NotoSansTamil-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* taprehalftamil
	* llauuvowelsigntamil
	* ssaprehalftamil
	* oovowelsigntamil
	* satamil
	* nnnauuvowelsigntamil
	* llauvowelsigntamil
	* caiivowelsigntamil
	* monthsigntamil and 110 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 63 more.

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

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<80.0,0.0>--<79.0,360.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] NotoSansTamil-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* taprehalftamil
	* llauuvowelsigntamil
	* ssaprehalftamil
	* oovowelsigntamil
	* satamil
	* nnnauuvowelsigntamil
	* llauvowelsigntamil
	* caiivowelsigntamil
	* monthsigntamil and 117 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<371.0,0.0>--<372.0,483.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansTamil-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tchaprehalftamil
	* tchaiivowelsigntamil and tchatamil
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[16] NotoSansTamil-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* ssaprehalftamil
	* nnnauuvowelsigntamil
	* nyauvowelsigntamil
	* itamil
	* ssatamil
	* nnaiivowelsigntamil
	* nnauuvowelsigntamil
	* tauvowelsigntamil
	* tchaprehalftamil and 8 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSansTamil-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* taprehalftamil
	* llauuvowelsigntamil
	* ssaprehalftamil
	* nnnauuvowelsigntamil
	* llauvowelsigntamil
	* caiivowelsigntamil
	* nauuvowelsigntamil
	* nyauvowelsigntamil
	* itamil and 72 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<86.0,0.0>--<85.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansTamil-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
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
<path d="M88.0,0.0L88.0,554.0L604.0,554.0L604.0,482.0L430.0,482.0L430.0,324.0Q450.0,336.0 482.0,349.0Q514.0,362.0 558.0,362.0Q633.0,362.0 675.5,319.5Q718.0,277.0 718.0,201.0Q718.0,165.0 708.0,132.0Q698.0,99.0 682.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,0.0L344.0,0.0L344.0,72.0L595.0,72.0Q612.0,97.0 622.0,127.5Q632.0,158.0 632.0,192.0Q632.0,245.0 607.0,267.0Q582.0,289.0 543.0,289.0Q511.0,289.0 481.5,276.0Q452.0,263.0 430.0,246.0L430.0,144.0L344.0,144.0L344.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z"  transform="translate(0, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z"  transform="translate(1044, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z"  transform="translate(346, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z"  transform="translate(1684, 870)"/>
<path d="M15.0,369.0L15.0,423.0L130.0,535.0Q170.0,574.0 191.0,598.5Q212.0,623.0 219.5,642.5Q227.0,662.0 227.0,684.0Q227.0,716.0 208.5,732.0Q190.0,748.0 160.0,748.0Q130.0,748.0 105.5,736.5Q81.0,725.0 55.0,705.0L20.0,751.0Q49.0,776.0 83.5,791.0Q118.0,806.0 161.0,806.0Q225.0,806.0 261.5,774.5Q298.0,743.0 298.0,688.0Q298.0,639.0 268.5,600.0Q239.0,561.0 183.0,508.0L102.0,431.0L297.0,431.0L297.0,369.0L15.0,369.0Z"  transform="translate(2510, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z"  transform="translate(2822, 870)"/>
<path d="M-278.0,660.0Q-362.0,660.0 -407.0,700.5Q-452.0,741.0 -452.0,815.0Q-452.0,844.0 -444.0,870.0L-376.0,856.0Q-379.0,846.0 -380.0,835.5Q-381.0,825.0 -381.0,817.0Q-381.0,781.0 -366.5,761.0Q-352.0,741.0 -328.0,733.0Q-304.0,725.0 -278.0,725.0Q-237.0,725.0 -206.0,746.0Q-175.0,767.0 -175.0,819.0Q-175.0,827.0 -176.0,836.5Q-177.0,846.0 -180.0,856.0L-111.0,870.0Q-108.0,858.0 -106.0,843.0Q-104.0,828.0 -104.0,815.0Q-104.0,742.0 -150.5,701.0Q-197.0,660.0 -278.0,660.0ZM-279.0,767.0Q-301.0,767.0 -315.0,781.0Q-329.0,795.0 -329.0,818.0Q-329.0,839.0 -315.0,853.5Q-301.0,868.0 -279.0,868.0Q-257.0,868.0 -242.5,853.5Q-228.0,839.0 -228.0,818.0Q-228.0,795.0 -242.5,781.0Q-257.0,767.0 -279.0,767.0Z"  transform="translate(3742, 1105)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4076 2240" transform="matrix(1 0 0 -1 0 0)">
<path d="M88.0,0.0L88.0,554.0L604.0,554.0L604.0,482.0L430.0,482.0L430.0,324.0Q450.0,336.0 482.0,349.0Q514.0,362.0 558.0,362.0Q633.0,362.0 675.5,319.5Q718.0,277.0 718.0,201.0Q718.0,165.0 708.0,132.0Q698.0,99.0 682.0,72.0L870.0,72.0L870.0,554.0L956.0,554.0L956.0,0.0L344.0,0.0L344.0,72.0L595.0,72.0Q612.0,97.0 622.0,127.5Q632.0,158.0 632.0,192.0Q632.0,245.0 607.0,267.0Q582.0,289.0 543.0,289.0Q511.0,289.0 481.5,276.0Q452.0,263.0 430.0,246.0L430.0,144.0L344.0,144.0L344.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z"  transform="translate(0, 870)"/>
<path d="M88.0,0.0L88.0,554.0L623.0,554.0L623.0,482.0L453.0,482.0L453.0,0.0L367.0,0.0L367.0,482.0L174.0,482.0L174.0,0.0L88.0,0.0Z"  transform="translate(1044, 870)"/>
<path d="M56.0,722.0Q56.0,775.0 89.5,809.0Q123.0,843.0 176.0,843.0Q229.0,843.0 262.5,809.0Q296.0,775.0 296.0,722.0Q296.0,669.0 262.5,635.5Q229.0,602.0 176.0,602.0Q123.0,602.0 89.5,635.5Q56.0,669.0 56.0,722.0ZM116.0,722.0Q116.0,695.0 132.5,677.5Q149.0,660.0 176.0,660.0Q202.0,660.0 219.0,677.5Q236.0,695.0 236.0,722.0Q236.0,750.0 219.0,767.5Q202.0,785.0 176.0,785.0Q149.0,785.0 132.5,767.5Q116.0,750.0 116.0,722.0Z"  transform="translate(346, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,95.5Q57.0,151.0 57.0,239.0Q57.0,316.0 82.0,373.0Q107.0,430.0 150.0,468.0Q197.0,511.0 268.0,532.5Q339.0,554.0 451.0,554.0L784.0,554.0L784.0,482.0L614.0,482.0L614.0,0.0L528.0,0.0L528.0,482.0L439.0,482.0Q375.0,482.0 332.0,474.5Q289.0,467.0 261.5,454.0Q234.0,441.0 214.0,423.0Q156.0,372.0 141.0,291.0Q167.0,308.0 197.5,318.0Q228.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q294.0,56.0 317.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z"  transform="translate(1653, 870)"/>
<path d="M15.0,369.0L15.0,423.0L130.0,535.0Q170.0,574.0 191.0,598.5Q212.0,623.0 219.5,642.5Q227.0,662.0 227.0,684.0Q227.0,716.0 208.5,732.0Q190.0,748.0 160.0,748.0Q130.0,748.0 105.5,736.5Q81.0,725.0 55.0,705.0L20.0,751.0Q49.0,776.0 83.5,791.0Q118.0,806.0 161.0,806.0Q225.0,806.0 261.5,774.5Q298.0,743.0 298.0,688.0Q298.0,639.0 268.5,600.0Q239.0,561.0 183.0,508.0L102.0,431.0L297.0,431.0L297.0,369.0L15.0,369.0Z"  transform="translate(2479, 870)"/>
<path d="M249.0,-12.0Q196.0,-12.0 152.0,14.0Q108.0,40.0 82.5,96.5Q57.0,153.0 57.0,242.0Q57.0,350.0 98.5,422.0Q140.0,494.0 209.0,530.0Q278.0,566.0 359.0,566.0Q427.0,566.0 478.0,540.5Q529.0,515.0 567.0,461.0Q585.0,505.0 623.0,535.5Q661.0,566.0 719.0,566.0Q756.0,566.0 785.5,555.0Q815.0,544.0 837.0,521.0Q863.0,494.0 876.0,452.5Q889.0,411.0 889.0,343.0L889.0,255.0Q889.0,200.0 897.0,160.5Q905.0,121.0 930.0,95.0Q960.0,62.0 1015.0,62.0Q1049.0,62.0 1076.0,78.0Q1103.0,94.0 1119.0,132.0Q1135.0,170.0 1135.0,237.0Q1135.0,336.0 1099.5,412.5Q1064.0,489.0 1009.0,547.0L1087.0,600.0Q1149.0,521.0 1185.5,434.0Q1222.0,347.0 1222.0,244.0Q1222.0,117.0 1167.5,52.5Q1113.0,-12.0 1009.0,-12.0Q921.0,-12.0 869.0,38.0Q837.0,68.0 819.5,121.0Q802.0,174.0 802.0,250.0L802.0,288.0Q802.0,353.0 797.5,390.0Q793.0,427.0 783.0,449.0Q773.0,473.0 755.0,483.5Q737.0,494.0 714.0,494.0Q693.0,494.0 677.5,485.0Q662.0,476.0 652.0,463.0Q637.0,444.0 630.0,417.5Q623.0,391.0 623.0,351.0L623.0,0.0L537.0,0.0L537.0,293.0Q537.0,356.0 520.0,393.5Q503.0,431.0 477.0,453.0Q449.0,476.0 420.5,484.0Q392.0,492.0 355.0,492.0Q265.0,492.0 209.5,436.0Q154.0,380.0 140.0,290.0Q167.0,308.0 198.0,318.0Q229.0,328.0 261.0,328.0Q333.0,328.0 377.5,284.0Q422.0,240.0 422.0,165.0Q422.0,82.0 375.5,35.0Q329.0,-12.0 249.0,-12.0ZM247.0,258.0Q216.0,258.0 188.5,245.5Q161.0,233.0 136.0,212.0Q140.0,126.0 173.0,91.0Q206.0,56.0 253.0,56.0Q292.0,56.0 316.0,81.5Q340.0,107.0 340.0,155.0Q340.0,205.0 314.0,231.5Q288.0,258.0 247.0,258.0Z"  transform="translate(2791, 870)"/>
<path d="M-278.0,660.0Q-362.0,660.0 -407.0,700.5Q-452.0,741.0 -452.0,815.0Q-452.0,844.0 -444.0,870.0L-376.0,856.0Q-379.0,846.0 -380.0,835.5Q-381.0,825.0 -381.0,817.0Q-381.0,781.0 -366.5,761.0Q-352.0,741.0 -328.0,733.0Q-304.0,725.0 -278.0,725.0Q-237.0,725.0 -206.0,746.0Q-175.0,767.0 -175.0,819.0Q-175.0,827.0 -176.0,836.5Q-177.0,846.0 -180.0,856.0L-111.0,870.0Q-108.0,858.0 -106.0,843.0Q-104.0,828.0 -104.0,815.0Q-104.0,742.0 -150.5,701.0Q-197.0,660.0 -278.0,660.0ZM-279.0,767.0Q-301.0,767.0 -315.0,781.0Q-329.0,795.0 -329.0,818.0Q-329.0,839.0 -315.0,853.5Q-301.0,868.0 -279.0,868.0Q-257.0,868.0 -242.5,853.5Q-228.0,839.0 -228.0,818.0Q-228.0,795.0 -242.5,781.0Q-257.0,767.0 -279.0,767.0Z"  transform="translate(3711, 1105)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஸஂஊௗஂசாஂஔஃ</span> (Added by SIESTA)</li>


<pre>Expected: satamil=0+1285|anusvaratamil=0@-819,0+0|uutamil=2+1540|aulengthmarktamil=2+1025|anusvaratamil=2@-1971,0+0|catamil=5+723|aavowelsigntamil=5+617|anusvaratamil=5@-1155,0+0|autamil=8+1992|visargatamil=9+896</pre>



<pre>Got     : satamil=0+1285|anusvaratamil=0@-819,0+0|uutamil=2+1540|aulengthmarktamil=2+1070|anusvaratamil=2@-2016,0+0|catamil=5+723|aavowelsigntamil=5+640|anusvaratamil=5@-1178,0+0|autamil=8+1992|visargatamil=9+896</pre>



<pre>                                                                                       ^^                  ^^^^                                       ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8146 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(466, 870)"/>
<path d=""  transform="translate(1285, 870)"/>
<path d=""  transform="translate(2825, 870)"/>
<path d=""  transform="translate(1879, 870)"/>
<path d=""  transform="translate(3895, 870)"/>
<path d=""  transform="translate(4618, 870)"/>
<path d=""  transform="translate(4080, 870)"/>
<path d=""  transform="translate(5258, 870)"/>
<path d=""  transform="translate(7250, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8078 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(466, 870)"/>
<path d=""  transform="translate(1285, 870)"/>
<path d=""  transform="translate(2825, 870)"/>
<path d=""  transform="translate(1879, 870)"/>
<path d=""  transform="translate(3850, 870)"/>
<path d=""  transform="translate(4573, 870)"/>
<path d=""  transform="translate(4035, 870)"/>
<path d=""  transform="translate(5190, 870)"/>
<path d=""  transform="translate(7182, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ணைடுஂஸாஂஹௗஂ</span> (Added by SIESTA)</li>


<pre>Expected: aivowelsigntamil=0+1160|nnatamil=0+1633|ttauvowelsigntamil=2+1015|anusvaratamil=2@-88,0+264|satamil=5+1285|aavowelsigntamil=5+609|anusvaratamil=5@-1428,0+0|hatamil=8+1619|aulengthmarktamil=8+1070|anusvaratamil=8@-2053,0+0</pre>



<pre>Got     : aivowelsigntamil=0+1160|nnatamil=0+1633|ttauvowelsigntamil=2+1015|anusvaratamil=2+352|satamil=5+1285|aavowelsigntamil=5+640|anusvaratamil=5@-1459,0+0|hatamil=8+1619|aulengthmarktamil=8+1070|anusvaratamil=8@-2053,0+0</pre>



<pre>                                                                                           ^^^^^^^^^^                                    ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8774 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1160, 870)"/>
<path d=""  transform="translate(2793, 870)"/>
<path d=""  transform="translate(3808, 870)"/>
<path d=""  transform="translate(4160, 870)"/>
<path d=""  transform="translate(5445, 870)"/>
<path d=""  transform="translate(4626, 870)"/>
<path d=""  transform="translate(6085, 870)"/>
<path d=""  transform="translate(7704, 870)"/>
<path d=""  transform="translate(6721, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8655 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1160, 870)"/>
<path d=""  transform="translate(2793, 870)"/>
<path d=""  transform="translate(3720, 870)"/>
<path d=""  transform="translate(4072, 870)"/>
<path d=""  transform="translate(5357, 870)"/>
<path d=""  transform="translate(4538, 870)"/>
<path d=""  transform="translate(5966, 870)"/>
<path d=""  transform="translate(7585, 870)"/>
<path d=""  transform="translate(6602, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ழாஂலூஂ</span> (Added by SIESTA)</li>


<pre>Expected: lllatamil=0+858|aavowelsigntamil=0+609|anusvaratamil=0@-1214,0+0|lauuvowelsigntamil=3+1624|anusvaratamil=3@-988,0+0</pre>



<pre>Got     : lllatamil=0+858|aavowelsigntamil=0+640|anusvaratamil=0@-1245,0+0|lauuvowelsigntamil=3+1624|anusvaratamil=3@-988,0+0</pre>



<pre>                                               +                    +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3122 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(858, 870)"/>
<path d=""  transform="translate(253, 870)"/>
<path d=""  transform="translate(1498, 870)"/>
<path d=""  transform="translate(2134, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3091 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(858, 870)"/>
<path d=""  transform="translate(253, 870)"/>
<path d=""  transform="translate(1467, 870)"/>
<path d=""  transform="translate(2103, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ரஃிஂயாஂஉூஂ</span> (Added by SIESTA)</li>


<pre>Expected: ratamil=0+581|visargatamil=1+896|uni25CC=1+562|ivowelsigntamil=1+262|anusvaratamil=1@-88,0+264|yatamil=4+963|aavowelsigntamil=4+640|anusvaratamil=4@-1298,0+0|utamil=7+1067|uuvowelsigntamil=7+844|anusvaratamil=7@-1554,0+0</pre>



<pre>Got     : ratamil=0+581|visargatamil=1+896|uni25CC=1+562|ivowelsigntamil=1+262|anusvaratamil=1+352|yatamil=4+963|aavowelsigntamil=4+640|anusvaratamil=4@-1298,0+0|utamil=7+1067|uuvowelsigntamil=7+844|anusvaratamil=7@-1554,0+0</pre>



<pre>                                                                                              ^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6167 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(581, 870)"/>
<path d=""  transform="translate(1477, 870)"/>
<path d=""  transform="translate(2039, 870)"/>
<path d=""  transform="translate(2301, 870)"/>
<path d=""  transform="translate(2653, 870)"/>
<path d=""  transform="translate(3616, 870)"/>
<path d=""  transform="translate(2958, 870)"/>
<path d=""  transform="translate(4256, 870)"/>
<path d=""  transform="translate(5323, 870)"/>
<path d=""  transform="translate(4613, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6079 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(581, 870)"/>
<path d=""  transform="translate(1477, 870)"/>
<path d=""  transform="translate(2039, 870)"/>
<path d=""  transform="translate(2213, 870)"/>
<path d=""  transform="translate(2565, 870)"/>
<path d=""  transform="translate(3528, 870)"/>
<path d=""  transform="translate(2870, 870)"/>
<path d=""  transform="translate(4168, 870)"/>
<path d=""  transform="translate(5235, 870)"/>
<path d=""  transform="translate(4525, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ௗஞறாஂஸணு</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+562|aulengthmarktamil=0+1041|nyatamil=1+1210|rratamil=2+869|aavowelsigntamil=2+609|anusvaratamil=2@-1220,0+0|satamil=5+1285|nnauvowelsigntamil=6+1841</pre>



<pre>Got     : uni25CC=0+562|aulengthmarktamil=0+1041|nyatamil=1+1210|rratamil=2+869|aavowelsigntamil=2+640|anusvaratamil=2@-1251,0+0|satamil=5+1285|nnauvowelsigntamil=6+1841</pre>



<pre>                                                                                                     +                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7448 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(562, 870)"/>
<path d=""  transform="translate(1603, 870)"/>
<path d=""  transform="translate(2813, 870)"/>
<path d=""  transform="translate(3682, 870)"/>
<path d=""  transform="translate(3071, 870)"/>
<path d=""  transform="translate(4322, 870)"/>
<path d=""  transform="translate(5607, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7417 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(562, 870)"/>
<path d=""  transform="translate(1603, 870)"/>
<path d=""  transform="translate(2813, 870)"/>
<path d=""  transform="translate(3682, 870)"/>
<path d=""  transform="translate(3071, 870)"/>
<path d=""  transform="translate(4291, 870)"/>
<path d=""  transform="translate(5576, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஆுஂகெஏதவுஂறுஂ</span> (Added by SIESTA)</li>


<pre>Expected: aatamil=0+1313|uvowelsigntamil=0+502|anusvaratamil=0@-1334,0+0|evowelsigntamil=3+901|katamil=3+825|eetamil=5+756|tatamil=6+825|vauvowelsigntamil=7+1044|anusvaratamil=7@-698,0+0|rrauvowelsigntamil=10+1135|anusvaratamil=10@-745,0+0</pre>



<pre>Got     : aatamil=0+1203|uvowelsigntamil=0+502|anusvaratamil=0@-1224,0+0|evowelsigntamil=3+901|katamil=3+825|eetamil=5+756|tatamil=6+825|vauvowelsigntamil=7+1044|anusvaratamil=7@-698,0+0|rrauvowelsigntamil=10+1135|anusvaratamil=10@-745,0+0</pre>



<pre>                     ^^                                          ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7191 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1203, 870)"/>
<path d=""  transform="translate(481, 870)"/>
<path d=""  transform="translate(1705, 870)"/>
<path d=""  transform="translate(2606, 870)"/>
<path d=""  transform="translate(3431, 870)"/>
<path d=""  transform="translate(4187, 870)"/>
<path d=""  transform="translate(5012, 870)"/>
<path d=""  transform="translate(5358, 870)"/>
<path d=""  transform="translate(6056, 870)"/>
<path d=""  transform="translate(6446, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7301 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1313, 870)"/>
<path d=""  transform="translate(481, 870)"/>
<path d=""  transform="translate(1815, 870)"/>
<path d=""  transform="translate(2716, 870)"/>
<path d=""  transform="translate(3541, 870)"/>
<path d=""  transform="translate(4297, 870)"/>
<path d=""  transform="translate(5122, 870)"/>
<path d=""  transform="translate(5468, 870)"/>
<path d=""  transform="translate(6166, 870)"/>
<path d=""  transform="translate(6556, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ளீஎௗஂன்ஈாஂறஆ</span> (Added by SIESTA)</li>


<pre>Expected: llaiivowelsigntamil=0+1039|etamil=2+770|aulengthmarktamil=2+1039|anusvaratamil=2@-1585,0+0|nnnaprehalftamil=5+1234|iitamil=7+707|aavowelsigntamil=7+618|anusvaratamil=7@-1148,0+0|rratamil=10+840|aatamil=11+1313</pre>



<pre>Got     : llaiivowelsigntamil=0+1039|etamil=2+739|aulengthmarktamil=2+1070|anusvaratamil=2@-1585,0+0|nnnaprehalftamil=5+1234|iitamil=7+707|aavowelsigntamil=7+640|anusvaratamil=7@-1170,0+0|rratamil=10+840|aatamil=11+1313</pre>



<pre>                                               +++++++++++++++++++++++++                                                                                       ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7582 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1039, 870)"/>
<path d=""  transform="translate(1778, 870)"/>
<path d=""  transform="translate(1263, 870)"/>
<path d=""  transform="translate(2848, 870)"/>
<path d=""  transform="translate(4082, 870)"/>
<path d=""  transform="translate(4789, 870)"/>
<path d=""  transform="translate(4259, 870)"/>
<path d=""  transform="translate(5429, 870)"/>
<path d=""  transform="translate(6269, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7560 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1039, 870)"/>
<path d=""  transform="translate(1809, 870)"/>
<path d=""  transform="translate(1263, 870)"/>
<path d=""  transform="translate(2848, 870)"/>
<path d=""  transform="translate(4082, 870)"/>
<path d=""  transform="translate(4789, 870)"/>
<path d=""  transform="translate(4259, 870)"/>
<path d=""  transform="translate(5407, 870)"/>
<path d=""  transform="translate(6247, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ஐௗஂ𑌁᳚றௗஂஷூஂணௗஂ</span> (Added by SIESTA)</li>


<pre>Expected: aitamil=0+1022|aulengthmarktamil=0+1048|anusvaratamil=0@-1735,0+0|candrabindu_1CDA_tamil=0@-1281,235+0|rratamil=5+869|aulengthmarktamil=5+1039|anusvaratamil=5@-1650,0+0|ssatamil=8+1345|uuvowelsignalttamil=8+830|anusvaratamil=8@-1678,0+0|nnatamil=11+1617|aulengthmarktamil=11+1070|anusvaratamil=11@-2039,0+0</pre>



<pre>Got     : aitamil=0+1022|aulengthmarktamil=0+1070|anusvaratamil=0@-1757,0+0|candrabindu_1CDA_tamil=0@-1303,235+0|rratamil=5+869|aulengthmarktamil=5+1070|anusvaratamil=5@-1681,0+0|ssatamil=8+1345|uuvowelsignalttamil=8+830|anusvaratamil=8@-1678,0+0|nnatamil=11+1617|aulengthmarktamil=11+1070|anusvaratamil=11@-2039,0+0</pre>



<pre>                                               +++++++++++++++++++++ ^^                                ^^^                                            ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8893 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1022, 870)"/>
<path d=""  transform="translate(335, 870)"/>
<path d=""  transform="translate(789, 1105)"/>
<path d=""  transform="translate(2092, 870)"/>
<path d=""  transform="translate(2961, 870)"/>
<path d=""  transform="translate(2350, 870)"/>
<path d=""  transform="translate(4031, 870)"/>
<path d=""  transform="translate(5376, 870)"/>
<path d=""  transform="translate(4528, 870)"/>
<path d=""  transform="translate(6206, 870)"/>
<path d=""  transform="translate(7823, 870)"/>
<path d=""  transform="translate(6854, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8840 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(1022, 870)"/>
<path d=""  transform="translate(335, 870)"/>
<path d=""  transform="translate(789, 1105)"/>
<path d=""  transform="translate(2070, 870)"/>
<path d=""  transform="translate(2939, 870)"/>
<path d=""  transform="translate(2328, 870)"/>
<path d=""  transform="translate(3978, 870)"/>
<path d=""  transform="translate(5323, 870)"/>
<path d=""  transform="translate(4475, 870)"/>
<path d=""  transform="translate(6153, 870)"/>
<path d=""  transform="translate(7770, 870)"/>
<path d=""  transform="translate(6801, 870)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">பௗஂஎஷஸ்ரீஆ॒</span> (Added by SIESTA)</li>


<pre>Expected: patamil=0+778|aulengthmarktamil=0+1039|anusvaratamil=0@-1604,0+0|etamil=3+770|ssatamil=4+1345|shritamil=5+1514|aatamil=9+1313|uni0952=9@-378,-317+0</pre>



<pre>Got     : patamil=0+778|aulengthmarktamil=0+1070|anusvaratamil=0@-1635,0+0|etamil=3+770|ssatamil=4+1345|shritamil=5+1514|aatamil=9+1313|uni0952=9@-378,-317+0</pre>



<pre>                                              ^^                    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6790 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(778, 870)"/>
<path d=""  transform="translate(213, 870)"/>
<path d=""  transform="translate(1848, 870)"/>
<path d=""  transform="translate(2618, 870)"/>
<path d=""  transform="translate(3963, 870)"/>
<path d=""  transform="translate(5477, 870)"/>
<path d=""  transform="translate(6412, 553)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6759 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(778, 870)"/>
<path d=""  transform="translate(213, 870)"/>
<path d=""  transform="translate(1817, 870)"/>
<path d=""  transform="translate(2587, 870)"/>
<path d=""  transform="translate(3932, 870)"/>
<path d=""  transform="translate(5446, 870)"/>
<path d=""  transform="translate(6381, 553)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ுஃஜ॒ிஂ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+562|uvowelsigntamil=0+483|visargatamil=1+896|jatamil=2+1022|uni0952=2@-233,-317+0|uni25CC=2+562|ivowelsigntamil=2+262|anusvaratamil=2@-88,0+264</pre>



<pre>Got     : uni25CC=0+562|uvowelsigntamil=0+483|visargatamil=1+896|jatamil=2+1022|uni0952=2@-233,-317+0|uni25CC=2+562|ivowelsigntamil=2+262|anusvaratamil=2+352</pre>



<pre>                                                                                                                                                         ++++++  ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4139 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(562, 870)"/>
<path d=""  transform="translate(1045, 870)"/>
<path d=""  transform="translate(1941, 870)"/>
<path d=""  transform="translate(2730, 553)"/>
<path d=""  transform="translate(2963, 870)"/>
<path d=""  transform="translate(3525, 870)"/>
<path d=""  transform="translate(3787, 870)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4051 2240" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 870)"/>
<path d=""  transform="translate(562, 870)"/>
<path d=""  transform="translate(1045, 870)"/>
<path d=""  transform="translate(1941, 870)"/>
<path d=""  transform="translate(2730, 553)"/>
<path d=""  transform="translate(2963, 870)"/>
<path d=""  transform="translate(3525, 870)"/>
<path d=""  transform="translate(3699, 870)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* taprehalftamil
	* llauuvowelsigntamil
	* ssaprehalftamil
	* nnnauuvowelsigntamil
	* caiivowelsigntamil
	* nauuvowelsigntamil
	* nyauvowelsigntamil
	* itamil
	* rrauuvowelsigntamil and 48 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[19] NotoSansTamil-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kauuvowelsigntamil
	* taprehalftamil
	* llauuvowelsigntamil
	* ssaprehalftamil
	* nnnauuvowelsigntamil
	* llauvowelsigntamil
	* caiivowelsigntamil
	* monthsigntamil
	* nauuvowelsigntamil
	* nyauvowelsigntamil and 89 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 89 more.

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

	* And rupeesigntamil (U+0BF9): B<<551.5,763.5>-<528.0,757.0>-<511.0,748.0>>/B<<511.0,748.0>-<515.0,749.0>-<519.0,749.0>> = 13.861027563021121 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<83.0,0.0>--<82.0,357.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansTamil-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.tamil (U+0021): L<<105.0,174.0>--<103.0,714.0>>

	* exclam.tamil (U+0021): L<<131.0,714.0>--<129.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSansTamilUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<372.0,51.0>--<373.0,531.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSansTamilUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 65 more.

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

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<80.0,51.0>--<79.0,411.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] NotoSansTamilUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 71 more.

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

	* And Wgrave (U+1E80): B<<506.5,526.5>-<502.0,551.0>-<501.0,567.0>>/B<<501.0,567.0>-<499.0,551.0>-<494.5,526.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* rupeesigntamil (U+0BF9): L<<371.0,51.0>--<372.0,534.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansTamilUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[15] NotoSansTamilUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSansTamilUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<86.0,51.0>--<85.0,405.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansTamilUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[18] NotoSansTamilUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 34 more.

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

	* And rupeesigntamil (U+0BF9): B<<551.5,814.5>-<528.0,808.0>-<511.0,799.0>>/B<<511.0,799.0>-<515.0,800.0>-<519.0,800.0>> = 13.861027563021121 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* hundredtamil (U+0BF1): L<<83.0,51.0>--<82.0,408.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSansTamilUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 322, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tamil UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.tamil	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.tamil (U+0021): L<<105.0,225.0>--<103.0,765.0>>

	* exclam.tamil (U+0021): L<<131.0,765.0>--<129.0,225.0>>

	* exclamdown (U+00A1): L<<122.0,405.0>--<124.0,-135.0>> 

	* And exclamdown (U+00A1): L<<96.0,-135.0>--<98.0,405.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansTamil[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTamil/googlefonts/slim-variable-ttf/NotoSansTamil[wght].ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamil-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Black.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Bold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-ExtraLight.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Light.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Medium.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Regular.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-SemiBold.ttf', 'fonts/NotoSansTamil/googlefonts/ttf/NotoSansTamilUI-Thin.ttf', 'fonts/NotoSansTamil/googlefonts/variable-ttf/NotoSansTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1063, but got 870 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.tamil": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- u1133C

	- uni1CDA

	- uni0951

	- uni0952

	- u11301 

	- And u1133B [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 292. [code: invalid-default-instance-subfamily-nameid:292]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- bracketright

	- eight

	- four

	- equal

	- less

	- zero

	- emdash

	- asterisk

	- numbersign

	- bracketleft 

	- And 34 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntamil (U+0BBE), anusvaratamil (U+0B82), aulengthmarktamil (U+0BD7), ivowelsign1tamil (unencoded), ivowelsign2tamil (unencoded), ivowelsign3tamil (unencoded), ivowelsign4tamil (unencoded), ivowelsigntamil (U+0BBF), u11303 (U+11303), uuvowelsignalttamil (unencoded) and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+11303 [code: non-mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 151 | 188 | 2265 | 140 | 1671 | 0 |
| 0% | 3% | 4% | 51% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
