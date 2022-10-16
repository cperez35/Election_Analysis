# Election Analysis 

## Overview of Project

### Purpose:

The election commission has requested some additional data to complete the audit:

 - The voter turnout for each county
 - The percentage of votes from each county out of the total count
 - The county with the highest turnout

 Using the election data file we used python code to find the result and print it to the terminal and then saved it to a .txt file. 

 ### Results 

 - How many votes were cast in this congressional election?

    - By initializing a code that read through each row in the file and then added "1" for each count of a candiates name we are able to count the total number of votes. 
    
     ![Code](Resources/Candidate%20and%20County%20Vote%20Count%20Code.PNG%0D)  
    
    
    - After running the script the total number of votes in the election were 369,711 total votes cast.
        
         ![Total Votes](Resources/Total%20Votes.PNG)
        
    

 - Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

    -   Created a code to read through each row and count every vote by county. We then divided the individual county total by the overall total vote number to produce individual count percentages.
    
        ![County Votes Code](Resources/County%20Votes%20Code.PNG)

    - The code yielded this output in the terminal:

        ![County Results](Resources/County%20Votes%20Result.PNG)

 - Which county had the largest number of votes?
 
    -   Denver had the highest number of votes with 82.8% of the total votes coming from them. 


 - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

    - By counting the total number of votes each candidate received and then diving by the total number of votes we were able to calculate the total votes each candidate received as well as the percentage breakdown for each candidate.
   
        ![Candidate Results Code](Resources/Candidate%20Results%20Code.PNG)

    - The code produced this result:

        ![Candidate Results](Resources/Candidate%20Results.PNG)

        There were 3 candidates with one clear winner. 

 - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

    - The winner of the election was Diana DeGette. She received 272,892 votes which accounted for 73.8% of the total votes!

        ![Candidate and County Results](Resources/Results.PNG%0D) [](Resources/election_results.csv) 

