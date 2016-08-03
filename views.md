# List of Screens / Views

## User Views

### Initial Screen
* Language Selection
* Welcome Message (in English and any other commonly used language expected by clients)
* Accessibility option listed

### Accessibility Screen
* Instruction to see front desk for assistance
* Option 1: Provide confirmation button that pushes notification to front desk that user needs assistance
* Option 2: No push notification, user must manually approach desk for assistance
* If no option is selected after set time, automatically return to Initial Screen

### Info Screen
* Text boxes provided for critical user information
* Each Option has the option for an audible accessibility option either by tapping the title or a speaker icon immediately next to the Text
* All critically important information is denoted with an asterisk(* )
* Critical information includes name and primary contact phone number
* Phone number includes option to check number as Work/Cell/home
* Non-critical information include street address, email address and secondary contact numbers
* Drop box for Insurance provider
* Any information that differs from records will be verified or updated as necessary manually with confirmation of patient
* Continue/Confirmation button provides an alert that all information is accurate and up to date
* If critical information is missing, continue/confirmation button spits out error to correct missing information
* If no input is received after a set time, return to Initial Screen

### Visit Summary Report
* Provide information regarding patients visit and brief summary of conditions
* Include text box for Type of visit (ie. well visit, follow-up, etc.)
* Option whether visit is appointment or walk-in
* Provide text box for appointment time if applicable
* Include text box for name of Physician
* All information is Non-critical
* Continue/Confirmation button provides an alert that all information is accurate
* If not input is received after a set time, return to Initial Screen

### Confirmation Screen
* Simple confirmation screen that information has been submitted correctly and to take a seat
* Provide button to return to Initial Screen
* Automatic and hidden countdown timer will automatically return to Initial Screen after set interval

## Admin Views

### Login Page
* Text Boxes for Username and Password
* Shared login page for both employee and superusers
* HIPAA Warning

### Main Page - Employee
* List of checked in patients by check in time
* Each patient has Last Name and First Initial along with Check-in time and appointment time (if applicable) along with Doctor's Name, new patient flag, and appointment/walk-in classification
* Patients are automatically sorted by check-in time
* Row is highlighted upon completion of Check-in
* Detail button listed beside each patients check in row, action causes pop up window for DETAIL PAGE
* Include button to automatically verify earliest check-in that has not been verified for ease of use
* If accessibility option has been togged by patient check-in, an alert message is to be displayed that is easily visible but does not impede the functionality of the rest of the page
* Logoff button required
* No activity for set time returns page to login screen

### Detail Page
* Pop-up screen with all information for each patient
* Information includes all critical and non-critical information as noted above
* Any information that differs from records will be automatically highlighted along with alert
* If primary contact number does not match patient database, verify whether patient is a new patient or needs to update contact info
* If updating primary contact number, provide new field for old primary contact number
* Upon verification or correction of information, employee presses check-in button to complete check-in process
* Window is closed and patient's row becomes highlighted
* No activity for set time automatically closes window
