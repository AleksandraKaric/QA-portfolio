Bug Report Document (iPhone 8, iOS 16.6)

**ID: 1**

**Operating system: iOS 16.6** 

**Summary:** Sign In |** Typo error ***“You don’t have a account?”*** before the SignUp link.

**Steps to reproduce:** 

1. Open app
1. Pay attention to the message before the Sign Up link 

**Expected result:** It should write ***“You don’t have an account?”***

**Actual result:** The text is ***“You don’t have a account?”***

**Priority/Severity:** Low/Low

**Attachment:**


**ID: 2**

**Operating system: iOS 16.6** 

**Summary:** Sign In | The two messages “Field is required.” under username and password field are not translated when changing the language.

**Description:** When the user taps the SIGN IN button leaving the username and password field empty the message “Field is required.” appears under them in the default language. When the user changes the language every text on the screen is translated except those two messages. When the user taps again SIGN IN button the messages are translated. This situation is repeated after changing languages.

**Steps to reproduce:** 

1. Open the app.
1. Tap on the ***SIGN IN*** button.
1. Change the language and pay attention to the messages.
1. Tap on the ***SIGN IN*** button and pay attention to the messages
1. Change the language again and pay attention to the messages.

**Expected result:** The message  “Field is required.” is translated with the rest of the text on the screen.

**Actual result:** The message  “Field is required.” stays in the default language or previously selected after tapping on the SIGN IN button.

**Priority/Severity:** Medium/Low

**Attachments**:




**ID: 3**

**Operating system: iOS 16.6** 

**Summary:** Reset password screen | The user is not redirected to the new screen with the message “The code for resetting the password is sent to your email”

**Description:** After the user enters a valid email the outline of the ***EMAIL*** field turns red and the error message “***Email already exists***” appears under it. The ***SEND EMAIL*** button responds on tap, but the user stays on the same screen. 

**Preconditions**: The user already has an account and it’s logged out.

**Steps to reproduce:** 

1. Open the app.
1. Tap on the ***Forgot your password*** link.
1. In the email field enter a valid email address.
1. Tap the ***SEND EMAIL*** button

**Expected result:** The user is redirected to the new screen with the message “The code for resetting the password is sent to your email” displayed, and in the user’s inbox is an email with the code for resetting the password.

**Actual result:** The user stays on the reset password page without a displayed message, the ***EMAIL*** field’s outline turns red and the message “***Email already exists***” appears under it. The ***SEND EMAIL*** button responds on tap, but the user stays on the same screen. Additionally, there is no email with the recovering code in the user’s inbox.

**Priority/Severity:** Critical/Critical

**Attachments**: [ResetPasswordNoWorking.mov](https://drive.google.com/file/d/1He8oPvuIpwo89Nn8OYxKk9bHktL7YFzW/view?usp=drive_link)


**ID**: **4**

**Operating system**: iOS 16.6 

**Summary**: Sign In | The ***Forgot your password*** link is inactive after the user taps the ***Sign-in*** button, then the ***Sign-up*** link, and then ***the Cancel*** button. 

**Precondition:** The app should be newly installed with no previous data of using it.

**Steps to reproduce**: 

1. Open the app.
1. On the Sign-In Screen tap the ***Sign-in*** button
1. On the Sign-In Screen tap the ***Sign-up*** link
1. On the Terms and Conditions Screen tap the ***Cancel*** button.
1. On the Sign-In Screen tap the ***Forgot your password*** link 

**Expected result**: When the user taps on the ***Forgot your password*** link a screen for password reset opens.

**Actual result**: The ***Forgot your password*** link is inactive.

**Priority/Severity**: High/High

**Attachment:   [Forgot password_inactive link.mov](https://drive.google.com/file/d/1LGJwJOS3NwJvIQhFWv3AxgJXVcVwVTqB/view?usp=drive_link)**


**ID: 5**

**Operating system: iOS 16.6** 

**Summary:**  Sign Up | Typo error ***“You have a account?”*** under the *Continue* button. It appears on the first and the next screen.

**Steps to reproduce:** 

1. Open the app
1. Tap the Sign Up link.
1. Scroll to the bottom of the screen 
1. Pay attention to the text before the Sign-in link.

**Expected result:** It should write ***“You have an account?”.***

**Actual result:** The text is ***“You have a account?”.***

**Priority/Severity:** Low/Low

**Attachment:**  



`            `First screen                            Next screen



**ID:** 6

**Operating system: iOS 16.6** 

**Summary:** Achievements (Profile Tab) |**  The Pets status does not change when the user achieves goals.

**Precondition:** The** user is signed in and has no pet yet.

**Steps to reproduce:** 

1. On the Profile tab pay attention that there is no pet.
1. Tap on Achievements
1. Scroll down to the ***Pets*** bar and pay attention to the progress bar
1. Go back and add a pet
1. Tap the Profile tab and then Achievements
1. Scroll down to the ***Pets*** bar and pay attention to the progress bar

**Expected result:** The progress bar of ***Pets*** will change and the Achievement goal will go to the next stage. 

**Actual result:** The progress bar and achievement goal of ***Pets*** are not changed.

**Priority/Severity:** Low/Low

**Attachment: [PetsAchievementsNoWorking.mp4](https://drive.google.com/file/d/1C_aBjmL5ANu31J5Xh0bOwba_bosN-sVQ/view?usp=drive_link)**


**ID**: 7

**Operating system: iOS 16.6** 

**Summary:** Achievements (Profile Tab) |**  The Posts status does not change when the user achieves goals.

**Precondition:** The** user is signed in and has at least one pet.

**Steps to reproduce:** 

1. On the Profile tab pay attention to the number of posts.
1. Tap on Achievements
1. Scroll down to the ***Posts*** bar and pay attention to the progress bar
1. Go back and add as many posts as needed so the goal is achieved.
1. Tap the Profile tab and then Achievements
1. Scroll down to the ***Posts*** bar and pay attention to the progress bar

**Expected result:** The progress bar of ***Posts*** will change and the Achievement goal will go to the next stage. 

**Actual result:** The progress bar and achievement goal of ***Posts*** are not changed.

**Priority/Severity:** Low/Low

**Attachment: [PostsAchievementsNoWorking.mp4](https://drive.google.com/file/d/1XfrYKjpUlTMnE8Cw_p5z-YNRR3V3zZi4/view?usp=drive_link)**


**ID:** 8

**Operating system: iOS 16.6** 

**Summary:** Pet Profile (Profile Tab) | The user profile icon is not visible when the pet type and breed have 26 or more letters in the line.

**Preconditions:** The user is signed in.

**Steps to reproduce:** 

1. Open the app.
1. Go to the Profile tab.
1. Tap on the Add pet button
1. Choose the image of the pet type (e.g. pet type: Parrot)
1. In the Pet username*** field enter a minimum of valid characters
1. In the Pet name*** field enter a minimum of valid characters
1. Choose a breed with a long name (e.g. pet type: Parrot, pet breed: Rose-ringed parakeet).
1. Fill the birthday field with valid data
1. Fill the City field with valid data

`       `10. Tap the ADD PET button

`       `11. Go to the Profile tab and then to Pet Profile

**Expected result:** The Profile icon is visible.

**Actual result:** The Profile icon is not displayed.

**Priority/Severity:** Low/Low

**Attachment:**



**ID:** 9

**Operating system: iOS 16.6** 

**Summary:** Pet Profile (Profile Tab) | The pet's name goes beyond the boundary of its field pushing the gender sign out of the screen when has 25 or more characters.

**Preconditions:** The user is signed in.

**Steps to reproduce:** 

1. Open the app.
1. Go to the Profile tab.
1. Tap on the Add pet button
1. Choose the image of the pet type (e.g. pet type: Cat)
1. In the **Pet username** enter valid data with 25 characters that contain lowercase letters, numbers, and underscore
1. In the **Pet name** enter valid data with 25 characters that contain letters
1. In the Pet name*** field enter a minimum of valid characters
1. From the ***Breed*** dropdown menu choose an option that contains a large number of characters 
1. Fill the birthday field with valid data
1. Fill the City field with valid data
1. Tap the ADD PET button
1. Go to the Profile tab and then to Pet Profile

**Expected result:** The pet’s name is correctly displayed.

**Actual result:** The pet's name goes beyond the boundary of its field covering the gender sign

**Priority/Severity:** Low/Low

**Attachment:**




**ID:** 10

**Operating system: iOS 16.6** 

**Summary:** Profile tab | The user’s profile contains the message button, and the follow/unfollow button when tapping the Profile icon from Pet Profile.

**Description:** When the user taps on the Profile icon from Pet Profile it takes him to the profile that contains the message button, and the follow/unfollow button instead of the Achievements and Update Profile buttons. 

**Precondition:** The user is signed in and has one pet.

**Steps to reproduce:** 

1. Go to the Pet Profile
1. Tap the User Profile icon
**


**Expected result:** The link takes the user to the profile where are displayed the Achievements and Update Profile buttons.

**Actual result:** The user is redirected to the profile that contains the message button, and the follow/unfollow button instead of the Achievements and Update Profile buttons. The user can follow himself.
**


**Priority/Severity:** Medium/Medium

**Attachment:**




**ID:** 11

**Operating system: iOS 16.6** 

**Summary:** Lost pet (Pet page) | The Lost pet notification is displayed twice on the user’s profile

**Precondition:** The user is signed in and has at least one pet.

**Steps to reproduce:** 

1. Open Pet Profile
1. Tap on the **Lost Pe**t icon and Yes
1. Go back to the **Profile Tab**
1. Tap **Pet page**
1. Tap the **Lost pet** option.
**


**Expected result:** The info about the Lost pet is displayed.

**Actual result:** There are two same Lost pet notifications.
**


**Priority/Severity:** Low/Low

**Attachment: [LostPetInfoDuplicate.mp4**](https://drive.google.com/file/d/1JWNj1sIrh8AhKKVx9IS0IZCCCNKYAI3d/view?usp=drive_link)**

**ID:** 12

**Operating system: iOS 16.6** 

**Summary:** Lost pet (Pet page) | Lost pet information overlaps and alternates, causing the application to crash.

**Precondition:** The user is signed in and has two pets.

**Steps to reproduce:** 

1. Open the Pet Profile of the first pet
1. Tap on the Lost pet icon
1. Tap Yes on confirmation message
1. Tap the back on the Notification screen
1. Go back to the **Profile Tab**
1. Open the Pet Profile of the second pet
1. Tap on the Lost pet icon
1. Tap Yes on confirmation message
1. Tap the back on the Notification screen
1. Go back to the **Profile Tab**
1. Tap **Pet page Tab**
1. Tap the **Lost pet** option.

**Expected result:** The info about the Lost pets is displayed.

**Actual result:** The information overlaps and alternates on the screen after which the application crashes.
**


**Priority/Severity:** Critical/Critical

**Attachment: [TwoLostPetsAppCrashesmp4.mp4](https://drive.google.com/file/d/14SLNSUijwoitlnPSLzwmesIADf9vqM5J/view?usp=drive_link)**


**ID:** 13

**Operating system: iOS 16.6** 

**Summary:** Walk Pet (Pet page) | Walk Pet invitation is created in past time and the snackbar message is displayed in a different language.

**Preconditions:** The user is signed in and has at least one pet.

**Steps to reproduce:** 

1. Open app
1. Tap the Pet page.
1. Tap Walk Pet.
1. Create an invitation and set the time to the past hour 
1. Tap Send button.

**Expected result:** The snackbar is displayed  with the message “You can’t create an invitation in past time.”

**Actual result:** The snackbar with the message “Uspešno poslato” is displayed.

**Priority/Severity:** Low/Low

**Attachment: [WalkPetInvitationInPast.mp4**](https://drive.google.com/file/d/1WsghNk5ykzSJMSG6Ipm4zQ1Jl0hAlktV/view?usp=drive_link)**


**ID:** 14

**Operating system: iOS 16.6** 

**Summary:** Explore our partners (Explore Tab) | In the Pet Shops category is a list of parks for pets.

**Preconditions:** The user is signed in.

**Steps to reproduce:** 

1. Open app
1. Tap the Explore tab.
1. From Explore our partners choose Pet Shops.
1. Pay attention to the content

**Expected result:** The Pet Shop category contains the list of pet shops that are partners of PetsMeet.

**Actual result:** There is a list of parks for pets and it is written in the Serbian language even though it is an English language selected.  

**Priority/Severity:** Medium/Low

**Attachment:** 



**ID:** 15

**Operating system: iOS 16.6** 

**Summary:** Explore our partners (Explore tab) | In the Vets category is a list of pet shops.

**Preconditions:** The user is signed in.

**Steps to reproduce:** 

1. Open app
1. Tap the Explore tab.
1. From Explore our partners choose Vets.

**Expected result:** The Vets category contains the list of veterinary clinics and veterinarians that are partners of PetsMeet.

**Actual result:** There is a list of pet shops and it is written in the Serbian language even though it is an English language selected.  

**Priority/Severity:** Medium/Low

**Attachment:**



**ID:** 16

**Operating system: iOS 16.6** 

**Summary:** Home Tab | User can comment on posts with the Turn off comment function.

**Preconditions:** There are two accounts. The first user has created a post with the Turn off comment function. The second user follows the first one.

**Steps to reproduce:** 

1. Open the app with the second account.
1. Tap the Explore Tab
1. Tap on the Search button
1. In the Search field enter the first user’s username.
1. Tap on the first user’s username.
1. Tap on the pet profile from which the post was created and find the post
1. Tap on the comment button and leave a comment.

**Expected result:** The post is closed for comments.

**Actual result:** The followers can leave comments.

**Priority/Severity:** High/High

**Attachment: [TurnOffCommentButton .mp4](https://drive.google.com/file/d/14DYfX-E2mipht_V1FHEfQPGm0EID5uHM/view?usp=drive_link)**


**ID:** 17

**Operating system: iOS 16.6** 

**Summary:** Home tab | The video from a post is not visible. 

**Description:** The video from the post is not visible and cannot be played. 

**Preconditions:** The user is signed in and has at least one pet.

**Steps to reproduce:** 

1. Open app 
1. Tap the Create post button and select the Create post option.
1. Tap Continue button
1. Tap on the video option
1. Make a video and tap a forward arrow sign
1. Tap Finish button 
1. Tap on the check mark sign

**Expected result:** The user is switched to the Home Tab and the video post is displayed.

**Actual result:** The post is displayed, but the video is not visible and cannot be played.

**Priority/Severity:** High/High

**Attachment: [VideoPostNotVisible.mp4](https://drive.google.com/file/d/1zKvUbLCDFcaNGsd214PehEnfQXt6-rW9/view?usp=drive_link)**





**ID:** 18

**Operating system: iOS 16.6** 

**Summary:** Pet Profile (Profile Tab) | The video post is not displayed

**Description:** The video post is displayed on the Home Tab, it shows one post number on the Profile tab, but is not displayed on the Pet Profile.

**Precondition**: The user is signed in and has at least one pet.

**Steps to reproduce:** 

1. Open app
1. Tap the Profile Tab and pay attention to the number of posts
1. Tap Home tab
1. Create a video post
1. Tap the Profile tab and pay attention to the number of posts
1. Tap on the Pet Profile and pay attention to posts.

**Expected result:** The post is displayed on Pet Profile.

**Actual result:** The video post is not visible on the Pet Profile.

**Priority/Severity:** Medium/Medium

**Attachment: [VideoPostNotVisible.mp4](https://drive.google.com/file/d/1zKvUbLCDFcaNGsd214PehEnfQXt6-rW9/view?usp=drive_link)**



**ID:** 19

**Operating system: iOS 16.6** 

**Summary:** Home page of website | The sidebar menu does not close after tapping any options from it.

**Description:** When the user taps on the sidebar menu its background covers the entire screen and the content behind is barely visible and inactive.

**Steps to reproduce:** 

1. In the mobile browser enter [www.petsmeet.org](http://www.petsmeet.org)
1. Tap the sidebar menu
1. Choose any options from the sidebar menu.

**Expected result:** When the user taps on an option on the sidebar menu, the link takes him to the corresponding option, and the sidebar menu closes.

**Actual result:** After the user taps the option from the sidebar menu it stays open and its background covers the entire screen.

**Priority/Severity:** High/High

**Attachment: [SidebarMenu.mp4](https://drive.google.com/file/d/1G6seYBTVqDQTIOSpYjtIs3N1vnZ8ro1s/view?usp=drive_link)**



**ID:** 20

**Operating system: iOS 16.6** 

**Summary:**  Pet Profile (Profile Tab) | Female sign is displayed instead of Male next to the pet name with leaving gender option by default(Male).

**Description:** When the user creates a pet leaving the gender field by default (The gender field is displayed as Male by default) Female sign ♀ is displayed on the pet profile. The same situation happens when the user creates a pet by selecting a Male option from the gender dropdown menu

**Steps to reproduce:** 

1. Open the app
1. Tap the Profile tab.
1. Tap Add pet
1. Choose the image of the pet type
1. In the Pet username*** field enter a minimum of valid characters
1. In the Pet name*** field enter a minimum of valid characters
1. Choose a breed 
1. Fill the birthday field with valid data
1. Fill the City field with valid data
1. Tap the ADD PET button
1. Tap the Profile tab.
1. Tap the created Pet profile and pay attention to the sign next to the pet name.

**Expected result:** The Male sign is displayed.

**Actual result:** There is a Female sign.

**Priority/Severity:** High/High

**Attachment: [MaleGenderByDefaultDisplayedFemale.mp4**](https://drive.google.com/file/d/15DYgOPsjHWISyfw8w-8wwa-rK7noPC_R/view?usp=drive_link)**


**ID:** 21

**Operating system: iOS 16.6** 

**Summary:**  Match pet (Pet Profile/Profile Tab) | No pets found with ideal generated pets

**Precondition:** The user has two pets, female and male, of the same breed, and in the same location.. 

**Steps to reproduce:** 

1. Open the app
1. Tap the Profile tab.
1. Tap on the pet icon
1. Tap on the Match pet icon
1. Choose the same breed
1. Choose the opposite gender
1. Choose a radius of 500
1. Tap Search button

**Expected result:** The list of matching pets is displayed.

**Actual result:** The message “Pets not found.“ is displayed.

**Priority/Severity:** High/High

**Attachment:** 


**ID:** 22

**Operating system: iOS 16.6** 

**Summary:**  Sign Up(“Do you have a pet?” screen) | The user is not redirected to the Create pet screen for the second time.

**Description:** When the user, from the Create a pet screen, goes back to the screen “Do you have a pet?” and taps the YES button again, it stays on the same screen and is not redirected to the Create pet screen. Additionally, the user is in the database and can sign in although it is not finished registration by creating a pet or tapping the NO button on the “Do you have a pet?” screen.

**Steps to reproduce:** 

1. Tap the Sign up link
1. Fill in all fields in the first step of registration and tap the CONTINUE button
1. Fill in all fields in the second step of registration and tap the CONTINUE button
1. Tap YES button
1. Tap on the go-back sign
1. Tap on the YES button

**Expected result:** The user is redirected to the Create pet page.

**Actual result:** The user stays on the same page.

**Priority/Severity:** High/High

**Attachment: [YesPetButton.mp4**](https://drive.google.com/file/d/1s-DjwzTilFG2TJtTR7ZU_1SKMH1nkjR5/view?usp=drive_link)**



