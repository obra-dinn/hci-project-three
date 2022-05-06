# Usability Testing Report

## Summary
This document records the outcome of a series of usability tests conducted on an in-development website created for the purpose of selling cybersecurity certifications and education. In no particular order, we present our finds from both rounds of usability testing.

## Findings

### Incorrect cart calculations
The cart was not properly keeping track of how many items were being effectively held in the cart. Additionally, the fees and total charges were incorrect. These changes were implemented following the second round of tests.

### Inappropriate input types for some fields on checkout
Some of the input fields during the checkout process have input types which add arrows to the input box. This was mildly misleading and could cause some confusion for people who assume you must use the arrows to input the number.

### Phone number formatting
The formatting on the phone number requires a specific format that most users did not realize the first time they entered their phone number. To avoid this, the formatting required should mostl likely be removed or it should be made more obvious. It is currently indicated in the placeholder text which it should not be since the text disappears when the user starts typing.

### Difficulty with date input
Some users had trouble inputting the expiration date using the selector. The option to just type the date in normally should make it easier for most people. This would require some more JavaScript to ensure the date is correctly formatted for data storage.

### Poor color contrast when using a dark theme
One user had an extension on their browser that made the page background change to be a dark color rather than the default white. This led to some issues with the background color of images being white and not matching the website. Also some icons where very hard to see on a dark background. The option to set a dark theme natively may be helpful for people who prefer it. 

### Understanding of the website
Most users were able to understand the purpose of the website as it is a marketplace to buy cybersecurity certifications. They were able to follow the simple logic of a marketplace website as they simply add items to the cart and work through a simple checkout process. 

## Conclusion
Overall, users were able to easily navigate most of the website and only ran into minor hiccups here and there. Most suggestions are small kinks that could be ironed out with some basic tweaks to the website. Further usability testing is required to find any other issues on mobile devices or unconventional screen sizes that were not covered in these rounds of testing.
