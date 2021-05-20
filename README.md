# Chek-list-for-fasebook.com
Checklist for the "Log In" field
1. Smoke Testing
                                             1.1. Entering correct data in the fields "Mobile number or email", "Password".
2. Critical-Path Testing
2.1. Invalid data entry:
                 2.1.1 Entering data for a non-existing user
                 2.2.2 Arabic numerals.
                 2.2.3 Roman numerals.
                 2.2.4 Entering Illegal Data.
                 2.2.5 Special characters (“>’. <\:. *; +.).
2.2. The site's reaction to filling in the fields:
                 2.2.1. Empty
                 2.2.2. Maximum number of characters
                 2.2.3. Maximum number of characters +1
                 2.2.4. Various encodings (l1 * .p / ?. "6c.)
                 2.2.5. Minimum characters
                2.2.6 Spaces.
                2.2.7 Space before / in the middle / at the end of fields.
                2.2.8 Data Entry in Different Languages
                2.2.9 For the "Password" field: how much data we can insert into the field from the buffer.
2.3 Different fonts in the fields
2.4. Various font sizes.
2.5. Obvious and understandable system messages.
 3. Expended Testing
3.1. Change the language while typing.
3.2. Enable Caps Lock.
3.3 Double click on the "Log In" button and check the reaction
3.4 Login to the site on different browsers.
3.5. Login to the site on different OS.
4. Usability Testing
4.1 Position of the form on the screen by default
4.2 Highlighting errors with indication of the reason.
4.3 Position of the form on the screen after correct / incorrect filling.
4.4 The state of the form after reloading (cleared / remains unchanged).
4.5. Appearance of the download bar (something else) when pressing "Log In", check its operation
4.6 Is there an indication of the allowed number of characters to be entered.
4.7 Availability of work opportunities for people with disabilities.
4.8. Whether an incorrectly filled field is highlighted.
4.9. The state of the form after the login is interrupted.
4.10 Form response to enabled / disabled JavaScript.	

Checklist for the "Sign Up" field
1. Smoke Testing
1.1. Registration of a new existing user.
2. Critical-Path Testing
  2.1. Page  «What’s your name?» 
                 2.1.1 Enter a non-existing user into the fields
                 2.1.2 Enter Arabic numerals.
                 2.1.3 Enter Roman numerals.
                 2.1.4 Special characters (“>’. <\:. *; +.).
                 2.1.5. Leave the field blank
                 2.1.6. Maximum number of characters
                 2.1.7. Maximum number of characters +1
                 2.1.8. Various encodings (l1 * .p / ?. "6c.)
                 2.1.9. Minimum characters
                2.1.10 Fill in the fields with spaces.
                2.1.7 Space before / in the middle / at the end of fields.
                2.1.8 Data Entry in Different Languages
                2.1.9 Different fonts in fields
                2.1.10 Various font sizes.
2.2. Page  «What’s your birthday?» 
              2.2.1 Correctness of the drop-down list.
              2.2.2 Leave in the lists “Month”, “Day”, “Year”.
              2.2.3 Date of birth in the future.
              2.2.4 Are there any age restrictions?
2.3.  Page  «Enter Your Phone Number» 
                 2.3.1 Enter a non-existing phone number in the field
                 2.3.2 Enter Roman numerals.
                 2.3.3 Special characters (“>’. <\:. *; +.).
                 2.3.4. Leave the field blank
                 2.3.5. Maximum number of characters
                 2.3.6. Maximum number of characters +1
                 2.3.7. Various encodings (l1 * .p / ?. "6c.)
                 2.3.8. Minimum characters
                2.3.9 Fill the fields with spaces.
                2.3.10 Space before / in the middle / at the end of fields.
                2.3.11 Data Entry in Different Languages
                2.3.12 Various font sizes.         
2.4. Page «What’s your gender?»
               2.4.1. Checkboxes are not checked at all.
               2.4.2 At the same time put 2, 3 checkboxes
               2.4.3 Checkbox state after reboot (cleared / remains unchanged)
               2.4.4 State of checkboxes by default (filled / not filled)
2.5. Page «Chosse a Pasword»
                2.5.1 Enter a password that does not exist in the field
                 2.5.2 Enter Roman numerals.
                 2.5.3 Special characters (“>’. <\:. *; +.).
                 2.5.4. Leave the field blank
                 2.5.5. Maximum number of characters
                 2.5.6. Maximum number of characters +1
                 2.5.7. Various encodings (l1 * .p / ?. "6c.)
                2.5.8. Minimum characters
                2.5.9 Fill the fields with spaces.
                2.5.10 Space before / in the middle / at the end of fields.
                2.5.11 Data Entry in Different Languages
                2.5.12 Acceptable font sizes.
                2.5.13 Enter Arabic numerals
                2.5.14 Different fonts in the field
            2.5.15 Is the field cleared after page reload
           2.5.16 There is a warning that the password is short and simple.
           2.5.17 Is there a warning that the password matches some personal information of the user.
3. Expended Testing
3.1. Change the language while typing.
3.2. Enable Caps Lock.
3.3 Registration on different browsers.
3.4. Registration on different OS.
4 Usability Testing
4.1 Default screen layout
4.2 Highlighting errors with indication of the reason.
4.3 Field state after reboot (cleared / remains unchanged).
4.4 Is there an indication of the allowed number of characters to be entered.
4.5 Availability of work opportunities for people with disabilities.
4.6 State of fields after interruption of registration.
4.7 Ability to return to the previous step.
4.8 Field response to enabled / disabled JavaScript


Checklist for the "Forget Password?"
1. Smoke Testing
1.1. Entering correct data for password recovery.
2. Critical-Path Testing
  2.1. Enter your mobile number tab
                 2.1.1 Enter a non-existent phone number in the fields
                 2.1.2 Enter Roman numerals.
                 2.1.3 Special characters (“>’. <\:. *; +.).
                 2.1.4. Leave the field blank
                 2.1.5. Maximum number of characters
                 2.1.6. Maximum number of characters +1
                 2.1.7. Various encodings (l1 * .p / ?. "6c.)
                 2.1.8. Minimum characters
                2.1.9 Fill in the fields with spaces.
                2.1.10 Space before / in the middle / at the end of fields.
                2.1.11 Data Entry in Different Languages
                2.1.12 Various font sizes.
2.2. Password recovery tab
               2.2.1. The checkbox is not checked at all.
               2.2.2 Checkbox state after reboot (cleared / remains unchanged)
               2.2.3 Checkbox default state (filled / not filled)
               2.2.4 Informational content of the link "No more access?"
2.3. Enter security code tab
                 2.3.1 Enter the wrong security code in the field
                 2.3.2 Enter Roman numerals.
                 2.3.3 Special characters (“>’. <\:. *; +.).
                 2.3.4. Leave the field blank
                 2.3.5. Maximum number of characters                 
                2.3.6. Maximum number of characters +1
                 2.3.7. Various encodings (l1 * .p / ?. "6c.)
                 2.3.8. Minimum characters
                2.3.9 Fill the fields with spaces.
                2.3.10 Space before / in the middle / at the end of fields.
                2.3.12 Various font sizes.
                 2.3.13 Informational content of the link "Didn't receive the code?"
2.4. Enter a new password tab
                 2.4.1 Enter a password that does not exist in the field
                 2.4.2 Enter Roman numerals.
                 2.4.3 Special characters (“>’. <\:. *; +.).
                 2.4.4. Leave the field blank
                 2.4.5. Maximum number of characters
                 2.4.6. Maximum number of characters +1
                 2.4.7. Various encodings (l1 * .p / ?. "6c.)
                2.4.8. Minimum characters
               2.4.9 Fill in the fields with spaces.                
                2.4.10 Space before / in the middle / at the end of fields.
                2.4.11 Data Entry in Different Languages
                2.4.12 Various font sizes.
                2.4.13 Enter Arabic numerals
                2.4.14 Acceptable fonts in the field
                2.4.15 Is the field cleared after page reload
                2.4.16 There is a warning that the password is short, simple.
                2.4.17 Is there a warning that the password matches some personal information of the user.
               2.4.18 Information content of the "?"
3. Expended Testing	
3.1. Change the language while typing.
3.2. Enable Caps Lock.
3.3 Registration on different browsers.
3.4. Registration on different OS.
4 Usability Testing
4.1 Default screen layout
4.2 Highlighting errors with indication of the reason.
4.3 Field state after reboot (cleared / remains unchanged).
4.4 Is there an indication of the allowed number of characters to be entered.
4.5 Availability of work opportunities for people with disabilities.
4.6 State of fields after interruption of registration.
4.7 Ability to return to the previous step.
4.8. Field reaction to enabled / disabled JavaScript

