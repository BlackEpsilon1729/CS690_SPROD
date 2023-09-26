Good Day is the Folder where we input and break the dataset given to us into the format to be used by modified_data_preprocessing.py

The data can be modified into 3 ways
a) Nothing is removed 
b) We take into consideration only the top 3000 genes only using Seurat normalization
c) We do (b) and normalised

On doing the imputation and using STAGATE we saw that ARI is score is in the order c)< b) ~ a)

Breaking the data:
we break the data into barcodes [protein sequence], features [], matrix.mtx in sparse matrix format and convert the matrix.tx into .gz file format and the rest we use in pickle format

Note:- the pre-processing that we were given used all the above files in .gz file format so we changed it to accept in pickle format

An Additional Function which changes the given png file into tif file as required by pre-processing


