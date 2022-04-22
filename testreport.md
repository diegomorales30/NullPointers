## User Stories

## [Test Report](https://diegomorales30.github.io/NullPointersWebsite/testreport)

# Component Testing

We did a lot of the data validation for our animal shelter and with doing this part of the project came a lot of testing on our end. The validation code is constantly changing based on what we need to complete. With changing the data validation constantly comes a lot of new testing. We did not us J-Unit or any other test software. The way we tested the code was by writing the input in a notebook and checking to see if the validation method was doing what it needed to do. If it worked for the output that we tested, then it should also work in the main program. We used a lot of print statements to test where the invalid input was located to make sure that our methods were catching the invalid characters if anything was found, and it would show use what index the invalid input was at. We used these print statements to verify that the input was invalid, and then we would scratch the invalid input from the notebook.  

# System Testing

In our project we performed system testing through testing the full functionality of ourGUI. We selected testing based on what the user or admin can input into the GUI. Whenthe admin opens the interface they are prompted to either add, delete or edit a customer’sprofile from the database. Based on these interactions with the user we created test casesthat fully test the capability of adding, deleting and editing a profile. For example, thetesting data we used is dummy profiles. These profiles are implemented by name, address,pets, strikes, withdrawals, if fixed and if proof of income exists. Most of these fields havespecific parameters, so to thoroughly check the functionality we tested empty and invalidparameters in each data entry for a profile. Just to make sure that the GUI didn’t crash ifthe admin tried to input something where they weren’t supposed to. The results of thetesting data gave a prompt saying “Invalid Data” or simply showing null for empty fields.Overall, the choice to use dummy profiles was a favorable choice because when workingwith GUI’s that's what its main purpose is going to be  and we need to make sure that theadmin doesn’t run into any system failures when utilizing this app, especially in a businesssetting.

# Acceptance Testing

1: Ease of Use
This simplicity of this program was tested rather simply. WE timed how long it would take to do a standard action (such as adding or removing an owner, or editing an attribute). WE ensured that it took no longer then ten seconds to complete these standard actions.

2: Data Validation
We ensured that whenever data is changed or written to the database, the user will see clearly that such action has taken place. Testing this required print statement to verify whenever data was altered, which we then assessed in terms of what the user needs to know. Generally, all date manipulation has been signified to the person using this software. 

3: Security

Security concerns have been lowered as we communicated with the customer. However we have implemented archive features so that even if the data is changed in some manner, the person who has this software can look back in their records. 

4: Intuitiveness

This was tested by having testers use our software without instruction and seeing if they can intuitively use the software. We only told them what the software is supposed to do, not how to do it. Our software appears to be very easy to use and understand.

5: Speed

We have done very little testing for speed simply because the software is already very fast.

6: Confidence in Manipulation

As previously mentioned, we have ensured that the user is notified when any changes are made to the data. We also have added popup text when the user hovers over a button so they can see additional material related to the function of the software. 