## User Stories

## [Test Report](https://diegomorales30.github.io/NullPointersWebsite/testreport)

# Component Testing

We did a lot of the data validation for our animal shelter and with doing this part of the project came a lot of testing on our end. The validation code is constantly changing based on what we need to complete. With changing the data validation constantly comes a lot of new testing. We did not us J-Unit or any other test software. The way we tested the code was by writing the input in a notebook and checking to see if the validation method was doing what it needed to do. If it worked for the output that we tested, then it should also work in the main program. We used a lot of print statements to test where the invalid input was located to make sure that our methods were catching the invalid characters if anything was found, and it would show use what index the invalid input was at. We used these print statements to verify that the input was invalid, and then we would scratch the invalid input from the notebook.  

# System Testing

In our project we performed system testing through testing the full functionality of ourGUI. We selected testing based on what the user or admin can input into the GUI. Whenthe admin opens the interface they are prompted to either add, delete or edit a customer’sprofile from the database. Based on these interactions with the user we created test casesthat fully test the capability of adding, deleting and editing a profile. For example, thetesting data we used is dummy profiles. These profiles are implemented by name, address,pets, strikes, withdrawals, if fixed and if proof of income exists. Most of these fields havespecific parameters, so to thoroughly check the functionality we tested empty and invalidparameters in each data entry for a profile. Just to make sure that the GUI didn’t crash ifthe admin tried to input something where they weren’t supposed to. The results of thetesting data gave a prompt saying “Invalid Data” or simply showing null for empty fields.Overall, the choice to use dummy profiles was a favorable choice because when workingwith GUI’s that's what its main purpose is going to be  and we need to make sure that theadmin doesn’t run into any system failures when utilizing this app, especially in a businesssetting.

# Acceptance Testing

