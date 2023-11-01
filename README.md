# UniProt_ID_Mapping

Aim: Map any ENST Transcirpt ID and any Version to its corresponding UniProt_ID

This repository provides 3 files:  
1-the .ipynb notebook to read the IDs into a dictionary, perform regex operations on them and store them as a python dictionary in a .json file  
2-the final ID Mapping from one UniProt ID to multiple Transcript IDs including different transcript versions  
3-the final ID Mapping from one UniProt ID to multiple Transcript IDs without transcript versions  

The raw ID Mapping file ("HUMAN_9606_idmapping_selected.tab.gz") from /by_organism subdirectory can be dowloaded on this UniProt website: https://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/idmapping/. And then be unzipped by typing gunzip {filepath} into your command line interface.
