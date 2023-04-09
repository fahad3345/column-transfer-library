# column-transfer-library
I have a dataset containing age,gender,fever,cough,city and has_covid columns

i want to clean this dataset using encoding and imputer depend upon the features of columns,  
firstly column age is perfect numerical type
i want to encode column gender and city using HotEncoding 
fever column is numerical column which represent temprature , there are some nan values i want to replace nan values with mean, i used simpleimputer
column cough i want to do OrdinalEncoding
we can do it separately , But using column transfer library we can do all this encoding and imputing in a single code
