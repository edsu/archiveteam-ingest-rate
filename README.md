# ArchiveTeam Ingest Rate


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5548129.svg)](https://doi.org/10.5281/zenodo.5548129)

This Jupyter notebook examines the ingest rate for the [ArchiveTeam collection]
at the Internet Archive. It uses the [Internet Archive API] to search for all
the items, and then retrieves the metadata for each item to count the total
size (bytes) of each of the files. You can see the resulting data in the
`data/archiveteam.csv` file.

<a href="https://gitlab.com/slowa/archiveteam-ingest-rate/-/raw/main/images/archiveteam-ingest-rate.png"><img width="800" src="https://gitlab.com/slowa/archiveteam-ingest-rate/-/raw/main/images/archiveteam-ingest-rate.png"></a> 

<a href="https://gitlab.com/slowa/archiveteam-ingest-rate/-/raw/main/images/archiveteam-collections.png"><img width="800" src="https://gitlab.com/slowa/archiveteam-ingest-rate/-/raw/main/images/archiveteam-collections.png"></a>

This notebook originally appeared in [edsu/notebooks](https://github.com/edsu/notebooks/) but was extracted here for citation and synchronization with Zenodo.

## Run

    pip install -r requirements.txt 
    jupyter notebook notebook.ipynb

[ArchiveTeam collection]: https://archive.org/details/archiveteam
