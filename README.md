## Flipkart Website Automation Suite Information:-

####__To run the suite from the command line in project folder__
###### mvn clean test

####__To run the suite in headless or non-headless mode__
###### Change the mode="headless/non-headless" in config.properties file in Resources folder

####__To run the suite in chrome/FF/IE browser__
###### Change the browser="chrome/FF/IE" in config.properties file in Resources folder


####__Packages description__
- com.Prateek_3185055_Selenium_ExitTest.pages: Defined all the page classes in which all the elements are being found.
- com.Prateek_3185055_Selenium_ExitTest.utils: Defining the utilities needed for capturing the failed test cases as well as reading the data.
- com.Prateek_3185055_Selenium_ExitTest.test: Defining all the test classes, grouping and assertions


####__Test files description__
- BaseTest: This is the base class where @Before and @After methods are defined also all the other test classes extends this class.

- LoginTest: This file includes tests to verify the login feature.

- AddressTest: This file includes tests to validate the add, edit as well as delete functionality of the address page.

- CategoriesTest: This file includes tests to watch the product categories of the website.

- CouponsTest: This file includes tests to validate the coupons feature of the website.

- FlipkartPlusTest: This file includes tests to validate the flipkartplus feature of the website.

- GiftCardsTest: This file includes tests to validate the giftcardsTest feature of the website.

- LogoutTest: This file includes tests to validate the logout feature of the website.

- NotificationsTest: This file includes tests to validate the notification feature of the website.

- OpenMyOrdersTest: This file includes tests to validate the my orders feature of the website.

- OpenMyProfileTest: This file includes tests to validate the my profile feature of the website.

- OpenMyWishlistTest: This file includes tests to validate the my wishlist feature of the website.

- SearchProductTest: This file includes tests to validate the valid as well as invalid search feature of the website.

- SuperCoinTest: This file includes tests to validate the supercoin feature of the website.


####__Other files description__
- pom.xml: This file contains all the dependencies as well as plugin which are required as part of the suite.

- testng(invalid_TestCases).xml: This file contains all the classes, groups to test invalid test cases as far as suite is concerned.

- testng(regression_TestCases).xml: This file contains all the classes, groups to test regression test cases as far as suite is concerned.

- testng(sanity_TestCases).xml: This file contains all the classes, groups to test sanity test cases as far as suite is concerned.


####__Folders __
- Drivers folder: This folder contains all the required drivers. 

- FailedScreenshots folder: This folder includes all the failed screenshots.

- Reports folder: This folder contains the reports of all the test scenarios as part of the suite.



