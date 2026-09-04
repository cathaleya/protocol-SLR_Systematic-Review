# 02. HARMONIZED DATABASE SEARCH SYNTAXES AND REPOSITORY OVERLAP MATRIX

**OSF Registration DOI:** [10.17605/OSF.IO/PZ5MD](https://doi.org/10.17605/OSF.IO/PZ5MD)  
**Last Search Execution Date:** 15 June 2026  

---

## 1. HARMONIZED BOOLEAN SEARCH QUERIES ACROSS 4 DATABASES

To satisfy PRISMA 2020 Item 7 (search strategy reproducibility and cross-database translation equivalence), search queries were systematically harmonized around three mandatory Boolean conceptual blocks across Scopus, Web of Science, ERIC, and IEEE Xplore:

| Database Repository | Database Platform & Field Tags | Fully Harmonized Query Syntax |
|---|---|---|
| **Scopus** | Elsevier (`TITLE-ABS-KEY`) | `TITLE-ABS-KEY(("pre-service teacher*" OR "student teacher*" OR "teacher candidate*" OR "prospective teacher*" OR "preservice teacher*") AND ("digital competenc*" OR "digital literac*" OR "AI literac*" OR "artificial intelligence literac*" OR "generative AI" OR "GenAI" OR "TPACK") AND (instrument* OR scale* OR questionnaire* OR assessment* OR measure* OR test* OR rubric* OR "situational judgment" OR performance OR psychometric* OR validation))` |
| **Web of Science** | Clarivate Web of Science Core Collection (`TS` = Topic) | `TS=(("pre-service teacher*" OR "student teacher*" OR "teacher candidate*" OR "prospective teacher*" OR "preservice teacher*") AND ("digital competenc*" OR "digital literac*" OR "AI literac*" OR "artificial intelligence literac*" OR "generative AI" OR "GenAI" OR "TPACK") AND (instrument* OR scale* OR questionnaire* OR assessment* OR measure* OR test* OR rubric* OR "situational judgment" OR performance OR psychometric* OR validation))` |
| **ERIC** | EBSCOhost / ProQuest (`TI` Title, `AB` Abstract, `DE` Descriptor) | `((TI "pre-service teacher*" OR AB "pre-service teacher*" OR DE "Preservice Teachers") OR (TI "student teacher*" OR AB "student teacher*") OR (TI "teacher candidate*" OR AB "teacher candidate*") OR (TI "prospective teacher*" OR AB "prospective teacher*")) AND ((TI "digital competenc*" OR AB "digital competenc*" OR DE "Digital Literacy") OR (TI "digital literac*" OR AB "digital literac*") OR (TI "AI literac*" OR AB "AI literac*") OR (TI "generative AI" OR AB "generative AI") OR (TI "TPACK" OR AB "TPACK")) AND ((TI instrument* OR AB instrument* OR DE "Educational Measurement") OR (TI scale* OR AB scale*) OR (TI questionnaire* OR AB questionnaire*) OR (TI assessment* OR AB assessment*) OR (TI measure* OR AB measure*) OR (TI "situational judgment" OR AB "situational judgment") OR (TI validation OR AB validation))` |
| **IEEE Xplore** | IEEE Xplore Digital Library (`Document Title` / `Abstract`) | `(("Document Title":"pre-service teacher" OR "Document Title":"student teacher" OR "Document Title":"teacher candidate" OR "Abstract":"pre-service teacher" OR "Abstract":"student teacher" OR "Abstract":"teacher candidate") AND ("Document Title":"digital competence" OR "Document Title":"digital literacy" OR "Document Title":"AI literacy" OR "Document Title":"generative AI" OR "Abstract":"digital competence" OR "Abstract":"digital literacy" OR "Abstract":"AI literacy" OR "Abstract":"generative AI") AND ("Document Title":assessment OR "Document Title":instrument OR "Document Title":scale OR "Document Title":rubric OR "Document Title":validation OR "Abstract":assessment OR "Abstract":instrument OR "Abstract":scale OR "Abstract":rubric OR "Abstract":validation))` |

---

## 2. CROSS-DATABASE YIELD AND REPOSITORY OVERLAP MATRIX ($N = 498$ Raw Records)

| Database Repository | Initial Raw Yield ($n$) | Unique Yield Only ($n$) | Overlap with Scopus | Overlap with Web of Science | Overlap with ERIC | Overlap with IEEE Xplore |
|---|---|---|---|---|---|---|
| **Scopus** | 210 | 124 | — | 64 | 18 | 4 |
| **Web of Science** | 145 | 70 | 64 | — | 11 | 0 |
| **ERIC** | 98 | 69 | 18 | 11 | — | 0 |
| **IEEE Xplore** | 45 | 41 | 4 | 0 | 0 | — |
| **Total Raw / Unique** | **498** | **304** | **86** | **75** | **29** | **4** |
