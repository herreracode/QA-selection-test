# Lang Test QA Suite
Demo test for new QAs.


## Getting started

Use this project to run the automated test in docker.
Commands:

docker exec -it name-of-container python3 -m pytest -rP test/name-of-test.py

## Test Cases

- Case 1: Fill out all fields of the "Practice Form" with random values.  
- Case 2: Fill out all the form fields to create a new user with random values.  
- Case 3: In the section Widgets/Select Menu, select the next values:  
    - Option Select Value: A root option  
    - Option Select One:  Ms.  
    - Option Old Style Select Menu: Indigo  
    - Option Multiselect drop down: Blue and Red,   
    - Option Standard multi select: Volvo and Opel.  
- Case 4: In the section Elements/Web Tables:  
    - Add a new element with random values.  
    - Edit the new element.  
    - Delete the new element.  
- Case 5: In the section Elements/Web Tables fill the new element form with incorrect format and empty fields.  
