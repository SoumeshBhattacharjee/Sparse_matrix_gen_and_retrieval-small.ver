# Sparseamatirxgenand-retirieval-small
This sparse matrix generator and retrieval program is used to generate a sparse matrix of 100,000 x 3000 fields where each of the 100,000 rows have their own  variation of numbers from the 3000 columns . it is used for mainly small delivery data storage.


The sparsematrix is created in a CSR storage format and stored as sparse_matrix.npz
The UI version is there to retrieve a a specific one product id and find the associated pincodes it can deliver .

I was unable to find datasets for the data of merchants and pincodes so sparse_matrix.py makes the datasets necessary.

 sparsetest is a simple testing algorithm which also looks for the edgecases and all . 
