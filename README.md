# EPolls
# Idea for codefundo++

We are planning to build a completely online voting platform for elections in India. Microsoft Azure Blockchain service and Aadhar authentication will be used to make the process secure at each step.

There will be following two types of facilities on the platform:

TYPE 1: Vote From home	

    • Register on the website using Voter ID. Fill in the necessary details.
    
    • Apply for online voting on the portal. While applying, the user needs to submit the reason for being unable to vote at the booth. Application should be submitted atleast 7 days prior to voting day. Possible reasons include-
    
          ▪ Disabled/Physically Unable to go to the booth: Proper medical certificates need to be attached.
          ▪ Overseas on election day: The voter needs to provide a scanned copy of visa/passport to prove that they will be o overseas on the election day.
          ▪ Other: If any other reason, then also the voter has to give proper proofs as to why he/she won’t be able to vote at the booth.  
          
    • The EC will verify the reason with proofs and display the status of the application (Accepted/Rejected) with reason.
    
    • If the EC accepts the application, the voter will be notified of the time slot he/she has to vote in through email/portal. Also, on polling day, a‘Unique Vote Key’ will be available to the user on the portal which will enable the voter to vote online in the given time slot. The Unique Vote Key will not be active outside the time slot.
    
    • The voter must log in to the portal and then use the Vote Key to cast their vote, which will count in their constituency of residence.
    
TYPE 2: Vote From Booth
 
    • Similar to the current system, but the portal will be used on polling booths instead of EVMs.
    
    • The EC officials will provide the 'Unique Vote Key' on the spot to the user after verifying his/her Elector's Photo ldentity Card (EPIC).
    
    • The vote key, in this case, ensures that no one is able to vote from home as type-2. 
    
The datasets available at https://data.gov.in/ will be used for this project. Sample Voter IDs will be created for demonstration. Later on, collaboration with Election Commission will be done to provide actual database of Voters.

The various technologies used will be Azure Blockchain Service for securing each step in the process, Azure App Service for deployment of the website and Github for Version Control.
