HAPPY PATH

Test Case ID: **TC001**

Test Priority (Low/Medium/High): **High**

Test Case Name: **Create an account with the required fields.**

Description: **Verify that a user can successfully sign up for an account with a pet filling the required fields and leaving the default option where there is.**





Test Designed by: **Aleksandra Karić**

Test Designed date: **10.09.2023.**

Test Executed by: **Aleksandra Karić**

Test Executed date: **11.09.2023.**




|No|Test Steps|Test Data|Expected Result|
| :-: | :- | :- | :- |
|1|Launch the application.||The application is open|
|2|Allow all necessary permissions ||The User is on the Sign In screen|
|3|Tap the **Sign up** link||<p>The “Terms and conditions” snackbar is displayed</p><p></p>|
|4|Tap the **CONFIRM** button||The User is redirected to the Sign up screen.|
|5|Tap the ***USERNAME*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|6|In the ***USERNAME*** field enter the minimum required characters (6) that contain lowercase letters, underscore, and number|Enter a valid data|The provided data is visible in the ***USERNAME*** field|
|7\. |Tap the ***E-MAIL*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|8|In the ***E-MAIL*** field enter a valid e-mail form |Enter a valid data|The provided data is visible in the ***E-MAIL*** field|
|9\.|Tap the ***PASSWORD*** field||Text cursor and eye icon appear, and the text placeholder moves to the upper side of the field’s outline.|
|10\.|In the ***PASSWORD*** field enter the minimum required characters (8) that contain uppercase letters, lowercase letters, and numbers.|Enter a valid data|The provided data is visible as dots in the ***PASSWORD*** field|
|11|Tap the ***CONFIRM PASSWORD*** field||The text cursor and eye icon appear, and the text placeholder moves to the upper side of the field’s outline.|
|12|In the ***CONFIRM PASSWORD*** field enter valid data |Enter a valid data|The provided data is visible as dots in the ***CONFIRM PASSWORD*** field|
|13|In the ***CONFIRM PASSWORD*** field tap on the eye icon||The password data is visible in the ***CONFIRM PASSWORD*** field|
|14|Tap the **CONTINUE** button||The user is redirected to the next Sign up screen|
|15|Tap the ***FIRST NAME*** field||Text cursor and the text placeholder moves to the upper side of the field’s outline.|
|16|In the ***FIRST NAME***  field enter valid data with the minimum characters that contain only the letter|Enter a valid data|The provided data is visible in the ***FIRST NAME*** field|
|17|Tap the ***LAST NAME*** field||Text cursor and the text placeholder moves to the upper side of the field’s outline.|
|18|In the ***LAST NAME***  field enter valid data with the minimum characters that contain only the letter|Enter a valid data|The provided data is visible in the ***LAST NAME*** field|
|19|Tap the ***CITY*** field||The user is redirected to the Search Locations screen |
|20|In the search location box enter valid data |pancevo|The list of locations that match the entered data is displayed |
|21|Tap the desired location|Pančevo, Serbia|The user is redirected to the previous screen and the selected location is visible in the ***CITY*** field|
|22|Tap the **CONTINUE** button||The user is redirected to the last Sign Up screen that contains the “Do you have a pet?” question.|
|23|Tap the YES button||The user is redirected to the screen for creating a pet|
|24|Choose the image of the pet type|Dog image|The outline of the chosen image turns blue|
|25|Tap the ***Pet username*** field.||The text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|26|In the ***Pet username*** field enter a minimum of 3 valid characters that contain lowercase letters, numbers, and underscore.|Enter a valid data|The provided data is visible in the ***Pet username*** field|
|27|Tap the ***Pet name*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|28|In the ***Pet name*** field enter valid data with minimum characters that contain only letters|Enter a valid data|The provided data is visible in the ***Pet name*** field|
|29|Tap the ***Birthday*** field||The Calendar is opened|
|30|On the calendar tap OK ||The current date is visible and the text placeholder moves to the upper side of the field’s outline|
|31|Tap the ***CITY*** field||The user is redirected to the Search Locations screen |
|32|In the search location box enter valid data |pancevo|The list of locations that match the entered data is displayed |
|33|Tap the desired location|Pančevo, Serbia|The user is redirected to the previous screen and the selected location is visible in the ***CITY*** field|
|34|Tap ***ADD PET*** button||The user is redirected to Home Tab|
|35|Tap the Profile Tab||The user is switched to Profile Tab|
|36|Verify provided data||All provided data are correct|
|37|Tap the Pet icon||The user is switched to Pet profile|
|38|Verify entered data||All provided data are correct|



Comment:

- In step 38 there is a bug, the female sign is displayed instead of a Male next to the pet name leaving the gender option by default(Male)


Test Case ID: **TC002**

Test Priority (Low/Medium/High): **High**

Test Case Name: **Create an account without a pet.**

Description: **Verify that a user can successfully sign up for an account without a pet.**

Test Designed by: **Aleksandra Karić**

Test Designed date: **10.09.2023.**

Test Executed by: **Aleksandra Karić**

Test Executed date: **11.09.2023.**



|No|Test Steps|Test Data|Expected Result|
| :-: | :- | :- | :- |
|1|Launch the application.||The application is open|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen.|
|3|Tap the ***USERNAME*** field||The text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|4|In the ***USERNAME*** field enter the maximum required characters (20) that contain lowercase letters, underscore, and number|Enter a valid data|The provided data is visible in the ***USERNAME*** field|
|5|Tap the ***E-MAIL*** field||The text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|6|In the ***E-MAIL*** field enter valid data |Enter a valid data|The provided data is visible in the ***E-MAIL*** field|
|7\. |Tap the ***PASSWORD*** field||The text cursor and eye icon appear, and the text placeholder moves to the upper side of the field’s outline.|
|8|<p>In the ***PASSWORD*** field enter the maximum required characters (32) that contain uppercase letters, lowercase letters, and numbers.</p><p></p>|Enter a valid data|The provided data is visible as dots in the ***PASSWORD*** field|
|9\.|In the ***PASSWORD*** field tap on the eye icon||The password data is visible in the ***PASSWORD*** field|
|10\.|Copy the password and paste it into the **CONFIRM**  ***PASSWORD*** field||The data is visible as dots in the ***CONFIRM PASSWORD*** field|
|11|Tap the **CONTINUE** button||The user is redirected to the next Sign up screen|
|12|Tap the ***FIRST NAME*** field||Text cursor and the text placeholder moves to the upper side of the field’s outline.|
|13|In the ***FIRST NAME*** field enter valid data with a large number of characters (>30) that contain only letters and space|Enter a valid data|The provided data is visible in the ***FIRST NAME*** field|
|14|Tap the ***LAST NAME*** field||Text cursor and the text placeholder moves to the upper side of the field’s outline.|
|15|In the ***LAST NAME***  field enter valid data with a large number of characters (>30) that contain only letters and space|Enter a valid data|The provided data is visible in the ***LAST NAME*** field|
|16|Tap the ***CITY*** field||The user is redirected to the Search Locations screen |
|17|In the search location box enter valid data |nis|The list of locations that match the entered data is displayed |
|18|Tap the desired location|Niš, Serbia|The user is redirected to the previous screen and the selected location is visible in the ***CITY*** field|
|19|From the Gender dropdown menu select gender|Male|The male gender is selected|
|20|Tap the **CONTINUE** button||The user is redirected to the last Sign Up screen that contains the “Do you have a pet?” question.|
|21|Tap the NO button||The user is redirected to the Home Tab|
|22|Tap on the Profile Tab||The user is switched to the Profile Tab|
|23|Verify provided data||The provided data are correct|






Test Case ID: **TC003**

Test Priority (Low/Medium/High): **High**

Test Case Name: **Inspect the button “go-back” and verify if the data are saved in the second and fourth phases of registration.**

Description: **Verify that the data is saved in the fields if the user goes back a step during registration using middle values in the fields.**




Test Designed by: **Aleksandra Karić**

Test Designed date: **10.09.2023.**

Test Executed by: **Aleksandra Karić**

Test Executed date: **11.09.2023.**




|No|Test Steps|Test Data|Expected Result|
| :-: | :- | :- | :- |
|1|Launch the application.||The application is open|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen.|
|3|Tap the ***USERNAME*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|4|In the ***USERNAME*** field enter mean values data (13) that contain lowercase letters, underscore, and number|Enter a valid data|The provided data is visible in the ***USERNAME*** field|
|5|Tap the ***E-MAIL*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|6|In the ***E-MAIL*** field enter valid data |Enter a valid data|The provided data is visible in the ***E-MAIL*** field|
|7\. |Tap the ***PASSWORD*** field||Text cursor and eye icon appear, and the text placeholder moves to the upper side of the field’s outline.|
|8|In the ***PASSWORD*** field enter mean values data (19) that contain uppercase letters, lowercase letters, and numbers.|Enter a valid data|The provided data is visible as dots in the ***PASSWORD*** field|
|9\.|In the ***PASSWORD*** field tap on the eye icon||The password data is visible in the ***PASSWORD*** field|
|10\.|Copy the password and paste it into the **CONFIRM**  ***PASSWORD*** field||The data is visible as dots in the ***CONFIRM PASSWORD*** field|
|11\. |Tap the **CONTINUE** button||The user is redirected to the next Sign up screen|
|12|Tap the ***FIRST NAME*** field||Text cursor and the text placeholder moves to the upper side of the field’s outline.|
|13|In the ***FIRST NAME***  field enter valid data with a number of characters between 2 and 30 that contain only letters|Enter a valid data|The provided data is visible in the ***FIRST NAME*** field|
|14|Tap the ***LAST NAME*** field||Text cursor and the text placeholder moves to the upper side of the field’s outline.|
|15|In the ***LAST NAME***  field enter valid data with a number of characters between 2 and 30 that contain only letters|Enter a valid data|The provided data is visible in the ***LAST NAME*** field|
|16|Tap the ***CITY*** field||The user is redirected to the Search Locations screen |
|17|In the search location box enter valid data |beo|The list of locations that match the entered data is displayed |
|18|Tap the desired location|Belgrade, Serbia|The user is redirected to the previous screen and the selected location is visible in the ***CITY*** field|
|19|From the Gender dropdown menu select gender|Female|Male gender is selected|
|20|Tap the go back sign||The user is redirected to the previous screen|
|21|Tap the **CONTINUE** button||The user is redirected to the next Sign up screen|
|22|Verify if the data are saved in the fields||The provided data are saved|
|23|Tap the **CONTINUE** button||The user is redirected to the last Sign Up screen that contains “Do you have a pet” question.|
|24|Tap the YES button||The user is redirected to the creating pet screen|
|25|Choose the pet type|Dog image|The outline of the chosen image turns blue|
|26|Tap the ***Pet username*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|27|In the ***Pet username*** field enter data between 10 and 20 characters that contain lowercase letters, numbers, and underscore.|Enter a valid data|The provided data is visible in the ***Pet username*** field|
|28|Tap the ***Pet name*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|29|In the ***Pet name*** field enter data between 10 and 20 characters that contain only letters.|Enter a valid data|The provided data is visible in the ***Pet name*** field|
|30|From the ***Breed*** dropdown menu choose an option|Select the last option on the list|The selected breed is visible in the ***Breed*** dropdown menu  |
|31|From the ***Gender*** dropdown menu choose an option|Select Female|The selected gender is visible in the ***Gender*** dropdown menu |
|32|Tap the ***Birthday*** field||The Calendar is opened|
|33|On the calendar choose the earliest date and tap OK|Select the 1.1.2000. date|The date is visible and the text placeholder moves to the upper side of the field’s outline|
|34|Tap the ***CITY*** field||The user is redirected to the Search Locations screen |
|35|In the search location box enter valid data |bel|The list of locations that match the entered data is displayed |
|36|Tap the desired location|Belgrade, Serbia|The user is redirected to the previous screen and the selected location is visible in the ***CITY*** field|
|37|Tap the go-back sign||The user is redirected to the previous screen|
|38|Tap the YES button||The user is redirected to the creating pet screen|
|39|Verify if the data are saved in the fields||The provided data are saved|



NEGATIVE TEST CASES




Test Case ID: **NTC001**

Test Priority (Low/Medium/High): **High**

Test Case Name: **The user can`t register with the blank fields**

Description: **Verify that the user can’t register with the blank field on the first screen of the registration form.**

Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:



|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Launch the application.||The User is on the Sign In screen|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen|
|3|Tap the **CONTINUE** button||The User is on the first screen of Sign up. The outlines of mandatory fields turn red, and the message “Field is required” is displayed under them. |

Test Case ID: **NTC002**

Test Priority (Low/Medium/High): **Low**

Test Case Name: **The user can’t add a username that contains less than is  required characters in the field “USERNAME”**

Description: **Verify that the user cannot add a username that contains less allowed characters than required.**



Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:



|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Launch the application.||The User is on the Sign In screen|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen|
|3|Tap the ***USERNAME*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|4|In the ***USERNAME*** field enter the less than required characters (6-20) that contain lowercase letters, underscores, and number|Enter a valid data|The provided data is visible in the ***USERNAME*** field, the outline of the field turns red and the message “*Username must contain 6-20 characters.*” appears under it.|

Test Case ID: **NTC003**

Test Priority (Low/Medium/High): **Low**

Test Case Name: **The user can’t add a username that contains more than is  required characters in the field “USERNAME”**

Description: **Verify that the user cannot add a username that contains more allowed characters than required.**


Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:



|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Launch the application.||The User is on the Sign In screen|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen|
|3|Tap the ***USERNAME*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|4|In the ***USERNAME*** field enter the fewer or more than required characters (6-20) that contain lowercase letters, underscores, and number|<p></p><p>Enter a valid data</p><p></p>|The provided data is visible in the ***USERNAME*** field, the outline of the field turns red and the message “*Username must contain 6-20 characters.*” appears under it.|





Test Case ID: **NTC004**

Test Priority (Low/Medium/High): **Low**

Test Case Name: **The user can’t add a username using unallowed characters in the field “USERNAME”**

Description: **Verify that the user cannot add a username that contains unallowed characters.**

Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:



|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Launch the application.||The User is on the Sign In screen|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen|
|3|Tap the ***USERNAME*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|4|In the ***USERNAME*** field enter the valid number of required characters (6-20) that contain uppercase letters, space, and special characters.|<p>Enter a valid data</p><p></p>|The provided data is visible in the ***USERNAME*** field, the outline of the field turns red and the message “*Username must contain only lowercase letters, numbers, and an underscore.*” appears under it.|

Comment:

The ***USERNAME*** field accepts special characters: -, ., \*, +, 




Test Case ID: **NTC005**

Test Priority (Low/Medium/High): **Medium**

Test Case Name: **The user can’t add a username that already exists.**

Description: 

Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:



|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Launch the application.||The User is on the Sign In screen|
|2|Tap the **Sign up** link||The User is redirected to the Sign up screen|
|3|Tap the ***USERNAME*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|4|In the ***USERNAME*** field enter the existing username|<p>Enter a valid data</p><p></p>|The provided data is visible in the ***USERNAME*** field, the outline of the field turns red and the message “*Username already exists*” appears under it.|





Test Case ID: **NTC006**

Test Priority (Low/Medium/High): **Low**

Test Case Name: **The user can’t add an invalid e-mail form in the field “E-MAIL”**

Description: 

Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:


|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the **Sign up** screen||The User is on to the Sign up screen|
|2|Tap the ***E-MAIL*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|3|In the ***E-MAIL*** field enter the invalid e-mail form.|<p>Enter a valid data</p><p></p>|The provided data is visible in the ***E-MAIL*** field, the outline of the field turns red and the message “*Enter a valid email. Valid email address example: example@email.com.*” appears under it.|




Test Case ID: **NTC007**

Test Priority (Low/Medium/High): **High**

Test Case Name: **The user can’t add an e-mail address from an existing account.**

Description:


Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:


|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the **Sign up** screen||The User is on to the Sign up screen|
|2|Tap the ***E-MAIL*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|3|In the ***E-MAIL*** field enter the existing e-mail address.|<p>Enter a valid data</p><p></p>|The provided data is visible in the ***E-MAIL*** field, the outline of the field turns red and the message “*Email already exists*” appears under it.|


Test Case ID: **NTC008**

Test Priority (Low/Medium/High): **High**

Test Case Name: **The** **user can’t add a password that contains less characters than required in the field “*PASSWORD*”**

Description: 



Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:




|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the **Sign up** screen||The User is on to the Sign up screen|
|2|Tap the ***PASSWORD*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|3|In the ***PASSWORD*** field enter less than required characters (8-32) that contain uppercase letters, lowercase letters, and numbers.|<p>Enter a valid data</p><p></p>|The provided data is visible in the ***PASSWORD*** field, the outline of the field turns red and the message “*Password must contain 8-32 characters.*” appears under it.|






Test Case ID: **NTC009**

Test Priority (Low/Medium/High): **High**

Test Case Name: **The** **user can’t add a password that contains more characters than required in the field “*PASSWORD*”**

Description: 




Test Designed by: **Aleksandra Karić**

Test Designed date: **16.9.2023**

Test Executed by:

Test Executed date:




|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the **Sign up** screen||The User is on to the Sign up screen|
|2|Tap the ***PASSWORD*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|3|In the ***PASSWORD*** field enter more than required characters (8-32) that contain uppercase letters, lowercase letters, and numbers.|<p></p><p>Enter a valid data</p><p></p>|The provided data is visible in the ***PASSWORD*** field, the outline of the field turns red and the message “*Password must contain 8-32 characters.*” appears under it.|

