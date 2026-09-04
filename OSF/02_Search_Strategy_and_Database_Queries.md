# DOCUMENTATION OF SEARCH STRATEGY & DATABASE QUERIES

**Project Title:** Pedagogical Digital Competence and AI Literacy of Pre-Service Primary Teachers  
**OSF Component:** Search Strategy & Execution Log  
**Execution Date:** 15 June 2026 (All databases searched simultaneously)  
**Target Coverage:** 2016 – 2026 (10-Year Publication Window)  

---

## I. SCOPUS DATABASE SEARCH QUERY (ELSEVIER)

**Search Interface:** Scopus Advanced Search  
**Date Executed:** 15 June 2026  
**Query String:**
```text
TITLE-ABS-KEY ( ( "pre-service teacher*"  OR  "student teacher*"  OR  "teacher candidate*"  OR  "preservice primary teacher*" )  AND  ( "primary school"  OR  "elementary school"  OR  "grade school"  OR  "PGSD" )  AND  ( "digital competence"  OR  "digital literacy"  OR  "TPACK"  OR  "pedagogical digital competence"  OR  "AI literacy"  OR  "generative AI" )  AND  ( "readiness"  OR  "preparedness"  OR  "self-efficacy"  OR  "assessment"  OR  "competence gap" ) )  AND  PUBYEAR  >  2015  AND  PUBYEAR  <  2027  AND  ( LIMIT-TO ( DOCTYPE ,  "ar" ) )  AND  ( LIMIT-TO ( LANGUAGE ,  "English" )  OR  LIMIT-TO ( LANGUAGE ,  "Indonesian" ) )
```
- **Initial Yield (Records Identified):** $N = 145$
- **Document Type:** Peer-reviewed journal articles (`DOCTYPE: ar`)

---

## II. WEB OF SCIENCE CORE COLLECTION (CLARIVATE)

**Search Interface:** Web of Science Advanced Search (SCI-EXPANDED, SSCI, A&HCI, ESCI)  
**Date Executed:** 15 June 2026  
**Query String:**
```text
TS=(( "pre-service teacher*" OR "student teacher*" OR "teacher candidate*" OR "preservice primary teacher*" ) AND ( "primary school" OR "elementary school" OR "grade school" OR "PGSD" ) AND ( "digital competence" OR "digital literacy" OR "TPACK" OR "pedagogical digital competence" OR "AI literacy" OR "generative AI" ) AND ( "readiness" OR "preparedness" OR "self-efficacy" OR "assessment" OR "competence gap" ))
```
- **Filter Applied:** Publication Years: 2016–2026; Document Types: Articles; Languages: English, Indonesian.
- **Initial Yield (Records Identified):** $N = 110$

---

## III. ERIC DATABASE (EBSCOhost / US DEPT OF EDUCATION)

**Search Interface:** ERIC Interface  
**Date Executed:** 15 June 2026  
**Query String:**
```text
( "pre-service teacher*" OR "student teacher*" OR "teacher candidate*" OR "preservice primary teacher*" ) AND ( "primary school" OR "elementary school" OR "grade school" ) AND ( "digital competence" OR "digital literacy" OR "TPACK" OR "AI literacy" )
```
- **Filter Applied:** Peer Reviewed Only; Publication Date: 20160101-20260615.
- **Initial Yield (Records Identified):** $N = 40$

---

## IV. GOOGLE SCHOLAR (CITATION TRACKING & GRAY LITERATURE)

**Search Interface:** Publish or Perish / Google Scholar API  
**Date Executed:** 15 June 2026  
**Keywords:** `pre-service primary teachers pedagogical digital competence AI literacy readiness`  
- **Initial Yield (Top Relevant Records):** $N = 55$

---

## V. RECAPITULATION OF INITIAL YIELD

| Database Source | Initial Records ($N$) | After Deduplication | Screened (Title/Abs) | Full-Text Eligible | Core Included |
|---|---|---|---|---|---|
| **Scopus** | 145 | 102 | 41 | 18 | 9 |
| **Web of Science** | 110 | 78 | 32 | 14 | 7 |
| **ERIC** | 40 | 32 | 15 | 7 | 3 |
| **Google Scholar** | 55 | 28 | 12 | 6 | 1 |
| **TOTAL** | **350** | **240** | **100** | **45** | **20 Core (+17 Synth = 37)** |
