## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[19] Jaro-24ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1200. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Jaro 24pt | Jaro 24pt |
| Subfamily Name | Regular | Regular |
| Full Name | Jaro 24pt Regular | Jaro 24pt Regular |
| Poscript Name | Jaro-24ptRegular | Jaro24pt-Regular |
| Typographic Family Name | Jaro | N/A |
| Typographic Subfamily Name | 24pt Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Phonetics_APA is almost fulfilled. Missing codepoints:

	- 0x03C6 (GREEK SMALL LETTER PHI)


	- 0x1D05 (LATIN LETTER SMALL CAPITAL D)


	- 0x1D7B (LATIN SMALL CAPITAL LETTER I WITH STROKE)


	- 0x1D4D (MODIFIER LETTER SMALL G)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- dotlessi_ogonek

	- uni03010304.001

	- uni03060303.case.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: arrowleft	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowright	Contours detected: 2	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 426 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 398:
less, lessequal

Width = 406:
greater

Width = 438:
multiply

Width = 702:
approxequal

Width = 376:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* K (U+004B): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* K (U+004B): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* K (U+004B): L<<611.0,666.0>--<534.0,484.0>> -> L<<534.0,484.0>--<494.0,410.0>>

	* Kmacronbelow (U+1E34): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* Kmacronbelow (U+1E34): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* Kmacronbelow (U+1E34): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* Kmacronbelow (U+1E34): L<<611.0,666.0>--<534.0,484.0>> -> L<<534.0,484.0>--<494.0,410.0>>

	* R (U+0052): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* Racute (U+0154): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* Rcaron (U+0158): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* Rcaron (U+0159): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* Rmacronbelow (U+1E5E): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* ae (U+00E6): L<<312.0,655.0>--<420.0,622.0>> -> L<<420.0,622.0>--<537.0,578.0>>

	* ae (U+00E6): L<<612.0,5.0>--<504.0,38.0>> -> L<<504.0,38.0>--<386.0,82.0>>

	* e (U+0065): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* eacute (U+00E9): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* ecaron (U+011B): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* ecircumflex (U+00EA): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* edieresis (U+00EB): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* edotaccent (U+0117): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* egrave (U+00E8): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* emacron (U+0113): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* eogonek (U+0119): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* kgreenlandic (U+0138): L<<611.0,526.0>--<534.0,398.0>> -> L<<534.0,398.0>--<494.0,340.0>>

	* lozenge (U+25CA): L<<168.0,362.0>--<176.0,349.0>> -> L<<176.0,349.0>--<301.0,167.0>>

	* lozenge (U+25CA): L<<301.0,167.0>--<309.0,178.0>> -> L<<309.0,178.0>--<434.0,362.0>>

	* lozenge (U+25CA): L<<302.0,549.0>--<292.0,537.0>> -> L<<292.0,537.0>--<168.0,362.0>>

	* lozenge (U+25CA): L<<434.0,362.0>--<425.0,374.0>> -> L<<425.0,374.0>--<302.0,549.0>>

	* oe (U+0153): L<<605.0,5.0>--<497.0,38.0>> -> L<<497.0,38.0>--<379.0,82.0>>

	* uni0136 (U+0136): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* uni0136 (U+0136): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* uni0136 (U+0136): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* uni0136 (U+0136): L<<611.0,666.0>--<534.0,484.0>> -> L<<534.0,484.0>--<494.0,410.0>>

	* uni0156 (U+0156): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni0198 (U+0198): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* uni0198 (U+0198): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* uni0198 (U+0198): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* uni01DD (U+01DD): L<<295.0,655.0>--<402.0,622.0>> -> L<<402.0,622.0>--<520.0,578.0>>

	* uni01E3 (U+01E3): L<<312.0,655.0>--<420.0,622.0>> -> L<<420.0,622.0>--<537.0,578.0>>

	* uni01E3 (U+01E3): L<<612.0,5.0>--<504.0,38.0>> -> L<<504.0,38.0>--<386.0,82.0>>

	* uni01E8 (U+01E8): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* uni01E8 (U+01E8): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* uni01E8 (U+01E8): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* uni01E8 (U+01E8): L<<611.0,666.0>--<534.0,484.0>> -> L<<534.0,484.0>--<494.0,410.0>>

	* uni0205 (U+0205): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni0207 (U+0207): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni0210 (U+0210): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni0212 (U+0212): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni0229 (U+0229): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni0247 (U+0247): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<146.0,54.0>>

	* uni024C (U+024C): L<<634.0,452.0>--<563.0,383.0>> -> L<<563.0,383.0>--<519.0,345.0>>

	* uni0256 (U+0256): L<<546.0,785.0>--<546.0,15.0>> -> L<<546.0,15.0>--<546.0,13.0>>

	* uni0259 (U+0259): L<<295.0,655.0>--<402.0,622.0>> -> L<<402.0,622.0>--<520.0,578.0>>

	* uni029D (U+029D): L<<222.0,-209.0>--<118.0,-209.0>> -> L<<118.0,-209.0>--<114.0,-209.0>>

	* uni029D (U+029D): L<<70.0,-161.0>--<113.0,-161.0>> -> L<<113.0,-161.0>--<173.0,-160.0>>

	* uni1E15 (U+1E15): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1E17 (U+1E17): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1E19 (U+1E19): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1E1B (U+1E1B): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1E1D (U+1E1D): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1E30 (U+1E30): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* uni1E30 (U+1E30): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* uni1E30 (U+1E30): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* uni1E30 (U+1E30): L<<611.0,666.0>--<534.0,484.0>> -> L<<534.0,484.0>--<494.0,410.0>>

	* uni1E32 (U+1E32): L<<329.0,490.0>--<369.0,639.0>> -> L<<369.0,639.0>--<401.0,792.0>>

	* uni1E32 (U+1E32): L<<412.0,9.0>--<370.0,177.0>> -> L<<370.0,177.0>--<336.0,285.0>>

	* uni1E32 (U+1E32): L<<494.0,410.0>--<535.0,336.0>> -> L<<535.0,336.0>--<626.0,135.0>>

	* uni1E32 (U+1E32): L<<611.0,666.0>--<534.0,484.0>> -> L<<534.0,484.0>--<494.0,410.0>>

	* uni1E58 (U+1E58): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni1E5A (U+1E5A): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni1E5C (U+1E5C): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni1EB9 (U+1EB9): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EBB (U+1EBB): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EBD (U+1EBD): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EBF (U+1EBF): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EC1 (U+1EC1): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EC3 (U+1EC3): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EC5 (U+1EC5): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni1EC7 (U+1EC7): L<<298.0,5.0>--<190.0,38.0>> -> L<<190.0,38.0>--<72.0,82.0>>

	* uni20A8 (U+20A8): L<<576.0,452.0>--<505.0,383.0>> -> L<<505.0,383.0>--<461.0,345.0>>

	* uni2C64 (U+2C64): L<<574.0,456.0>--<503.0,388.0>> -> L<<503.0,388.0>--<461.0,350.0>>

	* uniA740 (U+A740): L<<400.0,490.0>--<440.0,639.0>> -> L<<440.0,639.0>--<472.0,792.0>>

	* uniA740 (U+A740): L<<483.0,9.0>--<441.0,177.0>> -> L<<441.0,177.0>--<407.0,285.0>>

	* uniA740 (U+A740): L<<565.0,410.0>--<606.0,336.0>> -> L<<606.0,336.0>--<697.0,135.0>>

	* uniA740 (U+A740): L<<682.0,666.0>--<605.0,484.0>> -> L<<605.0,484.0>--<565.0,410.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* comma (U+002C): L<<40.0,57.0>--<41.0,207.0>>

	* five (U+0035): L<<25.0,327.0>--<26.0,785.0>>

	* fiveeighths (U+215D): L<<25.0,616.0>--<26.0,918.0>>

	* onehalf (U+00BD): L<<367.0,10.0>--<366.0,165.0>>

	* percent (U+0025): L<<343.0,367.0>--<542.0,368.0>>

	* percent (U+0025): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<343.0,367.0>--<542.0,368.0>>

	* perthousand (U+2030): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<612.0,367.0>--<811.0,368.0>>

	* pi (U+03C0): L<<651.0,496.0>--<652.0,155.0>>

	* quotedblbase (U+201E): L<<302.0,57.0>--<303.0,207.0>>

	* quotedblbase (U+201E): L<<42.0,57.0>--<43.0,207.0>>

	* quotedblleft (U+201C): L<<259.0,720.0>--<258.0,570.0>>

	* quotedblleft (U+201C): L<<519.0,720.0>--<518.0,570.0>>

	* quotedblright (U+201D): L<<302.0,717.0>--<303.0,867.0>>

	* quotedblright (U+201D): L<<42.0,717.0>--<43.0,867.0>>

	* quoteleft (U+2018): L<<261.0,720.0>--<260.0,570.0>>

	* quoteright (U+2019): L<<42.0,717.0>--<43.0,867.0>>

	* quotesinglbase (U+201A): L<<42.0,57.0>--<43.0,207.0>>

	* semicolon (U+003B): L<<40.0,57.0>--<41.0,207.0>>

	* two (U+0032): L<<39.0,15.0>--<38.0,249.0>>

	* uni00B2 (U+00B2): L<<39.0,15.0>--<38.0,249.0>>

	* uni0241 (U+0241): L<<57.0,15.0>--<56.0,300.0>>

	* uni0242 (U+0242): L<<57.0,14.0>--<56.0,182.0>>

	* uni0294 (U+0294): L<<57.0,15.0>--<56.0,300.0>>

	* uni0295 (U+0295): L<<423.0,300.0>--<422.0,15.0>>

	* uni02BB (U+02BB): L<<244.0,1011.0>--<243.0,861.0>>

	* uni02BC (U+02BC): L<<25.0,877.0>--<26.0,1022.0>>

	* uni02C0 (U+02C0): L<<26.0,320.0>--<25.0,497.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,867.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,867.0>>

	* uni0E3F (U+0E3F): L<<437.0,647.0>--<436.0,800.0>>

	* uni2154 (U+2154): L<<26.0,410.0>--<25.0,565.0>>

	* uni2C64 (U+2C64): L<<270.0,274.0>--<269.0,-139.0>>

	* zero (U+0030): L<<106.0,799.0>--<542.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] Jaro-6ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1200. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Jaro 6pt | Jaro 6pt |
| Subfamily Name | Regular | Regular |
| Full Name | Jaro 6pt Regular | Jaro 6pt Regular |
| Poscript Name | Jaro-6ptRegular | Jaro6pt-Regular |
| Typographic Family Name | Jaro | N/A |
| Typographic Subfamily Name | 6pt Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Phonetics_APA is almost fulfilled. Missing codepoints:

	- 0x03C6 (GREEK SMALL LETTER PHI)


	- 0x1D05 (LATIN LETTER SMALL CAPITAL D)


	- 0x1D7B (LATIN SMALL CAPITAL LETTER I WITH STROKE)


	- 0x1D4D (MODIFIER LETTER SMALL G)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- dotlessi_ogonek

	- uni03010304.001

	- uni03060303.case.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: arrowleft	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowright	Contours detected: 2	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 426 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 406:
greater, less, lessequal

Width = 424:
multiply

Width = 707:
approxequal

Width = 376:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* K (U+004B): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* K (U+004B): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* K (U+004B): L<<624.0,686.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* Kmacronbelow (U+1E34): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* Kmacronbelow (U+1E34): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* Kmacronbelow (U+1E34): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* Kmacronbelow (U+1E34): L<<624.0,686.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* R (U+0052): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* Racute (U+0154): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* Rcaron (U+0158): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* Rcaron (U+0159): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* Rmacronbelow (U+1E5E): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* ae (U+00E6): L<<321.0,655.0>--<428.0,629.0>> -> L<<428.0,629.0>--<550.0,588.0>>

	* ae (U+00E6): L<<641.0,5.0>--<534.0,31.0>> -> L<<534.0,31.0>--<412.0,72.0>>

	* e (U+0065): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* eacute (U+00E9): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* ecaron (U+011B): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* ecircumflex (U+00EA): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* edieresis (U+00EB): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* edotaccent (U+0117): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* egrave (U+00E8): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* emacron (U+0113): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* eogonek (U+0119): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* kgreenlandic (U+0138): L<<624.0,546.0>--<551.0,417.0>> -> L<<551.0,417.0>--<500.0,344.0>>

	* lozenge (U+25CA): L<<168.0,362.0>--<176.0,349.0>> -> L<<176.0,349.0>--<301.0,167.0>>

	* lozenge (U+25CA): L<<301.0,167.0>--<309.0,178.0>> -> L<<309.0,178.0>--<434.0,362.0>>

	* lozenge (U+25CA): L<<302.0,549.0>--<292.0,537.0>> -> L<<292.0,537.0>--<168.0,362.0>>

	* lozenge (U+25CA): L<<434.0,362.0>--<425.0,374.0>> -> L<<425.0,374.0>--<302.0,549.0>>

	* oe (U+0153): L<<631.0,5.0>--<524.0,31.0>> -> L<<524.0,31.0>--<402.0,72.0>>

	* uni0136 (U+0136): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* uni0136 (U+0136): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* uni0136 (U+0136): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* uni0136 (U+0136): L<<624.0,686.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* uni0156 (U+0156): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni0198 (U+0198): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* uni0198 (U+0198): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* uni0198 (U+0198): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* uni0198 (U+0198): L<<601.0,630.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* uni01B3 (U+01B3): L<<425.0,850.0>--<567.0,850.0>> -> L<<567.0,850.0>--<568.0,850.0>>

	* uni01B3 (U+01B3): L<<567.0,850.0>--<568.0,850.0>> -> L<<568.0,850.0>--<568.0,850.0>>

	* uni01B3 (U+01B3): L<<568.0,850.0>--<568.0,850.0>> -> L<<568.0,850.0>--<737.0,850.0>>

	* uni01DD (U+01DD): L<<297.0,655.0>--<404.0,629.0>> -> L<<404.0,629.0>--<526.0,588.0>>

	* uni01E3 (U+01E3): L<<321.0,655.0>--<428.0,629.0>> -> L<<428.0,629.0>--<550.0,588.0>>

	* uni01E3 (U+01E3): L<<641.0,5.0>--<534.0,31.0>> -> L<<534.0,31.0>--<412.0,72.0>>

	* uni01E8 (U+01E8): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* uni01E8 (U+01E8): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* uni01E8 (U+01E8): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* uni01E8 (U+01E8): L<<624.0,686.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* uni0205 (U+0205): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni0207 (U+0207): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni0210 (U+0210): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni0212 (U+0212): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni0229 (U+0229): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni0247 (U+0247): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<155.0,49.0>>

	* uni024C (U+024C): L<<638.0,453.0>--<572.0,389.0>> -> L<<572.0,389.0>--<516.0,341.0>>

	* uni0256 (U+0256): L<<558.0,785.0>--<558.0,15.0>> -> L<<558.0,15.0>--<558.0,13.0>>

	* uni0259 (U+0259): L<<297.0,655.0>--<404.0,629.0>> -> L<<404.0,629.0>--<526.0,588.0>>

	* uni029D (U+029D): L<<222.0,-194.0>--<118.0,-194.0>> -> L<<118.0,-194.0>--<114.0,-194.0>>

	* uni029D (U+029D): L<<70.0,-146.0>--<113.0,-146.0>> -> L<<113.0,-146.0>--<181.0,-145.0>>

	* uni1E15 (U+1E15): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1E17 (U+1E17): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1E19 (U+1E19): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1E1B (U+1E1B): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1E1D (U+1E1D): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1E30 (U+1E30): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* uni1E30 (U+1E30): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* uni1E30 (U+1E30): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* uni1E30 (U+1E30): L<<624.0,686.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* uni1E32 (U+1E32): L<<346.0,467.0>--<386.0,616.0>> -> L<<386.0,616.0>--<422.0,792.0>>

	* uni1E32 (U+1E32): L<<433.0,9.0>--<389.0,199.0>> -> L<<389.0,199.0>--<356.0,308.0>>

	* uni1E32 (U+1E32): L<<500.0,414.0>--<552.0,319.0>> -> L<<552.0,319.0>--<640.0,119.0>>

	* uni1E32 (U+1E32): L<<624.0,686.0>--<551.0,510.0>> -> L<<551.0,510.0>--<500.0,414.0>>

	* uni1E58 (U+1E58): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni1E5A (U+1E5A): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni1E5C (U+1E5C): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni1EB9 (U+1EB9): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EBB (U+1EBB): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EBD (U+1EBD): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EBF (U+1EBF): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EC1 (U+1EC1): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EC3 (U+1EC3): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EC5 (U+1EC5): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni1EC7 (U+1EC7): L<<315.0,5.0>--<208.0,31.0>> -> L<<208.0,31.0>--<86.0,72.0>>

	* uni20A8 (U+20A8): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni2C64 (U+2C64): L<<578.0,453.0>--<512.0,389.0>> -> L<<512.0,389.0>--<456.0,341.0>>

	* uni2C72 (U+2C72): L<<800.0,850.0>--<925.0,850.0>> -> L<<925.0,850.0>--<926.0,850.0>>

	* uni2C72 (U+2C72): L<<925.0,850.0>--<926.0,850.0>> -> L<<926.0,850.0>--<926.0,850.0>>

	* uni2C72 (U+2C72): L<<926.0,850.0>--<926.0,850.0>> -> L<<926.0,850.0>--<1095.0,850.0>>

	* uniA740 (U+A740): L<<413.0,467.0>--<453.0,616.0>> -> L<<453.0,616.0>--<489.0,792.0>>

	* uniA740 (U+A740): L<<500.0,9.0>--<456.0,199.0>> -> L<<456.0,199.0>--<423.0,308.0>>

	* uniA740 (U+A740): L<<567.0,414.0>--<619.0,319.0>> -> L<<619.0,319.0>--<707.0,119.0>>

	* uniA740 (U+A740): L<<691.0,686.0>--<618.0,510.0>> -> L<<618.0,510.0>--<567.0,414.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0246 (U+0246): L<<272.0,330.0>--<272.0,168.0>>/L<<272.0,168.0>--<306.0,330.0>> = 11.853004167744011 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* comma (U+002C): L<<48.0,57.0>--<49.0,209.0>>

	* five (U+0035): L<<25.0,335.0>--<26.0,785.0>>

	* fiveeighths (U+215D): L<<25.0,621.0>--<26.0,918.0>>

	* onehalf (U+00BD): L<<364.0,10.0>--<363.0,139.0>>

	* percent (U+0025): L<<343.0,367.0>--<542.0,368.0>>

	* percent (U+0025): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<343.0,367.0>--<542.0,368.0>>

	* perthousand (U+2030): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<612.0,367.0>--<811.0,368.0>>

	* pi (U+03C0): L<<672.0,510.0>--<673.0,141.0>>

	* quotedblbase (U+201E): L<<308.0,57.0>--<309.0,209.0>>

	* quotedblbase (U+201E): L<<48.0,57.0>--<49.0,209.0>>

	* quotedblleft (U+201C): L<<270.0,720.0>--<269.0,568.0>>

	* quotedblleft (U+201C): L<<530.0,720.0>--<529.0,568.0>>

	* quotedblright (U+201D): L<<308.0,717.0>--<309.0,869.0>>

	* quotedblright (U+201D): L<<48.0,717.0>--<49.0,869.0>>

	* quoteleft (U+2018): L<<270.0,720.0>--<269.0,568.0>>

	* quoteright (U+2019): L<<48.0,717.0>--<49.0,869.0>>

	* quotesinglbase (U+201A): L<<48.0,57.0>--<49.0,209.0>>

	* semicolon (U+003B): L<<48.0,57.0>--<49.0,209.0>>

	* two (U+0032): L<<44.0,15.0>--<43.0,210.0>>

	* uni00B2 (U+00B2): L<<44.0,15.0>--<43.0,210.0>>

	* uni0241 (U+0241): L<<69.0,15.0>--<68.0,284.0>>

	* uni0242 (U+0242): L<<69.0,15.0>--<68.0,174.0>>

	* uni0294 (U+0294): L<<69.0,15.0>--<68.0,284.0>>

	* uni0295 (U+0295): L<<419.0,284.0>--<418.0,15.0>>

	* uni02BB (U+02BB): L<<247.0,1011.0>--<246.0,859.0>>

	* uni02BC (U+02BC): L<<25.0,877.0>--<26.0,1022.0>>

	* uni02C0 (U+02C0): L<<26.0,320.0>--<25.0,487.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,869.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,869.0>>

	* uni0E3F (U+0E3F): L<<440.0,665.0>--<439.0,800.0>>

	* uni2154 (U+2154): L<<26.0,410.0>--<25.0,539.0>>

	* zero (U+0030): L<<131.0,799.0>--<543.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] Jaro-72ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1200. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Jaro 72pt | Jaro 72pt |
| Subfamily Name | Regular | Regular |
| Full Name | Jaro 72pt Regular | Jaro 72pt Regular |
| Poscript Name | Jaro-72ptRegular | Jaro72pt-Regular |
| Typographic Family Name | Jaro | N/A |
| Typographic Subfamily Name | 72pt Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Phonetics_APA is almost fulfilled. Missing codepoints:

	- 0x03C6 (GREEK SMALL LETTER PHI)


	- 0x1D05 (LATIN LETTER SMALL CAPITAL D)


	- 0x1D7B (LATIN SMALL CAPITAL LETTER I WITH STROKE)


	- 0x1D4D (MODIFIER LETTER SMALL G)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- dotlessi_ogonek

	- uni03010304.001

	- uni03060303.case.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: arrowleft	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowright	Contours detected: 2	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 426 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 377:
greaterequal, less, lessequal

Width = 406:
greater

Width = 474:
multiply

Width = 687:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<766.0,1.0>--<334.0,0.0>>

	* AEacute (U+01FC): L<<766.0,1.0>--<334.0,0.0>>

	* OE (U+0152): L<<771.0,1.0>--<161.0,0.0>>

	* comma (U+002C): L<<18.0,57.0>--<19.0,202.0>>

	* five (U+0035): L<<25.0,305.0>--<26.0,785.0>>

	* fiveeighths (U+215D): L<<25.0,601.0>--<26.0,918.0>>

	* onehalf (U+00BD): L<<376.0,10.0>--<375.0,234.0>>

	* percent (U+0025): L<<343.0,367.0>--<542.0,368.0>>

	* percent (U+0025): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<343.0,367.0>--<542.0,368.0>>

	* perthousand (U+2030): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<612.0,367.0>--<811.0,368.0>>

	* pi (U+03C0): L<<595.0,457.0>--<596.0,191.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<285.0,57.0>--<286.0,202.0>>

	* quotedblleft (U+201C): L<<230.0,720.0>--<229.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<285.0,717.0>--<286.0,862.0>>

	* quoteleft (U+2018): L<<237.0,720.0>--<236.0,575.0>>

	* quoteright (U+2019): L<<25.0,717.0>--<26.0,862.0>>

	* quotesinglbase (U+201A): L<<25.0,57.0>--<26.0,202.0>>

	* semicolon (U+003B): L<<18.0,57.0>--<19.0,202.0>>

	* two (U+0032): L<<26.0,15.0>--<25.0,354.0>>

	* uni00B2 (U+00B2): L<<26.0,15.0>--<25.0,354.0>>

	* uni018B (U+018B): L<<34.0,799.0>--<531.0,801.0>>

	* uni01E2 (U+01E2): L<<766.0,1.0>--<334.0,0.0>>

	* uni0241 (U+0241): L<<26.0,15.0>--<25.0,344.0>>

	* uni0242 (U+0242): L<<26.0,13.0>--<25.0,205.0>>

	* uni0294 (U+0294): L<<26.0,15.0>--<25.0,344.0>>

	* uni0295 (U+0295): L<<434.0,344.0>--<433.0,15.0>>

	* uni02BB (U+02BB): L<<237.0,1011.0>--<236.0,866.0>>

	* uni02BC (U+02BC): L<<25.0,877.0>--<26.0,1022.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,862.0>>

	* uni0E3F (U+0E3F): L<<430.0,598.0>--<429.0,800.0>>

	* uni2154 (U+2154): L<<26.0,410.0>--<25.0,634.0>>

	* uni2C64 (U+2C64): L<<264.0,223.0>--<261.0,-146.0>>

	* uni2C72 (U+2C72): L<<25.0,171.0>--<26.0,785.0>>

	* uni2C72 (U+2C72): L<<856.0,679.0>--<857.0,171.0>>

	* zero (U+0030): L<<40.0,799.0>--<540.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Jaro-12ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1200. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Jaro 12pt | Jaro 12pt |
| Subfamily Name | Regular | Regular |
| Full Name | Jaro 12pt Regular | Jaro 12pt Regular |
| Poscript Name | Jaro-12ptRegular | Jaro12pt-Regular |
| Typographic Family Name | Jaro | N/A |
| Typographic Subfamily Name | 12pt Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Phonetics_APA is almost fulfilled. Missing codepoints:

	- 0x03C6 (GREEK SMALL LETTER PHI)


	- 0x1D05 (LATIN LETTER SMALL CAPITAL D)


	- 0x1D7B (LATIN SMALL CAPITAL LETTER I WITH STROKE)


	- 0x1D4D (MODIFIER LETTER SMALL G)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- dotlessi_ogonek

	- uni03010304.001

	- uni03060303.case.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: arrowleft	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowright	Contours detected: 2	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 426 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 403:
less, lessequal

Width = 406:
greater

Width = 429:
multiply

Width = 705:
approxequal

Width = 376:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* K (U+004B): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* K (U+004B): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* K (U+004B): L<<620.0,679.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* Kmacronbelow (U+1E34): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* Kmacronbelow (U+1E34): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* Kmacronbelow (U+1E34): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* Kmacronbelow (U+1E34): L<<620.0,679.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* R (U+0052): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* Racute (U+0154): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* Rcaron (U+0158): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* Rcaron (U+0159): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* Rmacronbelow (U+1E5E): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* ae (U+00E6): L<<318.0,655.0>--<425.0,627.0>> -> L<<425.0,627.0>--<546.0,585.0>>

	* ae (U+00E6): L<<631.0,5.0>--<524.0,33.0>> -> L<<524.0,33.0>--<403.0,75.0>>

	* e (U+0065): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* eacute (U+00E9): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* ecaron (U+011B): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* ecircumflex (U+00EA): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* edieresis (U+00EB): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* edotaccent (U+0117): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* egrave (U+00E8): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* emacron (U+0113): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* eogonek (U+0119): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* kgreenlandic (U+0138): L<<620.0,539.0>--<545.0,411.0>> -> L<<545.0,411.0>--<498.0,343.0>>

	* lozenge (U+25CA): L<<168.0,362.0>--<176.0,349.0>> -> L<<176.0,349.0>--<301.0,167.0>>

	* lozenge (U+25CA): L<<301.0,167.0>--<309.0,178.0>> -> L<<309.0,178.0>--<434.0,362.0>>

	* lozenge (U+25CA): L<<302.0,549.0>--<292.0,537.0>> -> L<<292.0,537.0>--<168.0,362.0>>

	* lozenge (U+25CA): L<<434.0,362.0>--<425.0,374.0>> -> L<<425.0,374.0>--<302.0,549.0>>

	* oe (U+0153): L<<622.0,5.0>--<515.0,33.0>> -> L<<515.0,33.0>--<394.0,75.0>>

	* uni0136 (U+0136): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* uni0136 (U+0136): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* uni0136 (U+0136): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* uni0136 (U+0136): L<<620.0,679.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* uni0156 (U+0156): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni0198 (U+0198): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* uni0198 (U+0198): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* uni0198 (U+0198): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* uni0198 (U+0198): L<<596.0,624.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* uni01DD (U+01DD): L<<296.0,655.0>--<403.0,627.0>> -> L<<403.0,627.0>--<524.0,585.0>>

	* uni01E3 (U+01E3): L<<318.0,655.0>--<425.0,627.0>> -> L<<425.0,627.0>--<546.0,585.0>>

	* uni01E3 (U+01E3): L<<631.0,5.0>--<524.0,33.0>> -> L<<524.0,33.0>--<403.0,75.0>>

	* uni01E8 (U+01E8): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* uni01E8 (U+01E8): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* uni01E8 (U+01E8): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* uni01E8 (U+01E8): L<<620.0,679.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* uni0205 (U+0205): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni0207 (U+0207): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni0210 (U+0210): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni0212 (U+0212): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni0229 (U+0229): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni0247 (U+0247): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<152.0,51.0>>

	* uni024C (U+024C): L<<637.0,453.0>--<569.0,387.0>> -> L<<569.0,387.0>--<517.0,342.0>>

	* uni0256 (U+0256): L<<554.0,785.0>--<554.0,15.0>> -> L<<554.0,15.0>--<554.0,13.0>>

	* uni0259 (U+0259): L<<296.0,655.0>--<403.0,627.0>> -> L<<403.0,627.0>--<524.0,585.0>>

	* uni029D (U+029D): L<<222.0,-199.0>--<118.0,-199.0>> -> L<<118.0,-199.0>--<114.0,-199.0>>

	* uni029D (U+029D): L<<70.0,-151.0>--<113.0,-151.0>> -> L<<113.0,-151.0>--<178.0,-150.0>>

	* uni1E15 (U+1E15): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1E17 (U+1E17): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1E19 (U+1E19): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1E1B (U+1E1B): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1E1D (U+1E1D): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1E30 (U+1E30): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* uni1E30 (U+1E30): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* uni1E30 (U+1E30): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* uni1E30 (U+1E30): L<<620.0,679.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* uni1E32 (U+1E32): L<<340.0,475.0>--<380.0,624.0>> -> L<<380.0,624.0>--<415.0,792.0>>

	* uni1E32 (U+1E32): L<<426.0,9.0>--<383.0,192.0>> -> L<<383.0,192.0>--<349.0,300.0>>

	* uni1E32 (U+1E32): L<<498.0,413.0>--<546.0,325.0>> -> L<<546.0,325.0>--<635.0,124.0>>

	* uni1E32 (U+1E32): L<<620.0,679.0>--<545.0,501.0>> -> L<<545.0,501.0>--<498.0,413.0>>

	* uni1E58 (U+1E58): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni1E5A (U+1E5A): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni1E5C (U+1E5C): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni1EB9 (U+1EB9): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EBB (U+1EBB): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EBD (U+1EBD): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EBF (U+1EBF): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EC1 (U+1EC1): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EC3 (U+1EC3): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EC5 (U+1EC5): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni1EC7 (U+1EC7): L<<309.0,5.0>--<202.0,33.0>> -> L<<202.0,33.0>--<81.0,75.0>>

	* uni20A8 (U+20A8): L<<577.0,453.0>--<510.0,387.0>> -> L<<510.0,387.0>--<458.0,342.0>>

	* uni2C64 (U+2C64): L<<577.0,454.0>--<509.0,389.0>> -> L<<509.0,389.0>--<458.0,344.0>>

	* uni2C66 (U+2C66): L<<88.0,750.0>--<250.0,750.0>> -> L<<250.0,750.0>--<252.0,750.0>>

	* uni2C72 (U+2C72): L<<789.0,850.0>--<917.0,850.0>> -> L<<917.0,850.0>--<918.0,850.0>>

	* uni2C72 (U+2C72): L<<917.0,850.0>--<918.0,850.0>> -> L<<918.0,850.0>--<918.0,850.0>>

	* uni2C72 (U+2C72): L<<918.0,850.0>--<918.0,850.0>> -> L<<918.0,850.0>--<1082.0,850.0>>

	* uniA740 (U+A740): L<<408.0,475.0>--<448.0,624.0>> -> L<<448.0,624.0>--<483.0,792.0>>

	* uniA740 (U+A740): L<<494.0,9.0>--<451.0,192.0>> -> L<<451.0,192.0>--<417.0,300.0>>

	* uniA740 (U+A740): L<<566.0,413.0>--<614.0,325.0>> -> L<<614.0,325.0>--<703.0,124.0>>

	* uniA740 (U+A740): L<<688.0,679.0>--<613.0,501.0>> -> L<<613.0,501.0>--<566.0,413.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* comma (U+002C): L<<45.0,57.0>--<46.0,208.0>>

	* five (U+0035): L<<25.0,332.0>--<26.0,785.0>>

	* fiveeighths (U+215D): L<<25.0,619.0>--<26.0,918.0>>

	* onehalf (U+00BD): L<<365.0,10.0>--<364.0,148.0>>

	* percent (U+0025): L<<343.0,367.0>--<542.0,368.0>>

	* percent (U+0025): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<343.0,367.0>--<542.0,368.0>>

	* perthousand (U+2030): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<612.0,367.0>--<811.0,368.0>>

	* pi (U+03C0): L<<665.0,505.0>--<666.0,146.0>>

	* quotedblbase (U+201E): L<<306.0,57.0>--<307.0,208.0>>

	* quotedblbase (U+201E): L<<46.0,57.0>--<47.0,208.0>>

	* quotedblleft (U+201C): L<<266.0,720.0>--<265.0,569.0>>

	* quotedblleft (U+201C): L<<526.0,720.0>--<525.0,569.0>>

	* quotedblright (U+201D): L<<306.0,717.0>--<307.0,868.0>>

	* quotedblright (U+201D): L<<46.0,717.0>--<47.0,868.0>>

	* quoteleft (U+2018): L<<267.0,720.0>--<266.0,569.0>>

	* quoteright (U+2019): L<<46.0,717.0>--<47.0,868.0>>

	* quotesinglbase (U+201A): L<<46.0,57.0>--<47.0,208.0>>

	* semicolon (U+003B): L<<45.0,57.0>--<46.0,208.0>>

	* two (U+0032): L<<42.0,15.0>--<41.0,223.0>>

	* uni00B2 (U+00B2): L<<42.0,15.0>--<41.0,223.0>>

	* uni0241 (U+0241): L<<65.0,15.0>--<64.0,289.0>>

	* uni0242 (U+0242): L<<65.0,15.0>--<64.0,177.0>>

	* uni0294 (U+0294): L<<65.0,15.0>--<64.0,289.0>>

	* uni0295 (U+0295): L<<420.0,289.0>--<419.0,15.0>>

	* uni02BB (U+02BB): L<<246.0,1011.0>--<245.0,860.0>>

	* uni02BC (U+02BC): L<<25.0,877.0>--<26.0,1022.0>>

	* uni02C0 (U+02C0): L<<26.0,320.0>--<25.0,490.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,868.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,868.0>>

	* uni0E3F (U+0E3F): L<<439.0,659.0>--<438.0,800.0>>

	* uni2154 (U+2154): L<<26.0,410.0>--<25.0,548.0>>

	* zero (U+0030): L<<123.0,799.0>--<543.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] Jaro-48ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1200. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Jaro 48pt | Jaro 48pt |
| Subfamily Name | Regular | Regular |
| Full Name | Jaro 48pt Regular | Jaro 48pt Regular |
| Poscript Name | Jaro-48ptRegular | Jaro48pt-Regular |
| Typographic Family Name | Jaro | N/A |
| Typographic Subfamily Name | 48pt Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Phonetics_APA is almost fulfilled. Missing codepoints:

	- 0x03C6 (GREEK SMALL LETTER PHI)


	- 0x1D05 (LATIN LETTER SMALL CAPITAL D)


	- 0x1D7B (LATIN SMALL CAPITAL LETTER I WITH STROKE)


	- 0x1D4D (MODIFIER LETTER SMALL G)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- dotlessi_ogonek

	- uni03010304.001

	- uni03060303.case.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: arrowleft	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowright	Contours detected: 2	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dong	Contours detected: 5	Expected: 3or4

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023C	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4or7

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 4	Expected: 1

	- Glyph name: uni20B1	Contours detected: 6	Expected: 1, 2or4

	- Glyph name: uni20B4	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20B9	Contours detected: 4	Expected: 1

	- Glyph name: uni20BA	Contours detected: 4	Expected: 1

	- Glyph name: uni20BC	Contours detected: 3	Expected: 1

	- Glyph name: uni20BD	Contours detected: 4	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 426 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 388:
less, lessequal

Width = 406:
greater

Width = 456:
multiply

Width = 694:
approxequal

Width = 377:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<791.0,1.0>--<364.0,0.0>>

	* AEacute (U+01FC): L<<791.0,1.0>--<364.0,0.0>>

	* OE (U+0152): L<<798.0,1.0>--<183.0,0.0>>

	* comma (U+002C): L<<29.0,57.0>--<30.0,205.0>>

	* five (U+0035): L<<25.0,316.0>--<26.0,785.0>>

	* fiveeighths (U+215D): L<<25.0,608.0>--<26.0,918.0>>

	* onehalf (U+00BD): L<<372.0,10.0>--<371.0,199.0>>

	* percent (U+0025): L<<343.0,367.0>--<542.0,368.0>>

	* percent (U+0025): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<343.0,367.0>--<542.0,368.0>>

	* perthousand (U+2030): L<<40.0,800.0>--<239.0,801.0>>

	* perthousand (U+2030): L<<612.0,367.0>--<811.0,368.0>>

	* pi (U+03C0): L<<623.0,476.0>--<624.0,173.0>>

	* quotedblbase (U+201E): L<<293.0,57.0>--<294.0,205.0>>

	* quotedblbase (U+201E): L<<33.0,57.0>--<34.0,205.0>>

	* quotedblleft (U+201C): L<<245.0,720.0>--<244.0,572.0>>

	* quotedblleft (U+201C): L<<505.0,720.0>--<504.0,572.0>>

	* quotedblright (U+201D): L<<293.0,717.0>--<294.0,865.0>>

	* quotedblright (U+201D): L<<33.0,717.0>--<34.0,865.0>>

	* quoteleft (U+2018): L<<249.0,720.0>--<248.0,572.0>>

	* quoteright (U+2019): L<<33.0,717.0>--<34.0,865.0>>

	* quotesinglbase (U+201A): L<<33.0,57.0>--<34.0,205.0>>

	* semicolon (U+003B): L<<29.0,57.0>--<30.0,205.0>>

	* two (U+0032): L<<33.0,15.0>--<32.0,302.0>>

	* uni00B2 (U+00B2): L<<33.0,15.0>--<32.0,302.0>>

	* uni018B (U+018B): L<<50.0,799.0>--<550.0,801.0>>

	* uni01E2 (U+01E2): L<<791.0,1.0>--<364.0,0.0>>

	* uni0241 (U+0241): L<<42.0,15.0>--<41.0,322.0>>

	* uni0242 (U+0242): L<<42.0,14.0>--<41.0,194.0>>

	* uni0294 (U+0294): L<<42.0,15.0>--<41.0,322.0>>

	* uni0295 (U+0295): L<<429.0,322.0>--<428.0,15.0>>

	* uni02BB (U+02BB): L<<241.0,1011.0>--<240.0,863.0>>

	* uni02BC (U+02BC): L<<25.0,877.0>--<26.0,1022.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,865.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,865.0>>

	* uni0E3F (U+0E3F): L<<434.0,622.0>--<433.0,800.0>>

	* uni2154 (U+2154): L<<26.0,410.0>--<25.0,599.0>>

	* uni2C64 (U+2C64): L<<267.0,248.0>--<265.0,-142.0>>

	* uni2C72 (U+2C72): L<<42.0,165.0>--<43.0,785.0>>

	* zero (U+0030): L<<73.0,799.0>--<541.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 15 | 20 | 59 | 629 | 26 | 433 | 0 |
| 1% | 2% | 5% | 53% | 2% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
