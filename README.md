# Google Cloud for Data Science  
Instructions and guidance for creating and managing datalab notebooks in Google cloud

## Intended Audience 

## Starting Your DataLab Notebook
Activate your cloud sheel 
```datalab connect <UNIQUE_NAME>```

## Creating a New DataLab Notebook  
From the command line 
```datalab create --project nkbds-219022 --machine-type f1-micro --disk-size-gb 20 --idle-timeout "24h" --zone us-central1-c --no-connect <UNIQUE_NAME>```