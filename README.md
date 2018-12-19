# Task to EmailMessage README 


In summary, the enclosed script can be run in the salesforce developer console to convert the emails logged in the Task object and migrate them to the new EmailMessage Object. 

It finds 200 tasks, converts the tasks to emailmessage records with corresponding emailmessagerelation records, deletes the converted tasks and creates a record in the process transaction log for each conversion (this allows for verification). 
