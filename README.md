# Learn in 45: Building Process Automation Workflows with SecureX Orchestration

Thanks for joining the SecureX Orchestration Learn in 45 session! This repository contains sample code that you can import into SecureX to play a Blackjack style card game with the Cisco Action Orchestrator. We'll be having you try out this workflow during the session to win prizes!

## Getting Started

First, let's navigate to the dCloud instance we'll use to try out SecureX Orchestration. Navigate to [dCloud](https://dcloud.cisco.com/) and search SecureX Orchestration in the catalog. Select and launch the "Cisco SecureX Orchestration v1 - Instant Demo".

![S1](/images/dCloud-SecureX.png)

After launching SecureX, navigate to the Orchestration tab. Here, you will see all the SecureX Orchestration workflows that you have created.

![S2](/images/Orchestration-Workflows.png)

Select the Import button and then Browse. You will now be able to import the JSON file from this Github into SecureX. Make sure to select "Import as a new workflow" - this is needed because we will all be sharing the same dCloud SecureX environment. You can either import the file directly, or copy/paste the text into the window.

![S3](/images/Import-Workflow.png)

After importing the JSON file, select the new workflow that will appear in your menu. You will now be able to edit your imported workflow. Next, let's adjust the title to make it distinguishable from other's importing the same workflow.

![S4](/images/Adjust-Title.png)

If you run this workflow as is, you'll notice a final block will fail that involves sending the output to Webex. This is because the existing workflow does not have the Webex Room ID or Webex Bot authentication token set. You can do this by scrolling down to variables and setting a value of each of these. Using the Webex bot token and room ID provided during the session, copy/paste these into the value field of each.

![S5](/images/Set-Variables.png)

![S6](/images/Set-Webex-Auth.png)

You should now be all set to run the script! Select Run and enter in values into the two input variables - Participants and Cards to Draw. Select a number of cards between two and four.

![S6](/images/Run.png)

You should now see the cards you've drawn displayed in the Learn in 45 Webex group!

## Platforms used in these modules

[SecureX](https://developer.cisco.com/securex/)

[SecureX Orchestration](https://developer.cisco.com/securex/orchestration/)

## Getting help

Having issues with a lab, or just getting started? Reach out to Matt Quarisa (mquarisa@cisco.com)
