# DH-in-practice
The zip folder contains 3 jupyter notebook files. File named 'Queries_cont_words.jpynb' contains the code to query the LOD of the NMVW museum and a python code
to filter out the queried results to match the list of the contentious words.
The LOD can be found here: https://collectie.wereldculturen.nl/thesaurus/#/query/32f2ed10-dd23-475e-ad1e-d40a7bee8cd8 
File named 'Calculations_cont_words_types_objects.ipynb' includes the querying code to get a) all of the unique types of objects from the digital collection
and b) the number of objects that include both the type and the description in its metadata. 
The last jupyter notebook file 'cont_words_full.jpynb' contains the code to calculate the proportions of the types whihch descriptions contained contentious words
to the total number of types. 
The text files contain results of the calculations: 1) counts of all the contentious words that were above 0, 2) counts of all of the unoque types in the NMVW
collection, 3) counts of unique types that had contetnious terms in their descriptions and 4) the calculated proprtion of types with contetnious terms to the 
total count of unique object types. 
Lastly the zip file contains a csv with subject's IDs, object types, object descriptions and a contentious term found in the description. 
