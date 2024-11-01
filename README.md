The methodology is as follows:
The script if run in jupyter has two code blocks.
First requires login credentials at NASA GES DISC website. The credentials are:
Username: chitvan
Password: Cclimate26@sm

The second code block retrieves the data from the website based on the links provided in the text file and appropriately subsets the hours (11,12 and 13 UTC) the same.
The changes will be required in second block which are:

In the line defining the variable "SUBSETLIST", the text file is read. Hence, its path will need to be changed based on where you have saved it.
In the line defining the variable "CHCKLIST" , the path to the folder where the files will be saved is given. That will need to change.
In the line defining the variable "FILENAME", the path of the files is created, which includes the path of the folder in which they have to be saved. Hence, that path needs to be modified.

The text file is valid only for two days.
