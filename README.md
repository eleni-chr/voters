# voters
Construct a database of name-value pairs.

Function written by Eleni Christoforidou in MATLAB R2022b.

This function takes an unspecified number of inputs, but the first input is the current database. The rest of the arguments must come in the order of name (a string or char array) and ID (an integer or integer-valued double). If there is at least one occurrence of no ID number after a name, or the data types are not what is required, the function returns the original database. The function returns a struct array containing Name (a string) and ID (a double) fields as shown in the example below.

Testing:

database = voters([], 'Adam', 11111)

database = voters(database, 'Eve', 22222)

database(1)

database(2)
