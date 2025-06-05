# Parkinon_and_Gut_Microbiome_Interface
This repository is to store all of the human gut microbiome datasets that links to the Parkinson's Disease. It also incorporates an application in Python that is able to take these datasets and then convert them into the desired dataset format that we would like to obtain.

If the user has downloaded the dataset from the European Nucleotide Archive Database, the good databse to start from is ERP016332. The European Nucleotide Archive Database is a public database to store the nucleotide sequeue data for people interested to obtain those pieces of biological information for their research for example. The script to extract these .fastq files in a folder for ease of analysis is inside extract_fastq.sh file. To utilize, start with: 
- chmod +x extract_fastq.sh
- ./extract_fastq.sh

Multiple tickets are created and are managed using BitBucket and Fork. By the end of August, we should have an interface that will be deployed so that users are able to utilize the application. Tickets will be continuously added to this and will be removed accordingly: 
- 2234: Creating a sketchboard of what the application needs to look like
- 1234: Information Tab to provide information to the user on what the application does
- 3321: Work on the Buttons UI
- 3312: Work on the Conversion Button tab to open up another page
- 2243: Work on the python methods to convert the table
- 1121: Figure out how does qiime comes into the resulting table
- 2212: Figure out how will you take the table from qiime and then format it in a desired manner
- 3131: Think about where the file will be stored for the user once they finish using it 
- 3434: Invoking the QIIME environment behind-the-scenes
- 3123: Adding buttons for different file formats
- 3111: Research all the possible file formats for the human gut microbiome
- 3112: Display a loading button until the process is completed for the user
- 3323: Create the logic for inputting the .fastq files 
