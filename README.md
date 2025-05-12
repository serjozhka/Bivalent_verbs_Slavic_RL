Supplementary materials for the paper "Bivalent verb classes across Slavic: Areal and genealogical patterns' (submitted to "Russian Linguistics").

This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

# Overview
The materials in this repository are organized into three folders:

- Input_data contains the raw data used for the analysis, primarily derived from the latest development version of the BivalTyp database as of February 12, 2025, and partially pre-annotated manually.
- Output_data contains four distance matrices generated from the raw data.
- Additional_visualization contains a visualization that is not included in the main publication but is referenced in a footnote in Section 4.1 of the paper.

## 1. Input data

### 1.1. languages_preprocessed.xlsx

This file contains basic information about the languages in the BivalTyp sample. It is based on the languges.csv file in the BivalTyp repository (https://github.com/macleginn/bivaltyp/tree/master/data) but reflects some preprocessing.

### 1.2. data_for_download_preprocessed.xlsx

This file contains the bulk of the BivalTyp data. It is based on the data_for_download.csv file in the BivalTyp repository (https://github.com/macleginn/bivaltyp/tree/master/data) but reflects some preprocessing.

### 1.3. predicates.xlsx

This file contains an overview of predicates used as BivalTyp's questionnaire. It is based on the file predicates.csv in the BivalTyp repository (https://github.com/macleginn/bivaltyp/tree/master/data).

### 1.4. language_stats.xlsx

This file contains some statistic data on languages of the BivalTyp sample. It is downloaded from the BivalTyp repository (https://github.com/macleginn/bivaltyp/tree/master/data) .

### 1.5. Slavic_verbs_cognacy.xlsx

This files contains annotations showing cognacy sets in the Slavic verbs used in parallel BivalTyp entries.

### 1.6. Slavic_patterns_cognacy.xlsx

This files contains annotations showing cognacy sets in the Slavic valency paterns used in parallel BivalTyp entries.

## 2. Output_data

### 2.1. DistVerbEtym.xlsx

This is a distance matrix showing (dis)similarities among 11 Slavic languages calculated as the normalized Hamming distance based on cognacy relations between verbs used in parallel entries.

### 2.2. DistValEtym.xlsx

This is a distance matrix showing (dis)similarities among 11 Slavic languages calculated as the normalized Hamming distance based on cognacy relations between argument-coding devices used in parallel entries.

### 2.3. DistValLoc.xlsx

This is a distance matrix showing (dis)similarities among 139 BivalTyp  languages calculated as the normalized Hamming distance based on locus of (non)transitivity distinctions used in parallel entries.

### 2.4. DistValPat.xlsx

This is a distance matrix showing (dis)similarities among 139 languages based on the lexical distribution of verbs into language-specific valency classes. It is based on Mutual Information, as described in Section 4.4 of the paper. 

## 3. Additional visualization

### 3.1. MDS_DistVerbEtym.jpg 

This an MDS plot based on DistVerbEtym and the distance matrix in 2.1 above.
