# codefundo_blockchain

Basic Idea- I am planning to build an application to make the voting process hassle free and secure, added to these benefits my application will also increase the voting turnout and would try to reach the parts where it is generally neglected. 

The application will have a blockchain backbone supported by a DBMS and a SMS-to-Computer Software for the data collection and processing process.

# Process:-

1)Initially we will map each adhar id with its respective contact number, this process is necessary for verification of the user and also for security purposes.

2)Once the contact number is linked with the adhar id , a mass sms appication will send the voter a message:

                                                    //SAMPLE MESSAGE
                                                    
                               Welcome to the voting portal , please choose the candidate you wish to elect:-
                               
                               A) xyz
                               B)....
                               .
                               .
                               xyz) Non of the Above
                               
                               Reply with your choice to xxxxxx contact number.
                               
3)After the voter sends the sms , the SMS-to Computer Software will append the data into the database and thus giving us the total voters record

4)Cleaning of data will be done later on to remove redundant responses and the final database will be created.

5)Now comes the blockchain part where in we will create a Smart contract which will initially check the age of the user , it will proceed further only if the user is of age 18 and above , the contract will also give exactly 1 numerical vote to each adhar id , in this way the problem of double-spending will be resolved and also we will remove the chance of frauds by using authentication methods, these votes will be added to the blocks and will become part of the blockchain.

# Benefits
1)Even though the blockchain process is very secure the verification at the very starting will make the process double secure.

2)Sending a sms is very cheap and is easily affordable so many costs will be reduced.

3)Using blockchain will keep the process transparent and anonymous.

4)The low turnout is generally from urban areas now-a-days because of their busy schedule but this method will be very easy and quick(hardly 30 seconds)

# Resources to be used
1)Microsoft Azure

2)sms enabler(http://smsenabler.com/) or any such application

3)DBMS(Microsoft Access, mySql or any such application)

4)https://data.gov.in/ for linking adhar
