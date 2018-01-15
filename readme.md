This sample code will allow user to create a flow based based approach, without needing to create a feature file but by using BDD principles.

Here the code was moodularised to make it reusable.


# End to End Tests

## To run

Go to nightwatch

Run npm install
Run npm start for phantomjs
Run npm run start:chome for chrome
To run the test, in the terminal use 
    <br /> "start": "nightwatch --tag demo",
    <br /> "start:chrome": "nightwatch --tag demo --env chrome",
    <br /> "start:parallel-single-browser": "nightwatch --tag demo_paralall --env chrome",
    <br /> "start:parallel-multiple-browser": "nightwatch --tag demo --env chrome,firefox"

This was presented in London SDET meetup at skills matter on 14 June 2017. 
    
    






