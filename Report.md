# Overview<br>

This report is built based on the tutorial of https://www.youtube.com/watch?v=s5y1XNKENbk.

**In this report, we have developed and analyzed the LC-MS/MS data set of MSV000088759, which includes three sub-files:<br>**

*MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_1.mzML<br>
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_2.mzML<br>
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_3.mzML<br>*


We explored the molecular networking of a special molecular cluster :**Doxorubacin** and use different Precursor Ion Mass Tolerance 
and Fragment Ion Mass Tolerance to discuss the how tolerance value affects results.

In *Case 1*, we set the parameters as following:

**<span style="font-size: 20px;">Basic Options</span>**

Spectrum Files(Required):3 files are selected
*MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_1.mzML
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_2.mzML
 MSV000088759/peak/5ugmL_Opti_NCE_stepped20-30-40_3.mzML*

Precursor Ion Mass Tolerance: 0.02 Da
Fragment Ion Mass Tolerance: 0.02 Da
Other:Default
__________________________________________________________________________________________
**Advanced Network Options**
Minimum Cosine Score: 0.7
Network TopK: 10
Maximum Connected Component Size:100
Minimum Matched Fragment Ions: 6
Minimum Cluster Size:2
Maximum shift:1999 Da
Other:Default
__________________________________________________________________________________________
**Advanced Library Search Options**
Library Search Min Matched Peaks: 6
Score Threshold: 0.7
Maximum aNALOG sEARCH mASS dIFFERENCE: 100
Other:Default
__________________________________________________________________________________________
**Advanced Filtering Options**
Filter below Std Dev: 0.0
Minimum Peak Intensity: 0.0
Other:Default
__________________________________________________________________________________________
**Advanced GNPS Repository Search Options**
Default
__________________________________________________________________________________________
**Advanced Output Options**
Default


