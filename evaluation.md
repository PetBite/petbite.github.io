# PetBite Usability Evaluation Design

## User Goals
- Able to quickly Upload/modify their pet's information (name, breed, weight, age, etc...).
- Able to easily view and add their pet's activities.
- Able to maintain an accurate and consistent daily feeding schedule for their pet.
- ABle to add multiple different pets and track them seperately

## Scenarios
### Task: Quickly upload/modify pet's information

Scenario #1: Imagine you just adopted a new dog, but you never owned a pet before so you decided that you are going to use an app to help you with managing your dog's health. You found PetBite on the playstore and need to set up a profile for your new dog, including details like name, breed, age, etc... and you want to be able to do that quickly and easily so you can use all the functions of the app. Add a new pet and update its information.
<br> Successful behavior: Successfully entering all required pet's information quickly and create a profile.

### Task: Able to easily view and add their pet's activities

Scenario #1: Imagine you are a new pet owner and want to make sure your pet is meeting all their needs. You want to be able to keep track of your pets activities throughout the week so you can go back and check that they are meeting all their food and activity needs. Luckily, you've heard about the PetBite app and hear that there is a way to keep track of such activities. Add an activity or two to the pet activity list and view their information.
<br> Successful behavior: Successfully create pet activities and able to view and keep track of them easily.

### Task: Able to create and maintain a consistent daily feeding schedule for the user to follow 

Scenario #1: Imagine you are a new pet owner and while you've done your research, there's so much to keep track of. You heard of an app called PetBite from a friend and downloaded it. You want to be able to easily input times and amounts to feed your pet so when it's time to feed your pet you get a notification with details on how much to feed your pet. Create a schedule for your pet to follow throughout the week. 
<br> Successful behavior: New user is able to input feeding schedule information and receive notifications at the provided times

### Task: Able to add multiple different pets and keep track of them seperately

Scenario #1: Imagine that you are the owner of many different pets. You love animals and wanted to experience taking care of many different kinds of species. However, many of these pets have different schedules so it's not as easy to keep track of their food intake, activities throughout the week, and feeding is not as simple as feeding everyone at "lunchtime". Luckily, the PetBite app has the ability to add multiple pets and keep track of them at the same time. Add additional pets past the first one and add activities and a schedule to each of them.
<br> Successful behavior: User is able to add and track multiple different pets. 

## User Types
Pet owners, and potential pet adopters.

## Recruitment
- Ask people around us like friends classmates, and family members
- Post on online pet's communities

## Participant descriptions
A - Non-pet owner
B - Experienced pet owner
C - Non-pet owner
D - Experienced pet owner
E - Aspiring pet owner
F - Experienced pet owner
G - Experienced pet owner
H - Non-pet owner

## Test Locations

Tests took place at the test user's homes. Tests were conducted either individually with provided instructions, or online with live communication and screen sharing. 

## Test Script

The first 2 sections of this evaluation.md file were used as the test script throughout the tests. 

## Raw Data

A (Emulator)- Task 1: User went through the input fields and filled them out normally. Scenario 2: User added an activity and was able to view it easily. Scenario 3: Screen was bugged and user was not able to add a feeding schedule effectively. Scenario 4: User was able to find the add pet option and added a pet normally.

B (Emulator)- Scenario 1: User went through the input fields and filled them out normally (albeit with wacky information due to lack of form validation). Scenario 2: User added an activity and was able to view it, although they didn't realise how they viewed the activity initially. Scenario 3: Screen was bugged and user was not able to add a feeding schedule. Scenario 4: User was able to find the add pet option and added a pet normally, but noted that it would be better if there was a more clear indicator of the "Your Pets" dropdown menu.

C (Own device)- Scenario 1: User went through the input fields and filled them out normally. Scenario 2: User added an activity but could not figure out how to view the detailed information. Scenario 3: User was able to add entries to the schedule through trial and error despite bugs with the screen (It was not easy or fast). Scenario 4: User was unable to find the "Your Pets" dropdown menu without guidance, but noted that it's easy to understand once you know how, and was able to add additional pets once there. 

D (Own device) - Scenario 1: User went through the input fields and filled them out with their own pet's information. Scenario 2: User added an activity and was able to view the detailed information easily. Scenario 3: User was able to add entries to the schedule through trial and error despite bugs with the screen. Wanted the page to be synced with the current day, as each time he went back to the main schedule page it would default to Monday. Scenario 4: User was able to figure out how to add additional pets, but noted that it would be better if there was a more clear indicator of the "Your Pets" dropdown menu.

E (Emulator) - Scenario 1: User went through the input fields and filled them out normally. Scenario 2: User added an activity, but took a little bit to figure out how to view the detailed information. Scenario 3: Screen was bugged and user was not able to add a feeding schedule. Scenario 4: User was able to find the add pet option and added a pet normally. 

F (PetBite team member device) - Scenario 1: User went through the input fields and filled them out with their own pet's information. Scenario 2: User added an activity, but was unable to figure out how to view the detailed information without guidance. Scenario 3: User attempted to add information to the feeding schedule but was unable to add information easily due to a bug. Scenario 4: User was unable to find the "Your Pets" dropdown menu without guidance, but was able to add another pet once there.

G (Own device) - Task 1: User went through the input fields and filled them out easily. Task 2: User added an activity and was able to view the detailed information easily. Task 3: Added schedule information but noted that it was confusing to setup because it was difficult to tell which meal they were inputting information for, but liked how simple it was. Task 4: User was able to add an additional pet and noted the "Your Pets" dropdown menu was nice and convenient.

H (Own device) - Task 1: User went through the input fields and filled them out easily. Task 2: User added an activity and was able to view the detailed information, but noted it was slightly confusing to figure out what information to add. Task 3: User was able to add information to the feeding schedule but ran into a bug on the screen making it difficult. Task 4: User felt the "Your Pets" dropdown menu was difficult to find. They also noted it was difficult to figure out which pet you were editing information for. 

## Results

- Address bug discovered on deployed app in Edit Feeding Schedule page
- Make functionality of components more obvious through appearance/design
- Change submit button locations to be more natural
