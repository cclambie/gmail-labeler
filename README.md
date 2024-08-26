# gmail-labeler

Google Script that you can trigger based on time (I suggest every 5 minutes) to label your incoming mail according to rules in a spreadsheet.

Create a spreadsheet in sheets.new and create a sheet "Email Labeling" with 2 columns Email address and Labels

Create a rule in Gmail that is "any new important email, add the label "NewImportantEmail"

You can also create "Labels by Gmail" to manually run the function "GetLabelsForGmail()"
