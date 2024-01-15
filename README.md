# test-cases-example

Login - Verify form validation
| Steps         | Input         | Expected result         |
| ------------- | ------------- | ----------------------- |
| 1. Proceed to the login screen  | - | Login screen is opened according to design [design link] |
| 2. Enter the Email field and click on the Password field  | test.com  | Invalid email error label is shown for the Email field |
| 3. Click on the Email field and enter the valid email | test@test.com | Invalid email error label is hidden |
| 4. Click on the Login button | Password is empty | Password is required error label is shown for the Password field |
| 5. Enter the some char to the Password field | - | Password error-label is hidden |

Login - Credentials
| Steps         | Input         | Expected result         |
| ------------- | ------------- | ----------------------- |
| 1. Proceed to the login screen  | - | Login screen is opened according to design [design link] |
| 2. a) Enter the credentials and click on the Login button | User with email does not exist in the system | "User does not exist in the system" error label is shown |
| 2. b) Enter the credentials and click on the Login button | Wrong password | "Email or password is wrong" error label is shown |
| 2. с) Enter the credentials and click the Login button | Correct credentials | User successfully logs in to the platform. Platform Home screen is shown according to the design [design link]|
