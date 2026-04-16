# TikTok_modality_MFA

This page displays the variables and references for a pilot study on tiktok modality. The study is based upon a UD treebank of 10 tiktok videos (tot. ca. 5000 tokens) of three formats (stitch, answer, storytime), and aims at a first exploration of some characteristics of modality of online spoken italian. 


## Variables investigated and their group subdivision

#### Syntactic complexity:
1-max_clause_embedding;\
2-nonproj_arcs;\
3-nonproj_sent;\
4-implicit_subordinate_clauses;\
5-implicit_clauses;\
6-total_clauses;\
7-subordinate_clauses;\
8-coordinate_clauses\
* ref. Beaman 1984; Givòn 1991

#### Derivation:
9-derived_tokens;\
10-derived_nouns;\
11-derived_verbs;\
12-derived_adj;\
13-derived_adv;\
14-suffixed;\
15-prefixed;\
16-parasynthetics;\
17-derived_lemmas;\
18-derived_types;\
19-total_affixes;\
20-demonstratives_det;\
21-demonstratives_pron\
* ref. Iacobini & Adinolfi (2008)

#### Epistemics:
22-epistemic_tokens;\
23-epistemic_types\
* ref. Coates 1983

#### MDD:
24-mean_distance_head/dependent\
* ref. Zhu 2019; Lintunen & Mäkilä 2014

#### NP high weight:
25-subj_weight_ii;\
26-subj_weight_i;\
27-obj_weight_ii;\
28-obj_weight_i;\
29-n/obj_weight_ii;\
30-n/obj_weight_i;\
* ref. Voghera et al. 2004

#### Unmarked word order:
31-SV;\
32-VO;\
* ref. Voghera et al. 2004;2017

#### Marked word order:
33-VS;\
34-OV\
* ref. Voghera et al. 2004;2017

#### Personal pronouns:
35-pron_1sg;\
36-pron_1pl;\
37-pron_2sg;\
38-pron_2pl;\
39-pron_3sg;\
40-pron_3pl\
* ref. Chafe & Tannen 1987

#### Large scope words:
41-mean_word_vagueness;\
42-light_verbs\
* ref. Voghera 2017;Pisciotta & Masini 2025

## References

* Agnoloni, T., Bartolini, R., Frontini, F., Marchetti, C., Montemagni, S., Quochi, V., Ruisi, M., & Venturi, G. (2022). Making Italian Parliamentary Records Machine-Actionable: The Construction of the ParlaMint-IT Corpus. In Fišer, D., Eskevich, M., Lenardič,, J., & de Jong, F. (eds.), _Proceedings of ParlaCLARIN III @ LREC2022 pages 117–124, Marseille, 20 June 2022_. European Language Resources Association (ELRA).
* Beaman, K. (1984). Coordination and subordination revisited: syntactic complexity in spoken and written narrative discourse. In Tannen, D. (ed.), Coherence in spoken and written discourse. ABLEX, Norwood New Jersey, 45-80.
* Biber, D. (1988). _Variation across Speech and Writing_. Cambridge, Cambridge University Press.
* Biber, D. (1992). The multi-dimensional approach to linguistic analyses of genre variation: An overview of methodology and findings. Computers and the Humanities, 26, 331–345.
* Chafe, W., & Tannen, D. (1987). The Relation between Written and Spoken Language. _Annual Review of Anthropology_, 16, 383–407.
* Coates, J. (1983). _The Semantics of Modal Auxiliaries_ . London: Croom, Helm Context and Cognition; Amsterdam: John Benjamins.
* Givòn, T. (1991). Markedness in grammar: structural, distributional and cognitive considerations. _Studies in Language_, 15(2), 1-42.
* Iacobini, C. & Adinolfi, A. (2008). La derivazione suffissale nel parlato dell'italiano messa a confronto con quella dello scritto. In Pettorino, M., Giannini, A., Vallone, M., & Savy, R. (a cura di), _Atti del Congresso Internazionale “La comunicazione parlata”_. NAPOLI, Liguori Editore, 494-512.
* Lintunen, P. & Mäkilä, M. (2014). Measuring Syntactic Complexity in Spoken and Written Learner Language: Comparing the Incomparable?. _Research in Language_ 12 (4): 377-99.
* Mauri, C., Ballarè, S., Goria, E., Cerruti, M. & Suriano, F. (2019). KIParla Corpus: A New Resource for Spoken Italian. In Bernardi, R., Navigli,R. & Semerano, G. (a cura di), _CLiC-it 2019 – Italian Conference on Computational Linguistics. Proceedings of the Sixth Italian Conference on Computational Linguistics_. Bari, AI*IA series.
* Pannitto, L. & Mauri, C. (2024). The KIPARLA Forest treebank of spoken Italian: an overview of initial design choices. ArXiv, abs/2411.06554.
* Pisciotta, F. & Masini, F. 2025. A paradigm of psych-predicates: unraveling the constructional competition between light verbs constructions and derived verbs in Italian. In Riccio, A. & Fleischhauer, J. (eds.), _Light verbs: synchronic and diachronic studies_, 123-176. Berlin/Boston: Düsseldorf University Press.
* Troncone, L. (2025). Building It-tok. An Italian TikTok corpus. _Proceedings of the CLiC-it 2025: Eleventh Italian Conference on Computational Linguistics_, September 24 — 26, 2025, Cagliari, AI*IA series.
* Voghera, M. Basile, G., Cerbasi, D. Fiorentino, G. (2004). La sintassi della clausola nel dialogo. In Albano Leoni, F., Cutugno, F., Pettorino, M., Savy, R. (a cura di). Il parlato italiano, Atti del Convegno nazionale di Napoli (13-15 febbraio 2003).
* Voghera, M. (2017). _Dal parlato alla gramamtica. Costruzione e forma dei testi spontanei_. Roma, Carocci.
* Voghera, M. (2022). How speech mode emerges in language. In Voghera, M. (ed.), _From speaking to grammar_. Berlin, Peter Lang, 21-56.
* Voghera, M. (2026). Multimodalità e multimedialità nell'italiano contemporaneo. Presented at, Italianistiktag 2026. Graz.
* Zhu, Y. (2019). A Comparative Study on NP Length, Complexity and Pattern in Spoken and Written English. _Glottometrics_ 47, 104-122.



### Most influencing variables and dimensions
| dimensione |	variabile	gruppo |	contributo |	coordinata |	cos2 |
| ---- |	--- |	--- |	--- |	-- |
| Dim.1	| VO |	ordine_non_marcato |		10.0759728828546 |		0.736335655510527 |		0.542190197576106 |	
 |	Dim.1	 |	max_clause_embedding	 |	complessita_frasale	 |	8.08673049792697 |		0.813914160878389	 |	0.662456261278386 |	
 |	Dim.1 |		vsupp_count	 |	vaghezza	 |	7.58292042813358 |		0.545810548207642	 |	0.297909154534736 |	
 |	Dim.1	 |	SV	 |	ordine_non_marcato	 |	7.27974516626251	 |	0.625879063612154	 |	0.391724602268026 |	
 |	Dim.1	 |	tot_subordinate	 |	tipi_di_frasi	 |	6.37294721712535 |		0.829401642630167 |		0.687907084797618 |	
 |	Dim.1	 |	mdd	 |	complessita_frasale	 |	5.40681484003322	 |	0.665522692402972	 |	0.442920454103298 |	
 |	Dim.1	 |	det_dimostrativi	 |	dimostrativi |		4.56462079967324 |		0.427543754221404	 |	0.18279366177373 |	
 |	Dim.1	 |	OBJ_ii_DETNPMOD	 |	pensantezza_SN	 |	4.10430688216716 |		0.464713190386406 |		0.215958349319109 |	
 |	Dim.1	 |	tot_implicite_globali	 |	tipi_di_frasi |		4.10152129580544 |		0.665376128562377 |		0.442725392460655 |	
 |	Dim.1	 |	subordinate_implicite	 |	tipi_di_frasi |		4.01904848624919	 |	0.658652513049556 |		0.433823132946488 |	
 |	Dim.2	 |	OV	 |	ordine_marcato |		14.5274340860999	 |	0.507076654546495	 |	0.257126733586066 |	
 |	Dim.2	 |	vsupp_count	 |	vaghezza |		10.7152259345156 |		0.430602352751435 |		0.185418386195077 |	
 |	Dim.2	 |	NOBJ_ii_DETNPMOD |		pensantezza_SN	 |	9.21901779171646	 |	-0.462231427500902	 |	0.213657892569523 |	
 |	Dim.2	 |	pron_1sg	 |	persone_pronominali |		7.51006231147037	 |	0.398252295042481 |		0.158604890506608 |	
 |	Dim.2	 |	pron_1pl |		persone_pronominali	 |	7.43881875799969 |		0.396358800830833	 |	0.157100298996058 |	
 |	Dim.2	 |	OBJ_ii_DETNPMOD	 |	pensantezza_SN |		5.58938520396309	 |	-0.359914351264407	 |	0.129538340246077 |	
 |	Dim.2	 |	pron_2sg |		persone_pronominali |		3.75542864011775	 |	0.281621802635852 |		0.079310839719871 |	
 |	Dim.2	 |	pron_3sg	 |	persone_pronominali	 |	3.5498880311057	 |	0.273806557185614	 |	0.0749700307578366 |	
 |	Dim.2	 |	n_forme_derivate_distinte	 |	derivazione	 |	2.50274233514753	 |	-0.544523059155554 |		0.296505361952119 |	
 |	Dim.2	 |	derivati_tot |		derivazione	 |	2.47660388690999	 |	-0.54167211741307	 |	0.293408682782761 |	
 |	Dim.3	 |	VS	 |	ordine_marcato |		26.6219875364955	 |	-0.633159323970275 |		0.400890729530498 |	
 |	Dim.3	 |	pron_1pl	 |	persone_pronominali	 |	15.741981222143 |	-0.531838559283296	 |	0.282852253140534 |	
 |	Dim.3	 |	OV |		ordine_marcato	 |	12.9805560357726	 |	0.442119242233395 |		0.195469424353032 |	
 |	Dim.3	 |	pron_3sg	 |	persone_pronominali |		10.7951283471207 |		0.440416956478718 |		0.193967095553971 |	
 |	Dim.3	 |	SOGG_ii_DETNPMOD |	pensantezza_SN	 |	7.52815169287755	 |	-0.385278641289723	 |	0.148439631434054 |	
 |	Dim.3 |		vsupp_count	 |	vaghezza |		5.05958623326961 |		-0.272927214255868 |		0.0744892642814707 |	
 |	Dim.3	 |	pron_1sg |		persone_pronominali |		3.816385411411	 |	0.261864266703635	 |	0.0685728941762349 |	
 |	Dim.3	 |	SOGG_i_DETNPREL	 |	pensantezza_SN |		2.33995159145951 |		-0.214799956626499 |		0.046139021366748 |	
 |	Dim.3 |		VO |		ordine_non_marcato |		1.97365660328263	 |	0.199495818854485 |		0.0397985817404209 |	
 |	Dim.3	 |	pron_2pl	 |	persone_pronominali	 |	1.72009362887537	 |	0.175802954691441 |		0.0309066788782409 |	
 |	Dim.4	 |	pron_dimostrativi	 |	dimostrativi	 |	31.8526221108085	 |	0.593601877591638	 |	0.352363189080322 |	
 |	Dim.4	 |	OV	 |	ordine_marcato	 |	13.0695906134202 |		0.380892614744307	 |	0.145079183966755 |	
 |	Dim.4	 |	VO	 |	ordine_non_marcato	 |	8.09241635042908	 |	-0.346829398369646 |		0.120290631573448 |	
 |	Dim.4	 |	vsupp_count |	vaghezza	 |	7.22252664134975	 |	-0.279970780942589	 |	0.0783836381816057 |	
 |	Dim.4	 |	SOGG_ii_DETNPMOD |		pensantezza_SN	 |	7.19428804551098 |		0.323372776190059	 |	0.104569952380865 |	
 |	Dim.4	 |	det_dimostrativi	 |	dimostrativi	 |	6.41666017035925 |		-0.266426359803878	 |	0.0709830051983443 |	
 |	Dim.4		 |	OBJ_ii_DETNPMOD		 |	pensantezza_SN		 |	4.03011652302247		 |	-0.242029523402696		 |	0.0585782901985352	 |	
 |	Dim.4		 |	pron_3sg		 |	persone_pronominali		 |	3.46445832915164		 |	0.21421337732875		 |	0.0458873710265882	 |	
 |	Dim.4		 |	NOBJ_ii_DETNPMOD	 |		pensantezza_SN		 |	3.0938241678611	 |		0.212059316802637		 |	0.0449691538428012	 |	
 |	Dim.4		 |	VS		 |	ordine_marcato	 |		2.86469731787836	 |		0.178324465399011		 |	0.0317996149598435	 |	
 |	Dim.5		 |	epistemici	 |		epistemici		 |	28.5020488342211		 |	0.752237512801486		 |	0.565861275665745	 |	
 |	Dim.5		 |	n_epistemici_distinti		 |	epistemici	 |		27.8381501629933		 |	0.743424952555868		 |	0.5526806600827	 |	
 |	Dim.5		 |	pron_dimostrativi	dimostrativi		 |	13.3252754761787		 |	-0.37302575175638		 |	0.139148211473414	 |	
 |	Dim.5		 |	pron_1sg		 |	persone_pronominali		 |	7.3382652292286		 |	0.302903062757133		 |	0.0917502654276548	 |	
 |	Dim.5		 |	vsupp_count	 |		vaghezza	 |		3.52164050098163	 |		-0.189940985655144	 |		0.0360775780316489	 |	
 |	Dim.5		 |	NOBJ_i_DETNPREL		 |	pensantezza_SN		 |	2.80357736404641	 |		0.196129924616096	 |		0.0384669473299157	 |	
 |	Dim.5		 |	pron_1pl		 |	persone_pronominali	 |		2.46552178524178		 |	-0.175574477449462		 |	0.030826397131652	 |	
 |	Dim.5		 |	mean_V_w		 |	vaghezza		 |	2.39503796240523	 |		-0.156639893140574		 |	0.0245360561230905	 |	
 |	Dim.5		 |	VS		 |	ordine_marcato		 |	1.902685496406	 |		-0.141199483722496		 |	0.0199372942034995	 |	
 |	Dim.5		 |	pron_3pl	 |		persone_pronominali	 |		1.13784417432745	 |		-0.119274706766759		 |	0.0142264556742967	 |	
