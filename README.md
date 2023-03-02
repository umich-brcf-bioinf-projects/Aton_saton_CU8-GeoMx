# Aton_saton_CU8-GeoMx

Analysis code and input files for QC and DE comparisons of GeoMx whole transcriptional assay (WTA) and protein assay data. 

## WTA

* `GeoMx_WTA_analysis_combined.Rmd` - WTA data analysis code, including QC, filtering, and mixed model differential expression comparisons
* `Mm_R_NGS_WTA_v1.0.pkc` - PKC file for Mouse WTA panel; downloaded from Nanostrings's website; maps probe IDs in DCC data to gene targets; required input for GeoMxTools
* `WTA_full_annotation.xlsx` - spreadsheet of selected ROIs with experimental group labels; required input for GeoMxTools


## Protein 

* `GeoMx_protein_QC-DE.Rmd` - Protein data analysis code, including QC, filtering, and mixed model differential expression comparisons
* `PKCFiles` -  PKC files for Mouse protein panels; downloaded from Nanostrings's website; maps probe IDs in DCC data to gene targets; required input for GeoMxTools 
* `4791-LW_LabWorksheet_Annotations.xlsx` - spreadsheet of selected ROIs with experimental group labels; required input for GeoMxTools
