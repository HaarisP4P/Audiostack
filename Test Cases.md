# Test Cases

These test cases have been created based off the acceptance criteria that was provided.

| **Test ID** | **Title** | **Summary** | **Prerequisites** | **Test Data** | **Steps** | **Expected Result** |
|-------------|-----------|--------------|--------------------|---------------|------------|---------------------|
| TC01 | Fields shown as required | Verify that both fields are shown as required on the form | User is on the registration page | N/A | Verify an asterisk is present next to field name  | Asterisk is present next to field name 
| TC02 | Enter name | Able to enter a name in the 'Name' field | User is on the registration page | TestName123 | Click on the 'Name' field and type name  | Name entered into field
| TC03 | Select Pokemon | Able to select different Pokemons | User is on the registration page | Bulbasaur, Charmandar, Squirtle, Pikachu | 1. Select 'Pokemon' from 'Starter Pokemon' dropdown field <br> 2. Repeat step 1 for remaining Pokemons | Pokemon selected and shown within field |
| TC04 | See selected Pokemon's stats | Able to see stats of selected Pokemon | User is on the registration page | Bulbasaur, Charmandar, Squirtle, Pikachu | 1. Select 'Pokemon' from 'Starter Pokemon' dropdown field <br> 2. Verify Pokemon stats are shown <br> 3. Repeat step 1-2 for remaining Pokemons | 1.Pokemon selected <br> 2. Stats shown |
| TC05 | Legible and consistent Pokemon stats | Pokemon stats are legible and consistent | User is on the registration page | Bulbasaur, Charmandar, Squirtle, Pikachu | 1. Select 'Pokemon' from 'Starter Pokemon' dropdown field <br> 2. Verify Pokemon stats are legible and consistent <br> 3. Repeat step 1-2 for remaining Pokemons | 1.Pokemon selected <br> 2. Stats are legible and consistent |
| TC06 | Successful registration | When submit button is clicked, user should be notified of successful registration | User is on the registration page | TestName123 Bulbasaur | 1. Enter name and Select 'Pokemon' from 'Starter Pokemon' dropdown field <br> 2. Click 'Submit' button <br> 3. Verify user is alerted of successful registration | 1. Name entered and Pokemon selected <br> 2. Submit button clicked <br> 3.Successful registration alert is shown |
| TC07 | 'Name' field value missing at submission | 'Name' field is empty when form is submitted | User is on the registration page | Bulbasaur | 1. Select 'Pokemon' from 'Starter Pokemon' dropdown field <br> 2. Click 'Submit' button <br> 3. Verify form is not submitted and error message is shown reffering to the 'Name' field  | 1. Pokemon selected <br> 2. Submit button clicked <br> 3.Registration is unsuccessful and error message is shown for the 'Name' field |
| TC08 | 'Pokemon' field value not selected at submission | Name is entered and 'Pokemon' not selected and value will remain 'Select your starter' | User is on the registration page | TestName123 | 1. Enter name <br> 2. Leave default value for 'Starter Pokemon' dropdown field <br> 3. Click 'Submit' button <br> 4. Verify form is not submitted and error message is shown referring to the 'Starter Pokemon' field | 1. Name entered <br>2. Pokemon not selected <br> 3. Submit button clicked <br> 4.Registration is unsuccessful and error message is shown for the 'Starter Pokemon' field|
| TC09 | Both fields left empty at submission | Name is not entered and 'Pokemon' not selected | User is on the registration page | N/A | 1. Do not enter name <br> 2. Leave default value for 'Starter Pokemon' dropdown field <br> 3. Click 'Submit' button <br> 4. Verify form is not submitted and error is shown reffering to both fields | 1. No name entered<br> 2. Pokemon not selected <br> 3. Submit button clicked <br> 4.Registration is unsuccessful and error message is shown for both fields |

###  Potential future test cases

After sessions with the team where BA/Product owner and designer are also present as well as developer and QA, design spec and business rules can be shared. So a developer knows what they are building and a QA knows what they are testing and against what.

There would be more detailed test cases including unhappy paths (negative test cases) - 

For e.g: 

**Form design** - layout, does form reset after submission 

**Enter name** -  what sort of validation is requitred, What special characters allowed? Min and Max characters.

**Select Pokemon** - Capital letters? When 'Select your starter' is chosen again does previosly selected Pokemon stats disapper?

**Pokemon stats** - Font style, color, size and spacing.

**Submitting form** - Alert type, style, position, does form reset?

**Missing fields when submitting** - Error message type, error message in-line with fields, 




