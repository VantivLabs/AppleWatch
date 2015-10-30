#<a name=top></a> AppleWatch
Take me to [Setup](#setup) | [Pre-Reqs](#pre) | [Code](#code) | [Links](#links) | [Use Cases](#c1)

- - -

##Overview
This document will provide information about the Apple Watch and integrating into the Vantiv API for those who choose to accept the [Vantiv](https://www.vantiv.com/) API Challenge at the [2015 Money2020 Hackathon](http://www.money2020.com/2015-money2020-hackathon) in Las Vegas.

##Unboxing 
Teams interested in accepting the Vantiv Vantiv API Challenge at the 2015 Money2020 Hackathon in Las Vegas will receive an [Apple Watch](http://www.apple.com/watch) on a first come basis. **Supplies are limited.**

##<a name=setup></a>Setup
Super simple. Launch the Watch app on your iOS device and follow the instructions. Took me less then 3 minutes to set up.

![Apple Watch](https://github.com/vantivlabs/AppleWatch/blob/master/images/IMG_2770.PNG)

For more details on setting up the Apple Watch with your iOS device [check this link out.](https://support.apple.com/en-us/HT204505)

##<a name=pre></a>Prerequisites
Technically you do not need a hardware device (i.e. Apple Watch) to write an app for Apple Watch. So don't let that stop ya. 
* Mac with Xcode 6.1 or newer
  * Install WatchKit App + Extension in Xcode Project
* Apple Watch requires that an iPhone be present in order to run third party apps. 
* Newer iOS device (iPhone / iPad)
* [Apple Developer Account](https://developer.apple.com)
* [iOS Developer Program Membership](https://developer.apple.com/programs/)
* [Apple Merchant ID](https://developer.apple.com/account/ios/identifiers/merchant/merchantCreate.action)
* [Apple Pay Certificate](https://developer.apple.com/library/ios/ApplePay_Guide/Configuration.html)

##<a name=code></a>Code
Below is an example of Apple Pay and Apple Watch development. You guys are the experts. Be it Objective-C or Swift, let those poetic lines of code flow... links below are just a resource should you need one. 
* [Apple WatchKit Tutorial Part 1](http://www.raywenderlich.com/89562/watchkit-tutorial-with-swift-getting-started)
* [Apple WatchKit Tutorial Part 2](http://www.raywenderlich.com/96589/watchkit-tutorial-swift-tables-network-requests)

## <a name=links></a>Useful Links
* [Apple Watch Support](http://www.apple.com/support/watch)
* [Apple iPhone Support](http://www.apple.com/support/iphone)

- - -

## <a name=c1></a>Use Case Examples
Here are some ideas to help get the creative juices flowing. Nothing is without commmerce.

## Use Case 1

> ON FRIDAY MORNING, VITO A CROSS FIT TRAINER IS TAKING A BREAK FROM TRAINING A CLIENT AND WANTS TO PLAY A GAME ON HIS APPLE WATCH. VITO SELECTS A GAME ON HIS APPLE WATCH AND BEGINS TO PLAY BEFORE HIS CLIENT RETURNS FROM A BREAK. 
WHEN VICTOR SEE HIS CLIENT WALKING BACK HE WANT TO COMPLETE HIS CURRENT LEVEL, SO HE USES IN-APP PURCHASING TO ‘PAY OFF’ THE CURRENT LEVEL.

> SINCE VICTOR HAS ALREADY SIGNED UP FOR IN-APP PURCHASE ON HIS IPHONE AND THE GAME IS STORING A TOKEN ON VITO’S DEVICE. VITO CAN QUICKLY ‘LEVEL UP’ TO OBTAIN ACCESS TO THE NEXT LEVEL AND HE CAN GET BACK TO TRAINING HIS CLIENT AND PLAY THE GAME ON HIS NEXT BREAK.

> If you like what you see look for more information on Hosted Checkout which allows you to take card holder data and return a token for future use and then use the REST or SOAP API to process the actual payment transaction.

## <a name=c2></a>Use Case 2

> ON TUESDAY ON HER WAY TO SCHOOL, SARA STOPS AT HER FAVORITE LOCAL COFFEE SHOP TO GET A COFFEE AND WANTS TO USE HER APPLE WATCH TO PAY FOR HER COFFEE. SHE ORDERS HER COFFEE THEN PRESENTS HER WRISTS TO THE BARISTA TO SCAN HER WATCH AND TAKE FUNDS FROM HER STORED VALUE ACCOUNT WITH THE MERCHANT.  SARA ONLY HAS .23 CENTS LEFT AFTER HER TRANSACTION. SHE THEN PRESSES A BUTTON ON HER WATCH TO DONATE THE REMAINING .23 CENTS TO THE COFFEE HOUSE CHARITY SHE SELECTED WHEN SETTING UP HER STORED VALUE CARD

> If you like what you see look for more information on Storecard or Gift processing.

- - -
Take me back to the [Top](#top)

#Legal Stuff

[https://vantiv.com/privacy-policy Privacy Policy, Copyright Notices, and Terms of Use]


Apple, AppleWatch, iPhone, and iOS are registered or unregistered marks belonging to their respective owners who are unaffiliated with and do not endorse or sponsor Vantiv, and Vantiv likewise does not endorse or sponsor Apple, AppleWatch, iPhone, or iOS.
