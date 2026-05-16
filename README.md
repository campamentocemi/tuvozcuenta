# Recipient mailing group template setup

This folder has the reusable template setup:

- `base-bill-page-template.html`
- `senate-recipients.js`
- `house-recipients.js`

Generated from the uploaded compiled spreadsheet.

Included recipient counts:
- Senate: 28
- House: 53
- Total: 81

## How to use for a new bill/action

1. Copy these three files into the bill folder.
2. Rename `base-bill-page-template.html` to `index.html`.
3. Add the campaign image to the same folder.
4. In `index.html`, update:
   - page title
   - image filename
   - default email subject
   - default email body
5. In `senate-recipients.js` and `house-recipients.js`, update each person's `vote` value for the bill/action.

Recommended vote values:
- `A Favor`
- `En Contra`
- `Ausente`
- `Abstención`

The HTML page lets users email:
- all recipients
- Senate only
- House only
- recipients filtered by vote
