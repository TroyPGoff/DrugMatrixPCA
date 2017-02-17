# DrugMatrix Drug & Side Effects PCA
Dimensionality reduction of DrugMatrix Variables

This PCA reduces the (so far) 46 side effects annotated in the DrugMatrix database using TOXNET's (NIH) toxicity database. The data is in binary format in accordance with known toxicity and will be updated with coinciding databases as soon as possible. 

There already is enough data to show some clustering, but ideally there would be much more input from various toxicity databases, as currently it would require utilizing the top 8 principal components to account for ~75% of the data's variation.
__________________________________________________________________________________________________________________________________________
# DrugMatrix GE & Drug PCAs (separated by tissue)

Tissue     | 	  Drugs     |  	 Var. top 2 PCs     |	   Var. top 8 PCs

Thigh      |	    41      |  	     ~33%            |    	      ~59%

Heart      |  	  208     | 	     ~13%            | 	         ~28%

Cell (Hep) | 	 	 274      | 	     ~23%            |          ~35%

Kidney     | 	  364       |	    ~12%       	       |        ~24%

Liver      |	    659     |  	    ~15%             |     	    ~29%

*Entire genome; unfiltered
