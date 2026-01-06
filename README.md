# Task-3-data-Validation-and-Cleaning-
Detects duplicates and removes using Data-> remove Duplicate value 
replace empty cells using unknown text  
=if(isblank([@gender]),"unknown",[@gender])
taking average in performace column and filled that average value in empty cells
=if(isblank([@permance rating]),Average(R2:C7:R100:C7),([@permance rating]))
