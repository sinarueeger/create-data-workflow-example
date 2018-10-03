# openSNP data

Task: Get OpenSNP data and process it into small files 

The main file is `opensnp-data.Rmd` that will download the big openSNP file and chop it up into small pieces. 

After knitting `opensnp-data.Rmd`, the folder `data/out/*` will contain three files that are ready to be copied and used: 

- `genotyping_data_subset_train.bim`: genotype data description
- `genotyping_data_subset_train.raw`: genotype data
- `training_set_details.txt`: phenotype data
