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
user which would be used for showing store locations and stuff in the app and which will be sent to the backend.

HomePage after Signup/Login
=========================

<img width="228" alt="homepage" src="https://user-images.githubusercontent.com/125003312/226851087-5ed38e06-1342-4712-be67-393820a730a3.png">
This is what a user sees when they signup for the first time. In the AppBar at the top is
"hi user" and on the other side of the appbar is user's amount of plus coins
and another option for help/chatting with a rep.

This page will redirect to 7-10 pages.
Mainly -
1. Start Savings Page (It will have options to choose between **Plus_Safe** and __Jewellery_Savings__)
2. Explore Savings Page (It will have schemes from all the brands which are partners of __PLUS__)
3. Top Offers Nearby Page (It will have offers from the nearby stores which are __PLUS__ partners.
4. Below the title **Savings Ki Baatein** there are different articles of sorts for informing users about benefits of gold savings and savings in general.
5. In the __bottom NavBar__ the __savings__ button takes to a page which has details about the user's savings.
6. **Play & Win** takes to a page which is some sort of a game.
7. **Rewards** page is where the rewards earned by a user show up which showed up based on their purchases/investments.
8. **Account** has all the user details. 



Plus Safe Plan Page
==========================
<img width="230" alt="plus_safe_chosen_plan" src="https://user-images.githubusercontent.com/125003312/227086774-6ceb8186-8221-4d7b-bfc6-42749c613aef.png">
User chooses frequency, amount and tenure which is then put in a json and is sent to the backend.
After these the user is asked to complete kyc. For which the user is directed to the next page - 

<img width="228" alt="pan_details" src="https://user-images.githubusercontent.com/125003312/227088292-bf489ce3-6b14-4f0f-8d14-213bb190c5a9.png">

Here the user is asked for pan details and SurePass API is used for that.
From here, the user chooses to make payment with UPI and is taken to the next page which is - 

<img width="200" alt="upi_payment_page" src="https://user-images.githubusercontent.com/125003312/227089045-786e7806-ef8b-468d-9bc0-8c6a1507b317.png">

Here, either paytm/razorpay is integrated for UPI payment.
Then, after completing the payment the user is directed to a page where there is acknowledgment of payment and next due date displayed.
<img width="200" alt="payment_confirm_ _next_due_date" src="https://user-images.githubusercontent.com/125003312/227090462-8b214bac-e359-433c-bf1b-12479f27d807.png">



Explore Savings Schemes
==========================
<img width="281" alt="explore_savings_schemes" src="https://user-images.githubusercontent.com/125003312/226897376-d67c1819-59f2-4a08-bb5a-7e37f7f33231.png">

Shows different jewellers which are **PLUS** partners with their respective benefits.
On tapping any of the cards, takes to the jeweller specific information page which would be like - 

<img width="284" alt="tanishq_golden_harvest_details" src="https://user-images.githubusercontent.com/125003312/227082371-6b576184-280f-481c-9f5d-fc1ac7d0ac68.png">

This page would basically create a json of scheme details which the user is interested in 
and send that to the backend and also allow them to setup a call back and take them to the next page which would be -

<img width="275" alt="call_back_scheduled" src="https://user-images.githubusercontent.com/125003312/227085765-69b95e9a-c414-494f-b178-002eec7cbc1a.png">

When tapped on done on the above page the user is taken back to the home screen.


Nearby Offers Page 
===========================
<img width="314" alt="nearby_offers" src="https://user-images.githubusercontent.com/125003312/227091186-3b07fd38-038a-4343-b32b-8812288d59d8.png">
Shows offers from nearby **PLUS partner jewellers** based on user location. A map is
also shown to the user which shows approximate location of the jewellers in reference to the user's location.

When tapped on a specific brand's offer a pop-up appears with options for either sharing on whatsapp or booking an appointment.




For an existing user these pages are shown -
=========================================

### Homepage with some savings stats
<img width="236" alt="existing_user_homepage" src="https://user-images.githubusercontent.com/125003312/227092749-0e97eeb6-8ef4-4b8e-adab-25f951beb430.png">
 
### Savings Page with Savings stats
<img width="212" alt="existing_user_savings_page" src="https://user-images.githubusercontent.com/125003312/227092989-2c4b8ce3-7a84-4a50-bdf1-d6f81387ff73.png">
When tapped on details, a page is shown with transactions and all.

<img width="234" alt="plus_safe_transactions_screen" src="https://user-images.githubusercontent.com/125003312/227093103-49b6f43c-15d3-4024-8a0a-f187cbc43c4c.png">







