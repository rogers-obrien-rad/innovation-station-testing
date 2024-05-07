# Testing Instructions: Creating a Challenge - Desktop
This set of instructions asks the user to test the various functionalities related to creating a challenge on the Innovation Station.

These instructions can also be found online [here](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/01_instructions.md).

## 🔑 Login
_Navigate to the Innovation Station and login with a dummy account_
1. On the web browser of your choosing, input the following URL: https://ro-innovation-station.flutterflow.app/
2. You will see a login prompt. Use the credentials provided by R&D. 

You should be logged in! Feel free to explore the site before continuing.

## 💪 Create Your Challenge
_Submit an challenge to the platform_

Navigate to the challenge create page. There are multiple ways to accomplish this task; feel free to use any method. You will know you are on the correct page if you see the "Challenge" icon of two mountains with a flag on the summit.

### Basic Information
1. **Thumbnail**: Change the default thumbnail to an image of your choosing. You can use the [sample thumbnail](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/03_sample_thumbnail_challenge.png) provided in this kit. 
2. **Title**: Enter a title for your challenge. You can use the template provided in [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt) to help you; anything will do though.
3. **Tagline**: Enter a tagline or objective for your challenge. You can use the template provided in [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt) to help you; anything will do though.
4. **Description**: Enter a description for your challenge. You can use the template provided in [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt) to help you; anything will do though.
5. **Host Department**: Check that the host department is set to "R&D". Try to change the host department and, if you cannot, use the information icon to understand why.

### Dynamic Fields
The following three fields on the Create Challenge form -- Guidelines, Judging Criteria, and Prizes -- function in a similar manner. For each one, you will be Performing the same three tasks: Add, Edit, and Delete. Although the process is similar, it is important to test all three since each section was built separately and could have unique issues that the others do not. 

#### Guidelines
1. **Add Guideline**: Tap the banner to "Add Guideline". Enter a guideline and then confirm. You can create any guideline you like or use one provided in the [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt).
2. **Edit Guideline**: Edit the guideline you just created. Please replace at least a part of the text you entered previously with something new. You can use more sample text provided [here](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt). Confirm the change and check to make sure your guideline text updated. 
3. **Delete Guideline**: Tap the "Add Guideline" banner again to add a second guideline. You can write anything you like or use one provided in the [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt). Once you confirm the guideline, delete it or the guideline your previously created. Ensure you have at least one guideline at the end of this process.

#### Judging Criteria
1. **Add Criterion**: Tap the banner to "Add Criterion". Enter a criterion and then confirm. You can create any criterion you like or use one provided in the [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt).
2. **Edit Criterion**: Edit the criterion you just created. Please replace at least a part of the text you entered previously with something new. You can use more sample text provided [here](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt). Confirm the change and check to make sure your criterion text updated. 
3. **Delete Criterion**: Tap the "Add Criterion" banner again to add a second criterion. You can write anything you like or use one provided in the [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt). Once you confirm the criterion, delete it or the one your previously created. Ensure you have at least one criterion at the end of this process.

#### Prizes
1. **Add Prize**: Tap the banner to "Add Prize". Enter a prize and then confirm. You can create any prize you like or use one provided in the [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt).
2. **Edit Prize**: Edit the prize you just created. Please replace at least a part of the text you entered previously with something new. You can use more sample text provided [here](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt). Confirm the change and check to make sure your prize text updated. 
3. **Delete Prize**: Tap the "Add Prize" banner again to add a second prize. You can write anything you like or use one provided in the [sample text](https://github.com/rogers-obrien-rad/innovation-station-testing/blob/main/kits/create-challenge-desktop/02_sample_text.txt). Once you confirm the prize, delete it or the one your previously created. Ensure you have at least one prize at the end of this process.

### Timeline
1. **Submission Start**: Choose a Submission Start date for your challenge. 
2. **Submission End**: Choose a Submission End date for your challenge.
3. **Voting Start**: Choose a Voting Start date for your challenge.
4. **Voting End**: Choose a Voting End date 
5. **Winner(s) Announced**: Choose a date to announce the winner

### Create Challenge
_Review and create your challenge_

#### Testing Scenarios - Choose ONE
Before creating the challenge, we are going to ask you to test one of the following scenarios below that will not allow you to proceed with the creation. You only need to perform _one_ of these scenarios; you will not be able to provide feedback on more than one of these scenarios.
* **Remove Text Box**: Scroll to any of the Title, Tagline, or Description Text Box Inputs and delete the text you have entered. Scroll back down and try to re-submit - you should not advance to the Success screen. Scroll back to the text entry box that you deleted information from and you should see red text appear beneath the text entry box. Re-input your information (or something similar). 
* **Delete Dynamic Field**: Delete all of one of Guidelines, Judging Criteria, or Prizes. Scroll back down and try to re-submit - you should not advance to the Success screen. You should be prompted to add at least one of the fields you deleted.
* **Timeline Discrepancy**: The milestones in the "Timeline" are shown in chronological order i.e. the milestone directly below another _has_ to be fall on a later date. Choose any of Sumbmission End, Voting Start, Voting End, or Winner(s) Announced and change the day to one that is earlier than the preceeding milestone. Scroll back down and try to re-submit - you should not advance to the Success screen. You should be prompted to change the date of the invalid milestone. Select that milestone and change the date to a valid selection.

#### Create the Challenge
1. Tap the "Create Challenge" Button.
2. If any issues persist, either a banner at the bottom of your screen or red text below a text entry box should indicate which field is giving you an error. 
3. If you were successful, you should see a success screen showing the title of your challenge and the timeframe over which it is being conducted. 

## ✔️ View and Verify your Challenge
_Review the idea you submitted and ensure all the information is correct_
1. If you are still on the submission success screen, you should see a button to take you to the challenge that you just created. If not, you will need to find your challenge.
2. **Verify Thumbnail**: Ensure the thumbnail you provided is prominently displayed as the backdrop of the page.
3. **Verify Title and Tagline**: Ensure your title is correct and the tagline/objective is correct below the title.
4. **Verify Timeline**: Ensure the dates for each of your milestones is correct.
4. **Verify Description**: Ensure the description of your idea is correct and displayed when you first navigated to the page. 
5. **Verify Guidelines, Judging Criteria, and Prizes**: Ensure the number and text of each of these fields is correct. 

## 📝 Feedback
Thank you for following the steps above and submitting one of the first ideas to the Innovation Station! 

Please use this [form](https://forms.office.com/r/dgN5RjGNUv) to answer questions about the process you just went through so that we might improve the Innovation Station. You will be asked to sign into your RO account and we will record your name and email with your submission. 
