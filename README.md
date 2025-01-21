This repository contains a Python-based workflow for processing DNase-seq narrowPeak files obtained from the ENCODE portal. The pipeline automates interval-to-sequence conversion using bedtools, ensures uniform sequence lengths, and outputs standardized positive (accessible) and negative (non-accessible) datasets for subsequent analyses.

Features:
Automated Data Download: Briefly mention how you obtain the data from ENCODE (e.g., wget, curl, or manual download).
Interval Conversion: Describe the use of bedtools to convert genomic intervals to nucleotide sequences.
Sequence Standardization: Explain how sequences are trimmed or discarded to achieve a consistent length.
Negative Set Creation: Detail the logic used to identify non-accessible regions and generate a corresponding negative dataset.
Scalability: Note that the pipeline supports multiple experiments (e.g., at least 10 narrowPeak files).
