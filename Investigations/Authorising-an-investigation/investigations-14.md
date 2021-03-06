[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Authorising an Investigation - Status Change

##Description
The Case Status of an incident should change when a completed Investigation form is authorised.

##Preconditions 
+ The tester is logged in as the Accountable Person for the incident in question.
+ The Case Status for the incident in question must be 'Investigation (Finalised)'.

##Assumptions
+ A supported browser is being used.

##Test Steps:

1 Navigate to the 'Investigation' tab of the incident in question.

2 Click the 'Authorise' button.

3 In the pop-up box, click the 'OK' button.

##Expected Results
+ The pop-up box displays the message, "Thank you for authorising this investigation.  It has now been passed to the Health & Safety Team to close the case."
+ The Case Status of the incident in question changes to 'Investigation (Authorised)'.
