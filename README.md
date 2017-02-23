# ccavenue-android-mobile
Integration with CCAvenue is possible using their Android Mobile Integration Kit.

Git Ref: https://github.com/rishirdua/commerce-ccavenue

Integration with CCAvenue is possible using their Mobile Integration Kit. They provide sample code for iOS and Android which can be downloaded from here:

https://mars.ccavenue.com/downloads/Mobile_Integraion_Kit.zip

They describe two ways of integrating with their payment gateway, seamless and non-seamless. Either way requires you to redirect the user to a web page to complete the payment process or acquire authorisation from the users bank. Once done CCAvenue can redirect the user to whatever URL you prefer. This could be a website, merchant server API or a custom URI like myapp:// where you could handle the response locally.

Further Reading

Seamless means you have the opportunity to present the payment options natively and collect all required fields first, then submit this to CCAvenue.

Non-Seamless means you just pass the amount and currency to CCAvenue and the billing and payment details are collected from the redirected page.

Either way will you require you to handle integration with CCAvenue with a separate WebView Activity to which CCAvenue provide sample code for.
