# Test Report

## Component Testing

We did a lot of the data validation for the animal shelter and with doing this part of the project came a lot of testing on our end. The validation code is constantly changing based on what we need to complete. With changing the data validation constantly comes a lot of new testing. We did not us J-Unit or any other test software. The way we tested the code was by writing the input in a notebook and checking to see if the validation method was doing what it needed to do. If it worked for the output that we tested, then it should also work in the main program. We used a lot of print statements to test where the invalid input was located to make sure that our methods were catching the invalid characters if anything was found, and it would show use what index the invalid input was at. We used these print statements to verify that the input was invalid, and then we would scratch the invalid input from the notebook.  

After testing with these above methods, we started to make individual test files that ran through all code branches. As errors were found they were fixed immediately. Fortunately, we weren't as prone to errors as we anticipated. The GUI was the source of most errors, but the problems were not usually central to the functionality, and moresoe towards the front-end, quality of life improvements. 

## System Testing

In our project we performed system testing through testing the full functionality of our GUI. We selected testing based on what the user or admin can input into the GUI. Whenthe admin opens the interface they are prompted to either add, delete or edit a customer’s profile from the database. Based on these interactions with the user we created test cases that fully test the compatibility of adding, deleting and editing a profile. For example, the testing data we used is dummy profiles. These profiles are implemented by name, address, pets, strikes, withdrawals, if fixed and if proof of income exists. Most of these fields have specific parameters, so to thoroughly check the functionality we tested empty and invalid parameters in each data entry for a profile. Just to make sure that the GUI didn’t crash if the admin tried to input something where they weren’t supposed to. The results of the testing data gave a prompt saying “Invalid Data” or simply showing null for empty fields. Overall, the choice to use dummy profiles was a favorable choice because when working with GUI’s that's what its main purpose is going to be and we need to make sure that the admin doesn’t run into any system failures when utilizing this app, especially in a business setting. 

## Acceptance Testing

### Test objectives:  
• How the test will be run 
• What criteria will be used to determine when the testing is 
complete

### 1: Ease of Use
This simplicity of this program was tested by timing how long it would take to do a standard action (such as adding or removing an owner, or editing an attribute). We ensured that it took no longer then 10 seconds to complete these standard actions (tester has full understanding of how the GUI works). We repeated the testing with a 5 second requirement after we were able to get ten seconds consistantly.

    Objective: Ensure time to do any action is acceptable.
    Test: Print testing result in a file. Attempt to search, edit, and save an owner. 
    Criteria: Action takes no more than 10 (then 5) seconds to complete. 
    Status: Passed.

### 2: Data Validation
We ensured that whenever data is changed or written to the database, the user will see clearly that such action has taken place. Testing this requires a print statement to verify whenever data was altered, which we then assessed in terms of what the user needs to know. Generally, all date manipulation has been signified to the person using this software. 

    Objective: Insure at the front and back end, saved data is asknowledged or ensured.
    Test: Save data in all ways possible, especially data that should not be saved. Run a random name generator into the data validation.
    Criteria: Test will be complete if zero faults are recovered after testing 100,000 names.
    Status: Passed.

### 3: Security

Security concerns have been lowered as we communicated with the customer. However we have implemented archive features so that even if the data is changed in some manner, the person who has this software can look back in their records. 

    Objective: See how easy it is to change data by accessing files.
    Test: Access files and change data.
    Criteria: null
    Status: In progress/ passed. Due to scope constraints, we have not added additional security measures beyond the password projection of the user's personal computer. We have hidden the files containing metadata and the main database so these files will not be mistakenly altered. 

### 4: Intuitiveness

This was tested by having testers use our software without instruction and seeing if they can intuitively use the software. We only told them what the software is supposed to do, not how to do it. Our software appears to be very easy to use and understand.

    Objective: Ensure software is not confusing.
    Test: Use testers.
    Criteria: Testers have no questions about the actions they are taking.
    Status: Passed

### 5: Speed

We have done very little testing for speed simply because the software is already fast enough in all cases. We did however isolate some operations that could be done fast (search function and file reading/writing operations).

    Objective: Ensure the software doesn't slow or stutter.
    Test: Output analysis.
    Criteria: Ensure operations are O(n) time at least. 

### 6: Confidence in Manipulation

As previously mentioned, we have ensured that the user is notified when any changes are made to the data. We also have added popup text when the user hovers over a button so they can see additional material related to the function of the software. 

    Objective: Ensure person using the software is not ever concerned about actions they are taking.
    Test: Ensure appropriate popup windows open suring data manipulation.
    Criteria: Ensure all branches are accessed in  data manipulation actions and that anytime the csv is changed the user is notified.
    Status: Passed

### [Back](https://diegomorales30.github.io/NullPointersWebsite/)