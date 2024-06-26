# CPcm_dataset
COTAN PBMC cell map (CPcm), a labelled dataset of single-cell RNA sequences designed to be the transcriptomic equivalent of foundational image datasets.

## Description
The dataset was split into three subsets, 75% for training, 15% for validation,
and 15% for testing (respectively, 7,061, 1,515 and 1,538 cells), maintaining
the original unbalanced distribution of labels, and stratifying the sets for total
number of reads.

The datasets CPcm-44 and CPcm-15 differ only by their labels. The former
labels are integer numbers from 1 to 45, with the 44 removed. The labels of the
dataset CPcm-15 are integers from 0 to 14, and in the meta directory
there is a conversion table to the names of 15 biological subpopulations.
