# ArchiveTeam Ingest Rate

This Jupyter notebook examines the ingest rate for the [ArchiveTeam collection]
at the Internet Archive. It uses the [Internet Archive API] to search for all
the items, and then retrieves the metadata for each item to count the total
size (bytes) of each of the files. You can see the resulting data in the
`data/archiveteam.csv` file.

<a href="https://raw.githubusercontent.com/archiveteam-ingest-rate/hydrator/main/images/archiveteam-ingest-rate.png"><img width="800" src="https://raw.githubusercontent.com/archiveteam-ingest-rate/hydrator/main/images/archiveteam-ingest-rate.png"></a> 

<a href="https://raw.githubusercontent.com/archiveteam-ingest-rate/main/images/archiveteam-collections.png"><img width="800" src="https://raw.githubusercontent.com/archiveteam-ingest-rate/main/images/archiveteam-collections.png"></a>

## Run

    pip install -r requirements.txt 
    jupyter notebook notebook.ipynb
