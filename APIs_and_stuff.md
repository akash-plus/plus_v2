Login/SignUp Screen
=========================
<img width="199" alt="login_page" src="https://user-images.githubusercontent.com/125003312/226836737-91cac229-7108-4fa0-b98c-340e9a6e4032.png">
This is the login/signup page and would use otpless or mobile authentication.

A first time user either taps on the whatsapp button or mobile login.

If whatsapp, then the user is directed to a webpage and then from there to an otpless
contact on whatsapp for sending a message which then authenticates the user and also
provides a waID which when used with the clientID and clientSecret gives User Name and Mobile Number.

If user straightup wants to signup with the mobile number then the user is asked for their mobile number and sent an OTP for verification which is then verified on the backend.


OTP Verification Screen
=========================
<img width="235" alt="otp_verification_screen" src="https://user-images.githubusercontent.com/125003312/226845976-1bf2fe6c-4820-4a81-a582-e0b0114253e8.png">
This screen shows up if the user chooses to signup/login with mobile number and on the
same page there would be a field for accepting email id and a mechanism for verifying that too. 


Security and Location Enable Screen
=========================
<img width="194" alt="security_and_login" src="https://user-images.githubusercontent.com/125003312/226847807-011fc3e3-b5d3-47c4-8622-bb87c4dedfa6.png">
Although this page is for enabling security(PIN/password/faceID) and would be handled mostly
on the frontend but this page will also have a pop-up for getting access to location of the 
user which would be used for showing store locations and stuff in the app.
