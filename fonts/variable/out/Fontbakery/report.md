## FontBakery report

fontbakery version: 0.11.2

<h2>Experimental checks</h2><p>These won't break the CI job for now, but will become effective after some time if nobody raises any concern.</p><details><summary><b>[1] Jaro[opsz].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure the font supports case swapping for all its glyphs. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/case_mapping">com.google.fonts/check/case_mapping</a>)</summary><div>


* 🔥 **FAIL** The following glyphs lack their case-swapping counterparts:

| Glyph present in the font | Missing case-swapping counterpart |
| :--- | :--- |
| U+0114: LATIN CAPITAL LETTER E WITH BREVE | U+0115: LATIN SMALL LETTER E WITH BREVE |
| U+012C: LATIN CAPITAL LETTER I WITH BREVE | U+012D: LATIN SMALL LETTER I WITH BREVE |
| U+013F: LATIN CAPITAL LETTER L WITH MIDDLE DOT | U+0140: LATIN SMALL LETTER L WITH MIDDLE DOT |
| U+014E: LATIN CAPITAL LETTER O WITH BREVE | U+014F: LATIN SMALL LETTER O WITH BREVE |
| U+018B: LATIN CAPITAL LETTER D WITH TOPBAR | U+018C: LATIN SMALL LETTER D WITH TOPBAR |
| U+01C4: LATIN CAPITAL LETTER DZ WITH CARON | U+01C6: LATIN SMALL LETTER DZ WITH CARON |
| U+01C7: LATIN CAPITAL LETTER LJ | U+01C9: LATIN SMALL LETTER LJ |
| U+01CA: LATIN CAPITAL LETTER NJ | U+01CC: LATIN SMALL LETTER NJ |
| U+01FA: LATIN CAPITAL LETTER A WITH RING ABOVE AND ACUTE | U+01FB: LATIN SMALL LETTER A WITH RING ABOVE AND ACUTE |
| U+01FC: LATIN CAPITAL LETTER AE WITH ACUTE | U+01FD: LATIN SMALL LETTER AE WITH ACUTE |
| U+021C: LATIN CAPITAL LETTER YOGH | U+021D: LATIN SMALL LETTER YOGH |
| U+03BB: GREEK SMALL LETTER LAMDA | U+039B: GREEK CAPITAL LETTER LAMDA |
| U+03C7: GREEK SMALL LETTER CHI | U+03A7: GREEK CAPITAL LETTER CHI |
| U+A792: LATIN CAPITAL LETTER C WITH BAR | U+A793: LATIN SMALL LETTER C WITH BAR |

 [code: missing-case-counterparts]
</div></details><br></div></details><h2>All other checks</h2><details><summary><b>[1] Family checks</b></summary><div><details><summary>ℹ <b>INFO:</b> Check axis ordering on the STAT table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/axis_order">com.google.fonts/check/STAT/axis_order</a>)</summary><div>


* ℹ **INFO** None of the fonts lack a STAT table.

	And these are the most common STAT axis orderings:
	('opsz-wght', 1) [code: summary]
</div></details><br></div></details><details><summary><b>[19] Jaro[opsz].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_African glyphset:

| Language | FAIL messages |
| :--- | :--- |
| mua_Latn (Mundang) | The locl feature did not affect Eng |
| gng_Latn (Ngangam) | The locl feature did not affect Eng |
| kyf_Latn (Kouya) | The locl feature did not affect Eng |
| bsc_Latn (Bassari) | The locl feature did not affect Eng |
| lmp_Latn (Limbum) | The locl feature did not affect Eng |
| nhu_Latn (Noone) | The locl feature did not affect Eng |
| dop_Latn (Lukpa) | The locl feature did not affect Eng |
| nus_Latn (Nuer) | The locl feature did not affect Eng |
| bcw_Latn (Bana) | The locl feature did not affect Eng |
| sxw_Latn (Saxwe Gbe) | The locl feature did not affect Eng |
| toq_Latn (Toposa) | The locl feature did not affect Eng |
| kdh_Latn (Tem) | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni028A |
|  ^  | The locl feature did not affect Eng |
| ahs_Latn (Ashe) | The locl feature did not affect Eng |
| ekm_Latn (Elip) | The locl feature did not affect Eng |
| ffm_Latn (Maasina Fulfulde) | The locl feature did not affect Eng |
| tpm_Latn (Tampulma) | The locl feature did not affect Eng |
| wan_Latn (Wan) | The locl feature did not affect Eng |
| moa_Latn (Mwan) | The locl feature did not affect Eng |
| mgo_Latn (Metaʼ) | The locl feature did not affect Eng |
| lob_Latn (Lobi) | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
| dnj_Latn_LR (Dan) | Shaper didn't attach uni0302 to uniA78D |
|  ^  | Shaper didn't attach tildecomb to uniA78D |
|  ^  | Shaper didn't attach gravecomb to uniA78D |
|  ^  | Shaper didn't attach acutecomb to uniA78D |
| xsm_Latn_BF (Kasem) | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
| dyo_Latn (Jola-Fonyi) | The locl feature did not affect Eng |
| kvf_Latn (Kabalai) | The locl feature did not affect Eng |
| tuq_Latn (Tedaga) | The locl feature did not affect Eng |
| dow_Latn (Doyayo) | The locl feature did not affect Eng |
| tem_Latn (Timne) | The locl feature did not affect Eng |
| fuh_Latn (Fulfulde, Western Niger) | The locl feature did not affect Eng |
| lok_Latn (Loko) | The locl feature did not affect Eng |
| adj_Latn (Adioukrou) | The locl feature did not affect Eng |
| nnw_Latn (Southern Nuni) | The locl feature did not affect Eng |
| byv_Latn (Medumba) | Shaper didn't attach uni0302 to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni0251 |
|  ^  | Shaper didn't attach gravecomb to uni0251 |
| tnr_Latn (Ménik) | The locl feature did not affect Eng |
| mhi_Latn (Ma’di) | The locl feature did not affect Eng |
| ikx_Latn (Ik) | The locl feature did not affect Eng |
| nmg_Latn (Kwasio) | The locl feature did not affect Eng |
| lig_Latn (Ligbi) | The locl feature did not affect Eng |
| ewo_Latn (Ewondo) | The locl feature did not affect Eng |
| god_Latn (Godié) | The locl feature did not affect Eng |
| gna_Latn (Kaansa) | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach uni030C to uni0196 |
|  ^  | Shaper didn't attach uni0302 to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
| ted_Latn (Krumen, Tepo) | The locl feature did not affect Eng |
| bib_Latn (Bissa) | The locl feature did not affect Eng |
| mmu_Latn (Mmaala) | The locl feature did not affect Eng |
| dyi_Latn (Sénoufo, Djimini) | The locl feature did not affect Eng |
| anv_Latn (Denya) | The locl feature did not affect Eng |
| bim_Latn (Bimoba) | The locl feature did not affect Eng |
| sok_Latn (Sokoro) | The locl feature did not affect Eng |
| dts_Latn (Dogon, Toro So) | The locl feature did not affect Eng |
| bza_Latn (Bandi) | The locl feature did not affect Eng |
| nym_Latn (Nyamwezi) | The locl feature did not affect Eng |
| dje_Latn (Zarma) | The locl feature did not affect Eng |
| mcp_Latn (Makaa) | The locl feature did not affect Eng |
| mbu_Latn (Mbula-Bwazza) | The locl feature did not affect Eng |
| hag_Latn (Hanga) | The locl feature did not affect Eng |
| kst_Latn (Winyé) | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
| xrb_Latn (Karaboro, Eastern) | The locl feature did not affect Eng |
| sig_Latn (Paasaal) | The locl feature did not affect Eng |
| acd_Latn (Gikyode) | The locl feature did not affect Eng |
| spp_Latn (Sénoufo, Supyire) | The locl feature did not affect Eng |
| gud_Latn (Dida, Yocoboué) | The locl feature did not affect Eng |
| naw_Latn (Nawuri) | The locl feature did not affect Eng |
| ade_Latn (Adele) | The locl feature did not affect Eng |
| yam_Latn (Yamba) | The locl feature did not affect Eng |
| krs_Latn (Gbaya (Sudan)) | The locl feature did not affect Eng |
| knp_Latn (Kwanja) | The locl feature did not affect Eng |
| xon_Latn (Konkomba) | The locl feature did not affect Eng |
| ken_Latn (Kenyang) | The locl feature did not affect Eng |
| csk_Latn (Jola-Kasa) | The locl feature did not affect Eng |
| pbi_Latn (Parkwa) | The locl feature did not affect Eng |
| mgc_Latn (Morokodo) | The locl feature did not affect Eng |
| bud_Latn (Ntcham) | The locl feature did not affect Eng |
| fue_Latn (Fulfulde, Borgu) | The locl feature did not affect Eng |
| avn_Latn (Avatime) | The locl feature did not affect Eng |
| bex_Latn (Jur Modo) | The locl feature did not affect Eng |
| vai_Latn (Vai (Latin)) | The locl feature did not affect Eng |
| gnd_Latn (Zulgo-Gemzek) | The locl feature did not affect Eng |
| goa_Latn (Guro) | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach uni030C to uni01B2 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni0196 |
|  ^  | Shaper didn't attach uni0302 to uni0196 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach uni030C to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
| kye_Latn (Krache) | The locl feature did not affect Eng |
| mcu_Latn (Mambila, Cameroon) | The locl feature did not affect Eng |
| etu_Latn (Ejagham) | The locl feature did not affect Eng |
| ntr_Latn (Delo) | The locl feature did not affect Eng |
| meq_Latn (Merey) | The locl feature did not affect Eng |
| lgg_Latn (Lugbara) | The locl feature did not affect Eng |
| fub_Latn (Fulfulde, Adamawa) | The locl feature did not affect Eng |
| tuz_Latn (Turka) | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach gravecomb to uni0196 |
| mfi_Latn (Wandala) | The locl feature did not affect Eng |
| bfo_Latn (Malba Birifor) | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
| fmp_Latn (Fe’fe’) | Shaper didn't attach uni0304 to uni0251 |
|  ^  | Shaper didn't attach gravecomb to uni0251 |
|  ^  | Shaper didn't attach acutecomb to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni0251 |
|  ^  | The locl feature did not affect Eng |
| rub_Latn (Gungu) | The locl feature did not affect Eng |
| kzr_Latn (Karang) | The locl feature did not affect Eng |
| mnf_Latn (Mundani) | The locl feature did not affect Eng |
| agq_Latn (Aghem) | The locl feature did not affect Eng |
| nfr_Latn (Nafaanra) | The locl feature did not affect Eng |
| fod_Latn (Foodo) | The locl feature did not affect Eng |
| neb_Latn (Toura) | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach uni0302 to uni0196 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
| teo_Latn (Teso) | Some base glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |
| vag_Latn (Vagla) | The locl feature did not affect Eng |
| xuo_Latn (Kuo) | The locl feature did not affect Eng |
| nuv_Latn (Nuni, Northern) | The locl feature did not affect Eng |
| apd_Latn (Sudanese Arabic) | Some mark glyphs were missing: ◌͟ |
| nko_Latn (Nkonya) | The locl feature did not affect Eng |
| log_Latn (Logo) | The locl feature did not affect Eng |
| kpo_Latn (Ikposo) | The locl feature did not affect Eng |
| sil_Latn (Sisaala, Tumulung) | The locl feature did not affect Eng |
| ses_Latn (Koyraboro Senni) | The locl feature did not affect Eng |
| kus_Latn (Kusaal) | The locl feature did not affect Eng |
| ncu_Latn (Chumburung) | The locl feature did not affect Eng |
| tik_Latn (Tikar) | The locl feature did not affect Eng |
| ktj_Latn (Krumen, Plapo) | The locl feature did not affect Eng |
| srr_Latn (Serer) | The locl feature did not affect Eng |
| sld_Latn (Sissala) | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | The locl feature did not affect Eng |
| sav_Latn (Saafi-Saafi) | The locl feature did not affect Eng |
| dua_Latn (Duala) | The locl feature did not affect Eng |
| ny_Latn (Nyanja) | The locl feature did not affect Eng |
| udu_Latn (Uduk) | Some base glyphs were missing: T͟H, t͟h |
|  ^  | Some mark glyphs were missing: ◌͟ |
|  ^  | Shaper produced a .notdef |
| nnh_Latn (Ngiemboon) | The locl feature did not affect Eng |
| gde_Latn (Gude) | The locl feature did not affect Eng |
| bas_Latn (Basaa) | The locl feature did not affect Eng |
| mzw_Latn (Deg) | The locl feature did not affect Eng |
| avu_Latn (Avokaya) | The locl feature did not affect Eng |
| muy_Latn (Muyang) | The locl feature did not affect Eng |
| kqp_Latn (Kimré) | The locl feature did not affect Eng |
| ndz_Latn (Ndogo) | The locl feature did not affect Eng |
| pug_Latn (Phuie) | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
| yat_Latn (Yambeta) | The locl feature did not affect Eng |
| pil_Latn (Yom) | The locl feature did not affect Eng |
| blo_Latn (Anii) | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0196 |
|  ^  | Shaper didn't attach uni0302 to uni028A |
|  ^  | Shaper didn't attach gravecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni0196 |
|  ^  | Shaper didn't attach acutecomb to uni028A |
|  ^  | Shaper didn't attach gravecomb to uni028A |
|  ^  | The locl feature did not affect Eng |
| bzw_Latn (Basa) | The locl feature did not affect Eng |
| mas_Latn (Masai) | The locl feature did not affect Eng |
| wo_Latn (Wolof) | The locl feature did not affect Eng |
| nhb_Latn (Beng) | The locl feature did not affect Eng |
| yas_Latn (Nugunu) | The locl feature did not affect Eng |
| dgi_Latn (Northern Dagara) | The locl feature did not affect Eng |
| agc_Latn (Agatu) | The locl feature did not affect Eng |
| fuq_Latn (Central-Eastern Niger Fulfulde) | The locl feature did not affect Eng |
| dzg_Latn (Dazaga) | The locl feature did not affect Eng |
| dnj_Latn (Dan) | Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏ |
|  ^  | Shaper produced a .notdef |
| ahl_Latn (Igo) | The locl feature did not affect Eng |
| kyq_Latn (Kenga) | The locl feature did not affect Eng |
| gux_Latn (Gourmanchéma) | The locl feature did not affect Eng |
| cko_Latn (Anufo) | The locl feature did not affect Eng |
| wci_Latn (Gbe, Waci) | The locl feature did not affect Eng |
| lg_Latn (Ganda) | The locl feature did not affect Eng |
| kzc_Latn (Bondoukou Kulango) | Shaper didn't attach tildecomb to uniA7B6 |
|  ^  | Shaper didn't attach tildecomb to uniA7AE |
|  ^  | Shaper didn't attach tildecomb to uniA7B7 |
| bm_Latn (Bambara) | The locl feature did not affect Eng |
| myk_Latn (Mamara Senoufo) | The locl feature did not affect Eng |
| dyu_Latn (Dyula) | The locl feature did not affect Eng |
| twq_Latn (Tasawaq) | The locl feature did not affect Eng |
| yav_Latn (Yangben) | The locl feature did not affect Eng |
| ozm_Latn (Koonzime) | Shaper didn't attach acutecomb to oe |
|  ^  | Shaper didn't attach uni030C to oe |
|  ^  | Shaper didn't attach uni0302 to oe |
|  ^  | The locl feature did not affect Eng |
| gmm_Latn (Gbaya-Mbodomo) | The locl feature did not affect Eng |
| boz_Latn (Tiéyaxo Bozo) | The locl feature did not affect Eng |
| xed_Latn (Hdi) | The locl feature did not affect Eng |
| kmy_Latn (Koma) | The locl feature did not affect Eng |
| biv_Latn (Birifor, Southern) | Shaper didn't attach tildecomb to uni0196 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028A |
|  ^  | The locl feature did not affect Eng |
| xwe_Latn (Gbe, Xwela) | The locl feature did not affect Eng |
| mdj_Latn (Mangbetu) | The locl feature did not affect Eng |
| vut_Latn (Vute) | The locl feature did not affect Eng |
| mbo_Latn (Mbo) | The locl feature did not affect Eng |
| gej_Latn (Gen) | The locl feature did not affect Eng |
| bsp_Latn (Baga Sitemu) | The locl feature did not affect Eng |
| mur_Latn (Murle) | The locl feature did not affect Eng |
| cme_Latn (Cerma) | The locl feature did not affect Eng |
| nmz_Latn (Nawdm) | The locl feature did not affect Eng |
| daa_Latn (Dangaléat) | The locl feature did not affect Eng |
| lem_Latn (Nomaande) | The locl feature did not affect Eng |
| mfv_Latn (Mandjak) | The locl feature did not affect Eng |
| lee_Latn (Lyélé) | The locl feature did not affect Eng |
| soy_Latn (Miyobe) | The locl feature did not affect Eng |
| tvu_Latn (Tunen) | The locl feature did not affect Eng |
| maw_Latn (Mampruli) | The locl feature did not affect Eng |
| ksf_Latn (Bafia) | The locl feature did not affect Eng |
| gov_Latn (Goo) | Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂ |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper produced a .notdef |
| loq_Latn (Lobala) | The locl feature did not affect Eng |
| mor_Latn (Moro) | Some base glyphs were missing: Ꟈ, ꟈ |
|  ^  | Shaper produced a .notdef |
| bkm_Latn (Kom) | Shaper didn't attach gravecomb to oe |
|  ^  | Shaper didn't attach uni0302 to oe |
| bav_Latn (Vengo) | The locl feature did not affect Eng |
| ee_Latn (Ewe) | The locl feature did not affect Eng |
| las_Latn (Lama (Togo)) | The locl feature did not affect Eng |
| jgo_Latn (Ngomba) | The locl feature did not affect Eng |
| bqj_Latn (Bandial) | The locl feature did not affect Eng |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_African glyphset:

| Language | FAIL messages |
| :--- | :--- |
| hna_Latn (Mina) | No exemplar glyphs were defined for language Mina |
| amo_Latn (Amo) | No exemplar glyphs were defined for language Amo |
| gaa_Latn (Ga) | No variant glyphs were found for uni01B7 |
| ggn_Latn (Eastern Gurung, Latin) | No exemplar glyphs were defined for language Eastern Gurung, Latin |
| mgy_Latn (Mbunga) | No exemplar glyphs were defined for language Mbunga |
| dnj_Latn (Dan) | No variant glyphs were found for uni0181 |
| tod_Latn (Toma) | No variant glyphs were found for uni01B2 |
| kfo_Latn (Koro) | No exemplar glyphs were defined for language Koro |
| syi_Latn (Seki) | No exemplar glyphs were defined for language Seki |
| cch_Latn (Atsam) | No exemplar glyphs were defined for language Atsam |

 [code: warning-language-shaping]
</div></details><details><summary>🔥 <b>FAIL:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 🔥 **FAIL** Compulsory STAT Axis Values are incorrect:

 | Name | Axis | Current Value | Current Flags | Current LinkedValue | Expected Value | Expected Flags | Expected LinkedValue |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Regular | wght | 400.0 | 0 | None | 400.0 | 0 | 700.0 |
 [code: bad-axis-values]
</div></details><details><summary>🔥 <b>FAIL:</b> Check variable font instances don't have duplicate names (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont_duplicate_instance_names">com.google.fonts/check/varfont_duplicate_instance_names</a>)</summary><div>


* 🔥 **FAIL** Following instances names are duplicate:

* Regular
 [code: duplicate-instance-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
128 more.

Use -F or --full-lists to disable shortening of long lists.

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* ⚠ **WARN** fvar instance coordinates for non-wght axes are not the same as the fvar defaults. This may be intentional so please check with the font author:

| Name | current | expected |
| :--- | :--- | :--- |
| Regular | opsz=72.0 | opsz=12.0 | [code: suspicious-fvar-coords]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Ccaron.czech

	- IJ_acutecomb

	- Iacute.czech

	- dotlessi_ogonek
 [code: unreachable-glyphs]
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=398.0,Y=1335.0 (should be at cap-height 1333?)

	* zero (U+0030): X=204.0,Y=1332.0 (should be at cap-height 1333?)

	* zero (U+0030): X=905.0,Y=1335.0 (should be at cap-height 1333?)

	* colon (U+003A): X=100.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=419.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=466.5,Y=1331.0 (should be at cap-height 1333?)

	* k (U+006B): X=665.0,Y=1098.0 (should be at x-height 1100?)

	* k (U+006B): X=922.0,Y=1098.0 (should be at x-height 1100?)

	* s (U+0073): X=327.5,Y=1098.0 (should be at x-height 1100?)

	* exclamdown (U+00A1): X=444.0,Y=1334.0 (should be at cap-height 1333?)

	* 88 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̠᷄ i̠᷅ i̠᷆ i̠᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅

Your font fully covers the following languages that require the soft-dotted feature: Southern Kisi (Latn, 360,000 speakers), Dutch (Latn, 31,709,104 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), Navajo (Latn, 166,319 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ekpeye (Latn, 226,000 speakers), Igbo (Latn, 27,823,640 speakers), Nzakara (Latn, 50,000 speakers), Fur (Latn, 1,230,163 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Gulay (Latn, 250,478 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Avokaya (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Makaa (Latn, 221,000 speakers), Dan (Latn, 1,099,244 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><details><summary>ℹ <b>INFO:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* ℹ **INFO** Hinting filesize impact:

 |               | Jaro[opsz].ttf          |
 |:------------- | ---------------:|
 | Dehinted Size | 160.1kb |
 | Hinted Size   | 160.1kb   |
 | Increase      | 24 bytes      |
 | Change        | 0.0 %  |
 [code: size-impact]
</div></details><details><summary>ℹ <b>INFO:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ℹ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 1.000'] [code: version-not-detected]
</div></details><details><summary>ℹ <b>INFO:</b> EPAR table present in font? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/epar">com.google.fonts/check/epar</a>)</summary><div>


* ℹ **INFO** EPAR table not present in font. To learn more see https://github.com/fonttools/fontbakery/issues/818 [code: lacks-EPAR]
</div></details><details><summary>ℹ <b>INFO:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* ℹ **INFO** These are the ppm ranges declared on the gasp table:

PPM <= 65535:
	flag = 0x0F
	- Use grid-fitting
	- Use grayscale rendering
	- Use gridfitting with ClearType symmetric smoothing
	- Use smoothing along multiple axes with ClearType®
 [code: ranges]
</div></details><details><summary>ℹ <b>INFO:</b> Check for font-v versioning. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontv">com.google.fonts/check/fontv</a>)</summary><div>


* ℹ **INFO** Version string is: "Version 1.000"
The version string must ideally include a git commit hash and either a "dev" or a "release" suffix such as in the example below:
"Version 1.3; git-0d08353-release" [code: bad-format]
</div></details><details><summary>ℹ <b>INFO:</b> Font contains all required tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/required_tables">com.google.fonts/check/required_tables</a>)</summary><div>


* ℹ **INFO** This font contains the following optional tables:

	- loca

	- prep

	- GPOS

	- GSUB

	- gasp

	- vhea

	- vmtx [code: optional-tables]
</div></details><details><summary>ℹ <b>INFO:</b> List all superfamily filepaths (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/superfamily/list">com.google.fonts/check/superfamily/list</a>)</summary><div>


* ℹ **INFO** . [code: family-path]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 4 | 9 | 108 | 8 | 131 | 0 |
| 0% | 0% | 2% | 3% | 42% | 3% | 50% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **PASS**
* **DEBUG**
