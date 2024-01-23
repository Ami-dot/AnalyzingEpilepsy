Files: AAREADME.txt
Database: TUH EEG Epilepsy Corpus
Version: v2.0.0
-------------------------------------------------------------------------------

This file contains some basic statistics about the TUH EEG Epilepsy
Corpus, a corpus developed to motivate the development of new methods
for automatic analysis of EEG files using machine learning. This
corpus is a subset of the TUH EEG Corpus and contains sessions from
patients with epilepsy. To balance the corpus, some sessions are
provided from patients that do not have epilepsy.

Subjects were sorted into epilepsy and no epilepsy categories by searching
the associated EEG reports for indications as to an epilepsy/no epilepsy 
diagnosis based on clinical history, medications at the time of recording, 
and EEG features associated with epilepsy such as spike and sharp waves.
A board-certified neurologist, Daniel Goldenholz, and his research team
reviewed and verified the decisions about each patient.

When you use this specific corpus in your research or technology development, 
we ask that you reference the corpus using this publication:

 Veloso, L., McHugh, J. R., von Weltin, E., Obeid, I., & Picone,
 J. (2017). Big Data Resources for EEGs: Enabling Deep Learning
 Research. In I. Obeid & J. Picone (Eds.), Proceedings of the IEEE
 Signal Processing in Medicine and Biology Symposium
 (p. 1). Philadelphia, Pennsylvania, USA: IEEE.

This publication can be retrieved from:

 https://www.isip.piconepress.com/publications/conference_presentations/2017/ieee_spmb/data/

Our preferred reference for the TUH EEG Corpus, from which this
seizure corpus was derived, is:

 Obeid, I., & Picone, J. (2016). The Temple University Hospital EEG
 Data Corpus. Frontiers in Neuroscience, Section Neural Technology,
 10, 196.

v2.0.0 of the TUH EEG Epilepsy Corpus was based on v2.0.0 of the
TUH EEG Corpus. Please see the documentation for TUH EEG v2.0.0 to
understand how the data is structured.

The files subject_ids_*.list contain unique IDs for each subject that is
part of the corpus. We also provide links to the edf data for users who
have not downloaded the entire corpus.

BASIC STATISTICS:

  |-------------------------------------------------------|
  | Description |  Epilepsy   | No Epilepsy |    Total    |
  |-------------+-------------+-------------+-------------|
  | Patients    |         100 |         100 |         200 |
  |-------------+-------------+-------------+-------------|
  | Sessions    |         530 |         168 |         698 |
  |-------------+-------------+-------------+-------------|
  | Files       |       1,785 |         513 |       2,298 |
  |-------------------------------------------------------|

The total size of the corpus is 36.284 Gbytes.

---
If you have any additional comments or questions about the data,
please direct them to help@nedcdata.org.

Best Regards,
 
Joe Picone
