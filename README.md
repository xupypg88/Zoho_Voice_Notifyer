# Zoho_Voice_Notifyer
Python-based utility that notifies about newly added cases or answered cases in Zoho Desk

Structure:

1) Task scheduler with task queue
2) Zoho API based requestor of cases state
3) GOOGLE API's reader of the titles
4) Rcognizing of newly changed items or old ones to repeat it with different periods
5) Integrated audio lib (for Win/Linux) for playing received from google data
