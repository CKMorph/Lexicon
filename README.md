# Central Kurdish Lexicon


## Database of Central Kurdish Verbs
The Comprehensive database of Central Kurdish verbs used in CKMorph Morphological Analyzer.
Prepared By: Aso Mahmudi (`aso.mehmudi[at]gmail.com`)

For each verb the following properties are specified:
1. `Lemma`: the dictionary entry (e.g., بردن)
2. `Past stem`: for forming past tenses and present perfect (e.g., برد in بردم) 
3. `Present stem`: for forming simple present and imperative tenses (e.g., بە in دەیبەم)
4. `Passive/Causative stem`: for forming passive or causative forms (e.g., بر as in براوە or خەو in خەواندم)
5. `Agent stem`: for forming agent name/adjective in compounds (بێژ as in گۆرانیبێژ) 
6. `Transitive`: 0=intransitive (e.g., کەوتن), 1=transitive (e.g., خستن), 2=transitive only to indirect object (e.g., ڕوانین)
7. `Req.ەوە` : the verb will be ill-formed without "ەوە" suffix (e.g., پاڕان+ەوە)
8. Preverbs `هەڵ`, `دا`	,`ڕا`, `ڕۆ`,	`وەر`,	`سەر`,	`دەر`: the verb can occure with these preverbs for forming new meanings (e.g., هەڵ+گرتن)
9. `Req.Preverb`: the verb will be ill-formed without a preverb (e.g., هەڵ+واسین)
10. `Postp(ـە)`: the verb can take the postpositional clitic "ە" (e.g., هاتنە دەرەوە)
11. `FreePP`: the free past participle is a well-formed adjective (e.g., هاتوو)
12. `Only.3SG.Obj`: the verb is transitive but only takes 3rd person singular object (e.g., گوتن)

Notes:  
* Non-standard variations are in \[brackets\]
* For some transitive verbs, the agent stem is not exactly the present stem (marked by ²)   
* For the verb "ویستن" the present forms are conjugated differently (marked by ³)

## Cite:
The paper is submited to a journal and is under review. You can find the preprint in [Arxiv](https://arxiv.org/abs/2109.08615)

	@article{naserzade2021CKMorph,
		title={{CKMorph: A Comprehensive Morphological Analyzer for Central Kurdish}},
		author={Naserzade, Morteza; Mahmudi, Aso; Veisi, Hadi; Hosseini, Hawre; Mohammadamini, Mohammad},
		journal={arXiv preprint arXiv:2109.08615},
		year={2021},
	}
