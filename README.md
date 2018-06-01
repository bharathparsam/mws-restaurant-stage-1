# Restaurant Review Stage 1

- Restaurant review is an application which allows user to browse or view all types of restaurants.
- Google maps API is used to load the maps.
- This is a responsive web application which can be accessed over all screen sizes
- Web application meets the accessibility standards so that it makes convenient for the screen readers as well as keyboard users to access.
- Service worker for cache creation so this lets users to load even without internet.
## How to Run
- Clone the GitHub repository.
- Install python if you don't have it on your system using the following link
[website](https://www.python.org/)
- If you are using Python 2.x, then run the server with `python -m SimpleHTTPServer 2000`
- If you are using Python 3.x, then run the server with `python3 -m http.server 2000`
- Run `http://localhost:2000` to launch the website
- If you wish to change the `port number` then change it in `dphelper.js(line 11)`
- If images doesn't get loaded just refresh or reload the page again in new tab.
- This wont occur again once it is loaded because images are being cached and you will not have any issue with it.
