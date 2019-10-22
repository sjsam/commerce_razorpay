# commerce_razorpay
Razorpay Payment Gateway Integration for Drupal 7 Commerce module

- Installation
Install it like any other user Drupal 7 module
- Settings
  - First things first - Login to Razorpay and under Settings >> API Keys 
    create your key_id/key_secret pair. Note that, you need separate pairs
    for Live/Test modes.
  - Go to /admin/commerce/config/payment-methods/manage/commerce_payment_commerce_razorpay
    and edit 'Enable payment method: Razorpay' action. This is where you should enter the 
    key_id/key_secret pair(from the above step) and the company slogan which will be used
    in the payment page.


