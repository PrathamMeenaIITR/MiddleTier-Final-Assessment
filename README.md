# MiddleTier-Final-Assessment
Mobile Recharge Application 

## Mobile Recharge Application

Problem Statement: Mobile Service Provider needs an application for Customer to provide support, so the customer is able to perform various operations like Account Balance Enquiry and Recharge Account. 
1.	Account Balance Enquiry Option	:
        If customer selects this option, MobileNo should be accepted from the user.  
        If mobileNo exists in the AccountEntry Map, Balance amount should be displayed, otherwise error message should be displayed.



        Sample Run

        Enter Mobile No : 9922943943

        Your Current Balance is Rs. 500.00

        OR

        Enter MobileNo : 9834391234

        ERROR:  Given Account Id Does Not Exits

2. 	Recharge Account : 
        If customer selects this option, then Mobile No and Recharge Amount needs to be entered by the customer.
        Depending on the given Mobile no update the final amount in Account table i.e.
        Note :  New Account Balance=Existing Balance Amount+ New Recharge Amount

                    On Success Recharge display “Account Recharged successfully : “ and also display the account details as below.


        Sample Run

        Enter MobileNo : 9932012345
        Enter Recharge Amount : 140

        Your Account Recharged Successfully 
        Hello Manish ,Available Balance is 440 .
        OR

        Enter Mobile No : 90110212

        ERROR:  Cannot Recharge Account as Given Mobile No  Does Not Exits

## ScreenShots
#        1. Application Executed
![alt text](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/1.Server%20Created.png)
#        2. Getting Information of all accounts succesfully (Get)
![alt text](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/2.Getting%20All%20Accounts%20Info.png)
#        3. Getting Information of a specific account (Get)
![alt text](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/3.Getting%20Required%20Account%20Information.png)
#        4. Account Not existing error (Get)
![alt text](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/4.Showing%20Account%20not%20exist.png)
#        5. Recharge of required amount done succesfully (Put)
![alt text](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/5.Recharge%20Done%20of%20Required%20Account.png)
#        6. Added New User Succesfully (Post)
![alt text](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/6.Added%20New%20User.png)
#        7. Table Preview 
![alt texxt](https://github.com/PrathamMeenaIITR/MiddleTier-Final-Assessment/blob/master/mobileRechargeApplication_992042/ResultScreenShots/TablePreview.png)
