PokeDex https://gina49-jh.github.io/ID_PokeDex_website/

Building a Pokedex for users to search for the specific pokemon name or number which contains information of data to allow users to search and find more about specific pokemon.

Design Process

We created a template to follow on AdobeXD after getting the foundations down on HTML. We collaborated frequently with the live share feature on Visual Studio Code in order to make sure no conflicts in code happen at any time.

for the design protype can be reference from Protyping of design layout.xd  


Existing Features
1. Existing Features
    1.1 - allows users to type a text or an number to search for the pokemon index.
    1.2 - allows users to click on a specific pokemon and display an popup contain the data.
    1.3 - allows users to see an loading bar animation before redirect to a new page.
    1.4 - allows users to see the loading animation while scrolling down the page to find a specific pokemon and hide when completed.
    1.5 - allows users to enter the input of the contact details and send the data to restdb database.
    1.6 - allows users to clear the user input when reloading the page.

2. Features Left to Implement
    1. Allows users to click on a random number which will generate a random number of pokemon in an array.
    2. Allows users to see the charts of the pokemon stat when click on the card.
    3. Allows users to see the description of the pokemon when click on the card.
    4. Allows users to click on the pokemon types and will generate a pokemon data matches with the types.

3. Technologies Used
    3.1 JQuery
        The project uses JQuery to simplify DOM manipulation.
        reference link: [JQuery](https://jquery.com/)
    2. Bootstrap 
        The project uses Bootstrap version 5.0.0 and 3.4 to simplify default template for html.
        reference link for v5.0  : [Bootstrap5] (https://getbootstrap.com/)
        reference link for v3.4.1: [Bootstrap3.4.1](https://getbootstrap.com/docs/3.4/)
    3. PokeAPI
        The project uses PokeAPI to retrieve the data and simplify DOM mainpulation.
        reference link: [PokeAPI] (https://pokeapi.co/pokemon/)
    4. RestDB
        The project uses RestDB to send the user data to store in the database.
        reference link: [Restdb] (https://restdb.io/)
    5. Lottie
        The project uses Lottie as a loading spinner as the page loads.
        reference link: [Lottie] (https://unpkg.com/@lottiefiles/lottie-player@0.5.1/dist/lottie-player.js)

Testing
    1. Contact form:
        1.1 Go to the "Contact Us" page
        1.2 Try to click on the first textbox and without user input and click on second textbox verify a red border color appears on the 1.3 screen for empty or invalid input.
        1.4 Try to submit the form with an invalid email address and verify that a relevant error message appears
        1.5 Try to submit the form with all inputs valid and verify that a success message appears.
    
    2 Homepage:
        2.1 Go to the "Homepage" page
        2.2 Try to type a random number or pokemon name on the textbox and verify that specifc data appears below the textbox.
        2.3 Try to reload the page which cause the text that was pervious typed will be deleted and will display prompt message.
        2.4 Try to click on any random pokemon name in the card which will display an popup with the pokemon data in the same window.
        2.5 Try to click close which close the popup contain pokemon data and only display array of pokemon name and number.

The project looks and how it works was when users use eg computer...etc to access the page, the css will check for the screen sizes 
of the devices used to access the page. If the device eg computer screen of height 1366px and width 768px, css will check the width if width is more than 740px, then it will only use the code from 1 to 216 in mainstyle.css to display the website layout for web version. If the device eg mobile screen of height 360px and width 740px, css will check the width if width is less than 740px, then it will only use the media query code from line 218 to line 305 in a mainstyle.css to display the website layout meant for mobile version. How it looks 

For the mobile version that width is scaled to max of 740px.
1. navbar has be reduced to text with background color of black box contains 3 white bar inside a button
2. box contains title with text color of grey and background color of white below the navbar
3. box contains Name or number with text color of white, textbox contain message and background colour of blue below title
4. box contains text of how to use the site text colour of white and background colour of grey below Name or number
5. card contain the pokemon number , name and picture of each pokemon and background colour of white.

For the web version:
1. navbar which contain the title, home and contactpage button background colour of black and text colour is white.
2. box contains title with text color of grey and background color of white below the navbar
3. box contains Name or number, textbox contain message, text of how to use the site, background colour and text is white below title.
4. card contain the pokemon number , name and picture of each pokemon and background colour of white which each row contain 3 cards.

Bugs or known issues that was not addressed:
1. There is a first bug where users type the correct values and press submit button, the page is freeze and did not display an alert for sent successfully to the restdb database however when we check on the database we found a new records of the user input on the contactpage this issue have not addresssed yet.

2. You can send an empty contact form, as there is no data validation, which also causes the slide to freeze.

3. There is a second bug where users refreshed the page on the contactpage, when run on google chrome it was able to clear user input on textbox successfully. While using firefox browser, when refreshed it was not able to clear user input on textbox successfully.

Credits
    Content
        The texts used in this site were obtained from [PokeDex](https://pokeapi.co/api/v2/pokemon/1) to [PokeDex](https://pokeapi.co/api/v2/pokemon/898) in a JSON Format.
        
        The README.MD template used in this site were obtained from [GitHub](https://gina49-jh.github.io/ID_PokeDex_website/)

    Media
        The photos used in this site were obtained from [PokeDex](https://pokeapi.co/api/v2/pokemon/1) to [PokeDex](https://pokeapi.co/api/v2/pokemon/898) in a JSON Format.

    Acknowledgements

        I received inspiration for this project design layout from [PokeDex](https://www.pokemon.com/us/pokedex/)
        
        I received inspiration of building this project PokeDex from: 
        [YouTube] (https://www.youtube.com/watch?v=L0pPRauLP2E&t=s&ab_channel=JamesQQuick) 
        [YouTube] (https://www.youtube.com/watch?v=T-VQUKeSU1w&ab_channel=JamesQQuick)

        I received inspiration of building this project search request from:
        [YouTube] (https://www.youtube.com/watch?v=wxz5vJ1BWrc)

        I received inspiration of the progress bar to work from:
        [YouTube] (https://www.youtube.com/watch?v=xuA83OYTE7I&t=320s)
