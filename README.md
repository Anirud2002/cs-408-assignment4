# Accessibility lab

## Overview

Lab regarding accessibility

## Instructions for code reviewers

Thank you for taking the time to review my code. Please follow the steps below to get the project running on your local machine:

1. **Start the Live Server**

   - If you're using Visual Studio Code, you can use the Live Server extension by right-clicking on `index.html` and selecting "Open with Live Server."

## Accessibility Lab Answers

The color contrast between #2a2a2a and #ffffff was 14:1 which good enough but not great. However, I changed the color of the text to pure black and color contrast ratio came out as 21:1 which was a lot more improved.

When I tried to navigate the site using keyboard after cloning the repo, I noticed some of the elements like image of bears, and table were not highlighted and therefore screen reader wouldn't be able to pick up those as well.

I updated the navigated html element to <nav>.

Other considerations:

1. Make the page responsive (make it all screen size friendly)
2. Maybe add functionality to toggle between dark mode and night mode. That would be nice!

## Sources and Credits

ChatGPT : https://chatgpt.com/ - for quickly knowing how to make sections accessible
W3Schools : https://www.w3schools.com/tags/tag_cite.asp - used for css style properties like "flex-grow"
