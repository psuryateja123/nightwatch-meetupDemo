This sample code will allow user to create a flow based based approach, by creating feature file and usig page object model.

. In page objects, there are [page objects](https://github.com/psuryateja123/nightwatch-meetupDemo/tree/master/page_objects) that are created with respect to the page names.


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
    
    






