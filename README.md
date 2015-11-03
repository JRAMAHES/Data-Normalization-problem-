# Data-Normalization-problem-

Database Normalisation is a structure of organizing the data in the database.
It is a multi-step process that puts data into tabular form by removing duplicated data from the relation tables.
Normalization is a systematic approach of decomposing tables to eliminate data redundancy and undesirable characteristics like Insertion, 
Update and Deletion Anamolies.

Normalization is used for mainly two reason,

one- to Eliminate the reduntant(useless) data.
second- to Ensure data dependency to make sense i.e data is logically stored.
 Problem!!!
 the Normalition becomes difficult to handle the update without facing data loss. 
 To understand these anomalies let us take an example of research table. 
 
S_id	S_Name	S_Address	Subject_opted
401	   Adam   	Noida	      Bio
402	    Alex	   Panipat	  Maths
403	   Stuart   	Jammu	    Maths
404	     Adam	     Noida   	Physics
