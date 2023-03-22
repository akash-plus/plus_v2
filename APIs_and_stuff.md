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

HomePage after Signup/Login
=========================

<img width="228" alt="homepage" src="https://user-images.githubusercontent.com/125003312/226851087-5ed38e06-1342-4712-be67-393820a730a3.png">
This is what a user sees when they signup for the first time. In the AppBar at the top is
a salutation for the user and on the other side of the appbar is user's amount of plus coins
and another option for help/chatting with a rep.

This page will redirect to 7-10 pages.
Mainly -
1. Start Savings Page (It will have options to choose between **Plus_Safe** and __Jewellery_Savings__)
2. Explore Savings Page (It will have schemes from all the brands which are partners of __PLUS__)
3. Top Offers Nearby Page (It will have offers from the nearby stores which are __PLUS__ partners.
4. Below the title Savings Ki Baatein there is a thing called 


