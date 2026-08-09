Cleopatra Ink — Call Log Form

A quick tool for logging Vonage call results into the format used by the Sheets tracker. Paste a screenshot, review the auto-filled fields, and copy a ready-to-paste row.

How to use
Open the form Go to the live link (shared by your Team Leader) or open index.html in a browser.
Add a screenshot
Click the upload box and select a Timely / BookNow screenshot, or
Copy a screenshot and paste it directly into the page (Ctrl+V / Cmd+V), or
Drag and drop the image file onto the upload box
Wait for auto-fill The form reads the screenshot and fills in what it can: customer name, phone, email, studio, channel, appointment date, and type. This takes a few seconds.
Check every field Auto-fill is a starting point, not a final answer. Always verify:
Customer name spelling
Phone number (auto-cleaned to 10 digits, no +1)
Studio and channel match what's actually in Timely
Appointment date is based on the customer's local time, not branch time
Set the call details yourself The form never guesses these — you choose them based on the actual call:
Call Reason: Confirmation, Reminder, Follow-up, Booknow Lead, Regain, Pencilled-In Mail, Pencilled-In Landing, Other
Call Outcome: Scheduled, Rescheduled, Confirmed, Scheduled by Mistake, Cancelled, Wrong Number, Didn't Pick Up, VM Left, Potential Customer, Already Confirmed, Call Back Later, Do Not Call, Not Interested, Pending Call
Need Call Back auto-switches to "Yes" for Potential Customer / Call Back Later — add a callback date if you have one
Copy and paste Click "TSV satırını kopyala". The row is now on your clipboard, tab-separated and ready to paste directly into a Google Sheets row.
Notes
The Call Date field defaults to today automatically.
The bottom preview line shows exactly what will be copied, field by field — check it before copying.
Screenshot auto-fill only works on the live hosted link (it calls Claude's API from the page). If you download the file and open it locally without hosting, the form still works but auto-fill won't.
One customer = one row. For multiple customers, repeat the process and paste each row on its own line in Sheets.
Updating the agent list

When a new agent joins, ask your Team Leader to add their name to the Agent dropdown in index.html and re-upload the file to GitHub.
