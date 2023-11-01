## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[24] Jaro-6ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


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
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1271, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 410, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 7, 'y': 0}
	* {'glyph': 'quotedblright', 'component': 'comma', 'x': 7, 'y': 660} and {'glyph': 'uni02EE', 'component': 'comma', 'x': 7, 'y': 660} [code: found-duplicates]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030D

	- uni030F

	- uni0310

	- uni0311

	- uni0312

	- uni0313

	- uni031B

	- uni0320

	- uni0324

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0329

	- uni032D

	- uni032E

	- uni032F

	- uni0330

	- uni0331

	- uni0332

	- uni0334

	- uni0335

	- uni1DC7

	- uni1DCA [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- M.alt

	- N.alt

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- nine.ALT

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.ALT

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni006A0301

	- uni0181.alt

	- uni01A4.001

	- uni01A4.002

	- uni01A4.003

	- uni01A4.004

	- uni01A4.005

	- uni03010304.001

	- uni03060303.case.001

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: currency	Contours detected: 0	Expected: 2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: logicalnot	Contours detected: 0	Expected: 1

	- Glyph name: plusminus	Contours detected: 0	Expected: 1or2

	- Glyph name: uni00B5	Contours detected: 0	Expected: 1

	- Glyph name: onequarter	Contours detected: 0	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 0	Expected: 3

	- Glyph name: threequarters	Contours detected: 0	Expected: 3or4

	- Glyph name: AE	Contours detected: 2	Expected: 3

	- Glyph name: Egrave	Contours detected: 2	Expected: 3

	- Glyph name: Eacute	Contours detected: 2	Expected: 3

	- Glyph name: Ecircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Edieresis	Contours detected: 3	Expected: 4

	- Glyph name: Oslash	Contours detected: 2	Expected: 3

	- Glyph name: Aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 2	Expected: 3

	- Glyph name: Ebreve	Contours detected: 2	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 2	Expected: 3

	- Glyph name: Ecaron	Contours detected: 2	Expected: 3

	- Glyph name: Gcircumflex	Contours detected: 2	Expected: 3or4

	- Glyph name: Gbreve	Contours detected: 2	Expected: 3or4

	- Glyph name: Gdotaccent	Contours detected: 2	Expected: 3or4

	- Glyph name: uni0122	Contours detected: 2	Expected: 3or4

	- Glyph name: Hbar	Contours detected: 2	Expected: 1

	- Glyph name: IJ	Contours detected: 2	Expected: 3or4

	- Glyph name: kgreenlandic	Contours detected: 0	Expected: 1or2

	- Glyph name: OE	Contours detected: 2	Expected: 3

	- Glyph name: Racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 3	Expected: 2

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: Ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01C8	Contours detected: 1	Expected: 3

	- Glyph name: uni01C7	Contours detected: 2	Expected: 3

	- Glyph name: uni01CB	Contours detected: 1	Expected: 3

	- Glyph name: uni01CA	Contours detected: 2	Expected: 3

	- Glyph name: uni018E	Contours detected: 1	Expected: 2

	- Glyph name: uni01E2	Contours detected: 3	Expected: 4

	- Glyph name: uni01E4	Contours detected: 1	Expected: 2

	- Glyph name: Gcaron	Contours detected: 2	Expected: 3or4

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F4	Contours detected: 2	Expected: 3

	- Glyph name: AEacute	Contours detected: 3	Expected: 4

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0204	Contours detected: 3	Expected: 4

	- Glyph name: uni0206	Contours detected: 2	Expected: 3

	- Glyph name: uni0210	Contours detected: 4	Expected: 3

	- Glyph name: uni0212	Contours detected: 3	Expected: 2

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni0246	Contours detected: 1	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 2	Expected: 1

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: pi	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 0	Expected: 3or5

	- Glyph name: uni1E02	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 3	Expected: 4

	- Glyph name: uni1E16	Contours detected: 3	Expected: 4

	- Glyph name: uni1E20	Contours detected: 2	Expected: 3or4

	- Glyph name: uni1E5A	Contours detected: 3	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1EB8	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBA	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBE	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ECA	Contours detected: 2	Expected: 3

	- Glyph name: uni1EDA	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDC	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDE	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni2016	Contours detected: 0	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 3	Expected: 2

	- Glyph name: quotedblright	Contours detected: 3	Expected: 2

	- Glyph name: quotedblbase	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 0	Expected: 6or7

	- Glyph name: minute	Contours detected: 0	Expected: 1

	- Glyph name: second	Contours detected: 0	Expected: 2

	- Glyph name: fraction	Contours detected: 0	Expected: 1

	- Glyph name: colonmonetary	Contours detected: 0	Expected: 1or3

	- Glyph name: uni20A6	Contours detected: 0	Expected: 1, 3or5

	- Glyph name: uni20A9	Contours detected: 0	Expected: 1, 3, 4or7

	- Glyph name: uni20AA	Contours detected: 0	Expected: 2

	- Glyph name: dong	Contours detected: 0	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 0	Expected: 1

	- Glyph name: uni20B1	Contours detected: 0	Expected: 1, 2or4

	- Glyph name: uni20B2	Contours detected: 0	Expected: 1, 2or3

	- Glyph name: uni20B4	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B5	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B8	Contours detected: 0	Expected: 2

	- Glyph name: uni20B9	Contours detected: 0	Expected: 1

	- Glyph name: uni20BA	Contours detected: 0	Expected: 1

	- Glyph name: uni20BC	Contours detected: 0	Expected: 1

	- Glyph name: uni20BD	Contours detected: 0	Expected: 2

	- Glyph name: uni20BF	Contours detected: 0	Expected: 3

	- Glyph name: uni2113	Contours detected: 0	Expected: 2

	- Glyph name: estimated	Contours detected: 0	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1or3

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

	- Glyph name: partialdiff	Contours detected: 0	Expected: 2

	- Glyph name: emptyset	Contours detected: 0	Expected: 3

	- Glyph name: uni2206	Contours detected: 0	Expected: 2

	- Glyph name: product	Contours detected: 0	Expected: 1

	- Glyph name: summation	Contours detected: 0	Expected: 1

	- Glyph name: radical	Contours detected: 0	Expected: 1

	- Glyph name: infinity	Contours detected: 0	Expected: 3

	- Glyph name: integral	Contours detected: 0	Expected: 1

	- Glyph name: approxequal	Contours detected: 0	Expected: 2

	- Glyph name: notequal	Contours detected: 0	Expected: 1

	- Glyph name: lessequal	Contours detected: 0	Expected: 2

	- Glyph name: greaterequal	Contours detected: 0	Expected: 2

	- Glyph name: uni25CC	Contours detected: 0	Expected: 16or12

	- Glyph name: uni27E8	Contours detected: 0	Expected: 1

	- Glyph name: uni27E9	Contours detected: 0	Expected: 1

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: approxequal	Contours detected: 0	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: colonmonetary	Contours detected: 0	Expected: 1or3

	- Glyph name: currency	Contours detected: 0	Expected: 2

	- Glyph name: dong	Contours detected: 0	Expected: 3or4

	- Glyph name: emptyset	Contours detected: 0	Expected: 3

	- Glyph name: estimated	Contours detected: 0	Expected: 2

	- Glyph name: fraction	Contours detected: 0	Expected: 1

	- Glyph name: greaterequal	Contours detected: 0	Expected: 2

	- Glyph name: infinity	Contours detected: 0	Expected: 3

	- Glyph name: integral	Contours detected: 0	Expected: 1

	- Glyph name: kgreenlandic	Contours detected: 0	Expected: 1or2

	- Glyph name: lessequal	Contours detected: 0	Expected: 2

	- Glyph name: logicalnot	Contours detected: 0	Expected: 1

	- Glyph name: notequal	Contours detected: 0	Expected: 1

	- Glyph name: onehalf	Contours detected: 0	Expected: 3

	- Glyph name: onequarter	Contours detected: 0	Expected: 3or4

	- Glyph name: partialdiff	Contours detected: 0	Expected: 2

	- Glyph name: perthousand	Contours detected: 0	Expected: 6or7

	- Glyph name: pi	Contours detected: 0	Expected: 1

	- Glyph name: plusminus	Contours detected: 0	Expected: 1or2

	- Glyph name: product	Contours detected: 0	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 3	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 3	Expected: 2

	- Glyph name: quotedblright	Contours detected: 3	Expected: 2

	- Glyph name: radical	Contours detected: 0	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: summation	Contours detected: 0	Expected: 1

	- Glyph name: threequarters	Contours detected: 0	Expected: 3or4

	- Glyph name: uni00B5	Contours detected: 0	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01C8	Contours detected: 1	Expected: 3

	- Glyph name: uni01CB	Contours detected: 1	Expected: 3

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0244	Contours detected: 1	Expected: 2

	- Glyph name: uni0246	Contours detected: 1	Expected: 3

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 0	Expected: 3or5

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni2016	Contours detected: 0	Expected: 2

	- Glyph name: uni20A6	Contours detected: 0	Expected: 1, 3or5

	- Glyph name: uni20A9	Contours detected: 0	Expected: 1, 3, 4or7

	- Glyph name: uni20AA	Contours detected: 0	Expected: 2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 0	Expected: 1

	- Glyph name: uni20B1	Contours detected: 0	Expected: 1, 2or4

	- Glyph name: uni20B2	Contours detected: 0	Expected: 1, 2or3

	- Glyph name: uni20B4	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B5	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B8	Contours detected: 0	Expected: 2

	- Glyph name: uni20B9	Contours detected: 0	Expected: 1

	- Glyph name: uni20BA	Contours detected: 0	Expected: 1

	- Glyph name: uni20BC	Contours detected: 0	Expected: 1

	- Glyph name: uni20BD	Contours detected: 0	Expected: 2

	- Glyph name: uni20BF	Contours detected: 0	Expected: 3

	- Glyph name: uni2113	Contours detected: 0	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uni2206	Contours detected: 0	Expected: 2

	- Glyph name: uni25CC	Contours detected: 0	Expected: 16or12

	- Glyph name: uni27E8	Contours detected: 0	Expected: 1

	- Glyph name: uni27E9	Contours detected: 0	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 426:
minus, multiply, plus, equal, divide

Width = 406:
less, greater
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** Tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lozenge (U+25CA): L<<105.0,377.0>--<121.0,353.0>> -> L<<121.0,353.0>--<287.0,109.0>>

	* lozenge (U+25CA): L<<287.0,109.0>--<303.0,131.0>> -> L<<303.0,131.0>--<469.0,376.0>>

	* lozenge (U+25CA): L<<288.0,632.0>--<271.0,611.0>> -> L<<271.0,611.0>--<105.0,377.0>>

	* lozenge (U+25CA): L<<469.0,376.0>--<453.0,399.0>> -> L<<453.0,399.0>--<288.0,632.0>>

	* uni018F (U+018F): L<<79.0,728.0>--<206.0,730.0>> -> L<<206.0,730.0>--<450.0,730.0>>

	* uni018F (U+0259): L<<79.0,728.0>--<206.0,730.0>> -> L<<206.0,730.0>--<450.0,730.0>>

	* uni023A (U+023A): L<<75.0,13.0>--<75.0,15.0>> -> L<<75.0,15.0>--<75.0,571.0>>

	* uni023A (U+2C65): L<<75.0,13.0>--<75.0,15.0>> -> L<<75.0,15.0>--<75.0,571.0>>

	* uni029D (U+029D): L<<222.0,-250.0>--<118.0,-250.0>> -> L<<118.0,-250.0>--<114.0,-250.0>>

	* uni029D (U+029D): L<<70.0,-202.0>--<113.0,-202.0>> -> L<<113.0,-202.0>--<151.0,-201.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<816.0,1.0>--<384.0,0.0>>

	* AE (U+00E6): L<<816.0,1.0>--<384.0,0.0>>

	* AEacute (U+01FC): L<<816.0,1.0>--<384.0,0.0>>

	* AEacute (U+01FD): L<<816.0,1.0>--<384.0,0.0>>

	* OE (U+0152): L<<821.0,1.0>--<211.0,0.0>>

	* OE (U+0153): L<<821.0,1.0>--<211.0,0.0>>

	* comma (U+002C): L<<18.0,57.0>--<19.0,202.0>>

	* five (U+0035): L<<25.0,305.0>--<26.0,785.0>>

	* percent (U+0025): L<<342.0,367.0>--<541.0,368.0>>

	* percent (U+0025): L<<39.0,800.0>--<238.0,801.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<285.0,57.0>--<286.0,202.0>>

	* quotedblleft (U+201C): L<<230.0,720.0>--<229.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<285.0,717.0>--<286.0,862.0>>

	* quoteleft (U+2018): L<<237.0,720.0>--<236.0,575.0>>

	* quoteright (U+2019): L<<25.0,717.0>--<26.0,862.0>>

	* quotesinglbase (U+201A): L<<25.0,57.0>--<26.0,202.0>>

	* semicolon (U+003B): L<<18.0,57.0>--<19.0,202.0>>

	* two (U+0032): L<<26.0,15.0>--<25.0,354.0>>

	* uni00B2 (U+00B2): L<<26.0,15.0>--<25.0,354.0>>

	* uni018B (U+018B): L<<10.0,799.0>--<507.0,801.0>>

	* uni018B (U+018C): L<<10.0,799.0>--<507.0,801.0>>

	* uni0193 (U+0193): L<<167.0,800.0>--<404.0,799.0>>

	* uni0193 (U+0193): L<<304.0,507.0>--<556.0,506.0>>

	* uni0193 (U+0193): L<<440.0,-1.0>--<147.0,0.0>>

	* uni0193 (U+0193): L<<536.0,549.0>--<269.0,550.0>>

	* uni0193 (U+0193): L<<571.0,491.0>--<569.0,121.0>>

	* uni0193 (U+0260): L<<167.0,800.0>--<404.0,799.0>>

	* uni0193 (U+0260): L<<304.0,507.0>--<556.0,506.0>>

	* uni0193 (U+0260): L<<440.0,-1.0>--<147.0,0.0>>

	* uni0193 (U+0260): L<<536.0,549.0>--<269.0,550.0>>

	* uni0193 (U+0260): L<<571.0,491.0>--<569.0,121.0>>

	* uni01C7 (U+01C7): L<<341.0,1.0>--<36.0,0.0>>

	* uni01C7 (U+01C9): L<<341.0,1.0>--<36.0,0.0>>

	* uni01C8 (U+01C8): L<<352.0,1.0>--<36.0,0.0>>

	* uni01E2 (U+01E2): L<<816.0,1.0>--<384.0,0.0>>

	* uni01E2 (U+01E3): L<<816.0,1.0>--<384.0,0.0>>

	* uni01E4 (U+01E4): L<<167.0,800.0>--<536.0,799.0>>

	* uni01E4 (U+01E4): L<<430.0,-1.0>--<147.0,0.0>>

	* uni01E4 (U+01E4): L<<536.0,559.0>--<259.0,560.0>>

	* uni01E4 (U+01E4): L<<560.0,286.0>--<559.0,121.0>>

	* uni01E4 (U+01E5): L<<167.0,800.0>--<536.0,799.0>>

	* uni01E4 (U+01E5): L<<430.0,-1.0>--<147.0,0.0>>

	* uni01E4 (U+01E5): L<<536.0,559.0>--<259.0,560.0>>

	* uni01E4 (U+01E5): L<<560.0,286.0>--<559.0,121.0>>

	* uni0241 (U+0241): L<<73.0,15.0>--<72.0,344.0>>

	* uni0242 (U+0242): L<<26.0,13.0>--<25.0,205.0>>

	* uni0294 (U+0294): L<<26.0,15.0>--<25.0,344.0>>

	* uni0295 (U+0295): L<<575.0,344.0>--<574.0,15.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,862.0>>

	* uni0312 (U+0312): L<<218.0,1011.0>--<217.0,866.0>>

	* uni0313 (U+0313): L<<18.0,1004.0>--<19.0,1149.0>>

	* uni2075 (U+2075): L<<25.0,305.0>--<26.0,785.0>>

	* uni2082 (U+2082): L<<26.0,15.0>--<25.0,354.0>>

	* uni2085 (U+2085): L<<25.0,305.0>--<26.0,785.0>>

	* uni2154 (U+2154): L<<26.0,15.0>--<25.0,354.0>>

	* uni2C64 (U+027D): L<<269.0,223.0>--<266.0,-146.0>>

	* uni2C64 (U+2C64): L<<269.0,223.0>--<266.0,-146.0>>

	* uni2C72 (U+2C72): L<<12.0,171.0>--<13.0,785.0>>

	* uni2C72 (U+2C72): L<<843.0,679.0>--<844.0,171.0>>

	* uni2C72 (U+2C73): L<<12.0,171.0>--<13.0,785.0>>

	* uni2C72 (U+2C73): L<<843.0,679.0>--<844.0,171.0>>

	* zero (U+0030): L<<90.0,799.0>--<590.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Jaro-48ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


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
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1271, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 410, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 7, 'y': 0}
	* {'glyph': 'quotedblright', 'component': 'comma', 'x': 7, 'y': 660} and {'glyph': 'uni02EE', 'component': 'comma', 'x': 7, 'y': 660} [code: found-duplicates]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030D

	- uni030F

	- uni0310

	- uni0311

	- uni0312

	- uni0313

	- uni031B

	- uni0320

	- uni0324

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0329

	- uni032D

	- uni032E

	- uni032F

	- uni0330

	- uni0331

	- uni0332

	- uni0334

	- uni0335

	- uni1DC7

	- uni1DCA [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- M.alt

	- N.alt

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- nine.ALT

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.ALT

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni006A0301

	- uni0181.alt

	- uni01A4.001

	- uni01A4.002

	- uni01A4.003

	- uni01A4.004

	- uni01A4.005

	- uni03010304.001

	- uni03060303.case.001

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: currency	Contours detected: 0	Expected: 2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: logicalnot	Contours detected: 0	Expected: 1

	- Glyph name: plusminus	Contours detected: 0	Expected: 1or2

	- Glyph name: uni00B5	Contours detected: 0	Expected: 1

	- Glyph name: onequarter	Contours detected: 0	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 0	Expected: 3

	- Glyph name: threequarters	Contours detected: 0	Expected: 3or4

	- Glyph name: AE	Contours detected: 2	Expected: 3

	- Glyph name: Egrave	Contours detected: 2	Expected: 3

	- Glyph name: Eacute	Contours detected: 2	Expected: 3

	- Glyph name: Ecircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Edieresis	Contours detected: 3	Expected: 4

	- Glyph name: Oslash	Contours detected: 2	Expected: 3

	- Glyph name: Aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 2	Expected: 3

	- Glyph name: Ebreve	Contours detected: 2	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 2	Expected: 3

	- Glyph name: Ecaron	Contours detected: 2	Expected: 3

	- Glyph name: Gcircumflex	Contours detected: 2	Expected: 3or4

	- Glyph name: Gbreve	Contours detected: 2	Expected: 3or4

	- Glyph name: Gdotaccent	Contours detected: 2	Expected: 3or4

	- Glyph name: uni0122	Contours detected: 2	Expected: 3or4

	- Glyph name: Hbar	Contours detected: 2	Expected: 1

	- Glyph name: IJ	Contours detected: 2	Expected: 3or4

	- Glyph name: kgreenlandic	Contours detected: 0	Expected: 1or2

	- Glyph name: OE	Contours detected: 2	Expected: 3

	- Glyph name: Racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 3	Expected: 2

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: Ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01C8	Contours detected: 1	Expected: 3

	- Glyph name: uni01C7	Contours detected: 2	Expected: 3

	- Glyph name: uni01CB	Contours detected: 1	Expected: 3

	- Glyph name: uni01CA	Contours detected: 2	Expected: 3

	- Glyph name: uni018E	Contours detected: 1	Expected: 2

	- Glyph name: uni01E2	Contours detected: 3	Expected: 4

	- Glyph name: uni01E4	Contours detected: 1	Expected: 2

	- Glyph name: Gcaron	Contours detected: 2	Expected: 3or4

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F4	Contours detected: 2	Expected: 3

	- Glyph name: AEacute	Contours detected: 3	Expected: 4

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0204	Contours detected: 3	Expected: 4

	- Glyph name: uni0206	Contours detected: 2	Expected: 3

	- Glyph name: uni0210	Contours detected: 4	Expected: 3

	- Glyph name: uni0212	Contours detected: 3	Expected: 2

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni0246	Contours detected: 1	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 2	Expected: 1

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: pi	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 0	Expected: 3or5

	- Glyph name: uni1E02	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 3	Expected: 4

	- Glyph name: uni1E16	Contours detected: 3	Expected: 4

	- Glyph name: uni1E20	Contours detected: 2	Expected: 3or4

	- Glyph name: uni1E5A	Contours detected: 3	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1EB8	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBA	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBE	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ECA	Contours detected: 2	Expected: 3

	- Glyph name: uni1EDA	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDC	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDE	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni2016	Contours detected: 0	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 3	Expected: 2

	- Glyph name: quotedblright	Contours detected: 3	Expected: 2

	- Glyph name: quotedblbase	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 0	Expected: 6or7

	- Glyph name: minute	Contours detected: 0	Expected: 1

	- Glyph name: second	Contours detected: 0	Expected: 2

	- Glyph name: fraction	Contours detected: 0	Expected: 1

	- Glyph name: colonmonetary	Contours detected: 0	Expected: 1or3

	- Glyph name: uni20A6	Contours detected: 0	Expected: 1, 3or5

	- Glyph name: uni20A9	Contours detected: 0	Expected: 1, 3, 4or7

	- Glyph name: uni20AA	Contours detected: 0	Expected: 2

	- Glyph name: dong	Contours detected: 0	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 0	Expected: 1

	- Glyph name: uni20B1	Contours detected: 0	Expected: 1, 2or4

	- Glyph name: uni20B2	Contours detected: 0	Expected: 1, 2or3

	- Glyph name: uni20B4	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B5	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B8	Contours detected: 0	Expected: 2

	- Glyph name: uni20B9	Contours detected: 0	Expected: 1

	- Glyph name: uni20BA	Contours detected: 0	Expected: 1

	- Glyph name: uni20BC	Contours detected: 0	Expected: 1

	- Glyph name: uni20BD	Contours detected: 0	Expected: 2

	- Glyph name: uni20BF	Contours detected: 0	Expected: 3

	- Glyph name: uni2113	Contours detected: 0	Expected: 2

	- Glyph name: estimated	Contours detected: 0	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1or3

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

	- Glyph name: partialdiff	Contours detected: 0	Expected: 2

	- Glyph name: emptyset	Contours detected: 0	Expected: 3

	- Glyph name: uni2206	Contours detected: 0	Expected: 2

	- Glyph name: product	Contours detected: 0	Expected: 1

	- Glyph name: summation	Contours detected: 0	Expected: 1

	- Glyph name: radical	Contours detected: 0	Expected: 1

	- Glyph name: infinity	Contours detected: 0	Expected: 3

	- Glyph name: integral	Contours detected: 0	Expected: 1

	- Glyph name: approxequal	Contours detected: 0	Expected: 2

	- Glyph name: notequal	Contours detected: 0	Expected: 1

	- Glyph name: lessequal	Contours detected: 0	Expected: 2

	- Glyph name: greaterequal	Contours detected: 0	Expected: 2

	- Glyph name: uni25CC	Contours detected: 0	Expected: 16or12

	- Glyph name: uni27E8	Contours detected: 0	Expected: 1

	- Glyph name: uni27E9	Contours detected: 0	Expected: 1

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: approxequal	Contours detected: 0	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: colonmonetary	Contours detected: 0	Expected: 1or3

	- Glyph name: currency	Contours detected: 0	Expected: 2

	- Glyph name: dong	Contours detected: 0	Expected: 3or4

	- Glyph name: emptyset	Contours detected: 0	Expected: 3

	- Glyph name: estimated	Contours detected: 0	Expected: 2

	- Glyph name: fraction	Contours detected: 0	Expected: 1

	- Glyph name: greaterequal	Contours detected: 0	Expected: 2

	- Glyph name: infinity	Contours detected: 0	Expected: 3

	- Glyph name: integral	Contours detected: 0	Expected: 1

	- Glyph name: kgreenlandic	Contours detected: 0	Expected: 1or2

	- Glyph name: lessequal	Contours detected: 0	Expected: 2

	- Glyph name: logicalnot	Contours detected: 0	Expected: 1

	- Glyph name: notequal	Contours detected: 0	Expected: 1

	- Glyph name: onehalf	Contours detected: 0	Expected: 3

	- Glyph name: onequarter	Contours detected: 0	Expected: 3or4

	- Glyph name: partialdiff	Contours detected: 0	Expected: 2

	- Glyph name: perthousand	Contours detected: 0	Expected: 6or7

	- Glyph name: pi	Contours detected: 0	Expected: 1

	- Glyph name: plusminus	Contours detected: 0	Expected: 1or2

	- Glyph name: product	Contours detected: 0	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 3	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 3	Expected: 2

	- Glyph name: quotedblright	Contours detected: 3	Expected: 2

	- Glyph name: radical	Contours detected: 0	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: summation	Contours detected: 0	Expected: 1

	- Glyph name: threequarters	Contours detected: 0	Expected: 3or4

	- Glyph name: uni00B5	Contours detected: 0	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01C8	Contours detected: 1	Expected: 3

	- Glyph name: uni01CB	Contours detected: 1	Expected: 3

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0244	Contours detected: 1	Expected: 2

	- Glyph name: uni0246	Contours detected: 1	Expected: 3

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 0	Expected: 3or5

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni2016	Contours detected: 0	Expected: 2

	- Glyph name: uni20A6	Contours detected: 0	Expected: 1, 3or5

	- Glyph name: uni20A9	Contours detected: 0	Expected: 1, 3, 4or7

	- Glyph name: uni20AA	Contours detected: 0	Expected: 2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 0	Expected: 1

	- Glyph name: uni20B1	Contours detected: 0	Expected: 1, 2or4

	- Glyph name: uni20B2	Contours detected: 0	Expected: 1, 2or3

	- Glyph name: uni20B4	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B5	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B8	Contours detected: 0	Expected: 2

	- Glyph name: uni20B9	Contours detected: 0	Expected: 1

	- Glyph name: uni20BA	Contours detected: 0	Expected: 1

	- Glyph name: uni20BC	Contours detected: 0	Expected: 1

	- Glyph name: uni20BD	Contours detected: 0	Expected: 2

	- Glyph name: uni20BF	Contours detected: 0	Expected: 3

	- Glyph name: uni2113	Contours detected: 0	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uni2206	Contours detected: 0	Expected: 2

	- Glyph name: uni25CC	Contours detected: 0	Expected: 16or12

	- Glyph name: uni27E8	Contours detected: 0	Expected: 1

	- Glyph name: uni27E9	Contours detected: 0	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 426:
minus, multiply, plus, equal, divide

Width = 388:
less

Width = 406:
greater
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** Tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lozenge (U+25CA): L<<136.0,376.0>--<148.0,359.0>> -> L<<148.0,359.0>--<287.0,154.0>>

	* lozenge (U+25CA): L<<287.0,154.0>--<299.0,170.0>> -> L<<299.0,170.0>--<438.0,376.0>>

	* lozenge (U+25CA): L<<288.0,587.0>--<276.0,573.0>> -> L<<276.0,573.0>--<136.0,376.0>>

	* lozenge (U+25CA): L<<438.0,376.0>--<427.0,391.0>> -> L<<427.0,391.0>--<288.0,587.0>>

	* uni018F (U+018F): L<<47.0,728.0>--<174.0,730.0>> -> L<<174.0,730.0>--<418.0,730.0>>

	* uni018F (U+0259): L<<47.0,728.0>--<174.0,730.0>> -> L<<174.0,730.0>--<418.0,730.0>>

	* uni029D (U+029D): L<<222.0,-250.0>--<118.0,-250.0>> -> L<<118.0,-250.0>--<114.0,-250.0>>

	* uni029D (U+029D): L<<70.0,-202.0>--<113.0,-202.0>> -> L<<113.0,-202.0>--<151.0,-201.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<784.0,1.0>--<352.0,0.0>>

	* AE (U+00E6): L<<784.0,1.0>--<352.0,0.0>>

	* AEacute (U+01FC): L<<784.0,1.0>--<352.0,0.0>>

	* AEacute (U+01FD): L<<784.0,1.0>--<352.0,0.0>>

	* OE (U+0152): L<<789.0,1.0>--<179.0,0.0>>

	* OE (U+0153): L<<789.0,1.0>--<179.0,0.0>>

	* comma (U+002C): L<<18.0,57.0>--<19.0,202.0>>

	* five (U+0035): L<<25.0,305.0>--<26.0,785.0>>

	* percent (U+0025): L<<342.0,367.0>--<541.0,368.0>>

	* percent (U+0025): L<<39.0,800.0>--<238.0,801.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<285.0,57.0>--<286.0,202.0>>

	* quotedblleft (U+201C): L<<230.0,720.0>--<229.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<285.0,717.0>--<286.0,862.0>>

	* quoteleft (U+2018): L<<237.0,720.0>--<236.0,575.0>>

	* quoteright (U+2019): L<<25.0,717.0>--<26.0,862.0>>

	* quotesinglbase (U+201A): L<<25.0,57.0>--<26.0,202.0>>

	* semicolon (U+003B): L<<18.0,57.0>--<19.0,202.0>>

	* two (U+0032): L<<26.0,15.0>--<25.0,354.0>>

	* uni00B2 (U+00B2): L<<26.0,15.0>--<25.0,354.0>>

	* uni018B (U+018B): L<<10.0,799.0>--<507.0,801.0>>

	* uni018B (U+018C): L<<10.0,799.0>--<507.0,801.0>>

	* uni0193 (U+0193): L<<167.0,800.0>--<404.0,799.0>>

	* uni0193 (U+0193): L<<304.0,507.0>--<556.0,506.0>>

	* uni0193 (U+0193): L<<440.0,-1.0>--<147.0,0.0>>

	* uni0193 (U+0193): L<<536.0,549.0>--<269.0,550.0>>

	* uni0193 (U+0193): L<<571.0,491.0>--<569.0,121.0>>

	* uni0193 (U+0260): L<<167.0,800.0>--<404.0,799.0>>

	* uni0193 (U+0260): L<<304.0,507.0>--<556.0,506.0>>

	* uni0193 (U+0260): L<<440.0,-1.0>--<147.0,0.0>>

	* uni0193 (U+0260): L<<536.0,549.0>--<269.0,550.0>>

	* uni0193 (U+0260): L<<571.0,491.0>--<569.0,121.0>>

	* uni01C7 (U+01C7): L<<341.0,1.0>--<36.0,0.0>>

	* uni01C7 (U+01C9): L<<341.0,1.0>--<36.0,0.0>>

	* uni01C8 (U+01C8): L<<352.0,1.0>--<36.0,0.0>>

	* uni01E2 (U+01E2): L<<784.0,1.0>--<352.0,0.0>>

	* uni01E2 (U+01E3): L<<784.0,1.0>--<352.0,0.0>>

	* uni01E4 (U+01E4): L<<167.0,800.0>--<536.0,799.0>>

	* uni01E4 (U+01E4): L<<430.0,-1.0>--<147.0,0.0>>

	* uni01E4 (U+01E4): L<<536.0,559.0>--<259.0,560.0>>

	* uni01E4 (U+01E4): L<<560.0,286.0>--<559.0,121.0>>

	* uni01E4 (U+01E5): L<<167.0,800.0>--<536.0,799.0>>

	* uni01E4 (U+01E5): L<<430.0,-1.0>--<147.0,0.0>>

	* uni01E4 (U+01E5): L<<536.0,559.0>--<259.0,560.0>>

	* uni01E4 (U+01E5): L<<560.0,286.0>--<559.0,121.0>>

	* uni0241 (U+0241): L<<43.0,15.0>--<42.0,344.0>>

	* uni0242 (U+0242): L<<26.0,13.0>--<25.0,205.0>>

	* uni0294 (U+0294): L<<26.0,15.0>--<25.0,344.0>>

	* uni0295 (U+0295): L<<485.0,344.0>--<484.0,15.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,862.0>>

	* uni0312 (U+0312): L<<218.0,1011.0>--<217.0,866.0>>

	* uni0313 (U+0313): L<<18.0,1004.0>--<19.0,1149.0>>

	* uni2075 (U+2075): L<<25.0,305.0>--<26.0,785.0>>

	* uni2082 (U+2082): L<<26.0,15.0>--<25.0,354.0>>

	* uni2085 (U+2085): L<<25.0,305.0>--<26.0,785.0>>

	* uni2154 (U+2154): L<<26.0,15.0>--<25.0,354.0>>

	* uni2C64 (U+027D): L<<269.0,223.0>--<266.0,-146.0>>

	* uni2C64 (U+2C64): L<<269.0,223.0>--<266.0,-146.0>>

	* uni2C72 (U+2C72): L<<12.0,171.0>--<13.0,785.0>>

	* uni2C72 (U+2C72): L<<843.0,679.0>--<844.0,171.0>>

	* uni2C72 (U+2C73): L<<12.0,171.0>--<13.0,785.0>>

	* uni2C72 (U+2C73): L<<843.0,679.0>--<844.0,171.0>>

	* zero (U+0030): L<<58.0,799.0>--<558.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[25] Jaro-72ptRegular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


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
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1271, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 410, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 7, 'y': 0}
	* {'glyph': 'quotedblright', 'component': 'comma', 'x': 7, 'y': 660} and {'glyph': 'uni02EE', 'component': 'comma', 'x': 7, 'y': 660} [code: found-duplicates]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030D

	- uni030F

	- uni0310

	- uni0311

	- uni0312

	- uni0313

	- uni031B

	- uni0320

	- uni0324

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0329

	- uni032D

	- uni032E

	- uni032F

	- uni0330

	- uni0331

	- uni0332

	- uni0334

	- uni0335

	- uni1DC7

	- uni1DCA [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- M.alt

	- N.alt

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- nine.ALT

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.ALT

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni006A0301

	- uni0181.alt

	- uni01A4.001

	- uni01A4.002

	- uni01A4.003

	- uni01A4.004

	- uni01A4.005

	- uni03010304.001

	- uni03060303.case.001

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: currency	Contours detected: 0	Expected: 2

	- Glyph name: yen	Contours detected: 4	Expected: 1or2

	- Glyph name: logicalnot	Contours detected: 0	Expected: 1

	- Glyph name: plusminus	Contours detected: 0	Expected: 1or2

	- Glyph name: uni00B5	Contours detected: 0	Expected: 1

	- Glyph name: onequarter	Contours detected: 0	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 0	Expected: 3

	- Glyph name: threequarters	Contours detected: 0	Expected: 3or4

	- Glyph name: AE	Contours detected: 2	Expected: 3

	- Glyph name: Egrave	Contours detected: 2	Expected: 3

	- Glyph name: Eacute	Contours detected: 2	Expected: 3

	- Glyph name: Ecircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Edieresis	Contours detected: 3	Expected: 4

	- Glyph name: Oslash	Contours detected: 2	Expected: 3

	- Glyph name: Aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 2	Expected: 3

	- Glyph name: Ebreve	Contours detected: 2	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 2	Expected: 3

	- Glyph name: Ecaron	Contours detected: 2	Expected: 3

	- Glyph name: Gcircumflex	Contours detected: 2	Expected: 3or4

	- Glyph name: Gbreve	Contours detected: 2	Expected: 3or4

	- Glyph name: Gdotaccent	Contours detected: 2	Expected: 3or4

	- Glyph name: uni0122	Contours detected: 2	Expected: 3or4

	- Glyph name: Hbar	Contours detected: 2	Expected: 1

	- Glyph name: IJ	Contours detected: 2	Expected: 3or4

	- Glyph name: kgreenlandic	Contours detected: 0	Expected: 1or2

	- Glyph name: OE	Contours detected: 2	Expected: 3

	- Glyph name: Racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 3	Expected: 2

	- Glyph name: Rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: Ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01C8	Contours detected: 1	Expected: 3

	- Glyph name: uni01C7	Contours detected: 2	Expected: 3

	- Glyph name: uni01CB	Contours detected: 1	Expected: 3

	- Glyph name: uni01CA	Contours detected: 2	Expected: 3

	- Glyph name: uni018E	Contours detected: 1	Expected: 2

	- Glyph name: uni01E2	Contours detected: 3	Expected: 4

	- Glyph name: uni01E4	Contours detected: 1	Expected: 2

	- Glyph name: Gcaron	Contours detected: 2	Expected: 3or4

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F4	Contours detected: 2	Expected: 3

	- Glyph name: AEacute	Contours detected: 3	Expected: 4

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0204	Contours detected: 3	Expected: 4

	- Glyph name: uni0206	Contours detected: 2	Expected: 3

	- Glyph name: uni0210	Contours detected: 4	Expected: 3

	- Glyph name: uni0212	Contours detected: 3	Expected: 2

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni0246	Contours detected: 1	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 2	Expected: 1

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: pi	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 0	Expected: 3or5

	- Glyph name: uni1E02	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 3	Expected: 4

	- Glyph name: uni1E16	Contours detected: 3	Expected: 4

	- Glyph name: uni1E20	Contours detected: 2	Expected: 3or4

	- Glyph name: uni1E5A	Contours detected: 3	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1EB8	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBA	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 2	Expected: 3

	- Glyph name: uni1EBE	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EC6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ECA	Contours detected: 2	Expected: 3

	- Glyph name: uni1EDA	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDC	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDE	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni2016	Contours detected: 0	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 3	Expected: 2

	- Glyph name: quotedblright	Contours detected: 3	Expected: 2

	- Glyph name: quotedblbase	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 0	Expected: 6or7

	- Glyph name: minute	Contours detected: 0	Expected: 1

	- Glyph name: second	Contours detected: 0	Expected: 2

	- Glyph name: fraction	Contours detected: 0	Expected: 1

	- Glyph name: colonmonetary	Contours detected: 0	Expected: 1or3

	- Glyph name: uni20A6	Contours detected: 0	Expected: 1, 3or5

	- Glyph name: uni20A9	Contours detected: 0	Expected: 1, 3, 4or7

	- Glyph name: uni20AA	Contours detected: 0	Expected: 2

	- Glyph name: dong	Contours detected: 0	Expected: 3or4

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 0	Expected: 1

	- Glyph name: uni20B1	Contours detected: 0	Expected: 1, 2or4

	- Glyph name: uni20B2	Contours detected: 0	Expected: 1, 2or3

	- Glyph name: uni20B4	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B5	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B8	Contours detected: 0	Expected: 2

	- Glyph name: uni20B9	Contours detected: 0	Expected: 1

	- Glyph name: uni20BA	Contours detected: 0	Expected: 1

	- Glyph name: uni20BC	Contours detected: 0	Expected: 1

	- Glyph name: uni20BD	Contours detected: 0	Expected: 2

	- Glyph name: uni20BF	Contours detected: 0	Expected: 3

	- Glyph name: uni2113	Contours detected: 0	Expected: 2

	- Glyph name: estimated	Contours detected: 0	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1or3

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

	- Glyph name: partialdiff	Contours detected: 0	Expected: 2

	- Glyph name: emptyset	Contours detected: 0	Expected: 3

	- Glyph name: uni2206	Contours detected: 0	Expected: 2

	- Glyph name: product	Contours detected: 0	Expected: 1

	- Glyph name: summation	Contours detected: 0	Expected: 1

	- Glyph name: radical	Contours detected: 0	Expected: 1

	- Glyph name: infinity	Contours detected: 0	Expected: 3

	- Glyph name: integral	Contours detected: 0	Expected: 1

	- Glyph name: approxequal	Contours detected: 0	Expected: 2

	- Glyph name: notequal	Contours detected: 0	Expected: 1

	- Glyph name: lessequal	Contours detected: 0	Expected: 2

	- Glyph name: greaterequal	Contours detected: 0	Expected: 2

	- Glyph name: uni25CC	Contours detected: 0	Expected: 16or12

	- Glyph name: uni27E8	Contours detected: 0	Expected: 1

	- Glyph name: uni27E9	Contours detected: 0	Expected: 1

	- Glyph name: Euro	Contours detected: 4	Expected: 1or2

	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: approxequal	Contours detected: 0	Expected: 2

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 3	Expected: 1

	- Glyph name: braceright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 4	Expected: 1or2

	- Glyph name: colonmonetary	Contours detected: 0	Expected: 1or3

	- Glyph name: currency	Contours detected: 0	Expected: 2

	- Glyph name: dong	Contours detected: 0	Expected: 3or4

	- Glyph name: emptyset	Contours detected: 0	Expected: 3

	- Glyph name: estimated	Contours detected: 0	Expected: 2

	- Glyph name: fraction	Contours detected: 0	Expected: 1

	- Glyph name: greaterequal	Contours detected: 0	Expected: 2

	- Glyph name: infinity	Contours detected: 0	Expected: 3

	- Glyph name: integral	Contours detected: 0	Expected: 1

	- Glyph name: kgreenlandic	Contours detected: 0	Expected: 1or2

	- Glyph name: lessequal	Contours detected: 0	Expected: 2

	- Glyph name: logicalnot	Contours detected: 0	Expected: 1

	- Glyph name: notequal	Contours detected: 0	Expected: 1

	- Glyph name: onehalf	Contours detected: 0	Expected: 3

	- Glyph name: onequarter	Contours detected: 0	Expected: 3or4

	- Glyph name: partialdiff	Contours detected: 0	Expected: 2

	- Glyph name: perthousand	Contours detected: 0	Expected: 6or7

	- Glyph name: pi	Contours detected: 0	Expected: 1

	- Glyph name: plusminus	Contours detected: 0	Expected: 1or2

	- Glyph name: product	Contours detected: 0	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 3	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 3	Expected: 2

	- Glyph name: quotedblright	Contours detected: 3	Expected: 2

	- Glyph name: radical	Contours detected: 0	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: summation	Contours detected: 0	Expected: 1

	- Glyph name: threequarters	Contours detected: 0	Expected: 3or4

	- Glyph name: uni00B5	Contours detected: 0	Expected: 1

	- Glyph name: uni019F	Contours detected: 2	Expected: 3

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01C2	Contours detected: 3	Expected: 1

	- Glyph name: uni01C8	Contours detected: 1	Expected: 3

	- Glyph name: uni01CB	Contours detected: 1	Expected: 3

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni023E	Contours detected: 1	Expected: 2

	- Glyph name: uni0244	Contours detected: 1	Expected: 2

	- Glyph name: uni0246	Contours detected: 1	Expected: 3

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 0	Expected: 3or5

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni2016	Contours detected: 0	Expected: 2

	- Glyph name: uni20A6	Contours detected: 0	Expected: 1, 3or5

	- Glyph name: uni20A9	Contours detected: 0	Expected: 1, 3, 4or7

	- Glyph name: uni20AA	Contours detected: 0	Expected: 2

	- Glyph name: uni20AD	Contours detected: 3	Expected: 1

	- Glyph name: uni20AE	Contours detected: 0	Expected: 1

	- Glyph name: uni20B1	Contours detected: 0	Expected: 1, 2or4

	- Glyph name: uni20B2	Contours detected: 0	Expected: 1, 2or3

	- Glyph name: uni20B4	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B5	Contours detected: 0	Expected: 1or2

	- Glyph name: uni20B8	Contours detected: 0	Expected: 2

	- Glyph name: uni20B9	Contours detected: 0	Expected: 1

	- Glyph name: uni20BA	Contours detected: 0	Expected: 1

	- Glyph name: uni20BC	Contours detected: 0	Expected: 1

	- Glyph name: uni20BD	Contours detected: 0	Expected: 2

	- Glyph name: uni20BF	Contours detected: 0	Expected: 3

	- Glyph name: uni2113	Contours detected: 0	Expected: 2

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uni2206	Contours detected: 0	Expected: 2

	- Glyph name: uni25CC	Contours detected: 0	Expected: 16or12

	- Glyph name: uni27E8	Contours detected: 0	Expected: 1

	- Glyph name: uni27E9	Contours detected: 0	Expected: 1

	- Glyph name: yen	Contours detected: 4	Expected: 1or2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 426:
minus, multiply, plus, equal, divide

Width = 377:
less

Width = 406:
greater
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** Tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lozenge (U+25CA): L<<154.0,376.0>--<163.0,362.0>> -> L<<163.0,362.0>--<287.0,180.0>>

	* lozenge (U+25CA): L<<287.0,180.0>--<296.0,192.0>> -> L<<296.0,192.0>--<420.0,376.0>>

	* lozenge (U+25CA): L<<288.0,562.0>--<279.0,551.0>> -> L<<279.0,551.0>--<154.0,376.0>>

	* lozenge (U+25CA): L<<420.0,376.0>--<412.0,387.0>> -> L<<412.0,387.0>--<288.0,562.0>>

	* uni018F (U+018F): L<<29.0,728.0>--<156.0,730.0>> -> L<<156.0,730.0>--<400.0,730.0>>

	* uni018F (U+0259): L<<29.0,728.0>--<156.0,730.0>> -> L<<156.0,730.0>--<400.0,730.0>>

	* uni029D (U+029D): L<<222.0,-250.0>--<118.0,-250.0>> -> L<<118.0,-250.0>--<114.0,-250.0>>

	* uni029D (U+029D): L<<70.0,-202.0>--<113.0,-202.0>> -> L<<113.0,-202.0>--<151.0,-201.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Eng (U+014A): L<<299.0,1.0>--<338.0,0.0>>/B<<338.0,0.0>-<325.0,2.0>-<325.0,15.0>> = 7.277361548169348

	* Eng (U+014B): L<<299.0,1.0>--<338.0,0.0>>/B<<338.0,0.0>-<325.0,2.0>-<325.0,15.0>> = 7.277361548169348 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<766.0,1.0>--<334.0,0.0>>

	* AE (U+00E6): L<<766.0,1.0>--<334.0,0.0>>

	* AEacute (U+01FC): L<<766.0,1.0>--<334.0,0.0>>

	* AEacute (U+01FD): L<<766.0,1.0>--<334.0,0.0>>

	* OE (U+0152): L<<771.0,1.0>--<161.0,0.0>>

	* OE (U+0153): L<<771.0,1.0>--<161.0,0.0>>

	* comma (U+002C): L<<18.0,57.0>--<19.0,202.0>>

	* five (U+0035): L<<25.0,305.0>--<26.0,785.0>>

	* percent (U+0025): L<<342.0,367.0>--<541.0,368.0>>

	* percent (U+0025): L<<39.0,800.0>--<238.0,801.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<25.0,57.0>--<26.0,202.0>>

	* quotedblbase (U+201E): L<<285.0,57.0>--<286.0,202.0>>

	* quotedblleft (U+201C): L<<230.0,720.0>--<229.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblleft (U+201C): L<<490.0,720.0>--<489.0,575.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<25.0,717.0>--<26.0,862.0>>

	* quotedblright (U+201D): L<<285.0,717.0>--<286.0,862.0>>

	* quoteleft (U+2018): L<<237.0,720.0>--<236.0,575.0>>

	* quoteright (U+2019): L<<25.0,717.0>--<26.0,862.0>>

	* quotesinglbase (U+201A): L<<25.0,57.0>--<26.0,202.0>>

	* semicolon (U+003B): L<<18.0,57.0>--<19.0,202.0>>

	* two (U+0032): L<<26.0,15.0>--<25.0,354.0>>

	* uni00B2 (U+00B2): L<<26.0,15.0>--<25.0,354.0>>

	* uni018B (U+018B): L<<10.0,799.0>--<507.0,801.0>>

	* uni018B (U+018C): L<<10.0,799.0>--<507.0,801.0>>

	* uni0193 (U+0193): L<<167.0,800.0>--<404.0,799.0>>

	* uni0193 (U+0193): L<<304.0,507.0>--<556.0,506.0>>

	* uni0193 (U+0193): L<<440.0,-1.0>--<147.0,0.0>>

	* uni0193 (U+0193): L<<536.0,549.0>--<269.0,550.0>>

	* uni0193 (U+0193): L<<571.0,491.0>--<569.0,121.0>>

	* uni0193 (U+0260): L<<167.0,800.0>--<404.0,799.0>>

	* uni0193 (U+0260): L<<304.0,507.0>--<556.0,506.0>>

	* uni0193 (U+0260): L<<440.0,-1.0>--<147.0,0.0>>

	* uni0193 (U+0260): L<<536.0,549.0>--<269.0,550.0>>

	* uni0193 (U+0260): L<<571.0,491.0>--<569.0,121.0>>

	* uni01C7 (U+01C7): L<<341.0,1.0>--<36.0,0.0>>

	* uni01C7 (U+01C9): L<<341.0,1.0>--<36.0,0.0>>

	* uni01C8 (U+01C8): L<<352.0,1.0>--<36.0,0.0>>

	* uni01E2 (U+01E2): L<<766.0,1.0>--<334.0,0.0>>

	* uni01E2 (U+01E3): L<<766.0,1.0>--<334.0,0.0>>

	* uni01E4 (U+01E4): L<<167.0,800.0>--<536.0,799.0>>

	* uni01E4 (U+01E4): L<<430.0,-1.0>--<147.0,0.0>>

	* uni01E4 (U+01E4): L<<536.0,559.0>--<259.0,560.0>>

	* uni01E4 (U+01E4): L<<560.0,286.0>--<559.0,121.0>>

	* uni01E4 (U+01E5): L<<167.0,800.0>--<536.0,799.0>>

	* uni01E4 (U+01E5): L<<430.0,-1.0>--<147.0,0.0>>

	* uni01E4 (U+01E5): L<<536.0,559.0>--<259.0,560.0>>

	* uni01E4 (U+01E5): L<<560.0,286.0>--<559.0,121.0>>

	* uni0241 (U+0241): L<<26.0,15.0>--<25.0,344.0>>

	* uni0242 (U+0242): L<<26.0,13.0>--<25.0,205.0>>

	* uni0294 (U+0294): L<<26.0,15.0>--<25.0,344.0>>

	* uni0295 (U+0295): L<<434.0,344.0>--<433.0,15.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<25.0,717.0>--<26.0,862.0>>

	* uni02EE (U+02EE): L<<285.0,717.0>--<286.0,862.0>>

	* uni0312 (U+0312): L<<218.0,1011.0>--<217.0,866.0>>

	* uni0313 (U+0313): L<<18.0,1004.0>--<19.0,1149.0>>

	* uni2075 (U+2075): L<<25.0,305.0>--<26.0,785.0>>

	* uni2082 (U+2082): L<<26.0,15.0>--<25.0,354.0>>

	* uni2085 (U+2085): L<<25.0,305.0>--<26.0,785.0>>

	* uni2154 (U+2154): L<<26.0,15.0>--<25.0,354.0>>

	* uni2C64 (U+027D): L<<269.0,223.0>--<266.0,-146.0>>

	* uni2C64 (U+2C64): L<<269.0,223.0>--<266.0,-146.0>>

	* uni2C72 (U+2C72): L<<12.0,171.0>--<13.0,785.0>>

	* uni2C72 (U+2C72): L<<843.0,679.0>--<844.0,171.0>>

	* uni2C72 (U+2C73): L<<12.0,171.0>--<13.0,785.0>>

	* uni2C72 (U+2C73): L<<843.0,679.0>--<844.0,171.0>>

	* zero (U+0030): L<<40.0,799.0>--<540.0,801.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 9 | 21 | 43 | 379 | 16 | 248 | 0 |
| 1% | 3% | 6% | 53% | 2% | 35% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
