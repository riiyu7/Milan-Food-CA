# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.


| Page       | W3C URL                                                                                                         | Screenshot                                                            | Notes           |
| ---------  | ----------------------------------------------------------------------------------------------------------------| --------------------------------------------------------------------- | --------------- |
| Home       | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Friiyu7.github.io%2FMilan-Food-CA%2Findex.html)             | ![screenshot](documentation/testing/html-validation-home.png)         | pass: No errors |
| Menu       | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Friiyu7.github.io%2FMilan-Food-CA%2Fmenu.html)              | ![screenshot](documentation/testing/html-validation-menu.png)         | pass: No errors |
| Contact Us | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Friiyu7.github.io%2FMilan-Food-CA%2Fcontact_us.html)        | ![screenshot](documentation/testing/html-validation-cu.png)           | pass: No errors |
| Thank You  | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Friiyu7.github.io%2FMilan-Food-CA%2Fthank_you.html)         | ![screenshot](documentation/testing/html-validation-thank-you.png)    | pass: No errors |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File      | Jigsaw URL                                                                                                  | Screenshot                                                   | Notes           |
| --------- | ----------------------------------------------------------------------------------------------------------- |------------------------------------------------------------- | --------------- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Friiyu7.github.io%2FMilan-Food-CA%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)  | ![screenshot](documentation/testing/css-validation.png)      | Pass: No Errors |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home                                                         | Menu                                                         | Contact Us                                                 | Thank You | Notes              |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------------  | --------- | ------------------ |
| Chrome  | ![screenshot](documentation/testing/browser-chrome-home.png) | ![screenshot](documentation/testing/browser-chrome-menu.png) | ![screenshot](documentation/testing/browser-chrome-contact-us.png) | ![screenshot](documentation/testing/browser-chrome-thank-you.png)      | Works as expected  |
| Edge    | ![screenshot](documentation/testing/browser-edge-home.png)   | ![screenshot](documentation/testing/browser-edge-menu.png)   | ![screenshot](documentation/testing/browser-edge-contact-us.png)   | ![screenshot](documentation/testing/browser-edge-thank-you.png)     | Works as expected  |
| Brave   | ![screenshot](documentation/testing/browser-brave-home.png)  | ![screenshot](documentation/testing/browser-brave-menu.png)  | ![screenshot](documentation/testing/browser-brave-contact-us.png)  | ![screenshot](documentation/testing/browser-brave-thank-you.png)      | Works as expected  |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device                | Home                                                              | Menu                                                             | Contact Us    | Thank You                                                | 
| --------------------- | ----------------------------------------------------------------- | ---------------------------------------------------------------- | ------------- | --------------------------------------------------------- |
| Galaxy S23 Ultra      | ![screenshot](documentation/testing/my-own-mobile-home.jpg)       | ![screenshot](documentation/testing/my-own-mobile-menu.jpg)      | ![screenshot](documentation/testing/my-own-mobile-contact_us.jpg) | ![screenshot](documentation/testing/my-own-mobile-thank_you.jpg)         |
| Tablet (DevTools)     | ![screenshot](documentation/testing/responsive-tablet-home.png)   | ![screenshot](documentation/testing/responsive-tablet-menu.png)  | ![screenshot](documentation/testing/responsive-tablet-contact_us.png) | ![screenshot](documentation/testing/responsive-tablet-thank_you.png)      |
| Desktop (DevTools)    | ![screenshot](documentation/testing/responsive-desktop-home.png)  | ![screenshot](documentation/testing/responsive-desktop-menu.png) | ![screenshot](documentation/testing/responsive-desktop-contact_us.png) | ![screenshot](documentation/testing/responsive-desktop-thank_you.png)        |

There are slight noticeable scaling issues on the contact_us.html page.



## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page       | Mobile                                                          | Desktop                                                        | Notes               |
| ----       | --------------------------------------------------------------- | -------------------------------------------------------------  | ------------------- |
| Home       | ![screenshot](documentation/testing/la-home-mobile.png)         | ![screenshot](documentation/testing/la-home-desktop.png)       | Some minor warnings |
| Menu       | ![screenshot](documentation/testing/la-menu-mobile.png)         | ![screenshot](documentation/testing/la-menu-desktop.png)       | Some minor warnings |
| Contact Us | ![screenshot](documentation/testing/la-contact-us-mobile.png)   | ![screenshot](documentation/testing/la-contact-us-desktop.png) | Some minor warnings |
| Thank You  | ![screenshot](documentation/testing/la-thank_you-mobile.png)    | ![screenshot](documentation/testing/la-thank_you-desktop.png)  | Some minor warnings |

The main issues I faced with the home screen for both desktop and mobile are the following: 

Serve static assets with an efficient cache policy & Serve images in next-gen formats

## User Story Testing


| User Story                                                                    | Screenshot | Outcome |
| ----------------------------------------------------------------------------- | ---------- | ------- |
| As a new site user, I would not want to see a webpage that is cluttered or hard to use, I would like to see something that provides me information quick and efficiently.| ![screenshot](documentation/testing/User-1.png) | Passed: The site features a simple and easily readable design which doesnt feel overwhelming |
| When I look at a food website as a new user, my first go to link would be the Menu so I can get a little understanding of the type of food they will have. Im also not a fan of downloading PDF's onto my device so preferably id like to see the information on one page. | ![screenshot](documentation/testing/browser-chrome-menu.png) | Passed: A seperate page displays the menu with an easy to read layout. 
|As a site user and potential client, I want to easily find out opening times and contact information so i know what days the business is closed. | ![screenshot](documentation/testing/contact-info.png) | Passed: Easy to read contact information with opening times at the bottom of the screen.|
|As returning user, I want to be able to access the website through my phone at times I might be on the go, I would want to see similarities in the page from desktop and mobile so its easy to navigate. | ![screenshot](documentation/testing/responsive-desktop-home.png) |Passed: Website is responsive on mobile devices aswell as desktop.|

## Bugs

There are no remaining bugs that I am aware of.
