//Pay With PayPal//
#Getting started with Paypal integration in ionic app

#Understanding 
    We will use Paypal REST API to integrate Paypal Payment gateway in our app. To achieve that, first we need to register on Paypal developers console.  Once it’s done, we’ll create an App under REST API, and get access of Client Id’s. After that we will install PayPal Plugins in our app. After installation first we will inject plugin in app and then import plugin on respective page.

Steps:
#Registration on Paypal
    1.	Click on link https://www.paypal.com/in/webapps/mpp/account-selection
    2. Select account type and follow the instructions to register, after registration use link  https://www.paypal.com/in/webapps/mpp/merchant login to the portal and validate your email address. Go to developer dashboard after validation.
    3.	Login to developer dashboard https://developer.paypal.com/
    4.	Select Dashboard from login option drop down 
    5.	Create App inside REST API apps option.
    6.	You can toggle between Sandbox and Live Client Id.  For demo we will use Sandbox anccount

#Installations/Injection:
    For using Facebook plugin first we need to sign up to Facebook developer console, for that go to https://ionicframework.com/docs/native/paypal/.
    1.	Install the Cordova and Ionic Native plugins.use link(https://ionicframework.com/docs/native/paypal/)
    2.	Import libraries in app.module.ts page.(Dependencies  injection in app.module.ts page)

#How it Works:
    When user selects PayPal payment method, it redirects user to PayPal Payment page, from there user can select from the options i.e. Pay with PayPal or Pay with Card . Once user selects Pay with PayPal it redirects user to PayPal login screen, click on Pay button, after successful payment it alerts successful message and redirects user back to home page. We can switch payment option from all added payment options inside PayPal app

#References:
    1.	Plugin ionic-native for Paypal:
        i. https://ionicframework.com/docs/native/paypal/
        ii. https://www.paypal.com/in/webapps/mpp/merchant
    2.	Facebook Developer Console: https://developer.paypal.com/
    3.	Sample Application : https://github.com/vcjpierre/ionic-paypal