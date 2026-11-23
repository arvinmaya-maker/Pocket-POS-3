This is a light web-based POS for SMEs that connects to your Google Sheet. so here are a three things you'll need to start:
1. Google Account - You need one to create a Google Sheet
2. Create a Google Sheet file by opening a new blank, then you can copy the template from this Google Sheet: https://docs.google.com/spreadsheets/d/1oxVDfVbIU0DvkaoZlZy-9Vk9sH3RYc6E92jIPl_WXTE/edit?gid=1604214643#gid=1604214643.
3. Link a Google Sheet file to the application in the settings, this can be done by 2 ways:
  1. Use a Google Sheet file that is shared to "anyone with link can edit", then copy its url and paste it on the "GOOGLE SHEET URL" field, then click "Save Settings"
Note: using this option will make your Google Sheet accessible to anyone who can get a hold of the Google Sheet url.
  2. For a secure Google Sheet file, after copying the template, you can use the apps script from the Advance Syncing Option.
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

Done setting up, you can now apply your menu and price on the Google Sheet and it will reflect on the Pocket POS 3 UI, 
Note: make sure to click the Sync every after new updates on the Google Sheet. to ensure the data is updated.
