Bug Report Document (iPhone 8, iOS 16.6)


**ID: 1**

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



**ID: 2**

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



**ID: 3**

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




**ID: 4**

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



**ID: 5**

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



**ID: 6**

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


**ID: 7**

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


**ID: 8**

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




