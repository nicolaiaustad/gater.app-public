# Gater in GitHub - User Guide

## Why does Gater Exist

The rapid introduction of AI coding agents has transformed how software is built. 
While these tools are excellent at producing correct syntax, they often result in vibe coded designs that feel right but haven’t been deeply reasoned about. 
Vibe coding is acceptable for implementation details, but it becomes risky when applied to system architecture and design decisions. 

Gater exists to keep developers in the pilot seat.

## What is Gater

Gater is a tool to help developers validate their understanding of the code they have written before merging pull requests.

When a Pull Request is opened, Gater automatically generates a short quiz based on the changes in the PR. The PR owner must complete the quiz to demonstrate they understand the implications of their code before the PR can be approved or merged.


## Installation

### 1. Install Gater.app from https://github.com/marketplace

1. Navigate to https://github.com/apps/gater-app
2. Click **Install**
3. Select the repositories where you want Gater to exist
4. Click **Install & Authorize**

### 2. Install the Gater.app Chrome Extension

1. Download and unzip the `gater-chrome-extension.zip` file
2. Open Chrome and navigate to `chrome://extensions`
3. Enable **Developer mode** (toggle in the top-right corner)
4. Click **Load unpacked**
5. Select the unzipped `gater-chrome-extension` folder

## Usage

### Taking a Quiz

1. Open any Pull Request in a repository where Gater is enabled
2. The quiz UI will appear automatically as a sidebar on the right side of the PR page
3. Hover over the quiz panel to view questions
4. Answer all questions and click **Submit**
5. Click the verification button to acknowledge your understanding, allowing you to merge the PR.

### Admin settings

Click on the menu icon in the top right corner of the sidebar or navigate to https://guru-production-1f32.up.railway.app/admin/login to log in to the Admin portal
*Tips 1* If you are on the Free subscription, upgrade to Pro subcription or enter your own Claude API Key in the admin portal to avoid hitting the monthly quiz generation rate limit.
*Optional* If you are on the Pro subscription, choose the custom topics you want your team members to be quizzed on.
*Optional* If you are on the Pro subscription, disable the Gater quiz generation for certain team members if  

### Troubleshooting

**Quiz doesn't appear?**
- Refresh the page (F5 or Cmd+R)
- Verify the GitHub App is installed for this repository
- Check that the extension is enabled at `chrome://extensions` with no errors in the log

**Extension errors?**
- Click the extension icon in the Chrome toolbar
- Right-click the extension and select **Inspect popup** to view console errors
- Confirm you are on a Pull Request page, not Issues or other GitHub pages

## Support

If issues persist, contact your administrator by clicking the "Report bug" button in the top right corner inside the Gater sidebar, or send an email to austadservice@gmail.com
