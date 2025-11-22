- Create Workflow in n8n.

- Add "On Form Submission" Node:

  - Configure it to capture form data when submitted.

- Add "Append Row in Sheet" Node:

  - Set up Google Sheets to append form data to the sheet.

- Add "Google Sheets Trigger" Node:

  - Set it to trigger when a new row is added to the sheet.

- Add "Send Message" (Gmail) Node:

  - Configure Gmail to send an email with details from the newly added row.

- Connect Nodes:

  - Link "On Form Submission" to "Append Row in Sheet" and "Google Sheets Trigger" to "Send Message".

- Execute and Test:

  - Click "Execute Workflow" to test it.

- Save and Activate the workflow.


- # Screenshot
<img width="891" height="453" alt="image" src="https://github.com/user-attachments/assets/7ad46179-3994-4965-a0a5-2b6c21e75ff6" />

