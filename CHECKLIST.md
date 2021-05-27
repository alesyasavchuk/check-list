# Log In
***

##### 1.Input field for email address and phone number


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 1.1 | Email where you have a Facebook account | smoke test | 
| 1.2 | Email without a domain that has a Facebook account | smoke test | 
| 1.3 | Phone number with Facebook account with code via \"+\" | smoke test | 
| 1.4 | Phone number with Facebook account with code 80 | smoke test | 
| 1.5 | Phone number with Facebook account without code | smoke test | 
| 1.6 | Email or phone number using copy / paste | critical pass | 
| 1.7 | Email or phone number using the combinations Ctrl + C Ctrl + V | critical pass | 
| 1.8 | Delete values using \"Delete\" | smoke test | 
| 1.9 | Delete values using \"Backspace\" | smoke test | 
| 1.10 | Delete value using the menu via the right mouse button | smoke test | 
| 1.11 | Enter email using russian keyboard | critical pass | 
| 1.12 | Empty field | critical pass | 
| 1.13 | Special symbols | critical pass | 
| 1.14 | Enter only spaces | critical pass | 
| 1.15 | Email with spaces (before, in the middle, at the end) | critical pass | 
| 1.16 | Phone number with spaces | critical pass | 
| 1.17 | Phone number with \"-\" delimiters | critical pass | 
| 1.18 | Meaning from the alphabets of the eastern countries (Chinese characters) | critical pass |


##### 2.Password input field 


| ¹ | Check | Check type |
| ------ | ------ | ------ |
|2.1 | Ñorrect account password with hidden password | smoke test | 
| 2.2 | Ñorrect password with open password | smoke test | 
| 2.3 | Paste password using copy / paste | critical pass | 
| 2.4 | Paste password using combinations Ctrl + C Ctrl + V | critical pass | 
| 2.5 | Do not enter password | critical pass | 
| 2.6 | Enter wrong password | critical pass | 
| 2.7 | Enter password with Caps Lock on | critical pass | 
| 2.8 | Enter only spaces | critical pass | 
| 2.9 | Special symbols | critical pass | 


##### 3.Login to the system 


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 3.1 | Ñorrect email and password | smoke test | 
| 3.2 | correct phone number and password | smoke test | 
| 3.3 | Enter the password first, and then the login | critical pass | 
| 3.4 | Click on the \"Log In\" button once | smoke test | 
| 3.5 | Press the \"Enter\" key | smoke test | 
| 3.6 | Enter incorrect username, but correct password | critical pass | 
| 3.7 | Enter correct username, but incorrect password | critical pass | 
| 3.8 | Enter only login, leave the password field blank | critical pass | 
| 3.9 | Leave the login field blank, enter the password | critical pass | 
| 3.10 | Do not fill in all fields | critical pass | 
| 3.11 | Enter the password in the login field, and login in the password field | critical pass | 
| 3.12 | Click on the \"Log In\" button two or more times | critical pass | 
| 3.13 | Click near the \"Log In\" button | critical pass | 


# Sign up
***

##### 4.First name and Last name fields


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 4.1 | Correct first and last name | smoke test | 
| 4.2 | Enter only first name | critical pass | 
| 4.3 | Enter only last name | critical pass | 
| 4.4 | Enter only spaces | critical pass | 
| 4.5 | Enter only numbers | critical pass | 
| 4.6 | Special symbols | critical pass | 
| 4.7 | Leave fields blank | critical pass | 
| 4.8 | Paste values using copy / paste | critical pass | 
| 4.9 | Paste values using combinations Ctrl + C Ctrl + V | critical pass | 
| 4.10 | Enter in one field both first and last name separated by a space | critical pass | 
| 4.11 | Enter a name from one letter | critical pass | 
| 4.12 | Enter a last name from one letter | critical pass | 


##### 5.Mobile number or email field


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 5.1 | Valid email, not registered with Facebook | smoke test | 
| 5.2 | Phone number with code via \"+\", not registered with Facebook | smoke test | 
| 5.3 | Valid email without domain, not registered with Facebook | smoke test | 
| 5.4 | Phone number with a code that starts with \"80\", not registered with Facebook | smoke test | 
| 5.5 | Phone number without code, not registered with Facebook | critical pass | 
| 5.6 | Email that is already registered with Facebook | critical pass | 
| 5.7 | Phone number that is already registered with Facebook | critical pass | 
| 5.8 | Leave this field blank | critical pass | 
| 5.9 | Enter email using russian keyboard | critical pass | 
| 5.10 | Enter special characters, numbers | critical pass | 
| 5.11 | Phone number with delimiters \"-\" | critical pass | 
| 5.12 | Enter only spaces | critical pass | 
| 5.13 | Phone number with spaces | critical pass | 
| 5.14 | Email with spaces | critical pass | 
| 5.15 | Paste email or mobile number via copy / paste | critical pass | 
| 5.16 | Paste email or mobile number using the combinations Ctrl + C Ctrl + V | critical pass | 
| 5.17 | Insert both email and phone number | critical pass | 


##### 6.New Password field


| ¹ | Check | Check type |
| ------ | ------ | ------ |
|6.1 | Enter password in letters only (a-z) | smoke test | 
| 6.2 | Enter  |  | password only in numbers | smoke test | 
| 6.3 | Enter password with letters and numbers | smoke test | 
| 6.4 | Enter password using russian keyboard | critical pass | 
| 6.5 | One character password | critical pass | 
| 6.6 | Do not enter password | critical pass | 
| 6.7 | Enter password with Caps Lock enabled | critical pass | 
| 6.8 | Enter special characters | critical pass | 
| 6.9 | Enter only spaces | critical pass | 
| 6.10 | Enter password with spaces (before, inside, after) | critical pass | 
| 6.11 | Paste password using copy / paste | critical pass | 
| 6.12 | Paste password using combinations Ctrl + C Ctrl + V | critical pass | 


##### 7.Birthday field


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 7.1 | Choose the correct date of birthday | smoke test | 
| 7.2 | Select date of birth from dropdown using arrow keys on keyboard | smoke test | 
| 7.3 | Enter manually the date, month and year | critical pass | 
| 7.4 | Select the words \"Month\", \"Day\", \"Year\" from the drop-down lists | critical pass | 
| 7.5 | Select a future date | critical pass | 
| 7.6 | Select date 01.01.1905 | critical pass | 
| 7.7 | Delete date of birth | critical pass | 
| 7.8 | Don't choose a date of birth | critical pass | 


##### 8.Gender field


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 8.1 | Select \"Female\" | smoke test | 
| 8.2 | Select \"Male\" | smoke test | 
| 8.3 | Select \"Custome\" | smoke test | 
| 8.4 | Select multiple options | critical pass | 
| 8.5 | Ñhoose nothing | critical pass | 


# Forgot password
***

##### 9.Find Your Account


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 9.1 | Enter correct phone number | smoke test | 
| 9.2 | Enter correct email | smoke test | 
| 9.3 | Enter incorrect email | critical pass | 
| 9.4 | Do not fill in the field | critical pass | 
| 9.5 | Enter incorrect phone number | critical pass | 


##### 10.Identify Your Account


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 10.1 | Select \"This is my account\" | smoke test | 
| 10.2 | Ñlick \"Back\" | critical pass | 
| 10.3 | Push \"Enter\" | critical pass | 
| 10.4 | Refresh the page | critical pass | 


##### 11.Reset Your Password


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 11.1 | Select \"Send code via email\" | smoke test | 
| 11.2 | Select \"Use my Google account\" | smoke test | 
| 11.3 | Click \"Continue\" | smoke test | 
| 11.4 | Check if the code came | smoke test | 
| 11.5 | Click \"Not You?\" | smoke test | 
| 11.6 | Click \"No longer have access to these?\" | critical pass | 
| 11.7 | Select both options | critical pass | 
| 11.8 | Select nothing | critical pass | 
| 11.9 | Refresh the page | critical pass | 


##### 12.Enter Security Code


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 12.1 | Enter the correct code | smoke test | 
| 12.2 | Click \"Continue\" | smoke test | 
| 12.3 | Click \"Cancel\" | smoke test | 
| 12.4 | Enter the wrong code | critical pass | 
| 12.5 | Do not enter code | critical pass | 
| 12.6 | Paste a code using copy / paste | critical pass | 
| 12.7 | Paste a code using combinations Ctrl + C Ctrl + V | critical pass | 
| 12.8 | Click \"Didn't get a code?\" | critical pass | 


##### 13.Choose a New Password


| ¹ | Check | Check type |
| ------ | ------ | ------ |
| 13.1 | Make checks from chapter 6 | |
