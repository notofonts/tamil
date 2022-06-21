## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf', 'fonts/NotoSerifTamil/googlefonts/ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerifTamil[wght].ttf' must be renamed to 'NotoSerifTamil[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Check variable font instances have correct names (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont_instance_names">com.google.fonts/check/varfont_instance_names</a>)</summary><div>


* 🔥 **FAIL** Following instances are not supported: 
	- SemiCondensed ExtraLight
	- SemiCondensed Light
	- SemiCondensed
	- SemiCondensed Medium
	- SemiCondensed SemiBold
	- SemiCondensed Bold
	- Condensed ExtraLight
	- Condensed Light
	- Condensed
	- Condensed Medium
	- Condensed SemiBold
	- Condensed Bold
	- ExtraCondensed ExtraLight
	- ExtraCondensed Light
	- ExtraCondensed
	- ExtraCondensed Medium
	- ExtraCondensed SemiBold
	- ExtraCondensed Bold

Further info can be found in our spec https://github.com/googlefonts/gf-docs/tree/main/Spec#fvar-instances [code: bad-instance-names]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 297. [code: invalid-default-instance-postscript-nameid:297]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0BBE (U+0BBE), uni0BBF (U+0BBF), uni0BBF.alt01 (unencoded), uni0BBF.alt02 (unencoded), uni0BC1 (U+0BC1), uni0BC1.alt01 (unencoded), uni0BC1.alt02 (unencoded), uni0BC2 (U+0BC2), uni0BC2.alt01 (unencoded), uni0BC2.alt02 (unencoded), uni0BD7 (U+0BD7) and uniA8F3 (U+A8F3) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=328.0,Y=0.5 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* s (U+0073): X=123.0,Y=2.0 (should be at baseline 0?) 

	* And 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=765.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=117.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=317.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=317.0,Y=-1.0 (should be at baseline 0?)

	* p (U+0070): X=337.5,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=386.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=367.0,Y=1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=329.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=469.0,Y=2.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=480.5,Y=-1.0 (should be at baseline 0?) 

	* And 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ca-tamil (U+0B9A): L<<253.0,348.0>--<259.0,348.0>> -> L<<259.0,348.0>--<391.0,348.0>>

	* four-tamil (U+0BEA): L<<253.0,348.0>--<259.0,348.0>> -> L<<259.0,348.0>--<391.0,348.0>>

	* ka-tamil (U+0B95): L<<253.0,348.0>--<256.0,348.0>> -> L<<256.0,348.0>--<391.0,348.0>>

	* nine-tamil (U+0BEF): L<<253.0,348.0>--<259.0,348.0>> -> L<<259.0,348.0>--<391.0,348.0>>

	* one-tamil (U+0BE7): L<<253.0,348.0>--<256.0,348.0>> -> L<<256.0,348.0>--<391.0,348.0>> 

	* And six-tamil (U+0BEC): L<<253.0,348.0>--<259.0,348.0>> -> L<<259.0,348.0>--<391.0,348.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 

	* And ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifTamil-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=343.0,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=336.0,Y=2.0 (should be at baseline 0?)

	* J (U+004A): X=281.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=265.0,Y=-1.5 (should be at baseline 0?)

	* t (U+0074): X=119.0,Y=561.0 (should be at x-height 563?)

	* t (U+0074): X=332.5,Y=-1.0 (should be at baseline 0?)

	* Acircumflex (U+00C2): X=380.0,Y=861.0 (should be at cap-height 863?)

	* Ecircumflex (U+00CA): X=318.0,Y=861.0 (should be at cap-height 863?)

	* Icircumflex (U+00CE): X=200.0,Y=861.0 (should be at cap-height 863?)

	* Ocircumflex (U+00D4): X=392.0,Y=861.0 (should be at cap-height 863?) 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ai-tamil (U+0B90): B<<585.5,-212.0>-<571.0,-183.0>-<568.0,-158.0>>/B<<568.0,-158.0>-<561.0,-220.0>-<526.0,-256.5>> = 13.284373511965962

	* nga-tamil (U+0B99): B<<661.0,87.0>-<631.0,67.0>-<602.0,61.0>>/L<<602.0,61.0>--<842.0,61.0>> = 11.689369175439202

	* sa-tamil (U+0BB8): B<<590.0,515.5>-<670.0,462.0>-<692.0,360.0>>/L<<692.0,360.0>--<692.0,407.0>> = 12.171458208587458

	* three-tamil (U+0BE9): B<<651.5,87.0>-<621.0,67.0>-<592.0,61.0>>/L<<592.0,61.0>--<918.0,61.0>> = 11.689369175439202

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 

	* And ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>> 

	* And sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-Condensed.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=447.5,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=49.5,Y=-2.0 (should be at baseline 0?)

	* g (U+0067): X=441.0,Y=552.5 (should be at x-height 554?)

	* y (U+0079): X=222.0,Y=-1.0 (should be at baseline 0?)

	* y (U+0079): X=286.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=295.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=81.0,Y=1.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=226.0,Y=2.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=412.0,Y=2.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=257.0,Y=817.5 (should be at cap-height 819?) 

	* And 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-CondensedBlack.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* J (U+004A): X=105.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=280.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=465.0,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=258.0,Y=2.0 (should be at baseline 0?)

	* bracketright (U+005D): X=143.0,Y=2.0 (should be at baseline 0?)

	* p (U+0070): X=248.5,Y=-1.5 (should be at baseline 0?)

	* t (U+0074): X=325.0,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=288.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=411.5,Y=2.0 (should be at baseline 0?)

	* Adieresis (U+00C4): X=376.0,Y=854.0 (should be at cap-height 855?) 

	* And 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<578.0,121.0>--<578.0,605.0>>/L<<578.0,605.0>--<426.0,0.0>> = 14.103073662556335

	* fourinferior (U+2084): B<<167.0,228.0>-<167.0,245.0>-<170.0,264.0>>/B<<170.0,264.0>-<165.0,251.0>-<160.0,239.5>> = 12.064884410525359

	* foursuperior (U+2074): B<<167.0,713.0>-<167.0,730.0>-<170.0,749.0>>/B<<170.0,749.0>-<165.0,736.0>-<160.0,724.5>> = 12.064884410525359

	* y (U+0079): B<<296.5,179.5>-<302.0,151.0>-<303.0,132.0>>/B<<303.0,132.0>-<308.0,175.0>-<316.0,206.0>> = 9.645302119321792

	* yacute (U+00FD): B<<296.5,179.5>-<302.0,151.0>-<303.0,132.0>>/B<<303.0,132.0>-<308.0,175.0>-<316.0,206.0>> = 9.645302119321792

	* ycircumflex (U+0177): B<<296.5,179.5>-<302.0,151.0>-<303.0,132.0>>/B<<303.0,132.0>-<308.0,175.0>-<316.0,206.0>> = 9.645302119321792

	* ydieresis (U+00FF): B<<296.5,179.5>-<302.0,151.0>-<303.0,132.0>>/B<<303.0,132.0>-<308.0,175.0>-<316.0,206.0>> = 9.645302119321792 

	* And ygrave (U+1EF3): B<<296.5,179.5>-<302.0,151.0>-<303.0,132.0>>/B<<303.0,132.0>-<308.0,175.0>-<316.0,206.0>> = 9.645302119321792 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<399.0,334.0>--<258.0,335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] NotoSerifTamil-CondensedBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME entry for Win "Condensed Bold" must be "Bold". Please note, since the font style is RIBBI, this record can be safely deleted. [code: bad-win-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=429.0,Y=-1.0 (should be at baseline 0?)

	* j (U+006A): X=89.0,Y=-2.0 (should be at baseline 0?)

	* t (U+0074): X=106.0,Y=562.0 (should be at x-height 564?)

	* t (U+0074): X=293.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=295.0,Y=-2.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=486.5,Y=842.0 (should be at cap-height 841?)

	* Ntilde (U+00D1): X=509.5,Y=842.0 (should be at cap-height 841?)

	* Otilde (U+00D5): X=501.5,Y=842.0 (should be at cap-height 841?)

	* ij (U+0133): X=398.0,Y=-2.0 (should be at baseline 0?)

	* Eng (U+014A): X=527.0,Y=2.0 (should be at baseline 0?) 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* four (U+0034): B<<252.0,526.5>-<253.0,575.0>-<256.0,621.0>>/B<<256.0,621.0>-<250.0,601.0>-<237.0,573.0>> = 12.967847234833151

	* fourinferior (U+2084): B<<175.5,230.5>-<176.0,248.0>-<178.0,267.0>>/B<<178.0,267.0>-<174.0,256.0>-<169.0,245.5>> = 13.974100564405422 

	* And foursuperior (U+2074): B<<175.5,715.5>-<176.0,733.0>-<178.0,752.0>>/B<<178.0,752.0>-<174.0,741.0>-<169.0,730.5>> = 13.974100564405422 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<223.0,312.0>--<224.0,116.0>> 

	* And sterling (U+00A3): L<<375.0,337.0>--<238.0,338.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-CondensedExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=291.5,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=268.0,Y=-2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=243.0,Y=-2.0 (should be at baseline 0?)

	* bracketright (U+005D): X=142.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=228.5,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=95.0,Y=571.0 (should be at x-height 572?)

	* j (U+006A): X=86.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=311.0,Y=-0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=291.5,Y=-2.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=230.0,Y=846.0 (should be at cap-height 848?) 

	* And 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* fourinferior (U+2084): B<<170.5,229.0>-<171.0,246.0>-<173.0,265.0>>/B<<173.0,265.0>-<169.0,253.0>-<164.0,242.0>> = 12.425942865427455

	* foursuperior (U+2074): B<<170.5,714.0>-<171.0,731.0>-<173.0,750.0>>/B<<173.0,750.0>-<169.0,738.0>-<164.0,727.0>> = 12.425942865427455

	* y (U+0079): B<<288.5,172.0>-<294.0,142.0>-<296.0,122.0>>/B<<296.0,122.0>-<299.0,145.0>-<303.5,166.0>> = 13.142001108672124

	* yacute (U+00FD): B<<288.5,172.0>-<294.0,142.0>-<296.0,122.0>>/B<<296.0,122.0>-<299.0,145.0>-<303.5,166.0>> = 13.142001108672124

	* ycircumflex (U+0177): B<<288.5,172.0>-<294.0,142.0>-<296.0,122.0>>/B<<296.0,122.0>-<299.0,145.0>-<303.5,166.0>> = 13.142001108672124

	* ydieresis (U+00FF): B<<288.5,172.0>-<294.0,142.0>-<296.0,122.0>>/B<<296.0,122.0>-<299.0,145.0>-<303.5,166.0>> = 13.142001108672124 

	* And ygrave (U+1EF3): B<<288.5,172.0>-<294.0,142.0>-<296.0,122.0>>/B<<296.0,122.0>-<299.0,145.0>-<303.5,166.0>> = 13.142001108672124 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<241.0,308.0>--<242.0,119.0>> 

	* And sterling (U+00A3): L<<388.0,335.0>--<249.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-CondensedExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=146.5,Y=-2.0 (should be at baseline 0?)

	* parenright (U+0029): X=110.5,Y=-2.0 (should be at baseline 0?)

	* comma (U+002C): X=84.5,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=97.0,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=411.5,Y=-0.5 (should be at baseline 0?)

	* a (U+0061): X=213.0,Y=543.0 (should be at x-height 545?)

	* b (U+0062): X=279.0,Y=544.0 (should be at x-height 545?)

	* c (U+0063): X=223.0,Y=543.0 (should be at x-height 545?)

	* d (U+0064): X=219.0,Y=544.0 (should be at x-height 545?)

	* e (U+0065): X=220.0,Y=543.0 (should be at x-height 545?) 

	* And 78 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<425.0,359.0>--<423.0,30.0>>

	* E (U+0045): L<<161.0,359.0>--<160.0,30.0>>

	* Eacute (U+00C9): L<<161.0,359.0>--<160.0,30.0>>

	* Ecaron (U+011A): L<<161.0,359.0>--<160.0,30.0>>

	* Ecircumflex (U+00CA): L<<161.0,359.0>--<160.0,30.0>>

	* Edieresis (U+00CB): L<<161.0,359.0>--<160.0,30.0>>

	* Edotaccent (U+0116): L<<161.0,359.0>--<160.0,30.0>>

	* Egrave (U+00C8): L<<161.0,359.0>--<160.0,30.0>>

	* Emacron (U+0112): L<<161.0,359.0>--<160.0,30.0>>

	* Eogonek (U+0118): L<<161.0,359.0>--<160.0,30.0>>

	* OE (U+0152): L<<422.0,359.0>--<420.0,30.0>> 

	* And euro (U+20AC): L<<147.0,303.0>--<301.0,302.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-CondensedLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* g (U+0067): X=422.5,Y=548.5 (should be at x-height 549?)

	* t (U+0074): X=260.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=226.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=297.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=391.0,Y=0.5 (should be at baseline 0?)

	* twosuperior (U+00B2): X=75.0,Y=798.0 (should be at cap-height 800?)

	* yacute (U+00FD): X=226.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=226.0,Y=-1.0 (should be at baseline 0?)

	* Edotaccent (U+0116): X=269.0,Y=799.0 (should be at cap-height 800?)

	* Edotaccent (U+0116): X=269.0,Y=799.0 (should be at cap-height 800?) 

	* And 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ca-tamil (U+0B9A): L<<203.0,309.0>--<206.0,309.0>> -> L<<206.0,309.0>--<340.0,309.0>>

	* four-tamil (U+0BEA): L<<203.0,309.0>--<206.0,309.0>> -> L<<206.0,309.0>--<340.0,309.0>>

	* ka-tamil (U+0B95): L<<203.0,309.0>--<205.0,309.0>> -> L<<205.0,309.0>--<340.0,309.0>>

	* nine-tamil (U+0BEF): L<<203.0,309.0>--<206.0,309.0>> -> L<<206.0,309.0>--<340.0,309.0>>

	* one-tamil (U+0BE7): L<<203.0,309.0>--<204.0,309.0>> -> L<<204.0,309.0>--<340.0,309.0>>

	* onethousand-tamil (U+0BF2): L<<184.0,309.0>--<187.0,309.0>> -> L<<187.0,309.0>--<321.0,309.0>>

	* six-tamil (U+0BEC): L<<203.0,309.0>--<205.0,309.0>> -> L<<205.0,309.0>--<340.0,309.0>> 

	* And ta-tamil (U+0BA4): L<<203.0,309.0>--<206.0,309.0>> -> L<<206.0,309.0>--<340.0,309.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<451.0,355.0>--<450.0,38.0>>

	* OE (U+0152): L<<454.0,355.0>--<453.0,38.0>> 

	* And la-tamil (U+0BB2): L<<469.0,156.0>--<468.0,328.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-CondensedMedium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=457.0,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=231.0,Y=1.5 (should be at baseline 0?)

	* t (U+0074): X=92.0,Y=559.0 (should be at x-height 557?)

	* y (U+0079): X=220.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=295.0,Y=-2.0 (should be at baseline 0?)

	* twosuperior (U+00B2): X=164.0,Y=824.0 (should be at cap-height 825?)

	* threesuperior (U+00B3): X=162.0,Y=823.0 (should be at cap-height 825?)

	* Atilde (U+00C3): X=268.5,Y=824.5 (should be at cap-height 825?)

	* Ntilde (U+00D1): X=298.5,Y=824.5 (should be at cap-height 825?)

	* Otilde (U+00D5): X=279.5,Y=824.5 (should be at cap-height 825?) 

	* And 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<354.0,334.0>--<220.0,335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifTamil-CondensedSemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* a (U+0061): X=230.5,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=295.0,Y=-2.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=247.0,Y=834.0 (should be at cap-height 832?)

	* Aring (U+00C5): X=323.0,Y=831.0 (should be at cap-height 832?)

	* Ntilde (U+00D1): X=273.0,Y=834.0 (should be at cap-height 832?)

	* Otilde (U+00D5): X=260.0,Y=834.0 (should be at cap-height 832?)

	* agrave (U+00E0): X=230.5,Y=0.5 (should be at baseline 0?)

	* aacute (U+00E1): X=230.5,Y=0.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=230.5,Y=0.5 (should be at baseline 0?)

	* atilde (U+00E3): X=230.5,Y=0.5 (should be at baseline 0?) 

	* And 27 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-CondensedThin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Condensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=82.5,Y=1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=95.5,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=401.5,Y=-1.5 (should be at baseline 0?)

	* b (U+0062): X=270.0,Y=544.0 (should be at x-height 542?)

	* d (U+0064): X=218.0,Y=544.0 (should be at x-height 542?)

	* d (U+0064): X=356.0,Y=544.0 (should be at x-height 542?)

	* g (U+0067): X=328.5,Y=540.0 (should be at x-height 542?)

	* g (U+0067): X=400.0,Y=543.5 (should be at x-height 542?)

	* r (U+0072): X=262.0,Y=544.0 (should be at x-height 542?)

	* s (U+0073): X=179.0,Y=541.0 (should be at x-height 542?) 

	* And 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<408.0,362.0>--<406.0,25.0>>

	* E (U+0045): L<<149.0,362.0>--<148.0,25.0>>

	* Eacute (U+00C9): L<<149.0,362.0>--<148.0,25.0>>

	* Ecaron (U+011A): L<<149.0,362.0>--<148.0,25.0>>

	* Ecircumflex (U+00CA): L<<149.0,362.0>--<148.0,25.0>>

	* Edieresis (U+00CB): L<<149.0,362.0>--<148.0,25.0>>

	* Edotaccent (U+0116): L<<149.0,362.0>--<148.0,25.0>>

	* Egrave (U+00C8): L<<149.0,362.0>--<148.0,25.0>>

	* Emacron (U+0112): L<<149.0,362.0>--<148.0,25.0>>

	* Eogonek (U+0118): L<<149.0,362.0>--<148.0,25.0>> 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=348.5,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=274.0,Y=1.0 (should be at baseline 0?)

	* bracketright (U+005D): X=162.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=265.0,Y=-1.5 (should be at baseline 0?)

	* t (U+0074): X=351.0,Y=0.5 (should be at baseline 0?)

	* y (U+0079): X=353.0,Y=2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=353.0,Y=2.0 (should be at baseline 0?) 

	* And 34 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asabove-tamil (U+0BF8): L<<1781.0,69.0>--<1781.0,69.0>> -> L<<1781.0,69.0>--<1789.0,69.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eogonek (U+0119): B<<270.5,-58.5>-<297.0,-26.0>-<333.0,-9.0>>/B<<333.0,-9.0>-<329.0,-10.0>-<324.0,-10.0>> = 11.24147876762648

	* nga-tamil (U+0B99): B<<692.0,100.5>-<659.0,78.0>-<623.0,69.0>>/L<<623.0,69.0>--<852.0,69.0>> = 14.036243467926484

	* three-tamil (U+0BE9): B<<688.5,100.5>-<656.0,78.0>-<620.0,69.0>>/L<<620.0,69.0>--<946.0,69.0>> = 14.036243467926484

	* y (U+0079): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* yacute (U+00FD): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ycircumflex (U+0177): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ydieresis (U+00FF): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296 

	* And ygrave (U+1EF3): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<442.0,340.0>--<284.0,341.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraCondensed.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=417.5,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=44.5,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=410.5,Y=552.5 (should be at x-height 554?)

	* sterling (U+00A3): X=272.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=49.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=365.5,Y=1.5 (should be at baseline 0?)

	* section (U+00A7): X=72.0,Y=1.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=209.0,Y=2.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=383.0,Y=2.0 (should be at baseline 0?)

	* Adieresis (U+00C4): X=324.5,Y=816.5 (should be at cap-height 815?) 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraCondensedBlack.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=274.0,Y=0.5 (should be at baseline 0?)

	* J (U+004A): X=100.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=267.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=439.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=235.0,Y=1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=271.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=387.0,Y=2.0 (should be at baseline 0?)

	* Aacute (U+00C1): X=439.5,Y=847.0 (should be at cap-height 846?)

	* Aring (U+00C5): X=262.0,Y=848.0 (should be at cap-height 846?)

	* Aring (U+00C5): X=404.0,Y=848.0 (should be at cap-height 846?) 

	* And 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<312.0,0.0>--<165.0,609.0>>/L<<165.0,609.0>--<165.0,119.0>> = 13.570434385161475

	* M (U+004D): L<<545.0,120.0>--<545.0,608.0>>/L<<545.0,608.0>--<406.0,0.0>> = 12.877560320753728

	* W (U+0057): B<<313.5,228.0>-<319.0,198.0>-<321.0,177.0>>/B<<321.0,177.0>-<326.0,209.0>-<335.0,241.0>> = 14.320991181525747

	* Wacute (U+1E82): B<<313.5,228.0>-<319.0,198.0>-<321.0,177.0>>/B<<321.0,177.0>-<326.0,209.0>-<335.0,241.0>> = 14.320991181525747

	* Wcircumflex (U+0174): B<<313.5,228.0>-<319.0,198.0>-<321.0,177.0>>/B<<321.0,177.0>-<326.0,209.0>-<335.0,241.0>> = 14.320991181525747

	* Wdieresis (U+1E84): B<<313.5,228.0>-<319.0,198.0>-<321.0,177.0>>/B<<321.0,177.0>-<326.0,209.0>-<335.0,241.0>> = 14.320991181525747

	* Wgrave (U+1E80): B<<313.5,228.0>-<319.0,198.0>-<321.0,177.0>>/B<<321.0,177.0>-<326.0,209.0>-<335.0,241.0>> = 14.320991181525747

	* fourinferior (U+2084): B<<157.5,229.0>-<158.0,246.0>-<160.0,265.0>>/B<<160.0,265.0>-<156.0,252.0>-<151.0,241.0>> = 11.093723011557817

	* foursuperior (U+2074): B<<157.5,714.0>-<158.0,731.0>-<160.0,750.0>>/B<<160.0,750.0>-<156.0,737.0>-<151.0,726.0>> = 11.093723011557817

	* y (U+0079): B<<280.0,176.5>-<285.0,147.0>-<286.0,127.0>>/B<<286.0,127.0>-<290.0,173.0>-<299.0,206.0>> = 7.832145954222035 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<375.0,334.0>--<242.0,335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] NotoSerifTamil-ExtraCondensedBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME entry for Win "ExtraCondensed Bold" must be "Bold". Please note, since the font style is RIBBI, this record can be safely deleted. [code: bad-win-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=403.0,Y=-2.0 (should be at baseline 0?)

	* t (U+0074): X=100.0,Y=563.0 (should be at x-height 565?)

	* sterling (U+00A3): X=271.5,Y=-1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=378.0,Y=1.5 (should be at baseline 0?)

	* Agrave (U+00C0): X=337.0,Y=829.0 (should be at cap-height 831?)

	* Acircumflex (U+00C2): X=195.5,Y=829.0 (should be at cap-height 831?)

	* Acircumflex (U+00C2): X=429.0,Y=829.0 (should be at cap-height 831?)

	* Aring (U+00C5): X=313.0,Y=829.0 (should be at cap-height 831?)

	* Egrave (U+00C8): X=309.0,Y=829.0 (should be at cap-height 831?)

	* Ecircumflex (U+00CA): X=142.5,Y=829.0 (should be at cap-height 831?) 

	* And 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<549.0,117.0>--<549.0,623.0>>/L<<549.0,623.0>--<396.0,0.0>> = 13.797963717016383

	* four (U+0034): B<<235.0,529.0>-<236.0,576.0>-<239.0,622.0>>/B<<239.0,622.0>-<229.0,590.0>-<210.0,545.5>> = 13.622627637100871

	* fourinferior (U+2084): B<<161.5,233.5>-<162.0,252.0>-<164.0,271.0>>/B<<164.0,271.0>-<160.0,260.0>-<155.0,248.0>> = 13.974100564405422

	* foursuperior (U+2074): B<<161.5,718.5>-<162.0,737.0>-<164.0,756.0>>/B<<164.0,756.0>-<160.0,745.0>-<155.0,733.0>> = 13.974100564405422

	* y (U+0079): B<<261.0,163.5>-<268.0,130.0>-<270.0,108.0>>/B<<270.0,108.0>-<274.0,133.0>-<278.5,156.5>> = 14.284705828557108

	* yacute (U+00FD): B<<261.0,163.5>-<268.0,130.0>-<270.0,108.0>>/B<<270.0,108.0>-<274.0,133.0>-<278.5,156.5>> = 14.284705828557108

	* ycircumflex (U+0177): B<<261.0,163.5>-<268.0,130.0>-<270.0,108.0>>/B<<270.0,108.0>-<274.0,133.0>-<278.5,156.5>> = 14.284705828557108

	* ydieresis (U+00FF): B<<261.0,163.5>-<268.0,130.0>-<270.0,108.0>>/B<<270.0,108.0>-<274.0,133.0>-<278.5,156.5>> = 14.284705828557108 

	* And ygrave (U+1EF3): B<<261.0,163.5>-<268.0,130.0>-<270.0,108.0>>/B<<270.0,108.0>-<274.0,133.0>-<278.5,156.5>> = 14.284705828557108 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<352.0,333.0>--<224.0,334.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraCondensedExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=273.5,Y=1.5 (should be at baseline 0?)

	* J (U+004A): X=253.0,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=89.0,Y=573.0 (should be at x-height 571?)

	* t (U+0074): X=293.5,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=271.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=382.5,Y=1.5 (should be at baseline 0?)

	* questiondown (U+00BF): X=313.0,Y=2.0 (should be at baseline 0?)

	* IJ (U+0132): X=612.0,Y=-2.0 (should be at baseline 0?)

	* Eng (U+014A): X=507.0,Y=2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=293.5,Y=-1.0 (should be at baseline 0?) 

	* And 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<315.0,0.0>--<163.0,615.0>>/L<<163.0,615.0>--<163.0,118.0>> = 13.882694656125755

	* M (U+004D): L<<547.0,119.0>--<547.0,615.0>>/L<<547.0,615.0>--<401.0,0.0>> = 13.354706479230135

	* four (U+0034): B<<227.0,522.5>-<228.0,565.0>-<232.0,612.0>>/B<<232.0,612.0>-<220.0,576.0>-<203.0,534.5>> = 13.570434385161448

	* y (U+0079): B<<271.5,170.5>-<277.0,139.0>-<279.0,118.0>>/B<<279.0,118.0>-<282.0,142.0>-<285.5,163.5>> = 12.565348379907268

	* yacute (U+00FD): B<<271.5,170.5>-<277.0,139.0>-<279.0,118.0>>/B<<279.0,118.0>-<282.0,142.0>-<285.5,163.5>> = 12.565348379907268

	* ycircumflex (U+0177): B<<271.5,170.5>-<277.0,139.0>-<279.0,118.0>>/B<<279.0,118.0>-<282.0,142.0>-<285.5,163.5>> = 12.565348379907268

	* ydieresis (U+00FF): B<<271.5,170.5>-<277.0,139.0>-<279.0,118.0>>/B<<279.0,118.0>-<282.0,142.0>-<285.5,163.5>> = 12.565348379907268 

	* And ygrave (U+1EF3): B<<271.5,170.5>-<277.0,139.0>-<279.0,118.0>>/B<<279.0,118.0>-<282.0,142.0>-<285.5,163.5>> = 12.565348379907268 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<365.0,334.0>--<234.0,335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraCondensedExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=379.5,Y=-0.5 (should be at baseline 0?)

	* a (U+0061): X=197.0,Y=543.0 (should be at x-height 545?)

	* b (U+0062): X=258.0,Y=544.0 (should be at x-height 545?)

	* c (U+0063): X=205.0,Y=543.0 (should be at x-height 545?)

	* d (U+0064): X=202.0,Y=544.0 (should be at x-height 545?)

	* e (U+0065): X=203.0,Y=543.0 (should be at x-height 545?)

	* g (U+0067): X=194.0,Y=543.0 (should be at x-height 545?)

	* h (U+0068): X=251.0,Y=543.0 (should be at x-height 545?)

	* m (U+006D): X=260.0,Y=543.0 (should be at x-height 545?)

	* m (U+006D): X=492.0,Y=543.0 (should be at x-height 545?) 

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* fourinferior (U+2084): B<<173.5,245.5>-<174.0,268.0>-<175.0,288.0>>/B<<175.0,288.0>-<173.0,280.0>-<166.0,264.5>> = 11.173838241814705 

	* And foursuperior (U+2074): B<<173.5,730.5>-<174.0,753.0>-<175.0,773.0>>/B<<175.0,773.0>-<173.0,765.0>-<166.0,749.5>> = 11.173838241814705 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<392.0,359.0>--<390.0,30.0>>

	* E (U+0045): L<<149.0,359.0>--<148.0,30.0>>

	* Eacute (U+00C9): L<<149.0,359.0>--<148.0,30.0>>

	* Ecaron (U+011A): L<<149.0,359.0>--<148.0,30.0>>

	* Ecircumflex (U+00CA): L<<149.0,359.0>--<148.0,30.0>>

	* Edieresis (U+00CB): L<<149.0,359.0>--<148.0,30.0>>

	* Edotaccent (U+0116): L<<149.0,359.0>--<148.0,30.0>>

	* Egrave (U+00C8): L<<149.0,359.0>--<148.0,30.0>>

	* Emacron (U+0112): L<<149.0,359.0>--<148.0,30.0>>

	* Eogonek (U+0118): L<<149.0,359.0>--<148.0,30.0>> 

	* And OE (U+0152): L<<390.0,359.0>--<389.0,30.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraCondensedLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* g (U+0067): X=390.0,Y=548.5 (should be at x-height 549?)

	* g (U+0067): X=102.5,Y=-0.5 (should be at baseline 0?)

	* y (U+0079): X=207.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=272.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=77.0,Y=1.0 (should be at baseline 0?)

	* twosuperior (U+00B2): X=143.0,Y=794.0 (should be at cap-height 795?)

	* twosuperior (U+00B2): X=224.0,Y=795.5 (should be at cap-height 795?)

	* threesuperior (U+00B3): X=65.5,Y=797.0 (should be at cap-height 795?)

	* threesuperior (U+00B3): X=227.5,Y=796.5 (should be at cap-height 795?)

	* yacute (U+00FD): X=207.0,Y=-2.0 (should be at baseline 0?) 

	* And 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* fourinferior (U+2084): B<<170.5,243.0>-<171.0,265.0>-<173.0,285.0>>/B<<173.0,285.0>-<170.0,276.0>-<163.0,261.5>> = 12.724355685422335 

	* And foursuperior (U+2074): B<<170.5,728.0>-<171.0,750.0>-<173.0,770.0>>/B<<173.0,770.0>-<170.0,761.0>-<163.0,746.5>> = 12.724355685422335 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<419.0,355.0>--<418.0,38.0>>

	* E (U+0045): L<<169.0,355.0>--<168.0,38.0>>

	* Eacute (U+00C9): L<<169.0,355.0>--<168.0,38.0>>

	* Ecaron (U+011A): L<<169.0,355.0>--<168.0,38.0>>

	* Ecircumflex (U+00CA): L<<169.0,355.0>--<168.0,38.0>>

	* Edieresis (U+00CB): L<<169.0,355.0>--<168.0,38.0>>

	* Edotaccent (U+0116): L<<169.0,355.0>--<168.0,38.0>>

	* Egrave (U+00C8): L<<169.0,355.0>--<168.0,38.0>>

	* Emacron (U+0112): L<<169.0,355.0>--<168.0,38.0>>

	* Eogonek (U+0118): L<<169.0,355.0>--<168.0,38.0>>

	* OE (U+0152): L<<422.0,355.0>--<421.0,38.0>> 

	* And euro (U+20AC): L<<154.0,306.0>--<291.0,305.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-ExtraCondensedMedium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* fourinferior (U+2084): B<<165.5,238.5>-<166.0,259.0>-<168.0,278.0>>/B<<168.0,278.0>-<164.0,267.0>-<158.0,254.0>> = 13.974100564405422 

	* And foursuperior (U+2074): B<<165.5,723.5>-<166.0,744.0>-<168.0,763.0>>/B<<168.0,763.0>-<164.0,752.0>-<158.0,739.0>> = 13.974100564405422 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<331.0,332.0>--<207.0,333.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-ExtraCondensedSemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=439.0,Y=2.0 (should be at baseline 0?)

	* g (U+0067): X=260.0,Y=1.0 (should be at baseline 0?)

	* g (U+0067): X=169.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=93.0,Y=562.0 (should be at x-height 561?)

	* sterling (U+00A3): X=271.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=373.0,Y=1.5 (should be at baseline 0?)

	* threesuperior (U+00B3): X=154.0,Y=824.0 (should be at cap-height 825?)

	* Atilde (U+00C3): X=258.5,Y=824.5 (should be at cap-height 825?)

	* Ntilde (U+00D1): X=283.5,Y=824.5 (should be at cap-height 825?)

	* Otilde (U+00D5): X=271.5,Y=824.5 (should be at cap-height 825?) 

	* And 25 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<551.0,115.0>--<551.0,630.0>>/L<<551.0,630.0>--<391.0,0.0>> = 14.250032697803595 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-ExtraCondensedThin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraCondensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=369.5,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=248.0,Y=544.0 (should be at x-height 542?)

	* d (U+0064): X=202.0,Y=544.0 (should be at x-height 542?)

	* d (U+0064): X=324.0,Y=544.0 (should be at x-height 542?)

	* f (U+0066): X=221.0,Y=772.0 (should be at cap-height 771?)

	* g (U+0067): X=301.0,Y=541.0 (should be at x-height 542?)

	* g (U+0067): X=365.5,Y=543.5 (should be at x-height 542?)

	* r (U+0072): X=243.0,Y=544.0 (should be at x-height 542?)

	* s (U+0073): X=164.0,Y=541.0 (should be at x-height 542?)

	* sterling (U+00A3): X=272.5,Y=-2.0 (should be at baseline 0?) 

	* And 31 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* fourinferior (U+2084): B<<175.0,247.0>-<176.0,270.0>-<177.0,290.0>>/B<<177.0,290.0>-<175.0,283.0>-<167.5,266.5>> = 13.08299067481109 

	* And foursuperior (U+2074): B<<175.0,732.0>-<176.0,755.0>-<177.0,775.0>>/B<<177.0,775.0>-<175.0,768.0>-<167.5,751.5>> = 13.08299067481109 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<375.0,362.0>--<373.0,25.0>>

	* E (U+0045): L<<137.0,362.0>--<135.0,25.0>>

	* Eacute (U+00C9): L<<137.0,362.0>--<135.0,25.0>>

	* Ecaron (U+011A): L<<137.0,362.0>--<135.0,25.0>>

	* Ecircumflex (U+00CA): L<<137.0,362.0>--<135.0,25.0>>

	* Edieresis (U+00CB): L<<137.0,362.0>--<135.0,25.0>>

	* Edotaccent (U+0116): L<<137.0,362.0>--<135.0,25.0>>

	* Egrave (U+00C8): L<<137.0,362.0>--<135.0,25.0>>

	* Emacron (U+0112): L<<137.0,362.0>--<135.0,25.0>>

	* Eogonek (U+0118): L<<137.0,362.0>--<135.0,25.0>> 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifTamil-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* a (U+0061): X=248.0,Y=543.0 (should be at x-height 545?)

	* b (U+0062): X=327.0,Y=544.0 (should be at x-height 545?)

	* c (U+0063): X=265.0,Y=543.0 (should be at x-height 545?)

	* d (U+0064): X=257.0,Y=544.0 (should be at x-height 545?)

	* e (U+0065): X=261.0,Y=543.0 (should be at x-height 545?)

	* g (U+0067): X=251.0,Y=543.0 (should be at x-height 545?)

	* g (U+0067): X=487.5,Y=545.5 (should be at x-height 545?)

	* h (U+0068): X=322.0,Y=543.0 (should be at x-height 545?)

	* m (U+006D): X=330.0,Y=543.0 (should be at x-height 545?) 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSerifTamil-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=342.5,Y=1.5 (should be at baseline 0?)

	* nine (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* g (U+0067): X=498.0,Y=548.0 (should be at x-height 549?)

	* t (U+0074): X=89.0,Y=551.0 (should be at x-height 549?)

	* t (U+0074): X=297.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=269.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=354.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=79.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=460.5,Y=1.0 (should be at baseline 0?)

	* aring (U+00E5): X=267.0,Y=814.0 (should be at cap-height 812?) 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* question (U+003F): L<<200.0,201.0>--<199.0,346.0>> 

	* And questiondown (U+00BF): L<<203.0,215.0>--<204.0,333.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=337.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=271.0,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=316.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=213.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=216.0,Y=555.0 (should be at x-height 556?)

	* q (U+0071): X=408.5,Y=-2.0 (should be at baseline 0?)

	* t (U+0074): X=103.0,Y=554.0 (should be at x-height 556?)

	* y (U+0079): X=259.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=78.0,Y=2.0 (should be at baseline 0?) 

	* And 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* fourinferior (U+2084): B<<198.5,221.5>-<200.0,240.0>-<202.0,258.0>>/B<<202.0,258.0>-<199.0,250.0>-<194.5,241.5>> = 14.21585347367354

	* foursuperior (U+2074): B<<198.5,706.5>-<200.0,725.0>-<202.0,743.0>>/B<<202.0,743.0>-<199.0,735.0>-<194.5,726.5>> = 14.21585347367354

	* nga-tamil (U+0B99): B<<639.0,86.0>-<607.0,63.0>-<572.0,56.0>>/L<<572.0,56.0>--<835.0,56.0>> = 11.309932474020195 

	* And three-tamil (U+0BE9): B<<636.0,86.0>-<604.0,63.0>-<569.0,56.0>>/L<<569.0,56.0>--<893.0,56.0>> = 11.309932474020195 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<408.0,339.0>--<251.0,340.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSerifTamil-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?) 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* nga-tamil (U+0B99): B<<630.5,86.0>-<598.0,62.0>-<560.0,54.0>>/L<<560.0,54.0>--<832.0,54.0>> = 11.888658039627968 

	* And three-tamil (U+0BE9): B<<630.5,86.0>-<598.0,62.0>-<560.0,54.0>>/L<<560.0,54.0>--<884.0,54.0>> = 11.888658039627968 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=119.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=340.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=470.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=254.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=343.0,Y=-2.0 (should be at baseline 0?)

	* Aring (U+00C5): X=285.0,Y=851.5 (should be at cap-height 850?)

	* Aring (U+00C5): X=455.0,Y=851.5 (should be at cap-height 850?)

	* yacute (U+00FD): X=254.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=343.0,Y=-2.0 (should be at baseline 0?) 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* nga-tamil (U+0B99): B<<649.5,86.5>-<618.0,65.0>-<586.0,58.0>>/L<<586.0,58.0>--<838.0,58.0>> = 12.33908727832618 

	* And three-tamil (U+0BE9): B<<643.5,86.5>-<612.0,65.0>-<580.0,58.0>>/L<<580.0,58.0>--<905.0,58.0>> = 12.33908727832618 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<104.0,119.0>--<103.0,648.0>> 

	* And h (U+0068): L<<233.0,313.0>--<234.0,115.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-SemiCondensed.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=105.5,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=312.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=128.5,Y=1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=120.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=481.5,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=149.0,Y=2.0 (should be at baseline 0?)

	* y (U+0079): X=241.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=309.0,Y=-1.0 (should be at baseline 0?)

	* section (U+00A7): X=90.0,Y=2.0 (should be at baseline 0?)

	* twosuperior (U+00B2): X=174.0,Y=825.0 (should be at cap-height 824?) 

	* And 33 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[18] NotoSerifTamil-SemiCondensedBlack.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=309.0,Y=-1.0 (should be at baseline 0?)

	* J (U+004A): X=299.0,Y=1.0 (should be at baseline 0?)

	* Q (U+0051): X=298.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=494.0,Y=2.0 (should be at baseline 0?)

	* t (U+0074): X=345.0,Y=1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=308.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=438.5,Y=2.0 (should be at baseline 0?)

	* Acircumflex (U+00C2): X=376.0,Y=862.0 (should be at cap-height 864?)

	* Atilde (U+00C3): X=190.0,Y=864.5 (should be at cap-height 864?)

	* Ecircumflex (U+00CA): X=299.0,Y=862.0 (should be at cap-height 864?) 

	* And 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ca-tamil (U+0B9A): L<<233.0,345.0>--<234.0,345.0>> -> L<<234.0,345.0>--<357.0,345.0>>

	* four-tamil (U+0BEA): L<<233.0,345.0>--<234.0,345.0>> -> L<<234.0,345.0>--<357.0,345.0>>

	* nine-tamil (U+0BEF): L<<233.0,345.0>--<234.0,345.0>> -> L<<234.0,345.0>--<357.0,345.0>>

	* onethousand-tamil (U+0BF2): L<<245.0,345.0>--<248.0,345.0>> -> L<<248.0,345.0>--<369.0,345.0>>

	* six-tamil (U+0BEC): L<<233.0,345.0>--<234.0,345.0>> -> L<<234.0,345.0>--<357.0,345.0>> 

	* And ta-tamil (U+0BA4): L<<233.0,345.0>--<237.0,345.0>> -> L<<237.0,345.0>--<356.0,345.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<315.5,183.0>-<321.0,155.0>-<322.0,137.0>>/B<<322.0,137.0>-<325.0,159.0>-<328.5,176.0>> = 10.944996138289511

	* yacute (U+00FD): B<<315.5,183.0>-<321.0,155.0>-<322.0,137.0>>/B<<322.0,137.0>-<325.0,159.0>-<328.5,176.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<315.5,183.0>-<321.0,155.0>-<322.0,137.0>>/B<<322.0,137.0>-<325.0,159.0>-<328.5,176.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<315.5,183.0>-<321.0,155.0>-<322.0,137.0>>/B<<322.0,137.0>-<325.0,159.0>-<328.5,176.0>> = 10.944996138289511 

	* And ygrave (U+1EF3): B<<315.5,183.0>-<321.0,155.0>-<322.0,137.0>>/B<<322.0,137.0>-<325.0,159.0>-<328.5,176.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<425.0,335.0>--<276.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] NotoSerifTamil-SemiCondensedBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
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
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME entry for Win "SemiCondensed Bold" must be "Bold". Please note, since the font style is RIBBI, this record can be safely deleted. [code: bad-win-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=457.0,Y=-1.0 (should be at baseline 0?)

	* a (U+0061): X=246.5,Y=-1.0 (should be at baseline 0?)

	* j (U+006A): X=94.0,Y=-1.0 (should be at baseline 0?)

	* t (U+0074): X=112.0,Y=562.0 (should be at x-height 564?)

	* t (U+0074): X=312.0,Y=-1.5 (should be at baseline 0?)

	* y (U+0079): X=325.0,Y=2.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=183.5,Y=853.0 (should be at cap-height 851?)

	* Aring (U+00C5): X=276.0,Y=850.0 (should be at cap-height 851?)

	* Aring (U+00C5): X=434.5,Y=850.0 (should be at cap-height 851?)

	* Ntilde (U+00D1): X=208.5,Y=853.0 (should be at cap-height 851?) 

	* And 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asabove-tamil (U+0BF8): L<<1587.0,61.0>--<1587.0,61.0>> -> L<<1587.0,61.0>--<1596.0,61.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eogonek (U+0119): B<<244.5,-58.5>-<269.0,-26.0>-<303.0,-9.0>>/B<<303.0,-9.0>-<299.0,-10.0>-<294.5,-10.0>> = 12.528807709151492

	* k (U+006B): B<<234.0,288.5>-<233.0,269.0>-<232.0,267.0>>/L<<232.0,267.0>--<348.0,409.0>> = 12.680383491819796

	* kcommaaccent (U+0137): B<<234.0,288.5>-<233.0,269.0>-<232.0,267.0>>/L<<232.0,267.0>--<348.0,409.0>> = 12.680383491819796

	* y (U+0079): B<<299.0,162.5>-<305.0,135.0>-<307.0,114.0>>/B<<307.0,114.0>-<310.0,137.0>-<317.0,162.0>> = 12.871740002177972

	* yacute (U+00FD): B<<299.0,162.5>-<305.0,135.0>-<307.0,114.0>>/B<<307.0,114.0>-<310.0,137.0>-<317.0,162.0>> = 12.871740002177972

	* ycircumflex (U+0177): B<<299.0,162.5>-<305.0,135.0>-<307.0,114.0>>/B<<307.0,114.0>-<310.0,137.0>-<317.0,162.0>> = 12.871740002177972

	* ydieresis (U+00FF): B<<299.0,162.5>-<305.0,135.0>-<307.0,114.0>>/B<<307.0,114.0>-<310.0,137.0>-<317.0,162.0>> = 12.871740002177972 

	* And ygrave (U+1EF3): B<<299.0,162.5>-<305.0,135.0>-<307.0,114.0>>/B<<307.0,114.0>-<310.0,137.0>-<317.0,162.0>> = 12.871740002177972 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<237.0,310.0>--<238.0,117.0>> 

	* And sterling (U+00A3): L<<400.0,341.0>--<253.0,342.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] NotoSerifTamil-SemiCondensedExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=310.5,Y=0.5 (should be at baseline 0?)

	* J (U+004A): X=113.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=283.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=478.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=249.5,Y=2.0 (should be at baseline 0?)

	* t (U+0074): X=330.0,Y=-0.5 (should be at baseline 0?)

	* Atilde (U+00C3): X=187.5,Y=859.5 (should be at cap-height 858?)

	* Ntilde (U+00D1): X=207.5,Y=859.5 (should be at cap-height 858?)

	* Otilde (U+00D5): X=204.5,Y=859.5 (should be at cap-height 858?)

	* Abreve (U+0102): X=229.0,Y=858.5 (should be at cap-height 858?) 

	* And 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asabove-tamil (U+0BF8): L<<1615.0,67.0>--<1615.0,67.0>> -> L<<1615.0,67.0>--<1622.0,67.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<362.0,227.5>-<369.0,194.0>-<372.0,169.0>>/B<<372.0,169.0>-<375.0,192.0>-<383.0,222.0>> = 14.274181383803418

	* y (U+0079): B<<308.0,173.5>-<314.0,146.0>-<315.0,126.0>>/B<<315.0,126.0>-<318.0,149.0>-<323.0,169.5>> = 10.293813197284212

	* yacute (U+00FD): B<<308.0,173.5>-<314.0,146.0>-<315.0,126.0>>/B<<315.0,126.0>-<318.0,149.0>-<323.0,169.5>> = 10.293813197284212

	* ycircumflex (U+0177): B<<308.0,173.5>-<314.0,146.0>-<315.0,126.0>>/B<<315.0,126.0>-<318.0,149.0>-<323.0,169.5>> = 10.293813197284212

	* ydieresis (U+00FF): B<<308.0,173.5>-<314.0,146.0>-<315.0,126.0>>/B<<315.0,126.0>-<318.0,149.0>-<323.0,169.5>> = 10.293813197284212 

	* And ygrave (U+1EF3): B<<308.0,173.5>-<314.0,146.0>-<315.0,126.0>>/B<<315.0,126.0>-<318.0,149.0>-<323.0,169.5>> = 10.293813197284212 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<256.0,306.0>--<257.0,121.0>>

	* sterling (U+00A3): L<<414.0,338.0>--<265.0,339.0>> 

	* And uu-tamil (U+0B8A): L<<1227.0,452.0>--<1226.0,573.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-SemiCondensedExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=92.5,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=105.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=447.0,Y=-1.0 (should be at baseline 0?)

	* a (U+0061): X=230.0,Y=543.0 (should be at x-height 545?)

	* b (U+0062): X=302.0,Y=544.0 (should be at x-height 545?)

	* c (U+0063): X=243.0,Y=543.0 (should be at x-height 545?)

	* d (U+0064): X=237.0,Y=544.0 (should be at x-height 545?)

	* e (U+0065): X=240.0,Y=543.0 (should be at x-height 545?)

	* g (U+0067): X=230.0,Y=543.0 (should be at x-height 545?)

	* g (U+0067): X=446.0,Y=545.5 (should be at x-height 545?) 

	* And 45 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<461.0,359.0>--<460.0,30.0>>

	* E (U+0045): L<<175.0,359.0>--<174.0,30.0>>

	* Eacute (U+00C9): L<<175.0,359.0>--<174.0,30.0>>

	* Ecaron (U+011A): L<<175.0,359.0>--<174.0,30.0>>

	* Ecircumflex (U+00CA): L<<175.0,359.0>--<174.0,30.0>>

	* Edieresis (U+00CB): L<<175.0,359.0>--<174.0,30.0>>

	* Edotaccent (U+0116): L<<175.0,359.0>--<174.0,30.0>>

	* Egrave (U+00C8): L<<175.0,359.0>--<174.0,30.0>>

	* Emacron (U+0112): L<<175.0,359.0>--<174.0,30.0>>

	* Eogonek (U+0118): L<<175.0,359.0>--<174.0,30.0>> 

	* And euro (U+20AC): L<<318.0,272.0>--<153.0,273.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-SemiCondensedLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* g (U+0067): X=458.0,Y=548.5 (should be at x-height 549?)

	* g (U+0067): X=119.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=278.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=247.0,Y=-1.0 (should be at baseline 0?)

	* y (U+0079): X=297.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=324.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=71.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=424.0,Y=0.5 (should be at baseline 0?)

	* yacute (U+00FD): X=247.0,Y=-1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=297.0,Y=-1.0 (should be at baseline 0?) 

	* And 26 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one-tamil (U+0BE7): L<<219.0,309.0>--<224.0,309.0>> -> L<<224.0,309.0>--<377.0,309.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* E (U+0045): L<<194.0,355.0>--<193.0,38.0>>

	* Eacute (U+00C9): L<<194.0,355.0>--<193.0,38.0>>

	* Ecaron (U+011A): L<<194.0,355.0>--<193.0,38.0>>

	* Ecircumflex (U+00CA): L<<194.0,355.0>--<193.0,38.0>>

	* Edieresis (U+00CB): L<<194.0,355.0>--<193.0,38.0>>

	* Edotaccent (U+0116): L<<194.0,355.0>--<193.0,38.0>>

	* Egrave (U+00C8): L<<194.0,355.0>--<193.0,38.0>>

	* Emacron (U+0112): L<<194.0,355.0>--<193.0,38.0>> 

	* And Eogonek (U+0118): L<<194.0,355.0>--<193.0,38.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-SemiCondensedMedium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=108.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=314.5,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=121.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=490.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=250.5,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=293.0,Y=2.0 (should be at baseline 0?)

	* g (U+0067): X=196.0,Y=2.0 (should be at baseline 0?)

	* q (U+0071): X=376.5,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=97.0,Y=556.0 (should be at x-height 557?)

	* y (U+0079): X=238.0,Y=-1.0 (should be at baseline 0?) 

	* And 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* nga-tamil (U+0B99): B<<579.0,87.0>-<550.0,64.0>-<518.0,56.0>>/L<<518.0,56.0>--<753.0,56.0>> = 14.036243467926484 

	* And three-tamil (U+0BE9): B<<577.5,87.0>-<548.0,64.0>-<516.0,56.0>>/L<<516.0,56.0>--<809.0,56.0>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-SemiCondensedSemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=111.0,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=318.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=121.5,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=439.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=248.0,Y=0.5 (should be at baseline 0?)

	* t (U+0074): X=104.0,Y=559.0 (should be at x-height 560?)

	* y (U+0079): X=319.0,Y=1.0 (should be at baseline 0?)

	* agrave (U+00E0): X=248.0,Y=0.5 (should be at baseline 0?)

	* aacute (U+00E1): X=248.0,Y=0.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=248.0,Y=0.5 (should be at baseline 0?) 

	* And 31 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<219.0,314.0>--<220.0,114.0>> 

	* And sterling (U+00A3): L<<389.0,339.0>--<244.0,340.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTamil-SemiCondensedThin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil SemiCondensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=438.0,Y=-1.5 (should be at baseline 0?)

	* b (U+0062): X=294.0,Y=544.0 (should be at x-height 542?)

	* d (U+0064): X=236.0,Y=543.0 (should be at x-height 542?)

	* d (U+0064): X=392.0,Y=543.0 (should be at x-height 542?)

	* g (U+0067): X=438.5,Y=544.0 (should be at x-height 542?)

	* r (U+0072): X=283.0,Y=544.0 (should be at x-height 542?)

	* y (U+0079): X=282.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=329.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=424.5,Y=-1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=186.0,Y=782.0 (should be at cap-height 784?) 

	* And 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<326.0,470.0>-<366.0,450.0>-<389.0,410.0>>/B<<389.0,410.0>-<366.0,485.0>-<338.5,540.0>> = 12.849870866504741 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<444.0,362.0>--<443.0,25.0>>

	* OE (U+0152): L<<436.0,362.0>--<435.0,25.0>>

	* exclam (U+0021): L<<139.0,714.0>--<136.0,167.0>> 

	* And exclamdown (U+00A1): L<<112.0,-177.0>--<115.0,370.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTamil-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: a-tamil, aa-tamil, aaMatra-tamil, ai-tamil, aiMatra-tamil, anudatta-deva, anusvara-tamil, anusvara-tamil.alt, asabove-tamil, au-tamil and 142 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Tamil Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: softhyphen	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aaMatra-tamil (U+0BBE), aulengthmark-tamil (U+0BD7), candrabinduhalant-deva (U+A8F3), iMatra-tamil (U+0BBF), iMatra-tamil.alt01 (unencoded), iMatra-tamil.alt02 (unencoded), uMatra-tamil (U+0BC1), uMatra-tamil.alt01 (unencoded), uMatra-tamil.alt02 (unencoded), uuMatra-tamil (U+0BC2), uuMatra-tamil.alt01 (unencoded) and uuMatra-tamil.alt02 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=99.5,Y=-1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=111.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=407.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=477.5,Y=-1.5 (should be at baseline 0?)

	* b (U+0062): X=320.0,Y=544.0 (should be at x-height 542?)

	* d (U+0064): X=256.0,Y=543.0 (should be at x-height 542?)

	* d (U+0064): X=432.0,Y=543.0 (should be at x-height 542?)

	* g (U+0067): X=481.0,Y=544.0 (should be at x-height 542?)

	* r (U+0072): X=306.0,Y=544.0 (should be at x-height 542?)

	* sterling (U+00A3): X=362.5,Y=-1.5 (should be at baseline 0?) 

	* And 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476 

	* And sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<149.0,714.0>--<146.0,167.0>> 

	* And exclamdown (U+00A1): L<<123.0,-177.0>--<126.0,370.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSerifTamil[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTamil/googlefonts/slim-variable-ttf/NotoSerifTamil[wght].ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Black.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Bold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Condensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-CondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-ExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Light.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Medium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Regular.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensed.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBlack.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedExtraLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedLight.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedMedium.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedSemiBold.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-SemiCondensedThin.ttf', 'fonts/NotoSerifTamil/googlefonts/ttf/NotoSerifTamil-Thin.ttf', 'fonts/NotoSerifTamil/googlefonts/variable-ttf/NotoSerifTamil[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1178, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 635, but got 492 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 334. [code: invalid-default-instance-subfamily-nameid:334]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0BBE (U+0BBE), uni0BBF (U+0BBF), uni0BBF.alt01 (unencoded), uni0BBF.alt02 (unencoded), uni0BC1 (U+0BC1), uni0BC1.alt01 (unencoded), uni0BC1.alt02 (unencoded), uni0BC2 (U+0BC2), uni0BC2.alt01 (unencoded), uni0BC2.alt02 (unencoded), uni0BD7 (U+0BD7) and uniA8F3 (U+A8F3) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0BBE, U+0BBF, U+0BC1, U+0BC2, U+0BD7 and U+A8F3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=328.0,Y=0.5 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* s (U+0073): X=123.0,Y=2.0 (should be at baseline 0?) 

	* And 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 276 | 356 | 4552 | 280 | 2911 | 0 |
| 0% | 3% | 4% | 54% | 3% | 35% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
