Test Report

Project Information

**Project Name: PetsMeet Mobile Application** **& PetsMeet website [www.petsmeet.org](http://www.petsmeet.org)** 

PetsMeet is a social network mobile application for pet owners and animal lovers, where users can create a profile for their pets, connect with other pet owners in their local area and beyond, share photos and videos, participate in a variety of fun and informative discussions, and find and share information about local pet-friendly places.

The PetsMeet website ([www.petsmeet.org](http://www.petsmeet.org)) has all the information about the application, and detailed information about it can be obtained through the contact form. The site also has direct links to the application on the App Store and Google Play.

**The team assigned:** QA member** Aleksandra Karić

Document overview

Scope 

- Sign Up flow and email validation
- Sign In - Change languages
- Reset password functionality
- Home Tab: 
  - Recommended for you
  - Create, Edit, and Delete posts, Comment on posts;
  - Add new conversations, edit and delete messages;
  - Notifications
- Explore tab
  - Search field
  - Explore our partners
  - Map
  - Cats and Dogs - 20 take-care tips
  - Explore
- Pet page
  - Walk Pet notification
  - Walk Pet invitation
  - Lost Pet - information and contact
- Profile Tab
  - Settings/Security
    - Change password
    - Delete account
    - Delete pet account
  - Settings/Contact us
  - Settings/Log Out
  - Add picture
  - Update Profile
  - Achievements
  - Add pet
  - Pet Profile
    - Add picture
    - Match Pet 
    - Lost/Found Pet
    - Profile icon




- Web stranica 

Not in scope 

- Create Reels
- Reels Tab
- App in detail on Serbian and German Language
- Achievements (Followers, Follows, Reels)
- Performance testing

Test Objectives

How many defects were found: 22

Critical: 2

High: 7

Medium: 2

Low priority: 11

Functional: 12

Non-functional: 10

The number of test cases executed: 65

The number of test cases passes: 43

The number of test cases fails: 22

Pass percentage: 66,2 %

Fail percentage: 33,8 %

**Comments (Blocker and Critical)**: 

1. The user can’t reset the password and, therefore can’t sign in. On the ***Reset password screen*** when the user enters the valid email the outline of the ***EMAIL*** field turns red and the error message “***Email already exists***” appears under it. This is a critical bug that is a blocker. 
1. The app crashes when the user adds two lost pets. On the ***Lost pet screen (Pet page)*** information overlaps and alternates, causing the application to crash. 

Defects:

Total number of bugs: 21 

Breakdown by priority. and functional and non-functional bugs.

There are 12 functional bugs of which 2 are critical, 6 are high, and 3 are low.

There are 10 non-functional bugs of which 1 is high, 2 are medium, and 7 are low. 

It is important to fix the ***reset password*** functionality in this sprint.

Testing Execution

Regression: PetsMeet basic functionality

Feature/Function: 

Testing Execution Details

Test Suits:

Number of tests by type:

- passed: 43
- failed: 22 
- skipped: 2 

The defects are listed by Tabs/Screens and by priority/severity.

Sign Up Screen

1\. 

**Summary:**  Sign Up | Typo error ***“You have a account?”*** under the *Continue* button. It appears on the first and the next screen.

**Actual result:** The text is ***“You have a account?”***

**Priority/Severity:** Low/Low

2\. 

**Summary:**  Sign Up(“Do you have a pet?” screen) | The user is not redirected to the Create pet screen for the second time.

**Actual result:** The user stays on the same page.

**Priority/Severity:** High/High

**Attachment: [YesPetButton.mp4**](https://drive.google.com/file/d/1s-DjwzTilFG2TJtTR7ZU_1SKMH1nkjR5/view?usp=drive_link)**

Sign In Screen

1\.

**Summary:** Sign In | The two messages “Field is required.” under username and password field are not translated when changing the language.

**Actual result:** The message  “Field is required.” stays in the default language or previously selected after tapping on the SIGN IN button.

**Priority/Severity:** Medium/Low


2\.

**Summary:** Sign In | The ***Forgot your password*** link is inactive after the user taps the ***Sign-in*** button, then the ***Sign-up*** link, and then ***the Cancel*** button. 

**Actual result**: The ***Forgot your password*** link is inactive.

**Priority/Severity**: High/High

**Attachment:   [Forgot password_inactive link.mov](https://drive.google.com/file/d/1LGJwJOS3NwJvIQhFWv3AxgJXVcVwVTqB/view?usp=drive_link)**

3\.

**Summary:** Sign In |** Typo error ***“You don’t have a account?”*** before the SignUp link.

**Actual result:** The text is ***“You don’t have a account?”***

**Priority/Severity:** Low/Low


Reset Password Screen

1\.

**Summary:** Reset password screen | The user is not redirected to the new screen with the message “The code for resetting the password is sent to your email”.

**Actual result:** The user stays on the reset password page without a displayed message, the ***EMAIL*** field’s outline turns red and the message “***Email already exists***” appears under it. The ***SEND EMAIL*** button responds on tap, but the user stays on the same screen. Additionally, there is no email with the recovering code in the user’s inbox.

**Priority/Severity:** Critical/Critical


Home Tab 

1\.

**Summary:** Home Tab | It is possible to comment on posts with the enabled TURN OFF COMMENT button.

**Actual result:** The followers can leave comments.

**Priority/Severity:** High/High

**Attachment: [TurnOffCommentButton .mp4](https://drive.google.com/file/d/14DYfX-E2mipht_V1FHEfQPGm0EID5uHM/view?usp=drive_link)**

2\.

**Summary:** Home tab | The video from a post is not visible.

**Actual result:** The post is displayed, but the video is not visible and cannot be played.

**Priority/Severity:** High/High

**Attachment: [VideoPostNotVisible.mp4](https://drive.google.com/file/d/1zKvUbLCDFcaNGsd214PehEnfQXt6-rW9/view?usp=drive_link)**

Explore our partners (Explore Tab)

1\.

**Summary:** Explore our partners (Explore Tab) | In the Pet Shops category is a list of parks for pets.

**Actual result:** There is a list of parks for pets and it is written in the Serbian language even though it is an English language selected. 

**Priority/Severity:** Medium/Low


2\.

**Summary:** Explore our partners (Explore tab) | In the Vets category is a list of pet shops.

**Actual result:** There is a list of pet shops and it is written in the Serbian language even though it is an English language selected.

**Priority/Severity:** Medium/Low

Walk Pet (Pet page)

1\.

**Summary:** Walk Pet (Pet page) | Walk Pet invitation is created in past time and the snackbar message is displayed in a different language.

**Actual result:** The snackbar with the message “Uspešno poslato” is displayed.

**Priority/Severity:** Low/Low

**Attachment: [WalkPetInvitationInPast.mp4**](https://drive.google.com/file/d/1WsghNk5ykzSJMSG6Ipm4zQ1Jl0hAlktV/view?usp=drive_link)**

Lost Pet (Pet page)

**1.**

**Summary:** Lost pet (Pet page) | Lost pet information overlaps and alternates, causing the application to crash.

**Actual result:** The information overlaps and alternates on the screen after which the application crashes.

**Priority/Severity:** Critical/Critical

**Attachment: [TwoLostPetsAppCrashesmp4.mp4](https://drive.google.com/file/d/14SLNSUijwoitlnPSLzwmesIADf9vqM5J/view?usp=drive_link)**

**2.**

**Summary:** Lost pet (Pet page) | The Lost pet notification is displayed twice on the user’s profile

**Actual result:** There are two same Lost pet notifications.

**Priority/Severity:** Low/Low

**Attachment: [LostPetInfoDuplicate.mp4**](https://drive.google.com/file/d/1JWNj1sIrh8AhKKVx9IS0IZCCCNKYAI3d/view?usp=drive_link)**

Profile Tab

1\.

**Summary:** Profile tab | The user’s profile contains the message button, and the follow/unfollow button when tapping the Profile icon from Pet Profile.

**Actual result:** The user is redirected to the profile that contains the message button, and the follow/unfollow button instead of the Achievements and Update Profile buttons. 

**Priority/Severity:** Medium/Medium

Achievements (Profile Tab)

1\.

**Summary:** Achievements (Profile Tab) |**  The Pets status does not change when the user achieves goals.

**Actual result:** The progress bar and achievement goal of ***Pets*** are not changed.

**Priority/Severity:** Low/Low

**Attachment: [PetsAchievementsNoWorking.mp4](https://drive.google.com/file/d/1C_aBjmL5ANu31J5Xh0bOwba_bosN-sVQ/view?usp=drive_link)**

2\.

**Summary:** Achievements (Profile Tab) |**  The Posts status does not change when the user achieves goals.

**Actual result:** The progress bar and achievement goal of ***Posts*** are not changed.

**Priority/Severity:** Low/Low

**Attachment: [PostsAchievementsNoWorking.mp4](https://drive.google.com/file/d/1XfrYKjpUlTMnE8Cw_p5z-YNRR3V3zZi4/view?usp=drive_link)**

Pet Profile (Profile Tab)

1\.

**Summary:**  Pet Profile (Profile Tab) | Female sign is displayed instead of Male next to the pet name with leaving gender option by default(Male).

**Description:** When the user creates a pet leaving the gender field by default (The gender field is displayed as Male by default) Female sign ♀ is displayed on the pet profile. The same situation happens when the user creates a male pet by selecting a Male option from the gender dropdown menu

**Actual result:** There is a Female sign.

**Priority/Severity:** High/High

**Attachment: [MaleGenderByDefaultDisplayedFemale.mp4**](https://drive.google.com/file/d/15DYgOPsjHWISyfw8w-8wwa-rK7noPC_R/view?usp=drive_link)**

2\.

**Summary:** Pet Profile (Profile Tab) | The video post is not displayed

**Actual result:** There is no added post.

**Priority/Severity:** Medium/Medium

**Attachment: [VideoPostNotVisible.mp4](https://drive.google.com/file/d/1zKvUbLCDFcaNGsd214PehEnfQXt6-rW9/view?usp=drive_link)**

3\.

**Summary:** Pet Profile (Profile Tab) | The user profile icon is not visible when the pet type and breed have 26 or more letters in the line.

**Actual result:** The Profile icon is not displayed.

**Priority/Severity:** Low/Medium


4\.

**Summary:** Pet Profile (Profile Tab) | The pet's name goes beyond the boundary of its field covering the gender sign when has 25 or more characters.

**Actual result:** The pet's name goes beyond the boundary of its field covering the gender sign

**Priority/Severity:** Low/Low

**Attachment:**

Match Pet (Pet Profile)

1\.

**Summary:**  Match pet (Pet Profile/Profile Tab) | No pets found with ideal generated pets

**Actual result:** The message “Pets not found.“ is displayed.

**Priority/Severity:** High/High

Web Site Home Page

1\.

**Summary:** Home page of website | The sidebar menu does not close after tapping any options from it.

**Actual result:** After the user taps the option from the sidebar menu it stays open and its background covers the entire screen.

**Priority/Severity:** High/High



Test Environment

Devices: Mobile iPhone 8, screen resolution: 750px × 1334px,  iOS 16.6

Tools: No used 

Recommendations:

As a priority, increase account security through email validation and privacy through regulation of follow-up requests and options that only followers can see certain details (e.g.: Pet Walk Invitation, every user can see the time, date, and place where is the user).

Additionally, check the gender option in Add Pet if it saves the Male options. This bug is high severity if it is directly linked to Match Pet functionality. In ideal conditions, Match Pet functionality does not show the expected results

From the user's point of view, it is important to organize the partner information from the Explore our Partners tab and insert a location filter in each tab. 

Add some extra features to manage posts/reels.

**1.**

**Current:**  After registration, the greeting email is sent for account registration.

**Requested:** Create a button or a text link Verify for verifying the account in the greeting email. When the user taps/clicks on a button or text link it redirects to the new tab with the message “Thank you for your registration. Sign in and explore the pets world. ” 

**Reason:** It will improve the security of users. In History Version, v1.0.5. is added a new feature: "Added email validation feature for improved security."

2\.

**Current:** When the user opens the Map Tab it shows the device's location, not the pet's location, and it is not linked with the location of partners or pet-friendly places.

**Requested:** Remove the map and add a filter by location in every list of Vets, Adoption, Pet Friendly, Pet Shop, and Groomers in the ***Explore our partners*** section.

**Reason:** The sections in ***Explore our partners*** are clearly presented and divided according to the pet's needs, and if a location filter is added, the user will be able to find the location needed easily. 

3\. 

**Current:** The user cannot edit a post.

**Requested:** Add an **edit option** in the posts menu.

**Reason:** The user can easily change post details with this option.

4\. 

**Current:** The user cannot edit the option for comments in the post menu, although when preparing the post it says that it can be changed later with an option from the post menu.

**Requested:** Add an **edit option** in the posts menu.

**Reason:** The user can manage comments for posts with this option.

5\. 

**Current:** When creating a post user can only choose an image from the gallery and not a video.

**Requested:** Allow users to upload videos from the gallery.

**Reason:** The Petsmeet is a relatively new app and users want to upload some old videos of their pets. Also, many users can pre-edit videos in special video editors, and then upload them to the Petsmeet. 

Exit Criteria

There are 2 critical issues, both in the application.  

