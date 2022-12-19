# NeighborJoiningDistanceMetrics

Scroll through the notebook to see the results! The notebook has associated text comments with each cell to help follow along with the code. The results are also shown and explained.

## Running notebook

To run this code, open the ipynb file in Google Colabratory (or anywhere works) and run all cells. All the libraries that need to be installed are associated there. The datasets and images were loaded from PFAM and the true phylogenetic trees were created from these 2 websites, respectively.

1. https://www.ebi.ac.uk/interpro/entry/pfam/PF00015/entry_alignments/?type=seed
2. https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=simple_phylogeny-I20221219-021018-0406-22675723-p1m

So, when the code is ran, the alignment and phylogeny images files will not be found as those are populated at runtime. To add those, simply download the alignment from the first link for any protein that is desired and then upload the alignment file directly into Colabratory. Then when the createDistanceMatrix function is ran, pass that file into the filename parameter and a phylogenetic tree for that alignment will appear. In the second parameter of the function any distance meteric can be selected from 

1. Blosum45
2. Blosum45
3. Blosum45
4. Blosum45
5. Blosum45
6. Pam30
7. Pam70
8. Pam250
9. edit
10. editWithGaps
11. hamming

If the real phylogenetic tree is desired in order to compare to the various distance metrics, visit the 2nd link and input the multiple sequence alignment to find it!
