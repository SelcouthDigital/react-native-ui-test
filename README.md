# ⚛️ React Native - UI Test 

> This test should be hosted on github.com or any other source control platform
  
> You have 24h to complete this test, upload it and email the URL back

___

Create a React Native app which has 2 screens and uses the following tools:
- [Navigation](https://reactnavigation.org/)
- [Redux](https://redux.js.org/)
- [Redux Form](https://redux-form.com/8.2.0/)

___

## # 1st screen

First screen should contain a Redux Form with the following fields:
- `First name`
- `Last name`
- `Email address`

The validation for the fields should be as follows:
- `First name`, check for the presence
- `Last name`, check for the presence
- `Email`, check for the presence and email format

There should be a submit button located at the end of the form which should be disabled if the validation isn't valid and navigates to the 2nd screen otherwise.

___

## # 2nd screen

In this screen there should be a read-only area with all form details listed as text.

There should also be a button at the bottom of the screen which "deletes" the form information and navigates back to 1st screen after the action succeeds.

___

Good luck 🤞
