# Central Kurdish Lexicon


## Database of Central Kurdish Verbs
[![DOI](https://zenodo.org/badge/409043053.svg)](https://zenodo.org/badge/latestdoi/409043053)

The Comprehensive database of Central Kurdish verbs used in CKMorph Morphological Analyzer.
Prepared By: Aso Mahmudi (`aso.mehmudi[at]gmail.com`)

For each verb the following properties are specified:
1. `LEMMA`: the dictionary entry (e.g., بردن)
2. `PAST`: the stem for forming past tenses and present perfect (e.g., برد in بردم) 
3. `PRESENT`: the stem for forming simple present and imperative tenses (e.g., بە in دەیبەم)
4. `PASSIVE/CAUSATIVE`: the stem for forming passive or causative forms (e.g., بر as in براوە or خەو in خەواندم)
5. `AGENT`: the stem for forming agent name/adjective in compounds (بێژ as in گۆرانیبێژ) 
6. `TR`: the transitivity of the verb: 0=intransitive (e.g., کەوتن), 1=transitive (e.g., خستن)
7. `FLAGS`:
	- `ReqEWE`:  the verb will be ill-formed without "ەوە" suffix (e.g., پاڕان+ەوە)
	- `ReqPreverb`: the verb will be ill-formed without a preverb (e.g., هەڵ+واسین)
	- `PostpE`: the verb can take the postpositional clitic "ە" (e.g., هاتنە دەرەوە)
	- `FreePP`: the free past participle is a well-formed adjective (e.g., هاتوو)
	- `Object3SG`: the verb is transitive but only takes 3rd person singular object (e.g., گوتن)
	- `NoObject`: the verb does not occur with indirect object (e.g., ڕوانین)
	- `SpecialImperative`: the imperative verb is not formed from the present stem (هاتن|وەرە)
8. `SLANG`:

Notes:  
* Non-standard variations are in \[brackets\]
* The agent stem of transitive verbs is usually the present stem, except: 
بردن|بەر, بیستن|بیست, خستن|خەر, خواردن|خۆر, دان|دەر, کردن|کەر, کوتان|کوت, گوتن|بێژنان|نەر
* For the verb "ویستن" the present forms are conjugated differently

## Cite:
The paper is submited to a journal and is under review. You can find the preprint in [Arxiv](https://arxiv.org/abs/2109.08615)
	@article{naserzade2023CKMorph,
		title={CKMorph: A Comprehensive Morphological Analyzer for Central Kurdish},
		author={Naserzade, Morteza and Mahmudi, Aso and Veisi, Hadi and Hosseini, Hawre and MohammadAmini, Mohammad},
		journal={International Journal of Digital Humanities},
		year={2023},
		publisher={Springer}
	}
