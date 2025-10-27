# n8n-feedback-form-automation
This project contains an **n8n workflow** that automates feedback collection.  
It uses an n8n Form Trigger to collect user responses, stores them in Google Sheets, and sends a personalized thank-you email using Gmail.

# Features

**Form Trigger:**  
Collects user input such as name, email, and feedback directly from a custom n8n form.

**Google Sheets Integration:**  
Automatically appends each submission as a new row in a connected Google Sheet.

**Gmail Integration:**  
Sends an automatic thank-you email to the person who submitted the form.

**No-Code Automation:**  
Easily editable in the [n8n.io](https://n8n.io) workflow editor.

## Workflow Overview

### 1. **On Form Submission**
- Uses `n8n-nodes-base.formTrigger`
- Displays a form titled **"KHR Rocking Updates"**
- Collects:
  - **Name**
  - **Email**
  - **Feedback**

### 2. **Append Row in Sheet**
- Uses `n8n-nodes-base.googleSheets`
- Appends responses to your connected Google Sheet.

### 3. **Send a Message**
- Uses `n8n-nodes-base.gmail`
- Sends a thank-you email:
  
### Output of the Workflow
<img width="1919" height="932" alt="Screenshot 2025-10-27 121948" src="https://github.com/user-attachments/assets/c25d4d76-8e6a-4817-8299-373679fed708" />

