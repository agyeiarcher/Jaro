## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[18] Jaro-24ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* ⚠ **WARN** The most common width is 710 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 664:
less, lessequal

Width = 677:
greater

Width = 730:
multiply

Width = 1169:
approxequal

Width = 627:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* zero (U+0030): X=177.0,Y=1332.0 (should be at cap-height 1333?)

	* zero (U+0030): X=904.0,Y=1335.0 (should be at cap-height 1333?)

	* colon (U+003A): X=91.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=407.0,Y=1.0 (should be at baseline 0?)

	* k (U+006B): X=644.0,Y=1099.0 (should be at x-height 1100?)

	* k (U+006B): X=911.0,Y=1099.0 (should be at x-height 1100?)

	* exclamdown (U+00A1): X=340.0,Y=1334.0 (should be at cap-height 1333?)

	* exclamdown (U+00A1): X=24.0,Y=1334.0 (should be at cap-height 1333?)

	* sterling (U+00A3): X=375.5,Y=1331.5 (should be at cap-height 1333?)

	* copyright (U+00A9): X=340.0,Y=-2.0 (should be at baseline 0?)

	* copyright (U+00A9): X=827.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=340.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=827.0,Y=-2.0 (should be at baseline 0?)

	* AE (U+00C6): X=1361.0,Y=1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=328.0,Y=1332.0 (should be at cap-height 1333?)

	* ccaron (U+010D): X=396.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=479.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=547.0,Y=1332.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=585.0,Y=1331.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=718.0,Y=1331.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=472.0,Y=1332.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=540.0,Y=1332.0 (should be at cap-height 1333?)

	* OE (U+0152): X=1374.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=334.0,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=472.0,Y=2.0 (should be at baseline 0?)

	* scaron (U+0161): X=308.0,Y=1332.0 (should be at cap-height 1333?)

	* scaron (U+0161): X=376.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=342.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=410.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0188 (U+0188): X=429.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0188 (U+0188): X=785.0,Y=1332.0 (should be at cap-height 1333?)

	* uni018A (U+018A): X=520.0,Y=1332.0 (should be at cap-height 1333?)

	* uni018B (U+018B): X=949.0,Y=1334.0 (should be at cap-height 1333?)

	* uni0190 (U+0190): X=336.0,Y=1331.5 (should be at cap-height 1333?)

	* uni01B2 (U+01B2): X=916.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01B4 (U+01B4): X=716.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01B4 (U+01B4): X=1071.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=575.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=643.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=172.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=240.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=467.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=535.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01E2 (U+01E2): X=1361.0,Y=1.0 (should be at baseline 0?)

	* gcaron (U+01E7): X=479.0,Y=1332.0 (should be at cap-height 1333?)

	* gcaron (U+01E7): X=547.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=389.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=457.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=216.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=284.0,Y=1332.0 (should be at cap-height 1333?)

	* AEacute (U+01FC): X=1361.0,Y=1.0 (should be at baseline 0?)

	* uni0203 (U+0203): X=762.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0203 (U+0203): X=458.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=666.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=362.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=359.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=55.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=654.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=350.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=562.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=258.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=659.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=355.0,Y=1335.0 (should be at cap-height 1333?)

	* uni023A (U+023A): X=113.0,Y=1.0 (should be at baseline 0?)

	* uni0242 (U+0242): X=120.0,Y=-1.0 (should be at baseline 0?)

	* uni0242 (U+0242): X=430.0,Y=-1.0 (should be at baseline 0?)

	* uni0260 (U+0260): X=710.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0260 (U+0260): X=1066.0,Y=1332.0 (should be at cap-height 1333?)

	* uni030C (U+030C): X=217.0,Y=1332.0 (should be at cap-height 1333?)

	* uni030C (U+030C): X=285.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=397.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=93.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0329 (U+0329): X=67.0,Y=2.0 (should be at baseline 0?)

	* uni0329 (U+0329): X=220.0,Y=2.0 (should be at baseline 0?)

	* uni0358 (U+0358): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0358 (U+0358): X=298.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1DCA (U+1DCA): X=103.0,Y=-498.0 (should be at descender -500?)

	* uni1DCA (U+1DCA): X=213.0,Y=-498.0 (should be at descender -500?)

	* uni1E67 (U+1E67): X=308.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1E67 (U+1E67): X=376.0,Y=1332.0 (should be at cap-height 1333?)

	* perthousand (U+2030): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=507.0,Y=1332.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=767.0,Y=1332.0 (should be at cap-height 1333?)

	* uni20AD (U+20AD): X=698.0,Y=1331.0 (should be at cap-height 1333?)

	* emptyset (U+2205): X=795.0,Y=-2.0 (should be at baseline 0?)

	* emptyset (U+2205): X=340.0,Y=-2.0 (should be at baseline 0?)

	* uni2C73 (U+2C73): X=1173.0,Y=1332.0 (should be at cap-height 1333?)

	* uni2C73 (U+2C73): X=1529.0,Y=1332.0 (should be at cap-height 1333?)

	* uniA789 (U+A789): X=91.0,Y=1.0 (should be at baseline 0?)

	* uniA789 (U+A789): X=407.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<1018.0,1109.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* K (U+004B): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* K (U+004B): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* K (U+004B): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* Kmacronbelow (U+1E34): L<<1018.0,1109.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* Kmacronbelow (U+1E34): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* Kmacronbelow (U+1E34): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* Kmacronbelow (U+1E34): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* R (U+0052): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* Racute (U+0154): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* Rcaron (U+0158): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* Rcaron (U+0159): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* Rmacronbelow (U+1E5E): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* ae (U+00E6): L<<1019.0,8.0>--<840.0,64.0>> -> L<<840.0,64.0>--<643.0,136.0>>

	* ae (U+00E6): L<<520.0,1092.0>--<699.0,1036.0>> -> L<<699.0,1036.0>--<896.0,964.0>>

	* e (U+0065): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* eacute (U+00E9): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* ecaron (U+011B): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* ecircumflex (U+00EA): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* edieresis (U+00EB): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* edotaccent (U+0117): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* egrave (U+00E8): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* emacron (U+0113): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* eogonek (U+0119): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* kgreenlandic (U+0138): L<<1018.0,876.0>--<889.0,663.0>> -> L<<889.0,663.0>--<823.0,566.0>>

	* lozenge (U+25CA): L<<280.0,603.0>--<293.0,582.0>> -> L<<293.0,582.0>--<502.0,278.0>>

	* lozenge (U+25CA): L<<502.0,278.0>--<515.0,297.0>> -> L<<515.0,297.0>--<723.0,603.0>>

	* lozenge (U+25CA): L<<503.0,915.0>--<487.0,895.0>> -> L<<487.0,895.0>--<280.0,603.0>>

	* lozenge (U+25CA): L<<723.0,603.0>--<708.0,623.0>> -> L<<708.0,623.0>--<503.0,915.0>>

	* oe (U+0153): L<<1007.0,8.0>--<828.0,64.0>> -> L<<828.0,64.0>--<631.0,136.0>>

	* uni0136 (U+0136): L<<1018.0,1109.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* uni0136 (U+0136): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* uni0136 (U+0136): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* uni0136 (U+0136): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* uni0156 (U+0156): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni0198 (U+0198): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* uni0198 (U+0198): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* uni0198 (U+0198): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* uni0198 (U+0198): L<<979.0,1018.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* uni01AE (U+01AE): L<<283.0,-177.0>--<283.0,22.0>> -> L<<283.0,22.0>--<283.0,25.0>>

	* uni01AE (U+01AE): L<<283.0,22.0>--<283.0,25.0>> -> L<<283.0,25.0>--<283.0,1030.0>>

	* uni01DD (U+01DD): L<<491.0,652.0>--<670.0,596.0>> -> L<<670.0,596.0>--<867.0,524.0>>

	* uni01E3 (U+01E3): L<<1019.0,8.0>--<840.0,64.0>> -> L<<840.0,64.0>--<643.0,136.0>>

	* uni01E3 (U+01E3): L<<520.0,1092.0>--<699.0,1036.0>> -> L<<699.0,1036.0>--<896.0,964.0>>

	* uni01E8 (U+01E8): L<<1018.0,1109.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* uni01E8 (U+01E8): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* uni01E8 (U+01E8): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* uni01E8 (U+01E8): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* uni0205 (U+0205): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni0207 (U+0207): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni0210 (U+0210): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni0212 (U+0212): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni0229 (U+0229): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni0247 (U+0247): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<244.0,91.0>>

	* uni024C (U+024C): L<<1056.0,753.0>--<938.0,638.0>> -> L<<938.0,638.0>--<864.0,574.0>>

	* uni0259 (U+0259): L<<491.0,652.0>--<670.0,596.0>> -> L<<670.0,596.0>--<867.0,524.0>>

	* uni029D (U+029D): L<<117.0,-269.0>--<188.0,-269.0>> -> L<<188.0,-269.0>--<288.0,-267.0>>

	* uni1E15 (U+1E15): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1E17 (U+1E17): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1E19 (U+1E19): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1E1B (U+1E1B): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1E1D (U+1E1D): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1E30 (U+1E30): L<<1018.0,1109.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* uni1E30 (U+1E30): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* uni1E30 (U+1E30): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* uni1E30 (U+1E30): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* uni1E32 (U+1E32): L<<1018.0,1109.0>--<889.0,807.0>> -> L<<889.0,807.0>--<823.0,683.0>>

	* uni1E32 (U+1E32): L<<549.0,816.0>--<614.0,1065.0>> -> L<<614.0,1065.0>--<668.0,1320.0>>

	* uni1E32 (U+1E32): L<<687.0,15.0>--<616.0,296.0>> -> L<<616.0,296.0>--<560.0,475.0>>

	* uni1E32 (U+1E32): L<<823.0,683.0>--<891.0,560.0>> -> L<<891.0,560.0>--<1044.0,225.0>>

	* uni1E58 (U+1E58): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni1E5A (U+1E5A): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni1E5C (U+1E5C): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni1EB9 (U+1EB9): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EBB (U+1EBB): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EBD (U+1EBD): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EBF (U+1EBF): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EC1 (U+1EC1): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EC3 (U+1EC3): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EC5 (U+1EC5): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni1EC7 (U+1EC7): L<<496.0,8.0>--<317.0,64.0>> -> L<<317.0,64.0>--<120.0,136.0>>

	* uni20A8 (U+20A8): L<<959.0,753.0>--<841.0,638.0>> -> L<<841.0,638.0>--<768.0,574.0>>

	* uni2C64 (U+2C64): L<<956.0,760.0>--<839.0,646.0>> -> L<<839.0,646.0>--<768.0,583.0>>

	* uniA740 (U+A740): L<<1137.0,1109.0>--<1008.0,807.0>> -> L<<1008.0,807.0>--<942.0,683.0>>

	* uniA740 (U+A740): L<<668.0,816.0>--<733.0,1065.0>> -> L<<733.0,1065.0>--<787.0,1320.0>>

	* uniA740 (U+A740): L<<806.0,15.0>--<735.0,296.0>> -> L<<735.0,296.0>--<679.0,475.0>>

	* uniA740 (U+A740): L<<942.0,683.0>--<1010.0,560.0>> -> L<<1010.0,560.0>--<1163.0,225.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1361.0,1.0>--<657.0,0.0>>

	* AEacute (U+01FC): L<<1361.0,1.0>--<657.0,0.0>>

	* OE (U+0152): L<<1374.0,1.0>--<342.0,0.0>>

	* comma (U+002C): L<<66.0,95.0>--<68.0,345.0>>

	* five (U+0035): L<<42.0,544.0>--<43.0,1308.0>>

	* fiveeighths (U+215D): L<<42.0,1026.0>--<43.0,1530.0>>

	* numbersign (U+0023): L<<1091.0,922.0>--<1332.0,923.0>>

	* numbersign (U+0023): L<<163.0,920.0>--<419.0,921.0>>

	* numbersign (U+0023): L<<567.0,493.0>--<728.0,494.0>>

	* numbersign (U+0023): L<<674.0,921.0>--<836.0,922.0>>

	* numbersign (U+0023): L<<82.0,492.0>--<312.0,493.0>>

	* numbersign (U+0023): L<<983.0,494.0>--<1248.0,495.0>>

	* onehalf (U+00BD): L<<611.0,17.0>--<610.0,275.0>>

	* percent (U+0025): L<<572.0,612.0>--<903.0,613.0>>

	* percent (U+0025): L<<67.0,1333.0>--<398.0,1335.0>>

	* perthousand (U+2030): L<<1020.0,612.0>--<1352.0,613.0>>

	* perthousand (U+2030): L<<572.0,612.0>--<903.0,613.0>>

	* perthousand (U+2030): L<<67.0,1333.0>--<398.0,1335.0>>

	* pi (U+03C0): L<<1085.0,826.0>--<1087.0,258.0>>

	* quotedblbase (U+201E): L<<502.0,95.0>--<504.0,345.0>>

	* quotedblbase (U+201E): L<<69.0,95.0>--<71.0,345.0>>

	* quotedblleft (U+201C): L<<432.0,1200.0>--<430.0,950.0>>

	* quotedblleft (U+201C): L<<865.0,1200.0>--<863.0,950.0>>

	* quotedblright (U+201D): L<<502.0,1195.0>--<504.0,1445.0>>

	* quotedblright (U+201D): L<<69.0,1195.0>--<71.0,1445.0>>

	* quoteleft (U+2018): L<<435.0,1200.0>--<433.0,950.0>>

	* quoteright (U+2019): L<<69.0,1195.0>--<71.0,1445.0>>

	* quotesinglbase (U+201A): L<<69.0,95.0>--<71.0,345.0>>

	* semicolon (U+003B): L<<66.0,95.0>--<68.0,345.0>>

	* two (U+0032): L<<65.0,25.0>--<64.0,415.0>>

	* uni00B2 (U+00B2): L<<65.0,25.0>--<64.0,415.0>>

	* uni0123 (U+0123): L<<637.0,1337.0>--<636.0,1168.0>>

	* uni018B (U+018B): L<<109.0,1333.0>--<949.0,1334.0>>

	* uni01E2 (U+01E2): L<<1361.0,1.0>--<657.0,0.0>>

	* uni0241 (U+0241): L<<95.0,25.0>--<94.0,500.0>>

	* uni0242 (U+0242): L<<95.0,24.0>--<94.0,304.0>>

	* uni0294 (U+0294): L<<95.0,25.0>--<94.0,500.0>>

	* uni0295 (U+0295): L<<706.0,500.0>--<704.0,25.0>>

	* uni02BB (U+02BB): L<<407.0,1685.0>--<405.0,1435.0>>

	* uni02BC (U+02BC): L<<42.0,1462.0>--<43.0,1703.0>>

	* uni02C0 (U+02C0): L<<43.0,533.0>--<42.0,829.0>>

	* uni02EE (U+02EE): L<<42.0,1195.0>--<44.0,1445.0>>

	* uni02EE (U+02EE): L<<475.0,1195.0>--<477.0,1445.0>>

	* uni0312 (U+0312): L<<308.0,1337.0>--<307.0,1168.0>>

	* uni0313 (U+0313): L<<42.0,1360.0>--<43.0,1528.0>>

	* uni0315 (U+0315): L<<42.0,1360.0>--<43.0,1528.0>>

	* uni0E3F (U+0E3F): L<<729.0,1078.0>--<727.0,1333.0>>

	* uni2154 (U+2154): L<<43.0,684.0>--<42.0,942.0>>

	* uni2C64 (U+2C64): L<<449.0,456.0>--<448.0,-231.0>>

	* zero (U+0030): L<<177.0,1332.0>--<904.0,1335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Jaro-6ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* ⚠ **WARN** The most common width is 710 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 677:
less, greater, lessequal

Width = 707:
multiply

Width = 1178:
approxequal

Width = 627:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* zero (U+0030): X=218.0,Y=1332.0 (should be at cap-height 1333?)

	* zero (U+0030): X=905.0,Y=1335.0 (should be at cap-height 1333?)

	* colon (U+003A): X=105.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=425.0,Y=1.0 (should be at baseline 0?)

	* k (U+006B): X=675.0,Y=1098.0 (should be at x-height 1100?)

	* k (U+006B): X=928.0,Y=1098.0 (should be at x-height 1100?)

	* exclamdown (U+00A1): X=331.0,Y=1334.0 (should be at cap-height 1333?)

	* exclamdown (U+00A1): X=11.0,Y=1334.0 (should be at cap-height 1333?)

	* sterling (U+00A3): X=375.5,Y=1332.0 (should be at cap-height 1333?)

	* copyright (U+00A9): X=340.0,Y=-2.0 (should be at baseline 0?)

	* copyright (U+00A9): X=827.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=340.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=827.0,Y=-2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=345.0,Y=1332.0 (should be at cap-height 1333?)

	* ccaron (U+010D): X=413.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=503.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=571.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0123 (U+0123): X=661.0,Y=1332.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=585.0,Y=1331.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=718.0,Y=1331.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=493.0,Y=1332.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=561.0,Y=1332.0 (should be at cap-height 1333?)

	* scaron (U+0161): X=310.0,Y=1332.0 (should be at cap-height 1333?)

	* scaron (U+0161): X=378.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=347.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=415.0,Y=1332.0 (should be at cap-height 1333?)

	* uni018A (U+018A): X=530.0,Y=1331.0 (should be at cap-height 1333?)

	* uni01AD (U+01AD): X=127.0,Y=1335.0 (should be at cap-height 1333?)

	* uni01B2 (U+01B2): X=943.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=595.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=663.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=165.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=233.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=487.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=555.0,Y=1332.0 (should be at cap-height 1333?)

	* gcaron (U+01E7): X=503.0,Y=1332.0 (should be at cap-height 1333?)

	* gcaron (U+01E7): X=571.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=408.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=476.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=223.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=291.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0203 (U+0203): X=782.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0203 (U+0203): X=478.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=690.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=386.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=352.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=48.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=674.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=370.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=602.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=298.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=680.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=376.0,Y=1335.0 (should be at cap-height 1333?)

	* rtail (U+027D): X=448.0,Y=2.0 (should be at baseline 0?)

	* ogonek (U+02DB): X=138.0,Y=-2.0 (should be at baseline 0?)

	* uni030C (U+030C): X=217.0,Y=1332.0 (should be at cap-height 1333?)

	* uni030C (U+030C): X=285.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=397.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=93.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0312 (U+0312): X=308.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0328 (U+0328): X=120.0,Y=-2.0 (should be at baseline 0?)

	* uni0329 (U+0329): X=67.0,Y=2.0 (should be at baseline 0?)

	* uni0329 (U+0329): X=220.0,Y=2.0 (should be at baseline 0?)

	* uni0358 (U+0358): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0358 (U+0358): X=298.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1DCA (U+1DCA): X=103.0,Y=-498.0 (should be at descender -500?)

	* uni1DCA (U+1DCA): X=213.0,Y=-498.0 (should be at descender -500?)

	* uni1E67 (U+1E67): X=310.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1E67 (U+1E67): X=378.0,Y=1332.0 (should be at cap-height 1333?)

	* perthousand (U+2030): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=507.0,Y=1332.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=758.0,Y=1332.0 (should be at cap-height 1333?)

	* uni20AD (U+20AD): X=721.0,Y=1331.0 (should be at cap-height 1333?)

	* emptyset (U+2205): X=795.0,Y=-2.0 (should be at baseline 0?)

	* emptyset (U+2205): X=340.0,Y=-2.0 (should be at baseline 0?)

	* uniA789 (U+A789): X=105.0,Y=1.0 (should be at baseline 0?)

	* uniA789 (U+A789): X=425.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<1040.0,1143.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* K (U+004B): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* K (U+004B): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* K (U+004B): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* Kmacronbelow (U+1E34): L<<1040.0,1143.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* Kmacronbelow (U+1E34): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* Kmacronbelow (U+1E34): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* Kmacronbelow (U+1E34): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* R (U+0052): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* Racute (U+0154): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* Rcaron (U+0158): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* Rcaron (U+0159): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* Rmacronbelow (U+1E5E): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* ae (U+00E6): L<<1068.0,8.0>--<890.0,52.0>> -> L<<890.0,52.0>--<686.0,120.0>>

	* ae (U+00E6): L<<535.0,1092.0>--<713.0,1048.0>> -> L<<713.0,1048.0>--<917.0,980.0>>

	* e (U+0065): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* eacute (U+00E9): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* ecaron (U+011B): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* ecircumflex (U+00EA): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* edieresis (U+00EB): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* edotaccent (U+0117): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* egrave (U+00E8): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* emacron (U+0113): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* eogonek (U+0119): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* kgreenlandic (U+0138): L<<1040.0,910.0>--<918.0,695.0>> -> L<<918.0,695.0>--<833.0,573.0>>

	* lozenge (U+25CA): L<<280.0,603.0>--<293.0,582.0>> -> L<<293.0,582.0>--<502.0,278.0>>

	* lozenge (U+25CA): L<<502.0,278.0>--<515.0,297.0>> -> L<<515.0,297.0>--<723.0,603.0>>

	* lozenge (U+25CA): L<<503.0,915.0>--<487.0,895.0>> -> L<<487.0,895.0>--<280.0,603.0>>

	* lozenge (U+25CA): L<<723.0,603.0>--<708.0,623.0>> -> L<<708.0,623.0>--<503.0,915.0>>

	* oe (U+0153): L<<1052.0,8.0>--<874.0,52.0>> -> L<<874.0,52.0>--<670.0,120.0>>

	* uni0136 (U+0136): L<<1040.0,1143.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* uni0136 (U+0136): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* uni0136 (U+0136): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* uni0136 (U+0136): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* uni0156 (U+0156): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni0198 (U+0198): L<<1001.0,1050.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* uni0198 (U+0198): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* uni0198 (U+0198): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* uni0198 (U+0198): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* uni01B3 (U+01B3): L<<708.0,1417.0>--<945.0,1417.0>> -> L<<945.0,1417.0>--<946.0,1417.0>>

	* uni01B3 (U+01B3): L<<945.0,1417.0>--<946.0,1417.0>> -> L<<946.0,1417.0>--<947.0,1417.0>>

	* uni01B3 (U+01B3): L<<946.0,1417.0>--<947.0,1417.0>> -> L<<947.0,1417.0>--<1228.0,1417.0>>

	* uni01DD (U+01DD): L<<495.0,652.0>--<673.0,608.0>> -> L<<673.0,608.0>--<877.0,540.0>>

	* uni01E3 (U+01E3): L<<1068.0,8.0>--<890.0,52.0>> -> L<<890.0,52.0>--<686.0,120.0>>

	* uni01E3 (U+01E3): L<<535.0,1092.0>--<713.0,1048.0>> -> L<<713.0,1048.0>--<917.0,980.0>>

	* uni01E8 (U+01E8): L<<1040.0,1143.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* uni01E8 (U+01E8): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* uni01E8 (U+01E8): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* uni01E8 (U+01E8): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* uni0205 (U+0205): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni0207 (U+0207): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni0210 (U+0210): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni0212 (U+0212): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni0229 (U+0229): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni0247 (U+0247): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<258.0,82.0>>

	* uni024C (U+024C): L<<1063.0,755.0>--<953.0,648.0>> -> L<<953.0,648.0>--<860.0,568.0>>

	* uni0259 (U+0259): L<<495.0,652.0>--<673.0,608.0>> -> L<<673.0,608.0>--<877.0,540.0>>

	* uni029D (U+029D): L<<117.0,-243.0>--<188.0,-243.0>> -> L<<188.0,-243.0>--<302.0,-242.0>>

	* uni1E15 (U+1E15): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1E17 (U+1E17): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1E19 (U+1E19): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1E1B (U+1E1B): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1E1D (U+1E1D): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1E30 (U+1E30): L<<1040.0,1143.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* uni1E30 (U+1E30): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* uni1E30 (U+1E30): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* uni1E30 (U+1E30): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* uni1E32 (U+1E32): L<<1040.0,1143.0>--<918.0,850.0>> -> L<<918.0,850.0>--<833.0,690.0>>

	* uni1E32 (U+1E32): L<<577.0,778.0>--<643.0,1027.0>> -> L<<643.0,1027.0>--<703.0,1320.0>>

	* uni1E32 (U+1E32): L<<722.0,15.0>--<648.0,332.0>> -> L<<648.0,332.0>--<593.0,513.0>>

	* uni1E32 (U+1E32): L<<833.0,690.0>--<920.0,532.0>> -> L<<920.0,532.0>--<1067.0,198.0>>

	* uni1E58 (U+1E58): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni1E5A (U+1E5A): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni1E5C (U+1E5C): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni1EB9 (U+1EB9): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EBB (U+1EBB): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EBD (U+1EBD): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EBF (U+1EBF): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EC1 (U+1EC1): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EC3 (U+1EC3): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EC5 (U+1EC5): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni1EC7 (U+1EC7): L<<525.0,8.0>--<347.0,52.0>> -> L<<347.0,52.0>--<143.0,120.0>>

	* uni20A8 (U+20A8): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni2C64 (U+2C64): L<<963.0,755.0>--<853.0,648.0>> -> L<<853.0,648.0>--<760.0,568.0>>

	* uni2C72 (U+2C72): L<<1333.0,1417.0>--<1542.0,1417.0>> -> L<<1542.0,1417.0>--<1543.0,1417.0>>

	* uni2C72 (U+2C72): L<<1542.0,1417.0>--<1543.0,1417.0>> -> L<<1543.0,1417.0>--<1543.0,1417.0>>

	* uni2C72 (U+2C72): L<<1543.0,1417.0>--<1543.0,1417.0>> -> L<<1543.0,1417.0>--<1825.0,1417.0>>

	* uniA740 (U+A740): L<<1152.0,1143.0>--<1030.0,850.0>> -> L<<1030.0,850.0>--<945.0,690.0>>

	* uniA740 (U+A740): L<<689.0,778.0>--<755.0,1027.0>> -> L<<755.0,1027.0>--<815.0,1320.0>>

	* uniA740 (U+A740): L<<834.0,15.0>--<760.0,332.0>> -> L<<760.0,332.0>--<705.0,513.0>>

	* uniA740 (U+A740): L<<945.0,690.0>--<1032.0,532.0>> -> L<<1032.0,532.0>--<1179.0,198.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0246 (U+0246): L<<453.0,550.0>--<453.0,278.0>>/L<<453.0,278.0>--<510.0,550.0>> = 11.83556708047782 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* comma (U+002C): L<<80.0,95.0>--<82.0,348.0>>

	* five (U+0035): L<<42.0,558.0>--<43.0,1308.0>>

	* fiveeighths (U+215D): L<<42.0,1035.0>--<43.0,1530.0>>

	* numbersign (U+0023): L<<1091.0,922.0>--<1332.0,923.0>>

	* numbersign (U+0023): L<<163.0,920.0>--<424.0,921.0>>

	* numbersign (U+0023): L<<567.0,493.0>--<733.0,494.0>>

	* numbersign (U+0023): L<<674.0,921.0>--<841.0,922.0>>

	* numbersign (U+0023): L<<82.0,492.0>--<317.0,493.0>>

	* numbersign (U+0023): L<<983.0,494.0>--<1248.0,495.0>>

	* onehalf (U+00BD): L<<606.0,17.0>--<605.0,232.0>>

	* percent (U+0025): L<<572.0,612.0>--<903.0,613.0>>

	* percent (U+0025): L<<67.0,1333.0>--<398.0,1335.0>>

	* perthousand (U+2030): L<<1020.0,612.0>--<1352.0,613.0>>

	* perthousand (U+2030): L<<572.0,612.0>--<903.0,613.0>>

	* perthousand (U+2030): L<<67.0,1333.0>--<398.0,1335.0>>

	* pi (U+03C0): L<<1120.0,850.0>--<1122.0,235.0>>

	* quotedblbase (U+201E): L<<513.0,95.0>--<515.0,348.0>>

	* quotedblbase (U+201E): L<<80.0,95.0>--<82.0,348.0>>

	* quotedblleft (U+201C): L<<450.0,1200.0>--<448.0,947.0>>

	* quotedblleft (U+201C): L<<883.0,1200.0>--<881.0,947.0>>

	* quotedblright (U+201D): L<<513.0,1195.0>--<515.0,1448.0>>

	* quotedblright (U+201D): L<<80.0,1195.0>--<82.0,1448.0>>

	* quoteleft (U+2018): L<<450.0,1200.0>--<448.0,947.0>>

	* quoteright (U+2019): L<<80.0,1195.0>--<82.0,1448.0>>

	* quotesinglbase (U+201A): L<<80.0,95.0>--<82.0,348.0>>

	* semicolon (U+003B): L<<80.0,95.0>--<82.0,348.0>>

	* two (U+0032): L<<73.0,25.0>--<72.0,350.0>>

	* uni00B2 (U+00B2): L<<73.0,25.0>--<72.0,350.0>>

	* uni0123 (U+0123): L<<661.0,1332.0>--<660.0,1168.0>>

	* uni0241 (U+0241): L<<115.0,25.0>--<113.0,473.0>>

	* uni0242 (U+0242): L<<115.0,25.0>--<113.0,290.0>>

	* uni0294 (U+0294): L<<115.0,25.0>--<113.0,473.0>>

	* uni0295 (U+0295): L<<699.0,473.0>--<697.0,25.0>>

	* uni02BB (U+02BB): L<<412.0,1685.0>--<410.0,1432.0>>

	* uni02BC (U+02BC): L<<42.0,1462.0>--<43.0,1703.0>>

	* uni02C0 (U+02C0): L<<43.0,533.0>--<42.0,812.0>>

	* uni02EE (U+02EE): L<<42.0,1195.0>--<44.0,1448.0>>

	* uni02EE (U+02EE): L<<475.0,1195.0>--<477.0,1448.0>>

	* uni0312 (U+0312): L<<308.0,1332.0>--<307.0,1168.0>>

	* uni0313 (U+0313): L<<42.0,1365.0>--<43.0,1528.0>>

	* uni0315 (U+0315): L<<42.0,1365.0>--<43.0,1528.0>>

	* uni0E3F (U+0E3F): L<<733.0,1108.0>--<732.0,1333.0>>

	* uni2154 (U+2154): L<<43.0,684.0>--<42.0,899.0>>

	* zero (U+0030): L<<218.0,1332.0>--<905.0,1335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] Jaro-72ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* ⚠ **WARN** The most common width is 710 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 628:
less, greaterequal, lessequal

Width = 677:
greater

Width = 790:
multiply

Width = 1145:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1277.0,2.0>--<557.0,0.0>>

	* AEacute (U+01FC): L<<1277.0,2.0>--<557.0,0.0>>

	* OE (U+0152): L<<1285.0,2.0>--<268.0,0.0>>

	* comma (U+002C): L<<30.0,95.0>--<32.0,337.0>>

	* five (U+0035): L<<42.0,508.0>--<43.0,1308.0>>

	* fiveeighths (U+215D): L<<42.0,1002.0>--<43.0,1530.0>>

	* numbersign (U+0023): L<<1091.0,922.0>--<1332.0,923.0>>

	* numbersign (U+0023): L<<163.0,920.0>--<406.0,921.0>>

	* numbersign (U+0023): L<<567.0,493.0>--<715.0,494.0>>

	* numbersign (U+0023): L<<674.0,921.0>--<823.0,922.0>>

	* numbersign (U+0023): L<<82.0,492.0>--<299.0,493.0>>

	* numbersign (U+0023): L<<983.0,494.0>--<1248.0,495.0>>

	* onehalf (U+00BD): L<<626.0,17.0>--<625.0,390.0>>

	* percent (U+0025): L<<572.0,612.0>--<903.0,613.0>>

	* percent (U+0025): L<<67.0,1333.0>--<398.0,1335.0>>

	* perthousand (U+2030): L<<1020.0,612.0>--<1352.0,613.0>>

	* perthousand (U+2030): L<<572.0,612.0>--<903.0,613.0>>

	* perthousand (U+2030): L<<67.0,1333.0>--<398.0,1335.0>>

	* pi (U+03C0): L<<992.0,762.0>--<993.0,318.0>>

	* quotedblbase (U+201E): L<<42.0,95.0>--<44.0,337.0>>

	* quotedblbase (U+201E): L<<475.0,95.0>--<477.0,337.0>>

	* quotedblleft (U+201C): L<<383.0,1200.0>--<381.0,958.0>>

	* quotedblleft (U+201C): L<<816.0,1200.0>--<814.0,958.0>>

	* quotedblright (U+201D): L<<42.0,1195.0>--<44.0,1437.0>>

	* quotedblright (U+201D): L<<475.0,1195.0>--<477.0,1437.0>>

	* quoteleft (U+2018): L<<395.0,1200.0>--<393.0,958.0>>

	* quoteright (U+2019): L<<42.0,1195.0>--<44.0,1437.0>>

	* quotesinglbase (U+201A): L<<42.0,95.0>--<44.0,337.0>>

	* semicolon (U+003B): L<<30.0,95.0>--<32.0,337.0>>

	* two (U+0032): L<<43.0,25.0>--<42.0,590.0>>

	* uni00B2 (U+00B2): L<<43.0,25.0>--<42.0,590.0>>

	* uni0123 (U+0123): L<<573.0,1350.0>--<572.0,1168.0>>

	* uni018B (U+018B): L<<57.0,1332.0>--<885.0,1335.0>>

	* uni01E2 (U+01E2): L<<1277.0,2.0>--<557.0,0.0>>

	* uni0241 (U+0241): L<<43.0,25.0>--<42.0,573.0>>

	* uni0242 (U+0242): L<<43.0,22.0>--<42.0,342.0>>

	* uni0294 (U+0294): L<<43.0,25.0>--<42.0,573.0>>

	* uni0295 (U+0295): L<<723.0,573.0>--<722.0,25.0>>

	* uni02BB (U+02BB): L<<395.0,1685.0>--<393.0,1443.0>>

	* uni02BC (U+02BC): L<<42.0,1462.0>--<43.0,1703.0>>

	* uni02EE (U+02EE): L<<42.0,1195.0>--<44.0,1437.0>>

	* uni02EE (U+02EE): L<<475.0,1195.0>--<477.0,1437.0>>

	* uni0312 (U+0312): L<<308.0,1350.0>--<307.0,1168.0>>

	* uni0313 (U+0313): L<<42.0,1347.0>--<43.0,1528.0>>

	* uni0315 (U+0315): L<<42.0,1347.0>--<43.0,1528.0>>

	* uni0E3F (U+0E3F): L<<717.0,997.0>--<715.0,1333.0>>

	* uni2154 (U+2154): L<<43.0,684.0>--<42.0,1057.0>>

	* uni2C64 (U+2C64): L<<440.0,372.0>--<435.0,-243.0>>

	* uni2C72 (U+2C72): L<<1427.0,1132.0>--<1428.0,285.0>>

	* uni2C72 (U+2C72): L<<42.0,285.0>--<43.0,1308.0>>

	* zero (U+0030): L<<67.0,1332.0>--<900.0,1335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] Jaro-12ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* ⚠ **WARN** The most common width is 710 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 673:
less, lessequal

Width = 677:
greater

Width = 715:
multiply

Width = 1175:
approxequal

Width = 627:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* zero (U+0030): X=204.0,Y=1332.0 (should be at cap-height 1333?)

	* zero (U+0030): X=905.0,Y=1335.0 (should be at cap-height 1333?)

	* colon (U+003A): X=100.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=419.0,Y=1.0 (should be at baseline 0?)

	* k (U+006B): X=665.0,Y=1098.0 (should be at x-height 1100?)

	* k (U+006B): X=922.0,Y=1098.0 (should be at x-height 1100?)

	* exclamdown (U+00A1): X=334.0,Y=1334.0 (should be at cap-height 1333?)

	* exclamdown (U+00A1): X=15.0,Y=1334.0 (should be at cap-height 1333?)

	* sterling (U+00A3): X=375.5,Y=1331.5 (should be at cap-height 1333?)

	* copyright (U+00A9): X=340.0,Y=-2.0 (should be at baseline 0?)

	* copyright (U+00A9): X=827.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=340.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=827.0,Y=-2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=339.0,Y=1332.0 (should be at cap-height 1333?)

	* ccaron (U+010D): X=407.0,Y=1332.0 (should be at cap-height 1333?)

	* Eogonek (U+0118): X=834.0,Y=2.0 (should be at baseline 0?)

	* ecaron (U+011B): X=495.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=563.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0123 (U+0123): X=653.0,Y=1334.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=585.0,Y=1331.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=718.0,Y=1331.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=486.0,Y=1332.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=554.0,Y=1332.0 (should be at cap-height 1333?)

	* scaron (U+0161): X=309.0,Y=1332.0 (should be at cap-height 1333?)

	* scaron (U+0161): X=377.0,Y=1332.0 (should be at cap-height 1333?)

	* uogonek (U+0173): X=903.0,Y=2.0 (should be at baseline 0?)

	* zcaron (U+017E): X=345.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=413.0,Y=1332.0 (should be at cap-height 1333?)

	* uni018A (U+018A): X=527.0,Y=1331.0 (should be at cap-height 1333?)

	* uni01A5 (U+01A5): X=614.0,Y=1334.0 (should be at cap-height 1333?)

	* uni01A5 (U+01A5): X=434.0,Y=1334.0 (should be at cap-height 1333?)

	* uni01B2 (U+01B2): X=934.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01B3 (U+01B3): X=625.0,Y=1334.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=588.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=656.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=167.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=235.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=480.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=548.0,Y=1332.0 (should be at cap-height 1333?)

	* gcaron (U+01E7): X=495.0,Y=1332.0 (should be at cap-height 1333?)

	* gcaron (U+01E7): X=563.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=402.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=470.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=221.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=289.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0203 (U+0203): X=775.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0203 (U+0203): X=471.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=682.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=378.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=354.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=50.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=667.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=363.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=589.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=285.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=673.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=369.0,Y=1335.0 (should be at cap-height 1333?)

	* ogonek (U+02DB): X=139.0,Y=-2.0 (should be at baseline 0?)

	* uni030C (U+030C): X=217.0,Y=1332.0 (should be at cap-height 1333?)

	* uni030C (U+030C): X=285.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=397.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=93.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0312 (U+0312): X=308.0,Y=1334.0 (should be at cap-height 1333?)

	* uni0328 (U+0328): X=122.0,Y=-2.0 (should be at baseline 0?)

	* uni0329 (U+0329): X=67.0,Y=2.0 (should be at baseline 0?)

	* uni0329 (U+0329): X=220.0,Y=2.0 (should be at baseline 0?)

	* uni0358 (U+0358): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0358 (U+0358): X=298.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1DCA (U+1DCA): X=103.0,Y=-498.0 (should be at descender -500?)

	* uni1DCA (U+1DCA): X=213.0,Y=-498.0 (should be at descender -500?)

	* uni1E29 (U+1E29): X=462.0,Y=-2.0 (should be at baseline 0?)

	* uni1E29 (U+1E29): X=598.0,Y=-2.0 (should be at baseline 0?)

	* uni1E67 (U+1E67): X=309.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1E67 (U+1E67): X=377.0,Y=1332.0 (should be at cap-height 1333?)

	* perthousand (U+2030): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=507.0,Y=1332.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=761.0,Y=1332.0 (should be at cap-height 1333?)

	* uni20AD (U+20AD): X=713.0,Y=1331.0 (should be at cap-height 1333?)

	* seveneighths (U+215E): X=317.0,Y=1334.0 (should be at cap-height 1333?)

	* seveneighths (U+215E): X=58.0,Y=1334.0 (should be at cap-height 1333?)

	* emptyset (U+2205): X=795.0,Y=-2.0 (should be at baseline 0?)

	* emptyset (U+2205): X=340.0,Y=-2.0 (should be at baseline 0?)

	* uniA789 (U+A789): X=100.0,Y=1.0 (should be at baseline 0?)

	* uniA789 (U+A789): X=419.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<1033.0,1132.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* K (U+004B): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* K (U+004B): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* K (U+004B): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* Kmacronbelow (U+1E34): L<<1033.0,1132.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* Kmacronbelow (U+1E34): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* Kmacronbelow (U+1E34): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* Kmacronbelow (U+1E34): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* R (U+0052): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* Racute (U+0154): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* Rcaron (U+0158): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* Rcaron (U+0159): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* Rmacronbelow (U+1E5E): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* ae (U+00E6): L<<1052.0,8.0>--<873.0,56.0>> -> L<<873.0,56.0>--<672.0,125.0>>

	* ae (U+00E6): L<<530.0,1092.0>--<708.0,1044.0>> -> L<<708.0,1044.0>--<910.0,975.0>>

	* e (U+0065): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* eacute (U+00E9): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* ecaron (U+011B): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* ecircumflex (U+00EA): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* edieresis (U+00EB): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* edotaccent (U+0117): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* egrave (U+00E8): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* emacron (U+0113): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* eogonek (U+0119): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* kgreenlandic (U+0138): L<<1033.0,899.0>--<908.0,684.0>> -> L<<908.0,684.0>--<830.0,571.0>>

	* lozenge (U+25CA): L<<280.0,603.0>--<293.0,582.0>> -> L<<293.0,582.0>--<502.0,278.0>>

	* lozenge (U+25CA): L<<502.0,278.0>--<515.0,297.0>> -> L<<515.0,297.0>--<723.0,603.0>>

	* lozenge (U+25CA): L<<503.0,915.0>--<487.0,895.0>> -> L<<487.0,895.0>--<280.0,603.0>>

	* lozenge (U+25CA): L<<723.0,603.0>--<708.0,623.0>> -> L<<708.0,623.0>--<503.0,915.0>>

	* oe (U+0153): L<<1037.0,8.0>--<859.0,56.0>> -> L<<859.0,56.0>--<657.0,125.0>>

	* uni0136 (U+0136): L<<1033.0,1132.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* uni0136 (U+0136): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* uni0136 (U+0136): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* uni0136 (U+0136): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* uni0156 (U+0156): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni0198 (U+0198): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* uni0198 (U+0198): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* uni0198 (U+0198): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* uni0198 (U+0198): L<<994.0,1039.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* uni01AE (U+01AE): L<<308.0,-177.0>--<308.0,24.0>> -> L<<308.0,24.0>--<308.0,25.0>>

	* uni01AE (U+01AE): L<<308.0,24.0>--<308.0,25.0>> -> L<<308.0,25.0>--<308.0,1055.0>>

	* uni01DD (U+01DD): L<<494.0,652.0>--<672.0,604.0>> -> L<<672.0,604.0>--<874.0,535.0>>

	* uni01E3 (U+01E3): L<<1052.0,8.0>--<873.0,56.0>> -> L<<873.0,56.0>--<672.0,125.0>>

	* uni01E3 (U+01E3): L<<530.0,1092.0>--<708.0,1044.0>> -> L<<708.0,1044.0>--<910.0,975.0>>

	* uni01E8 (U+01E8): L<<1033.0,1132.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* uni01E8 (U+01E8): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* uni01E8 (U+01E8): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* uni01E8 (U+01E8): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* uni0205 (U+0205): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni0207 (U+0207): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni0210 (U+0210): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni0212 (U+0212): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni0229 (U+0229): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni0247 (U+0247): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<253.0,85.0>>

	* uni024C (U+024C): L<<1061.0,754.0>--<948.0,645.0>> -> L<<948.0,645.0>--<861.0,570.0>>

	* uni0259 (U+0259): L<<494.0,652.0>--<672.0,604.0>> -> L<<672.0,604.0>--<874.0,535.0>>

	* uni029D (U+029D): L<<117.0,-252.0>--<188.0,-252.0>> -> L<<188.0,-252.0>--<297.0,-250.0>>

	* uni1E15 (U+1E15): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1E17 (U+1E17): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1E19 (U+1E19): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1E1B (U+1E1B): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1E1D (U+1E1D): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1E30 (U+1E30): L<<1033.0,1132.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* uni1E30 (U+1E30): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* uni1E30 (U+1E30): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* uni1E30 (U+1E30): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* uni1E32 (U+1E32): L<<1033.0,1132.0>--<908.0,836.0>> -> L<<908.0,836.0>--<830.0,688.0>>

	* uni1E32 (U+1E32): L<<568.0,791.0>--<633.0,1040.0>> -> L<<633.0,1040.0>--<691.0,1320.0>>

	* uni1E32 (U+1E32): L<<710.0,15.0>--<637.0,320.0>> -> L<<637.0,320.0>--<582.0,500.0>>

	* uni1E32 (U+1E32): L<<830.0,688.0>--<910.0,541.0>> -> L<<910.0,541.0>--<1059.0,207.0>>

	* uni1E58 (U+1E58): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni1E5A (U+1E5A): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni1E5C (U+1E5C): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni1EB9 (U+1EB9): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EBB (U+1EBB): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EBD (U+1EBD): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EBF (U+1EBF): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EC1 (U+1EC1): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EC3 (U+1EC3): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EC5 (U+1EC5): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni1EC7 (U+1EC7): L<<515.0,8.0>--<337.0,56.0>> -> L<<337.0,56.0>--<135.0,125.0>>

	* uni20A8 (U+20A8): L<<962.0,754.0>--<849.0,645.0>> -> L<<849.0,645.0>--<763.0,570.0>>

	* uni2C64 (U+2C64): L<<961.0,757.0>--<848.0,647.0>> -> L<<848.0,647.0>--<763.0,573.0>>

	* uni2C66 (U+2C66): L<<147.0,1250.0>--<417.0,1250.0>> -> L<<417.0,1250.0>--<419.0,1250.0>>

	* uniA740 (U+A740): L<<1147.0,1132.0>--<1022.0,836.0>> -> L<<1022.0,836.0>--<944.0,688.0>>

	* uniA740 (U+A740): L<<682.0,791.0>--<747.0,1040.0>> -> L<<747.0,1040.0>--<805.0,1320.0>>

	* uniA740 (U+A740): L<<824.0,15.0>--<751.0,320.0>> -> L<<751.0,320.0>--<696.0,500.0>>

	* uniA740 (U+A740): L<<944.0,688.0>--<1024.0,541.0>> -> L<<1024.0,541.0>--<1173.0,207.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* comma (U+002C): L<<75.0,95.0>--<77.0,347.0>>

	* five (U+0035): L<<42.0,553.0>--<43.0,1308.0>>

	* fiveeighths (U+215D): L<<42.0,1032.0>--<43.0,1530.0>>

	* numbersign (U+0023): L<<1091.0,922.0>--<1332.0,923.0>>

	* numbersign (U+0023): L<<163.0,920.0>--<423.0,921.0>>

	* numbersign (U+0023): L<<567.0,493.0>--<731.0,494.0>>

	* numbersign (U+0023): L<<674.0,921.0>--<839.0,922.0>>

	* numbersign (U+0023): L<<82.0,492.0>--<315.0,493.0>>

	* numbersign (U+0023): L<<983.0,494.0>--<1248.0,495.0>>

	* onehalf (U+00BD): L<<608.0,17.0>--<607.0,246.0>>

	* percent (U+0025): L<<572.0,612.0>--<903.0,613.0>>

	* percent (U+0025): L<<67.0,1333.0>--<398.0,1335.0>>

	* perthousand (U+2030): L<<1020.0,612.0>--<1352.0,613.0>>

	* perthousand (U+2030): L<<572.0,612.0>--<903.0,613.0>>

	* perthousand (U+2030): L<<67.0,1333.0>--<398.0,1335.0>>

	* pi (U+03C0): L<<1108.0,842.0>--<1110.0,243.0>>

	* quotedblbase (U+201E): L<<509.0,95.0>--<511.0,347.0>>

	* quotedblbase (U+201E): L<<76.0,95.0>--<78.0,347.0>>

	* quotedblleft (U+201C): L<<444.0,1200.0>--<442.0,948.0>>

	* quotedblleft (U+201C): L<<877.0,1200.0>--<875.0,948.0>>

	* quotedblright (U+201D): L<<509.0,1195.0>--<511.0,1447.0>>

	* quotedblright (U+201D): L<<76.0,1195.0>--<78.0,1447.0>>

	* quoteleft (U+2018): L<<445.0,1200.0>--<443.0,948.0>>

	* quoteright (U+2019): L<<76.0,1195.0>--<78.0,1447.0>>

	* quotesinglbase (U+201A): L<<76.0,95.0>--<78.0,347.0>>

	* semicolon (U+003B): L<<75.0,95.0>--<77.0,347.0>>

	* two (U+0032): L<<70.0,25.0>--<69.0,372.0>>

	* uni00B2 (U+00B2): L<<70.0,25.0>--<69.0,372.0>>

	* uni0123 (U+0123): L<<653.0,1334.0>--<652.0,1168.0>>

	* uni0241 (U+0241): L<<108.0,25.0>--<107.0,482.0>>

	* uni0242 (U+0242): L<<108.0,25.0>--<107.0,295.0>>

	* uni0294 (U+0294): L<<108.0,25.0>--<107.0,482.0>>

	* uni0295 (U+0295): L<<701.0,482.0>--<699.0,25.0>>

	* uni02BB (U+02BB): L<<410.0,1685.0>--<408.0,1433.0>>

	* uni02BC (U+02BC): L<<42.0,1462.0>--<43.0,1703.0>>

	* uni02C0 (U+02C0): L<<43.0,533.0>--<42.0,818.0>>

	* uni02EE (U+02EE): L<<42.0,1195.0>--<44.0,1447.0>>

	* uni02EE (U+02EE): L<<475.0,1195.0>--<477.0,1447.0>>

	* uni0312 (U+0312): L<<308.0,1334.0>--<307.0,1168.0>>

	* uni0313 (U+0313): L<<42.0,1363.0>--<43.0,1528.0>>

	* uni0315 (U+0315): L<<42.0,1363.0>--<43.0,1528.0>>

	* uni0E3F (U+0E3F): L<<732.0,1098.0>--<730.0,1333.0>>

	* uni2154 (U+2154): L<<43.0,684.0>--<42.0,913.0>>

	* uni2C64 (U+2C64): L<<452.0,477.0>--<451.0,-228.0>>

	* zero (U+0030): L<<204.0,1332.0>--<905.0,1335.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] Jaro-48ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* ⚠ **WARN** The most common width is 710 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 646:
less, lessequal

Width = 677:
greater

Width = 760:
multiply

Width = 1157:
approxequal

Width = 628:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* parenleft (U+0028): X=425.0,Y=-1.0 (should be at baseline 0?)

	* parenright (U+0029): X=320.0,Y=-1.0 (should be at baseline 0?)

	* zero (U+0030): X=122.0,Y=1332.0 (should be at cap-height 1333?)

	* zero (U+0030): X=902.0,Y=1335.0 (should be at cap-height 1333?)

	* k (U+006B): X=604.0,Y=1099.0 (should be at x-height 1100?)

	* k (U+006B): X=889.0,Y=1099.0 (should be at x-height 1100?)

	* exclamdown (U+00A1): X=351.0,Y=1334.0 (should be at cap-height 1333?)

	* exclamdown (U+00A1): X=42.0,Y=1334.0 (should be at cap-height 1333?)

	* sterling (U+00A3): X=375.5,Y=1331.5 (should be at cap-height 1333?)

	* section (U+00A7): X=59.0,Y=1.0 (should be at baseline 0?)

	* copyright (U+00A9): X=340.0,Y=-2.0 (should be at baseline 0?)

	* copyright (U+00A9): X=827.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=340.0,Y=-2.0 (should be at baseline 0?)

	* registered (U+00AE): X=827.0,Y=-2.0 (should be at baseline 0?)

	* onequarter (U+00BC): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* onehalf (U+00BD): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* threequarters (U+00BE): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* AE (U+00C6): X=1319.0,Y=1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=305.0,Y=1332.0 (should be at cap-height 1333?)

	* ccaron (U+010D): X=373.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=447.0,Y=1332.0 (should be at cap-height 1333?)

	* ecaron (U+011B): X=515.0,Y=1332.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=585.0,Y=1331.0 (should be at cap-height 1333?)

	* Lcaron (U+013D): X=718.0,Y=1331.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=443.0,Y=1332.0 (should be at cap-height 1333?)

	* ncaron (U+0148): X=511.0,Y=1332.0 (should be at cap-height 1333?)

	* OE (U+0152): X=1330.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=333.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=475.0,Y=1.0 (should be at baseline 0?)

	* scaron (U+0161): X=306.0,Y=1332.0 (should be at cap-height 1333?)

	* scaron (U+0161): X=374.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=336.0,Y=1332.0 (should be at cap-height 1333?)

	* zcaron (U+017E): X=404.0,Y=1332.0 (should be at cap-height 1333?)

	* uni018B (U+018B): X=83.0,Y=1332.0 (should be at cap-height 1333?)

	* uni018B (U+018B): X=917.0,Y=1334.0 (should be at cap-height 1333?)

	* uni0190 (U+0190): X=270.0,Y=1.5 (should be at baseline 0?)

	* uni0190 (U+0190): X=294.5,Y=1331.5 (should be at cap-height 1333?)

	* uni01A5 (U+01A5): X=621.0,Y=1331.0 (should be at cap-height 1333?)

	* uni01B2 (U+01B2): X=881.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=549.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01CE (U+01CE): X=617.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=181.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D0 (U+01D0): X=249.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=441.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01D2 (U+01D2): X=509.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01E2 (U+01E2): X=1319.0,Y=1.0 (should be at baseline 0?)

	* gcaron (U+01E7): X=447.0,Y=1332.0 (should be at cap-height 1333?)

	* gcaron (U+01E7): X=515.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=363.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01EF (U+01EF): X=431.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=206.0,Y=1332.0 (should be at cap-height 1333?)

	* uni01F0 (U+01F0): X=274.0,Y=1332.0 (should be at cap-height 1333?)

	* AEacute (U+01FC): X=1319.0,Y=1.0 (should be at baseline 0?)

	* uni0203 (U+0203): X=736.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0203 (U+0203): X=432.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=634.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0207 (U+0207): X=330.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=368.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020B (U+020B): X=64.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=628.0,Y=1335.0 (should be at cap-height 1333?)

	* uni020F (U+020F): X=324.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=508.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0213 (U+0213): X=204.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=630.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0217 (U+0217): X=326.0,Y=1335.0 (should be at cap-height 1333?)

	* uni023B (U+023B): X=713.0,Y=1331.0 (should be at cap-height 1333?)

	* uni0242 (U+0242): X=94.0,Y=-2.0 (should be at baseline 0?)

	* uni0242 (U+0242): X=439.0,Y=-2.0 (should be at baseline 0?)

	* uni030C (U+030C): X=217.0,Y=1332.0 (should be at cap-height 1333?)

	* uni030C (U+030C): X=285.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=397.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0311 (U+0311): X=93.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0313 (U+0313): X=164.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0313 (U+0313): X=62.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0315 (U+0315): X=164.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0315 (U+0315): X=62.0,Y=1335.0 (should be at cap-height 1333?)

	* uni0329 (U+0329): X=67.0,Y=2.0 (should be at baseline 0?)

	* uni0329 (U+0329): X=220.0,Y=2.0 (should be at baseline 0?)

	* uni0358 (U+0358): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* uni0358 (U+0358): X=298.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1DCA (U+1DCA): X=103.0,Y=-498.0 (should be at descender -500?)

	* uni1DCA (U+1DCA): X=213.0,Y=-498.0 (should be at descender -500?)

	* uni1E67 (U+1E67): X=306.0,Y=1332.0 (should be at cap-height 1333?)

	* uni1E67 (U+1E67): X=374.0,Y=1332.0 (should be at cap-height 1333?)

	* perthousand (U+2030): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=507.0,Y=1332.0 (should be at cap-height 1333?)

	* dong (U+20AB): X=780.0,Y=1332.0 (should be at cap-height 1333?)

	* uni20AD (U+20AD): X=668.0,Y=1331.0 (should be at cap-height 1333?)

	* uni2153 (U+2153): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* uni2154 (U+2154): X=52.0,Y=1334.0 (should be at cap-height 1333?)

	* oneeighth (U+215B): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* threeeighths (U+215C): X=42.0,Y=1332.0 (should be at cap-height 1333?)

	* emptyset (U+2205): X=795.0,Y=-2.0 (should be at baseline 0?)

	* emptyset (U+2205): X=340.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1319.0,1.0>--<607.0,0.0>>

	* AEacute (U+01FC): L<<1319.0,1.0>--<607.0,0.0>>

	* OE (U+0152): L<<1330.0,1.0>--<305.0,0.0>>

	* comma (U+002C): L<<48.0,95.0>--<50.0,341.0>>

	* five (U+0035): L<<42.0,526.0>--<43.0,1308.0>>

	* fiveeighths (U+215D): L<<42.0,1014.0>--<43.0,1530.0>>

	* infinity (U+221E): L<<744.0,348.0>--<743.0,557.0>>

	* infinity (U+221E): L<<839.0,652.0>--<840.0,443.0>>

	* numbersign (U+0023): L<<1091.0,922.0>--<1332.0,923.0>>

	* numbersign (U+0023): L<<163.0,920.0>--<413.0,921.0>>

	* numbersign (U+0023): L<<567.0,493.0>--<721.0,494.0>>

	* numbersign (U+0023): L<<674.0,921.0>--<829.0,922.0>>

	* numbersign (U+0023): L<<82.0,492.0>--<305.0,493.0>>

	* numbersign (U+0023): L<<983.0,494.0>--<1248.0,495.0>>

	* onehalf (U+00BD): L<<619.0,17.0>--<618.0,333.0>>

	* percent (U+0025): L<<572.0,612.0>--<903.0,613.0>>

	* percent (U+0025): L<<67.0,1333.0>--<398.0,1335.0>>

	* perthousand (U+2030): L<<1020.0,612.0>--<1352.0,613.0>>

	* perthousand (U+2030): L<<572.0,612.0>--<903.0,613.0>>

	* perthousand (U+2030): L<<67.0,1333.0>--<398.0,1335.0>>

	* pi (U+03C0): L<<1039.0,794.0>--<1040.0,288.0>>

	* quotedblbase (U+201E): L<<489.0,95.0>--<491.0,341.0>>

	* quotedblbase (U+201E): L<<56.0,95.0>--<58.0,341.0>>

	* quotedblleft (U+201C): L<<407.0,1200.0>--<405.0,954.0>>

	* quotedblleft (U+201C): L<<840.0,1200.0>--<838.0,954.0>>

	* quotedblright (U+201D): L<<489.0,1195.0>--<491.0,1441.0>>

	* quotedblright (U+201D): L<<56.0,1195.0>--<58.0,1441.0>>

	* quoteleft (U+2018): L<<415.0,1200.0>--<413.0,954.0>>

	* quoteright (U+2019): L<<56.0,1195.0>--<58.0,1441.0>>

	* quotesinglbase (U+201A): L<<56.0,95.0>--<58.0,341.0>>

	* semicolon (U+003B): L<<48.0,95.0>--<50.0,341.0>>

	* two (U+0032): L<<54.0,25.0>--<53.0,503.0>>

	* uni00B2 (U+00B2): L<<54.0,25.0>--<53.0,503.0>>

	* uni0123 (U+0123): L<<605.0,1343.0>--<604.0,1168.0>>

	* uni018B (U+018B): L<<83.0,1332.0>--<917.0,1334.0>>

	* uni01E2 (U+01E2): L<<1319.0,1.0>--<607.0,0.0>>

	* uni0241 (U+0241): L<<69.0,25.0>--<68.0,537.0>>

	* uni0242 (U+0242): L<<69.0,23.0>--<68.0,323.0>>

	* uni0294 (U+0294): L<<69.0,25.0>--<68.0,537.0>>

	* uni0295 (U+0295): L<<714.0,537.0>--<713.0,25.0>>

	* uni02BB (U+02BB): L<<401.0,1685.0>--<399.0,1439.0>>

	* uni02BC (U+02BC): L<<42.0,1462.0>--<43.0,1703.0>>

	* uni02EE (U+02EE): L<<42.0,1195.0>--<44.0,1441.0>>

	* uni02EE (U+02EE): L<<475.0,1195.0>--<477.0,1441.0>>

	* uni0312 (U+0312): L<<308.0,1343.0>--<307.0,1168.0>>

	* uni0313 (U+0313): L<<42.0,1354.0>--<43.0,1528.0>>

	* uni0315 (U+0315): L<<42.0,1354.0>--<43.0,1528.0>>

	* uni0E3F (U+0E3F): L<<723.0,1037.0>--<721.0,1333.0>>

	* uni2154 (U+2154): L<<43.0,684.0>--<42.0,1000.0>>

	* uni2C64 (U+2C64): L<<445.0,414.0>--<442.0,-237.0>>

	* uni2C72 (U+2C72): L<<1478.0,1144.0>--<1479.0,275.0>>

	* uni2C72 (U+2C72): L<<70.0,275.0>--<71.0,1308.0>>

	* zero (U+0030): L<<122.0,1332.0>--<902.0,1335.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 15 | 10 | 63 | 629 | 26 | 439 | 0 |
| 1% | 1% | 5% | 53% | 2% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
