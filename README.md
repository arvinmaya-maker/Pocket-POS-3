This is a light web-based POS for SMEs that connects to your google sheet. so here are a couple of things you'll need to set you up
1. Google Account - You need one to create a google sheet
2. Link a google sheet file to the application, this can be done by 2 ways:
  1. The google sheet file that is shared to anyone with link, You can copy this template https://docs.google.com/spreadsheets/d/1oxVDfVbIU0DvkaoZlZy-9Vk9sH3RYc6E92jIPl_WXTE/edit?gid=1604214643#gid=1604214643 
Note: using this way will make your google sheet accessible to anyone who can get a hold of the google sheet url.
  2. For a secure google sheet file, after copying the template, you can use the apps script from the advance syncing option.
       Step 1: Go to Settings
       Step 2: Open the "Advance Syncing Option"
       Step 3: Click "Copy Code.gs"
       Step 4: On a separate browser tab, open a New Google Sheet File.
       Step 5: Change File Name to "Menu"
       Step 6: Select Extensions on the header toolbar
       Step 7: Click Apps Script, this will open a new tab and you'll see the Google Apps Script dashboard.
       Step 8: While the "Code.gs" tab is selected, delete the current content and paste the copied code.gs by simply pasting (Ctrl+v/Cmd+v)
       Step 9: Click "Deploy" button and select "New Deployment"
       Step 10: Select Type: "Web app"
       Step 11: On the "Who has access" field, change "only me" to "anyone"
       Step 12: Click Deploy
       Step 13: Authorize Access (this will open a modal and you'll have to select advance option and then it will show your google login and you'll simply allow it to proceed)
       Step 14: Deployment done, a modal will show your Web app url, copy that by clicking the copy button
       Step 15: Go to the Pocket POS in your browser tab, on the Advance Syncing Option, Paste the Web app url to the "APP SCRIPT WEB APP URL" field.
       Step 16: Click "Save Settings" button
       Step 17: Click the "Sync Sheet" button on the header, (if you're in mobile view, this option is inside the header menu)

Done setting up, you can now apply your menu and price on the google sheet and it will reflect on the Pocket POS 3 UI, 
Note: make sure to click the Sync every after new updates on the google sheet. to ensure the data is updated.
