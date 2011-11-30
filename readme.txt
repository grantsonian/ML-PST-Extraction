============== Marklogic PST extraction =============

Steps:
1. Create a new folder 
2. Place the .pst in the new folder 
3. Place the ML-PST.jar in the new folder
4. Open Terminal/Cmd and navigate to the new folder 
5. Execute the following command
 	java -jar ML-PST.jar
6. The command will generate all the .xml files in the same folder
7. Using infostudio or adminconsole or cq load all the documents in the new folder 
 	
 	
===========
Todo: 
1. Finalize the document structure for the output document 
2. Data that is created should be stored in a sub-directory called data 
3. assign URI based on the dir structure extracted from the .pst file 
4. cron job to delete the data directory once the data is loaded in ML 
// do let me know if I might have missed anything.


	
