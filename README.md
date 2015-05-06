# Named Entities Recognition module of the Systran LDK.
Delivery date: 06/04/2015 16:54:43

This package covers the following languages:
* Dutch
* English
* French
* German
* Italian
* Korean
* Portuguese
* Romanian
* Russian
* Slovene
* Somali
* Spanish
* Swedish
* Turkish

# Performance metrics

### German
*No data available*

---

### English

##### Tag set
* ENAMEX type="firstname"
* ENAMEX type="initials"
* ENAMEX type="lastname"
* ENAMEX type="location"
* ENAMEX type="middlename"
* ENAMEX type="organization"
* ENAMEX type="person"
* ENAMEX type="product"
* ENAMEX type="suffix"
* TIMEX type="date"
* TIMEX type="expression"
* alibaba
* title
* year


##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 457 | 243 | 255 | 167 | 41 | 27 | 20 | 0.7341 | 0.5317 | 0.6168 |
| Organization | 450 | 217 | 314 | 182 | 81 | 33 | 18 | 0.6218 | 0.4822 | 0.5432 |
| Person | 419 | 288 | 230 | 104 | 99 | 21 | 6 | 0.6957 | 0.6874 | 0.6915 |
| Product | 68 | 0 | 89 | 59 | 21 | 4 | 5 | 0.0000 | 0.0000 | 0.0000 |
| Time | 161 | 68 | 93 | 85 | 0 | 6 | 2 | 0.8947 | 0.4224 | 0.5738 |
| TOTAL | 1555 | 816 | 981 | 597 | 242 | 91 | 51 | 0.6800 | 0.5248 | 0.5924 |


---

### Spanish

##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 384 | 278 | 133 | 63 | 27 | 31 | 12 | 0.7989 | 0.7240 | 0.7596 |
| Organization | 508 | 360 | 195 | 121 | 47 | 19 | 8 | 0.8295 | 0.7087 | 0.7643 |
| Person | 375 | 196 | 184 | 164 | 5 | 5 | 10 | 0.9074 | 0.5227 | 0.6633 |
| Product | 44 | 30 | 17 | 12 | 3 | 1 | 1 | 0.8571 | 0.6818 | 0.7595 |
| Time | 126 | 57 | 69 | 68 | 0 | 1 | 0 | 0.9828 | 0.4524 | 0.6196 |
| TOTAL | 1437 | 921 | 598 | 428 | 82 | 57 | 31 | 0.8442 | 0.6409 | 0.7286 |


---

### French

##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 293 | 211 | 137 | 59 | 55 | 19 | 4 | 0.7301 | 0.7201 | 0.7251 |
| Organization | 365 | 124 | 272 | 203 | 31 | 13 | 25 | 0.6425 | 0.3397 | 0.4444 |
| Person | 315 | 211 | 112 | 90 | 8 | 5 | 9 | 0.9056 | 0.6698 | 0.7701 |
| Product | 74 | 31 | 50 | 40 | 7 | 0 | 3 | 0.7561 | 0.4189 | 0.5391 |
| Time | 216 | 86 | 133 | 111 | 3 | 19 | 0 | 0.7963 | 0.3981 | 0.5309 |
| day value="01" | 0 | 0 | 3 | 0 | 3 | 0 | 0 | 0.0000 | 0.0000 | 0.0000 |
| TOTAL | 1263 | 663 | 707 | 503 | 107 | 56 | 41 | 0.7647 | 0.5249 | 0.6225 |


---

### Italian
*No data available*

---

### Korean

##### Tag set
* ENAMEX type="firstname"
* ENAMEX type="initials"
* ENAMEX type="lastname"
* ENAMEX type="location"
* ENAMEX type="middlename"
* ENAMEX type="organization"
* ENAMEX type="person"
* ENAMEX type="product"
* TIMEX
* TIMEX type="date"
* TIMEX type="expression"
* TIMEX type="hour"
* day
* month
* title
* year


##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 610 | 342 | 337 | 258 | 69 | 10 | 0 | 0.8124 | 0.5607 | 0.6634 |
| Organization | 422 | 254 | 332 | 138 | 164 | 28 | 2 | 0.5670 | 0.6019 | 0.5839 |
| Person | 506 | 189 | 346 | 302 | 29 | 7 | 8 | 0.8112 | 0.3735 | 0.5115 |
| Product | 26 | 4 | 25 | 21 | 3 | 0 | 1 | 0.5000 | 0.1538 | 0.2353 |
| Time | 229 | 166 | 86 | 32 | 23 | 31 | 0 | 0.7545 | 0.7249 | 0.7394 |
| TOTAL | 1793 | 955 | 1126 | 751 | 288 | 76 | 11 | 0.7180 | 0.5326 | 0.6116 |


---

### Dutch
*No data available*

---

### Portuguese

##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 344 | 256 | 267 | 58 | 179 | 23 | 7 | 0.5505 | 0.7442 | 0.6329 |
| Organization | 368 | 154 | 250 | 188 | 36 | 14 | 12 | 0.7130 | 0.4185 | 0.5274 |
| Person | 316 | 191 | 134 | 91 | 9 | 4 | 30 | 0.8162 | 0.6044 | 0.6945 |
| Product | 66 | 0 | 66 | 57 | 0 | 0 | 9 | 0.0000 | 0.0000 | 0.0000 |
| Time | 140 | 27 | 116 | 113 | 3 | 0 | 0 | 0.9000 | 0.1929 | 0.3176 |
| TOTAL | 1234 | 628 | 833 | 507 | 227 | 41 | 58 | 0.6583 | 0.5089 | 0.5740 |


---

### Romanian

##### Tag set
* ENAMEX type="location"
* ENAMEX type="organization"
* ENAMEX type="person"
* TIMEX type="date"
* TIMEX type="expression"
* TIMEX type="hour"
* title


##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| AnnotatorNotes | 1 | 0 | 1 | 1 | 0 | 0 | 0 | 0.0000 | 0.0000 | 0.0000 |
| Location | 566 | 278 | 342 | 257 | 54 | 27 | 4 | 0.7658 | 0.4912 | 0.5985 |
| Organization | 559 | 96 | 497 | 404 | 34 | 52 | 7 | 0.5079 | 0.1717 | 0.2567 |
| Person | 374 | 233 | 150 | 131 | 9 | 5 | 5 | 0.9246 | 0.6230 | 0.7444 |
| Product | 7 | 0 | 7 | 7 | 0 | 0 | 0 | 0.0000 | 0.0000 | 0.0000 |
| Time | 200 | 99 | 117 | 89 | 16 | 11 | 1 | 0.7795 | 0.4950 | 0.6055 |
| TOTAL | 1707 | 706 | 1114 | 889 | 113 | 95 | 17 | 0.7583 | 0.4136 | 0.5353 |


---

### Russian

##### Tag set
* ENAMEX type="firstname"
* ENAMEX type="lastname"
* ENAMEX type="location
* ENAMEX type="location"
* ENAMEX type="organization"
* ENAMEX type="person"
* TIMEX type ="hour"
* TIMEX type="date"
* TIMEX type="expression"
* TIMEX type="hour"
* title
* year


##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 498 | 427 | 142 | 54 | 71 | 10 | 7 | 0.8291 | 0.8574 | 0.8430 |
| Organization | 402 | 260 | 178 | 120 | 36 | 16 | 6 | 0.8176 | 0.6468 | 0.7222 |
| Person | 348 | 319 | 54 | 20 | 25 | 7 | 2 | 0.9037 | 0.9167 | 0.9101 |
| Product | 57 | 0 | 57 | 56 | 0 | 0 | 1 | 0.0000 | 0.0000 | 0.0000 |
| Time | 95 | 91 | 5 | 2 | 1 | 2 | 0 | 0.9681 | 0.9579 | 0.9630 |
| TOTAL | 1400 | 1097 | 436 | 252 | 133 | 35 | 16 | 0.8564 | 0.7836 | 0.8184 |


---

### Slovene

##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 298 | 175 | 158 | 104 | 35 | 9 | 10 | 0.7642 | 0.5872 | 0.6641 |
| Organization | 279 | 36 | 297 | 211 | 54 | 26 | 6 | 0.2951 | 0.1290 | 0.1796 |
| Person | 318 | 111 | 219 | 201 | 12 | 6 | 0 | 0.8605 | 0.3491 | 0.4966 |
| Product | 14 | 0 | 14 | 14 | 0 | 0 | 0 | 0.0000 | 0.0000 | 0.0000 |
| Time | 189 | 61 | 137 | 119 | 9 | 9 | 0 | 0.7722 | 0.3228 | 0.4552 |
| TOTAL | 1098 | 383 | 825 | 649 | 110 | 50 | 16 | 0.6852 | 0.3488 | 0.4623 |


---

### Somali
*No data available*

---

### Swedish
*No data available*

---

### Turkish

##### Tag set
* ENAMEX type="firstname"
* ENAMEX type="lastname"
* ENAMEX type="location"
* ENAMEX type="organization"
* ENAMEX type="person"
* ENAMEX type="product"
* TIMEX type ="date"
* TIMEX type="date"
* TIMEX type="expression"
* TIMEX type="hour"
* TIMEX type="time"
* century
* day
* month
* title
* year


##### Metrics
| **TAG** | **Nb ref.** | **Correct** | **Errors** | **Missing** | **Excess** | **Partial** | **Label** | **Prec.** | **Recall** | **F1** |
|--------:|:------------|:------------|:-----------|:------------|:-----------|:------------|:----------|:----------|:-----------|:-------|
| Location | 358 | 310 | 73 | 43 | 25 | 4 | 1 | 0.9118 | 0.8659 | 0.8883 |
| Organization | 364 | 266 | 140 | 83 | 42 | 10 | 5 | 0.8235 | 0.7308 | 0.7744 |
| Person | 349 | 150 | 201 | 192 | 2 | 7 | 0 | 0.9434 | 0.4298 | 0.5906 |
| Product | 113 | 70 | 57 | 32 | 14 | 10 | 1 | 0.7368 | 0.6195 | 0.6731 |
| Time | 79 | 72 | 10 | 3 | 3 | 4 | 0 | 0.9114 | 0.9114 | 0.9114 |
| TOTAL | 1263 | 868 | 481 | 353 | 86 | 35 | 7 | 0.8715 | 0.6873 | 0.7685 |


---


Readme file generated 06/04/2015 16:54:43
Copyright © 2015 SYSTRAN. All rights reserved.
