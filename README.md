# Election Audit with Python: Just what we need...more bots in the election process

## Overview of Project:
Election integrity has been a hot button topic regardless of political affiliation.  Transparency and scrutiny play a key role in building confidence in the election process.  Vote casting happens in quite distinct ways: mail, paper ballots, electronic entry on a machine.  As technology advances, we could see an appetite for remote online voting or even smart phone-based ballots on site.  Vote counting also happens in distinct ways: manual human counting, counting machines, statistically based projections.   A process that can quickly and independently validate initial results adds tremendous benefits which could even include avoidance of civic unrest and uncertainty.   The Python script developed does just that.  Regardless of how the vote was cast, we only need the ballot ID, where it was cast, and who it was cast for in order to confirm election winners.  This script will also callout which location (i.e., counties) may have contributed most to that victory.

### Election-Audit Results: 
- There were 369,711 votes cast in this congressional election.
       <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/TotalVotes_Output.PNG?raw=true)
        <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/TotalVotes.PNG?raw=true)
 
- As reference to auditors, the script will publish the sum of votes by location as well as its percentage of total votes.
       <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/CountyResults.PNG?raw=true)
        <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/CountyResults_Output.PNG?raw=true)
 
- Denver had the largest turnout with 306,055 which equates to 82.8% of the total votes.  
       <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/Large_County.PNG?raw=true)
        <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/LargeCounty_Output.PNG?raw=true)
 
- As reference to auditors, the script will publish the sum of votes by candidate as well as its percentage of total votes.
       <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/CandResults.PNG?raw=true)
        <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/CandResultsOut.PNG?raw=true)

- Diana DeGette won the election with 272,892 which equates to 73.8% of the total votes.  
       <br>
 ![alt text](https://github.com/VinoSarran/Module3_Python_Election/blob/main/Winner_Output.PNG?raw=true)
        <br>
 ![alt text](https://raw.githubusercontent.com/VinoSarran/Module3_Python_Election/main/Winner.PNG)

### Summary:
I strongly encourage the adoption of this script into standard practice.  The heart of this audit is to increase confidence in election results and expose potential anomalies.  I demonstrated the use case for this Python script but there are additional value-adds with just a few modifications.   This script could be used to report which candidate received the most votes in each county.  This could show that Diana DeGette won in Denver but another county preferred a different candidate.  This script could also be used to report more accurate depiction of turnout if total population by county was referenced.  By comparing vote counts to the local population, this could show that a less populated county actually had higher participation in the election than a more densely populated county.  Future audits may require this detail.  In addition, it would supply strategic campaign data for future elections.
