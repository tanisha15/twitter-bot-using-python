# Twitter Bot 
The twitter bot works by automatically liking your hashtag posts on twitter. Your twitter page will also scroll down automatically. The bot recognizes the 'heart' emoji of the post and the cursor clicks on it and this loop continues without any user interference.

## Features:
* It uses 'tkinter' function of python to create the login window where you have to enter your email id,password and the hashtag to be liked.
* The webdriver opens the given browser page.
* You can choose your browser to be Firefox or Google Chrome but you have to import the drivers accordingly like for Firefox import geckodriver in the same path where you are saving the code or for google chrome its chrome driver.
* Your home page of twitter will open after you click on the 'GO' button.
* The 'pyautogui' package of python then finds the hashtag given and locates the heart emoji and scrolls down the page and the loop continues.

## Pre-Requisites:
* Python 3 installed
* Selenium package to be installed.
* Geckodriver to be installed for Firefox browser.
* Pyautogui to be installed.
* Tkinter to be imported.
* While inspecting the login page of twitter, inspect it by using the 'name' locator.

## Contributors:
Tanisha Rakshit
