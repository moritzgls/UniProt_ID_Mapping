# UniProt_ID_Mapping

Aim: Map any ENST Transcirpt ID and any Version to its corresponding UniProt_ID

This repository provides 4 files:  
1-the raw ID Mapping file ("HUMAN_9606_idmapping_selected.tab.gz") from /by_organism subdirectory of this UniProt website: https://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/idmapping/  
2-the .ipynb notebook to read the IDs into a dictionary, perform regex operations on them and store them as a python dictionary in a .json file  
3-the final ID Mapping from one UniProt ID to multiple Transcript IDs including different transcript versions  
4-the final ID Mapping from one UniProt ID to multiple Transcript IDs without transcript versions  
