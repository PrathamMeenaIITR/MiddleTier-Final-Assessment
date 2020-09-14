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
