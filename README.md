# Election_Analysis  

## Overview of the Election Audit  
  
The Colorado Board of Elections is conducting an audit to analyze the following data:  
	- Total number of votes cast  
	- A complete list of candidates who received votes    
	- Total number of votes each candidate received  
	- Percentage of votes each candidate won  
	- The winner of the election based on popular vote  
	- Each county and its total vote count  
	- Each county and its percentage of total votes  
	- The county with the highest voter turnout.  

The following resources were used to compile, write, and test data:  
	- Data Source: election_results.csv  
	- Software: Python 3.9; Visual Studio Code 1.57.1


## Election Analysis:  
	- Total votes cast were 369,711  
	- Results by county were:  
		**County**	**Percentage of Votes**		**Total Votes**  
		Jefferson		10.5%				38,855  
		Denver			82.8%			       306,055  **LARGEST COUNTY TURNOUT**   
		Arapahoe		 6.7%				24,801  
	
	-Results by candidate were:  	
	   **Candidate**	**Percentage of Votes**		**Popular Votes**  
	Charles Casper Stockham		23.0%				85,213  
	Diana DeGette			73.8%			       272,892  **WINNER OF ELECTION**   
	Raymon Anthony Doane		 3.1%				11,606  

## Election Audit Summary:  

Using the analysis, we can infer that Denver went primarily for Diana DeGette, having won over 73% of the vote and Denver casting over 82% of the overall vote.  
The script, as written, could be used for other analysis where values based on percentage are needed; such as how many votes in which county were cast for a specific candidate.  
Also with a little modification, if given the data set of the households in Colorado, whether they vote Democrat or Republican,  
we would only need to modify the script to show instead of "Candidate", you would have "Party Affiliation".  
We could even take it further to analyze how different counties vote during which election cycle as long, as the  
voting dates are made available, by adding a date condition.  


		  


