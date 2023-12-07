# PetBite Usability Evaluation

## Table of Contents
* [User Goals](#user-goals)
* [Scenarios](#scenarios)
* [User Types](#user-types)
* [Conset](#consent)
* [Recruitment](#recruitment)
* [Participant Description](#participant-descriptions)
* [Test Locations](#test-locations)
* [Test Script](#test-script)
* [Raw Data](#raw-data)
* [Results](#results)



## User Goals
- Able to quickly upload/modify their pet's information (name, breed, weight, age, etc...).
- Able to easily view and add their pet's activities.
- Able to maintain an accurate and consistent daily feeding schedule for their pet.
- Able to add multiple different pets and track them seperately

## Scenarios
### Task: Quickly upload/modify pet's information

Scenario: Imagine you are a pet owner and recently discovered the PetBite app. You log in and are prompted to add your pet information to begin using the app. Add pet information and begin using the app. 
<br> Successful behavior: Successfully entering all required pet's information quickly and create a profile.

### Task: Able to easily view and add their pet's activities

Scenario: You were told that the PetBite app has a way to add and track pet activities and you think it's a good way to ensure your pet is getting the exercise it needs. Add a pet activity and view its details. 
<br> Successful behavior: Successfully create pet activities and able to view and keep track of them easily.

### Task: Able to create and maintain a consistent daily feeding schedule for the user to follow 

Scenario: You were told that there is a way to establish and keep track of a feeding schedule for your pet in the PetBite app. Create a feeding schedule for the week.
<br> Successful behavior: User is able to input feeding schedule information for the week

### Task: Able to add multiple different pets and keep track of them seperately

Scenario: Imagine that you are the owner of multiple pets. Many of these pets have different schedules so it's not as easy to keep track of their food intake, activities throughout the week, and feeding is not as simple as feeding everyone at "lunchtime". Add an additional pet(s) and add activities and a feeding schedule for it. 
<br> Successful behavior: User is able to add and track multiple different pets. 

## User Types
Pet owners, and potential pet adopters.

## Consent

[Consent form](consent/Recording_consent_form_PetBite.pdf)
<br>
[Signed participants' consent forms](https://github.com/PetBite/petbite.github.io/tree/main/consent)


## Recruitment
- Ask people around us like friends classmates, and family members
- Post on online pet's communities

## Participant descriptions
- A - Non-pet owner
- B - Experienced pet owner - Slightly overweight dog
- C - Non-pet owner
- D - Experienced pet owner - Healthy turtle and cat
- E - Aspiring pet owner
- F - Experienced pet owner - Healthy dog
- G - Experienced pet owner - Slightly overweight cat
- H - Non-pet owner

## Test Locations

Tests took place at the test user's homes. Tests were conducted either individually with provided instructions, or online with live communication and screen sharing. 

## Test Script

The first 2 sections of this evaluation.md file were used as the test script throughout the tests. 

## Raw Data

<b> A (Emulator): </b>
- Task 1: User went through the input fields and filled them out normally, then clicked the submit button. 
- Task 2: User added an activity and was able to view it easily. 
- Task 3: Screen was bugged and user was not able to add a feeding schedule effectively. 
- Task 4: User was able to find the add pet option and added a pet normally.

<b> B (Emulator): </b>
- Task 1: User went through the input fields and filled them out normally (albeit with wacky information due to lack of form validation), then clicked the submit button. 
- Task 2: User added an activity and was able to view it, although they didn't realise how they viewed the activity initially.
- Task 3: Screen was bugged and user was not able to add a feeding schedule. 
- Task 4: User was able to find the add pet option and added a pet normally, but noted that it would be better if there was a more clear indicator of the "Your Pets" dropdown menu.

<b> C (Own device): </b>
- Task 1: User went through the input fields and filled them out normally, then pressed the submit button. 
- Task 2: User added an activity but could not figure out how to view the detailed information. 
- Task 3: User was able to add entries to the schedule through trial and error despite bugs with the screen (It was not easy or fast). 
- Task 4: User was unable to find the "Your Pets" dropdown menu without guidance, but noted that it's easy to understand once you know how, and was able to add additional pets once there. 

<b> D (Own device): </b>
- Task 1: User went through the input fields and filled them out with their own pet's information, then pressed the submit button. 
- Task 2: User added an activity and was able to view the detailed information easily.  
- Task 3: User was able to add entries to the schedule through trial and error despite bugs with the screen. Wanted the page to be synced with the current day, as each time he went back to the main schedule page it would default to Monday. 
- Task 4: User was able to figure out how to add additional pets, but noted that it would be better if there was a more clear indicator of the "Your Pets" dropdown menu.

<b> E (Emulator): </b>
- Task 1: User went through the input fields and filled them out normally, then pressed the submit button. 
- Task 2: User added an activity, but took a little bit to figure out how to view the detailed information.
- Task 3: Screen was bugged and user was not able to add a feeding schedule. 
- Task 4: User was able to find the add pet option and added a pet normally. 

<b> F (PetBite team member device): </b>
- Task 1: User went through the input fields and filled them out with their own pet's information, then pressed the submit button. 
- Task 2: User added an activity, but was unable to figure out how to view the detailed information without guidance. 
- Task 3: User attempted to add information to the feeding schedule but was unable to add information easily due to a bug. 
- Task 4: User was unable to find the "Your Pets" dropdown menu without guidance, but was able to add another pet once there.

<b> G (Own device): </b>
- Task 1: User went through the input fields and filled them out easily. 
- Task 2: User added an activity and was able to view the detailed information easily. 
- Task 3: Added schedule information but noted that it was confusing to setup because it was difficult to tell which meal they were inputting information for, but liked how simple it was. 
- Task 4: User was able to add an additional pet and noted the "Your Pets" dropdown menu was nice and convenient.

<b> H (Own device): </b>
- Task 1: User went through the input fields and filled them out easily. 
- Task 2: User added an activity and was able to view the detailed information, but noted it was slightly confusing to figure out what information to add. 
- Task 3: User was able to add information to the feeding schedule but ran into a bug on the screen making it difficult. 
- Task 4: User felt the "Your Pets" dropdown menu was difficult to find. They also noted it was difficult to figure out which pet you were editing information for. 

## Results

### Top 3 Usability Problems
1. [Address bug discovered on deployed app in Edit Feeding Schedule page](https://github.com/PetBite/app/issues/112)
2. [Make functionality of components more obvious through appearance/design](https://github.com/PetBite/app/issues/113)
3. [Change submit and reset buttons' locations to be more natural](https://github.com/PetBite/app/issues/114)
