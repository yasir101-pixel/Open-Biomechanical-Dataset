Supplementary materials for sensors-4621016, revision 2 (22 Nov 2026)
Manuscript: "Open Biomechanical Datasets for Human Motion Analysis: A Ten-Year Scoping Review"

These are the current versions. They replace the files in Supplementary_Materials_R1
(13 Nov 2026), which are kept unchanged for reference. The Zenodo deposit package holds
the same files (without the File S4 .docx and this README) plus File S1.csv, a
plain-text copy of the File S1 Datasets sheet. File S1.csv must be re-exported from
the revision 2 File S1 before upload.

FILE                              WHAT IT IS                                  CHANGED IN REVISION 2
File S1.xlsx                      Dataset-level extraction table, 74 rows     Yes: 7 records moved to the sheet
                                  (task, sensing, population, ethics, QAS),   "Excluded at access check"; final QAS
                                  data dictionary, live-formula summary,      scores; ethics category recoded to the
                                  figure source data, multi-label modality    C4 rule (two categories added);
                                  coding (AG to AQ), stated purpose (AR to    repository and access links updated
                                  AS), raw-versus-derived release coding      for 18 datasets; release coding
                                  (AT to AY).                                 updated for 7 datasets; Table 2
                                                                              subgroup labels B ("Inertial plus
                                                                              video") and E (eye tracking, ambient
                                                                              sensors) corrected.
File S2.xlsx                      Extraction field definitions and category   Yes: sensing labels, sheet pointers and
                                  schemes.                                    ID description updated.
File S3.xlsx                      Per-record screening decisions, Stage 1     Yes: 7 PubMed records (3, 5, 6, 10,
                                  and Stage 2, with exclusion codes and       39, 40, 67) moved from Included to
                                  rationales.                                 Stage 2 exclusion S2-C1.
File S4 - PRISMA-ScR              Completed PRISMA-ScR checklist; locations   Yes: title in the header; locations
  Checklist.pdf (+ .docx)         given by section.                           for items 9, 10, 12, 14, 15 and 16
                                                                              updated to manuscript v3 (changed
                                                                              cells highlighted green).
Supplementary Table S1.xlsx       QAS evidence sheet: source URL/DOI, item    Yes: 74 rows; final scores; source-
                                  scores, recorded evidence, and the          check findings added to the evidence
                                  revision 2 source-check findings.           columns; column T lists score
                                                                              changes; 7 excluded rows on a
                                                                              separate sheet.
Supplementary Table S2.xlsx       Deduplication log: matching field and       Wording only: "n = 81" qualified as
                                  retained record per duplicate pair.         the count after deduplication.
Sensitivity_Calculations.xlsx     Outlier participant-pool analysis, PubMed   Yes: recomputed at n = 74; new sheet
                                  search sensitivity check, QAS and category  "5 - Revision 2 effects" separates
                                  recomputation.                              the effect of the score revision from
                                                                              the effect of the exclusions; new
                                                                              sheet "6 - Coverage check" lists the
                                                                              89 datasets (2016 or later) from
                                                                              reviews [9], [20], [25] judged
                                                                              eligible or borderline, and whether
                                                                              the search retrieved them (16 of 65
                                                                              core; manuscript Section 4.7).

Changed cells in the .xlsx files are highlighted in yellow.

WHAT CHANGED IN REVISION 2, IN BRIEF
1. Second author check. A second author (S.H.) checked all quality scores of the
   81 datasets of revision 1 against the same rubric. Every
   disagreement, every C4 score of 0 given by both raters, and every C3 score of 1
   that rested on the publication alone was checked against the source.
2. C4 rule. The rule applied in practice is now stated in Section 2.3: an approval or
   registration number = 2; a committee without a number, an approval date only, a
   waiver, consent only, or a general statement = 1; no statement = 0.
3. Access check. Seven datasets ([49], [51], [52], [54], [78], [79], [91]) have no
   identifiable access point to their data and do not meet the definition of an open
   dataset in Section 2.1. They are Stage 2 exclusions (File S3, S2-C1). Reference
   numbers in the article are unchanged.
4. Figure S1 removed (22 Nov 2026). The multi-label modality coding stays in File S1
   (Datasets, columns AG to AQ; Figure source data, 28 combinations); the manuscript
   cites File S1 instead.
5. Consistency fixes (22 Nov 2026). File S2: sensing labels as in Table 1; sheet
   pointers corrected. Supplementary Table S1: repository column taken from File S1;
   Dataset ID replaced by the File S3 record number. File S1 and Table S1: repository
   of [74], [104], [107] and [122] corrected to match their C3 evidence. Supplementary
   Table S2: article references added to the duplicate pairs ([93], [94], [100],
   [123]) and a note relating the log to Figure 1. File S3: two Stage 2 summary rows
   coded S2-C3. File S1: titles of [125] and [127] as in the reference list; [118]
   named. Changed cells are highlighted in yellow.

KEY NUMBERS THESE FILES REPRODUCE
164 records identified; 57 excluded at Stage 1; 107 full texts; 16 excluded at
Stage 2; 91 remaining; 17 duplicates removed; 74 datasets.
3,941 participants (upper bound; 4 datasets do not report sample size); strictly
healthy 2,025 (51.4%); adjusted pool without Ferber et al. 2,143, healthy 76.0%.
Mean QAS 7.92 (reported as 7.9). Criterion means: C1 1.64, C2 1.57, C3 1.81,
C4 1.51, C5 1.39.
Ethics (Ethics category in File S1): approval or registration number 47 (63.5%),
committee named without a number 15, documented waiver 1, consent only 1, general
statement only 1, no statement found 9 (12.2%).

OPEN ITEMS
- [47] (resolved 22 Nov 2026): public download not located; original link broken. This
  does not establish that the data no longer exist. Retained by author decision, because
  the paper stated an access point when it was published; C3 kept at 1; disclosed in
  manuscript Section 4.7.
- The Data Availability Statement DOI (https://doi.org/10.5281/zenodo.XXXXXXX) is
  replaced once the Zenodo DOI is reserved.
