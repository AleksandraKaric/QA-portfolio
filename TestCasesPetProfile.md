
Test Case ID: **TC001**

Test Priority (Low/Medium/High): **Medium**

Test Case Name: **Verify if all elements are visible and displayed correctly on the Pet profile with a long name.**

Description: **Create a pet with a long pet username and pet name and verify if the pet info is visible and displayed correctly**




` `Test Designed by: **Aleksandra Karić**

Test Designed date: **12.09.2023**

Test Executed by: Aleksandra Karić

Test Executed date: 1.10.2023.



|No|Test Steps|Test Data|Expected Result|
| :-: | :- | :- | :- |
|1|Go to the Profile Tab||The User is on the Profile Tab|
|2|Tap the Add pet button||The screen for creating a pet is open|
|3|Tap on the pet type|Cat|The outline of Cat image turns blue|
|4|Tap the ***Pet username*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|5|In the **Pet username** enter valid data with 25 characters that contain lowercase letters, numbers, and underscore.|Enter a valid data|The entered data is displayed|
|6|Tap the ***Pet name*** field||Text cursor appears and the text placeholder moves to the upper side of the field’s outline.|
|7|In the **Pet name** enter valid data with 25 characters that contain letters|Enter a valid data|The entered data is displayed|
|8|From the ***Breed*** dropdown menu choose an option that contains a large number of characters |Japanese Bobtail (longhair)|The selected breed is visible in the ***Breed*** dropdown menu  |
|9|Tap the ***Birthday*** field||The Calendar is opened|
|10|Tap on the Birthday field||In the Birthday field displayed current date|
|11|Tap on the pencil icon to manually enter the date from a keyboard.||The calendar form is changed to enter the date manually in the format **mm/dd/yyyy**|
|12|Tap on the date, enter valid data in the format **mm/dd/yyyy** and tap OK button|Enter a valid data|The entered data is displayed in the ***Birthday*** field|
|13|Tap the ***CITY*** field||The user is redirected to the Search Locations screen |
|14|In the search location box enter valid data |bel|The list of locations that match the entered data is displayed |
|15|Tap the desired location|Belgrade, Serbia|The user is redirected to the previous screen and the selected location is visible in the ***CITY*** field|
|16|Tap ***ADD PET*** button||The user is redirected to the Home Tab|
|18|Tap the Profile tab||The Profile tabis open and the created pet is displayed|
|17|Tap on the Pet icon||The user is switched to the Pet profile|
|18|Verify the entered data||All provided data are correct and displayed |

` `Comments:

- There is a bug in step 18. On the Pet profile pet's name goes beyond the boundary of its field covering the gender sign.














Test Case ID: **TC002**

Test Priority (Low/Medium/High): Medium

Test Case Name: **Add the pet’s image on the Pet Profile by taking a photo.**

Test Designed by: **Aleksandra Karić**

Test Designed date: **12.09.2023.**

Test Executed by: Aleksandra Karić 

Test Executed date: 17.09.2023.

Precondition: The user has at least one pet created and it is on the Profile Tab


|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the pet profile||The user is on the pet profile|
|2|Tap the camera icon||The menu with two options is opened. |
|3|Tap the “**Take photo**” option.||The phone camera is activated.|
|4|Take a photo.||A menu with two options for further action is opened.|
|5|Tap on the “**Retake**” option.||The phone camera is activated.|
|6|Take a photo||A menu with two options for further action is opened.|
|7|Tap the “**Use Photo**” option.||The user is redirected to the pet profile and the picture is uploaded.|
|8 |Tap the camera icon||The menu with two options is opened. |
|9|Tap the “**Choose from gallery**” option.||The phone gallery is opened.|
|10|Tap on the photo||The user is redirected to the pet profile and the picture is uploaded|





Test Case ID: **TC003**

Test Priority (Low/Medium/High): Medium

Test Case Name: **Change the pet’s profile picture by choosing a photo from the gallery.**


Test Designed by: **Aleksandra Karić**

Test Designed date: **12.09.2023.**

Test Executed by: Aleksandra Karić 

Test Executed date: 17.09.2023.




Precondition: The user has at least one pet created that has a profile picture uploaded and it is on the Profile Tab.


|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the pet profile||The user is on the pet profile|
|2|Tap the camera icon||The menu with two options is opened. |
|3|Tap the “**Choose from gallery**” option.||The phone gallery is opened.|
|4|Tap on the photo||The user is redirected to the pet profile and the picture is uploaded|








































Test Case ID: **TC004**

Test Priority (Low/Medium/High): High

Test Case Name: **Find a matching pet using the ideal generated pet.**

Description: 

Test Designed by: **Aleksandra Karić**

Test Designed date: **15.9.2022.**

Test Executed by: Aleksandra Karić

Test Executed date: 17.09.2023.




Precondition: The user has two pets, female and male, of the same breed, and in the same location.


|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the pet profile||The pet profile screen is open|
|2|Tap on the Match pet icon||The Match pet screen is open|
|3|From the Breed dropdown menu select the breed|The same breed as a first pet|The selected breed is visible in the field|
|4|From the Gender of pet dropdown menu choose a gender.|Choose the opposite gender from the first pet|The selected gender is visible in the field|
|5|From the Radius dropdown menu choose a value.|Select the first value from the list. At this moment it is 10.|The selected value is visible in the field.|
|6|Tap on the SEARCH button||A list of matching pets is displayed, including the user's second pet.|

Comment:

- There is a bug in step 6, no pets are found even with ideal-generated pets.



Test Case ID: **TC005**

Test Priority (Low/Medium/High): **High**

Test Case Name: **Find a matching pet using random data from the dropdown menus.**

Description: **Verify that the Match pet function is working using random data with the highest radius value.**

Test Designed by: **Aleksandra Karić**

Test Designed date: **15.9.2023**

Test Executed by: Aleksandra Karić

Test Executed date: 17.09.2023.


Precondition: The user has at least one pet.


|No|Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1|Go to the pet profile||The pet profile screen is open|
|2|Tap on the Match pet icon||The Match pet screen is open|
|3|From the Breed dropdown menu select the breed|Choose random data|The selected breed is visible in the field|
|4|From the Gender of pet dropdown menu choose a gender.|Choose the opposite gender from the pet|The selected gender is visible in the field|
|5|From the Radius dropdown menu choose the highest value.|At this moment it is 500.|The selected value is visible in the field.|
|6|Tap on the SEARCH button||If there is a matching pet, a list of pets is displayed. If there is no matching pet, the message “Pets not found” is displayed.|

