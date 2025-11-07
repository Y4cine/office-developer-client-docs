---
title: "FIELDPICTURE Function"
 
 
manager: lindalu
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
f1_keywords:
- Vis_DSS.chm82251592
 
ms.localizationpriority: medium
ms.assetid: df88c55f-c098-dd4c-bf53-c7d7b60cf719
description: "Returns a format-picture string that matches the Microsoft Visio internal text field format code."
---

# FIELDPICTURE Function

Returns a format-picture string that matches the Microsoft Visio internal text field format code.
  
## Syntax

FIELDPICTURE(**code*** )
  
### Parameters

|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| *code* <br/> |Required  <br/> |**Number** <br/> | A text field format code. |

### Return value

String
  
## Remarks

**Codes**:
0 visFmtNumGenNoUnits
1 visFmtNumGenDefUnits
2 visFmt0PlNoUnits
3 visFmt0PlDefUnits
4 visFmt1PlNoUnits
5 visFmt1PlDefUnits
6 visFmt2PlNoUnits
7 visFmt2PlDefUnits
8 visFmt3PlNoUnits
9 visFmt3PlDefUnits
10 visFmtFeetAndInches
11 visFmtRadians
12 visFmtDegrees
13 visFmtFeetAndInches1Pl
14 visFmtFeetAndInches2Pl
15 visFmtFraction1PlNoUnits
16 visFmtFraction1PlDefUnits
17 visFmtFraction2PlNoUnits
18 visFmtFraction2PlDefUnits
20 visFmtDateShort
21 visFmtDateLong
22 visFmtDateMDYY
23 visFmtDateMMDDYY
24 visFmtDateMmmDYYYY
25 visFmtDateMmmmDYYYY
26 visFmtDateDMYY
27 visFmtDateDDMMYY
28 visFmtDateDMMMYYYY
29 visFmtDateDMMMMYYYY
30 visFmtTimeGen
31 visFmtTimeHMM
32 visFmtTimeHHMM
33 visFmtTimeHMM24
34 visFmtTimeHHMM24
35 visFmtTimeHMMAMPM
36 visFmtTimeHHMMAMPM
37 visFmtStrNormal
38 visFmtStrLower
39 visFmtStrUpper
44 visFmtDateyyyymd
45 visFmtDateyymmdd
46 visFmtTimeAMPMhmm_J
50 visFmtDateTWNfYYYYMMDDD_C
51 visFmtDateTWNsYYYYMMDDD_C
52 visFmtDateTWNfyyyymmddww_C
53 visFmtDateTWNfyyyymmdd_C
54 visFmtDategggemdww_J
55 visFmtDateyyyymdww_J
56 visFmtDategggemd_J
57 visFmtDateyyyymd_J
58 visFmtDateYYYYMMMDDDWWW_C
59 visFmtDateYYYYMMMDDD_C
60 visFmtDategeMMMMddddww_K
61 visFmtDateyyyymdww_K
62 visFmtDategeMMMMddd_K
63 visFmtDateyyyymd_K
64 visFmtDateyyyy_m_d
65 visFmtDateyy_mm_dd
66 visFmtTimeAMPMhmm_C
67 visFmtTimeAMPMhmm_K
68 visFmtTimeAMPM_hmm_J
69 visFmtTimehmm_J
70 visFmtTimeAMPM_hmm_C
71 visFmtTimehmm_C
72 visFmtTimeAMPM_hmm_K
73 visFmtTimehmm_K
74 visFmtTimeHMMAMPM_E
75 visFmtTimeHHMMAMPM_E
76 visFmtDateyyyymd_S
77 visFmtDateyyyymmdd_S
78 visFmtDatewwyyyymmdd_S
79 visFmtDatewwyyyymd_S
80 visFmtTimeAMPMhmm_S
81 visFmtTimeAMPMhhmm_S
200 visFmtMsoDateShort
201 visFmtMsoDateLongDay
202 visFmtMsoDateLong
203 visFmtMsoDateShortAlt
204 visFmtMsoDateISO
205 visFmtMsoDateShortMon
206 visFmtMsoDateShortSlash
207 visFmtMsoDateShortAbb
208 visFmtMsoDateEnglish
209 visFmtMsoDateMonthYr
210 visFmtMsoDateMon_Yr
211 visFmtMsoTimeDatePM
212 visFmtMsoTimeDateSecPM
213 visFmtMsoTimePM
214 visFmtMsoTimeSecPM
215 visFmtMsoTime24
216 visFmtMsoTimeSec24
217 visFmtMsoFEExtra1
218 visFmtMsoFEExtra2
219 visFmtMsoFEExtra3
220 visFmtMsoFEExtra4
221 visFmtMsoFEExtra5
John... Visio MVP

Format picture strings are used in the FORMAT function to define the expansion of values to dates, times, numbers, and unit labels.
  
## Example

FIELDPICTURE(0)
  
Returns the format picture string "esc(0)", which specifies a number that has one decimal place and a lowercase unit description when used in the FORMAT function.
  
