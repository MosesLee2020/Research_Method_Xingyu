# Overview<br>

This report is built based on the tutorial of https://www.youtube.com/watch?v=s5y1XNKENbk.

**In this report, we have developed and analyzed the LC-MS/MS data set of MSV000088759, which includes three sub-files:<br>**

*MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_1.mzML<br>
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_2.mzML<br>
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_3.mzML<br>*


We explored the molecular networking of a special molecular cluster :**Doxorubacin** and use different Precursor Ion Mass Tolerance 
and Fragment Ion Mass Tolerance to discuss the how tolerance value affects results.

# Jod Parameters<br>

## In *Case 1*, we set the parameters as following:<br>

**Basic Options<br>**

Spectrum Files(Required):3 files are selected<br>
*MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_1.mzML<br>
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_2.mzML<br>
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_3.mzML<br>*

Precursor Ion Mass Tolerance: 0.02 Da<br>
Fragment Ion Mass Tolerance: 0.02 Da<br>
Other:Default<br>
__________________________________________________________________________________________
**Advanced Network Options<br>**
Minimum Cosine Score: 0.7<br>
Network TopK: 10<br>
Maximum Connected Component Size:100<br>
Minimum Matched Fragment Ions: 6<br>
Minimum Cluster Size:2<br>
Maximum shift:1999 Da<br>
Other:Default<br>
__________________________________________________________________________________________
**Advanced Library Search Options<br>**
Library Search Min Matched Peaks: 6<br>
Score Threshold: 0.7v
Maximum aNALOG sEARCH mASS dIFFERENCE: 100<br>
Other:Default<br>
__________________________________________________________________________________________
**Advanced Filtering Options<br>**
Filter below Std Dev: 0.0<br>
Minimum Peak Intensity: 0.0<br>
Other:Default<br>
__________________________________________________________________________________________
**Advanced GNPS Repository Search Options<br>**
Default<br>
__________________________________________________________________________________________
**Advanced Output Options<br>**
Default<br>


