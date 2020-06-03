# Weekly Assignment No. 7

NOTE: This assignment will count for two weekly assignments (7 and 8).

## Due Date

This assignment is due on Tuesday, June 16, at 11:59 PM.

## Overview

This assignment will have you develop a web page that displays news stories from the New York Times. The stories will be retrieved using JavaScript AJAX calls to the application programming interface (API) provided by the New York Times.

Your page must allow users to display news from the following sections from the Top Stories API:

- Home (the default news displayed when the page is first loaded)
- Arts
- Business
- Dining
- Fashion
- Health Magazine
- National Opinion
- Politics
- Real Estate
- Science
- Sports
- Technology
- World

## Getting an API Key

You will need an API key in order to communicate with the API. Follow these steps to get one:

1. Go to https://developer.nytimes.com/accounts/create to create a login.
2. You may need to confirm your registration via email.
3. Once your account has been created an activated, login to the API site at https://developer.nytimes.com/accounts/login
4. Once logged in, click on the click on the API's - Learn about and try the API's panel.
5. Now locate the Top Stories API panel and click on it. Bookmark this page. You will need to refer back to it throughout this assignment.
6. You will now need to request an API key. You need the key in order to access the Top Stories API.
7. Click on your email address in the upper-right hand corner of the web page. Select Apps.
8. Now click on the +NEW APP button in the upper right hand corner of the page.
9. You will be brought to another page where you need to enter an App Name and a Description. For the App Name enter 'CTEC 126'. For the Description enter 'Using the NYT API for a school assignment'.
10. You then need to select which API you intend to use. Move the toggle in the Top Stories API panel to turn it on.
11. In the upper-right hand corner you will see the CREATE button enabled. Click on the button to create your API key.
12. A new page will be displayed that contains information about your app. In the API Keys section, click on the icon to the right of your API key. This will copy it to the clipboard.
13. Now save your API key somewhere that you won't lose it. You will need this key before you begin coding.
14. An HTML page that includes some very simple JavaScript has been provided to help you test your key. The name of the file is test_api_key.html. Look for the place in the code to insert your API key.
15. Test your API key. If it's not working, contact the instructor as soon as possible.
16. Now that you have your API key and have tested it, you are ready to start coding.

## Assignment Details

- Your page must show all of the stories returned from the API.
- An HTML ```<select>``` control should be used that allows a person to select the news section they want to retrieve stories from.
- The stories should be loaded on page load.
- When the user selects another news section, only the stories section of the page should reload. The entire page MUST NOT reload.
- A Refresh button must be provided that allows a person to click it to get the latest stories.
- For each story, the following information must be displayed:
  - The "section" of the newspaper the article appeared in
  - The "title" of the article. Make the title a clickable link to the URL of the story
  - The story "abstract"
  - The story "byline"
  - The "published date" in a format other than the one supplied. Take a look at moment.js reference in Canvas.
  - One of the multimedia images for the news story.
- All of the news stories should be displayed as cards.
- All of your JavaScript code must be in the js/nyt.js file.
- Your page needs to be styled using the nyt.css stylesheet and look professional.
- Your HTML and CSS must validate.
- Push your code back to GitHub when you have completed the assignment.