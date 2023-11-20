# Example datasets for ProteoMarker

Here, you can find a dataset to use in ProteoMarker as an example (other than the one that is already loaded, and runs when you press the "Press to test the example data" button on the "Upload data" tab). It was taken from the study performed by <a href="https://doi.org/10.1016/j.ccell.2021.06.003" target="_blank"> Joshi, S. K. et al. (2021)</a>. The raw data was downloaded from the <a href="https://cptac-data-portal.georgetown.edu/cptacPublic/" target="_blank"> CPTAC repository</a> (PDC000315), run on FragPipe (following the experimental design and parameters specified at the repository, only using the MOLM14 cell line data, which correspond to the first two plexes).

The following data can be found in the /dataset folder:

- `protein_plex1.tsv` and `protein_plex2.tsv`, the raw data files, which are the two quantification files resulting from FragPipe (they were originally named "protein.tsv", and were located within the folders created by FP for each plex),

- `metadata2.txt`, which contains all the information regarding the files above,

- `comparisons2.txt`, with the comparisons of interest.

Note that the headers of both the `metadata2.txt` and `comparisons2.txt` follow the instructions set in the <a href="https://patmartinezb.github.io/ProteoMarker/#files" target="_blank"> ProteoMarker tutorial</a> for these type of files, and that the samples names in the raw data files are the same as in the `key` variable of the metadata file.

Both the `metadata2.txt` and `comparisons2.txt` files can be used as templates.

For further details visit the <a href="https://patmartinezb.github.io/ProteoMarker/#files" target="_blank"> ProteoMarker tutorial</a>.

The app can be found <a href="https://patmartinezb.shinyapps.io/ProteoMarker/" target="_blank"> here</a>
