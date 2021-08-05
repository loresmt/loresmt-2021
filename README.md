# Summary

The [LoResMT 2021 Shared Task](https://github.com/loresmt/loresmt-2021) is a part of the [4th Workshop on Technologies for MT of Low Resource Languages](https://sites.google.com/view/loresmt/).

# Introduction
In the third edition of the __LoResMT Shared Task__, we introduce new shared tasks that focus on the building of MT systems for COVID-related texts and Sign language. The task aims to encourage research on MT systems involving three low-resource language pairs:

	Taiwanese↔Mandarin (Sign language)
	English↔Marathi
	English↔Irish
## Structure of the `LoResMT-2021 Shared Task data`:
```
loresmt2021/
├─ baseline_system/
├─ data/
│  ├─ en-mr/
│     └─ train.en
│     └─ train.mr
│     └─ dev.en
│     └─ dev.mr
│     └─ test.en-mr.en
│     └─ test.mr-en.mr
│  ├─ en-ga/
│     └─ train.en
│     └─ train.en
│     └─ dev.en
│     └─ dev.ga
│     └─ test.en-ga.en
│     └─ test.en-ga.ga
│  ├─ monolingual/
│  │  └─ mono.covid-2021.en
│     └─ mono.covid.2021.mr
│  ├─ sign_language/
|     ├─ train/
|      └─ C00(185-195,197,199,200-294,296-297,299-301 & 305-361)
|     ├─ dev(development)/
|      └─ C00(261,304 & 358)
|     └─ README.md
│     ├─ test/
|      └─ sgTW2zhTW & zhTW2sgTW
├─ LICENSE.md
├─ LICENSE.txt
├─ README.md
   
```
**The data statistics are presented below:
-----------------------------------------------------
```
│ Language	       | Total_sentences/ | Total_words     │
│	                 total_segments         	    │ 
│English (en)	       │  8826            │  171249	    │
│Marathi (mr)	       │  21902	          │  285502         │
│English↔Irish(dev)    │  502		  │  7731/9406      │
│English↔Marathi(dev)  │  500             │  11901/10937    │
│English↔Irish(train)  │  8112		  │ 126980/144258   │
│English↔Marathi(train)│  20933           │ 356456/292561   │
│English↔Irish (test)  │  750             │                 │
│English↔Marathi(test) │  1000            │                 │
│Taiwanese↔Mandarin    │  128608          │                 │
│ (train)              │                  │                 │
│Taiwanese↔Mandarin    │  3071            │  5027           │
│ (dev)                │                  │                 │
│Taiwanese↔Mandarin    │  7053            │                 │
│ (test)               │                  │                 │
```

# License
Please see the [LICENSE](https://github.com/loresmt/loresmt-2021/blob/main/LICENSE) file.

# Acknowledgments
We would like to thank [Cardamom-Comparative Deep Models of Language for Minority and Historical Languages](http://www.cardamom-project.org/) (funded by the Irish Research Council under the Consolidator Laureate Award scheme (grant number IRCLA/2017/129)) and [Panlingua Language Processing LLP](http://panlingua.co.in/) for providing English↔Irish and English↔Marathi parallel and/or monolingual COVID data. We would also like to thanks [Potamu Research Ltd](https://www.potamure.net/) for providing Taiwanese↔Mandarin (Traditional Chinese ) Sign language data. 

## References
<pre>
@inproceedings{ojha-etal-2021-findings,
title = {Findings of the {LoResMT 2021 Shared Task on COVID and Sign Language for Low-Resource Languages}},
  author = {Ojha, Atul Kr. and Liu, Chao-Hong  and Kann, Katharina  and Ortega, John and Satam, Sheetal and Fransen, Theodorus},
  booktitle = {Proceedings of the 4th Workshop on Technologies for MT of Low Resource Languages},
  year = {2021}
}
</pre>
<pre>
=== Machine-readable metadata (DO NOT REMOVE!) =====================================================
Data available since: LoResMT Shared Task-2021
License: CC BY-NC-SA 4.0
=======
Includes text/video: yes
Genre: Sign language/COVID data
Shared Task Organisers: Ojha, Atul Kr.; Liu, Chao-Hong; Kann, Katharina
Contact: atulkumar.ojha@insight-centre.org, ch.liu@acm.org, shashwatup9k@gmail.com
Contributor/&copy;holder: NUI Galway, Panlingua Language Processing LLP, N. Delhi, India, Potamu Research Ltd
=======================================================================================================
</pre>
