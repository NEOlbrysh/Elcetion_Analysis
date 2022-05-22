# Election_Analysis
## Overview of Election Audit: 

A Colorado election commission requests an election audit and analysis of a recent local congressional election. The expected results should include:
- The total number of votes cast.
- A complete list of candidates who received votes.
- The total number of votes for each candidate received.
-	The percentage of votes each candidate won.
-	The winner of the election based on popular vote.
-	The total voter turnout for each county.
-	The percentage of votes from each county.
-	The county with the highest turnout.



## Election-Audit Results:


### How many votes were cast in this congressional election?

- There were 369,711 total votes cast in the congressional election. 

![2022-05-22 (17)](https://user-images.githubusercontent.com/103701561/169713705-84e0e315-22e5-405d-bf6d-d333a3673bc3.png)



### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

- The breakdown of the total votes per county lists Denver with 82.8% of the popular vote achieving a total of 306,055 votes. The county of Jefferson received 10.5% of the popular vote with 38,855 votes while Arapahoe received 6.7% of the popular vote with a total of 24,801 votes.


### Which county had the largest number of votes?

- Denver produced 82.8% of voters, for a total of 306,055 voters.



### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

- Jefferson produced 10.5% of voters, for a total of 38,855 voters.
- Denver produced 82.8% of voters, for a total of 306,055 voters.
- Arapahoe produced 6.7% of voters, for a total of 24,801 voters.



### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

- Diana DeGette, who received 73.8% of the vote for a total of 272,892 votes.





![2022-05-22 (7)](https://user-images.githubusercontent.com/103701561/169712769-ed32848a-5b30-4516-8995-2cd736a97460.png)
![2022-05-22 (2)](https://user-images.githubusercontent.com/103701561/169712781-3313b870-bc6b-4151-b54a-7ea26bbfa185.png)
![2022-05-22 (19)](https://user-images.githubusercontent.com/103701561/169719437-dd5a6599-9ead-42f0-b0b9-2c2b2a8ff807.png)
![2022-05-22 (10)](https://user-images.githubusercontent.com/103701561/169712788-02efe04e-1627-4b35-bb51-efda3b16310b.png)
![2022-05-22 (9)](https://user-images.githubusercontent.com/103701561/169712789-557a7bdc-2ca3-483f-92b7-1b3bae0de022.png)
![2022-05-22 (8)](https://user-images.githubusercontent.com/103701561/169712792-2612ac5b-ed2f-4e91-8a90-55449d8df843.png)




## Audit Summary: 

It might be interesting to see the results expanded by adding an additional "if" statement to the current code, the number of candidates per county could be tally. This way we could see which candidate won which county, providing deeper insight into the voting patterns within a given county. 
This added insight can be a guide for future election performance, so that you may properly allocate resources where turnout is low, or demographics are hard to reach.
A little time invested into customizing the script can provide on-demand analysis for years to come.
Adding additional functionality to the Python script used to develop this audit we could also find voter turnout by polling location. A polling location column would need to be added to the election results csv file, the ability to drill deeply into polling locations would provide information on voter volume and may assist in planning future voting locations based on the analysis. 
This code can be used on similar projects such as senatorial districts, local elections, federal elections and more.
In short, no matter the number of candidates or counties, the script used to perform the Election Audit can be a valuable resource for the board.


