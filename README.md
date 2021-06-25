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
│  ├─ en-ga/
│     └─ train.en
│     └─ train.en
│     └─ train.en
│     └─ train.en
│  ├─ monolingual/
│  │  └─ mono.covid-2021.en
│     └─ mono.covid.2021.mr
│  ├─ sign_language/
└     └─ README.md
│  ├─ test/
├─ LICENSE.md
├─ LICENSE.txt
├─ README.md
   
```
**The data statistics are presented below:
-----------------------------------------------------
```
│ Language	       | Total_sentences/ | Total_words     │
│	                 total_segments         	    │ 
│English (en)	       │  10000           │	            │
│Marathi (mr)	       │  21902	          │  285502         │
│English↔Irish(dev)    │  500		  │  7758/9452      │
│English↔Marathi(dev)  │  500             │  11901/10937    │
│English↔Irish(train)  │  		  │                 │
│English↔Marathi(train)│  20933           │ 356456/292561   │
│English↔Irish (test)  │  1000            │                 │
│English↔Marathi(test) │  1000            │                 │
│Taiwanese↔Mandarin    │                  │                 │
│ (train)              │                  │                 │
│Taiwanese↔Mandarin    │  3071            │                 │
│ (dev)                │                  │                 │
│Taiwanese↔Mandarin    │                  │                 │
│ (test)               │                  │                 │
```

# License
Please see the [LICENSE](https://github.com/loresmt/loresmt-2021/blob/main/LICENSE) file.

# Acknowledgments
We would like to thank [Cardamom-Comparative Deep Models of Language for Minority and Historical Languages](http://www.cardamom-project.org/) (funded by the Irish Research Council under the Consolidator Laureate Award scheme (grant number IRCLA/2017/129)) and [Panlingua Language Processing LLP](http://panlingua.co.in/) for providing English-Irish and English-Marathi parallel and monolingual COVID data.

## References
TBD
<pre>
=== Machine-readable metadata (DO NOT REMOVE!) =====================================================
Data available since: LoResMT Shared Task-2021
License: CC BY-NC-SA 4.0
=======
Includes text/video: yes
Genre: Sign language/COVID data
Shared Task Organisers: Ojha, Atul Kr.; Liu, Chao-Hong; Kann, Katharina
Contact: atulkumar.ojha@insight-centre.org, shashwatup9k@gmail.com, ch.liu@acm.org
Contributor/&copy;holder: NUI Galway, Panlingua Language Processing LLP, N. Delhi, India, Potamu Research Ltd
=======================================================================================================
</pre>
