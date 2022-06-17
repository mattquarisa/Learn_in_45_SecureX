# Learn in 45: Building Process Automation Workflows with SecureX Orchestration

Thank you for joining the SecureX Orchestration Learn in 45 session! This repository contains sample code that you can import into SecureX to play a Blackjack style card game with the Cisco Action Orchestrator. We will have you test out this workflow during the session to win prizes!

## Getting Started

If you haven't already, clone this repository onto your local machine. You can do this by selecting *Download ZIP*, or through your bash shell if you have git installed locally.


![S1](/images/Git-Clone.png)


First, let's navigate to the dCloud instance of SecureX we will use for orchestration. Navigate to [dCloud](https://dcloud.cisco.com/) and search SecureX Orchestration in the catalog. Select and launch the *Cisco SecureX Orchestration v1 - Instant Demo*.


![S2](/images/dCloud-SecureX.png)


After launching SecureX, navigate to the Orchestration tab. Here, you will see all the SecureX Orchestration workflows that you have created.


![S3](/images/Orchestration-Workflows.png)


Select *Import* and then *Browse*. You will have the option to import a JSON file from your local desktop into SecureX. Select  the black-jack.json file you downloaded at the start.  Make sure to select **Import as a New Workflow** - this is needed because we will all be sharing the same dCloud SecureX environment.


![S4](/images/Import-Workflow.png)


After importing the JSON file, select the new workflow that will appear in your menu to view in detail. Let's edit the title to make it distinguishable from other's importing the same.


![S5](/images/Adjust-Title.png)


If you run this workflow as is, you'll notice a final block will fail that involves sending the output to Webex. This is because the existing workflow does not have the Webex Room ID or Webex Bot authentication token. You set these by navigating to *Variables* and assigning a value to each of these. Using the Webex Bot token and Room ID provided during the session, copy/paste these into the value field of each.


![S6](/images/Set-Variables.png)


![S7](/images/Set-Webex-Auth.png)


You should now be all set to run the script! Select *Run* and enter in values into the two input variables - Participants and Cards to Draw. Select a number of cards between two and four.


![S8](/images/Run.png)


You should now see the cards you've drawn displayed in the Learn in 45 Webex group!


## Platforms used in these modules

[SecureX](https://developer.cisco.com/securex/)

[SecureX Orchestration](https://developer.cisco.com/securex/orchestration/)

## Getting help

Having issues with a lab, or just getting started? Reach out to Matt Quarisa (mquarisa@cisco.com)
