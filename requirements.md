## Requirements
## [Requirements](https://diegomorales30.github.io/NullPointersWebsite/requirements)

1. Introduction
    1.1 Purpose of Product
    This software is a utility for a pet food distribution center. The organization allows for low-income pet owners to recieve free pet food and must manage how much food is allocated to individuals based on the specifics of their pet and their need. We are creating both a database to record the people who revieve food, as well as a simple UI to display, change, and record the distribution to each individual.
    
    1.2 Scope of Product
    The scope is ostensibly small. We only need to record individuals and keep track of ~5 data members per individual. However, the ultimate goal here is ease of use, so a lot of our effort will be put into designing a smart and intuitive UI.
    
    1.3 Acronyms, Abbreviations, Definitions
    NULL

    1.4 References
    NULL

2. General Description of Product
    2.1 Context of Product
        This software will be one one computer, and one person will be using it. This is a stand-alone piece of software. 

    2.2 Domain Model 
        Graphic needed. 
        This model works as such:
            CSV <--Data Validation--> UI
    
    2.3 Product Functions
        Quickly record and update a person's use of free pet food distributor. 

    2.4 User Characteristics and Expectations
        The sole user is not assumed to be good at working on computers. Simple design is essential.

    2.5 Constraints
        Product is limited to time of submission, and it's limited to the abilities of the person who will use it, rather it should be simple since we should assume the person using it is not an intuitive software user. 

    2.6 Assumptions and Dependencies
        JRE 11+ and JavaFX SDK.

3. Functional Requirements
# [User Stories](https://diegomorales30.github.io/NullPointersWebsite/user)


4. System and Non-Functional Requirements
    4.1 External Interface Requirements 
        NF.4.1.1
            Person-machine interface. Customer will be interacting with software.
        NF.4.1.2
            CSV to UI.
            
    4.2 Performance Requirements
        NF.4.2.1
            Updated Windows or MacOs.

    4.3 Design Constraints
        NF.4.3.1
            UI must be efficent and not distracting. This means flashyness is not helpful. We must be muted in our design choices, focus on intuitiveness. 

    4.4 Quality Requirements
        NF.4.4.1
            While non-life-critical, this product could have financial implications if it does not work properly.
        NF.4.4.2
            Expected to be totally and completely accurate to the input of the person using this software. 

    4.5 Other Requirements
        NF.4.5.1
            NULL

5. Appendices