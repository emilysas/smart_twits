# smart_twits

Makeathon Team: Andy Newman, Emily Sas, Bibiana Cristofol, Marcin Walendzik, Richard Ighodaro

[![Code Climate](https://codeclimate.com/github/andyg72/smart_twits/badges/gpa.svg)](https://codeclimate.com/github/andyg72/smart_twits)  [![Test Coverage](https://codeclimate.com/github/andyg72/smart_twits/badges/coverage.svg)](https://codeclimate.com/github/andyg72/smart_twits)

SmartTwits aims to provide users with information about currently trending tweets with a view to shedding a little light on the context of the trend. It displays the top ten trending tweets on the left hand side, and upon users clicking these, provides details of:

* the most frequently occuring words within the trending tweets
* the trending tweets that have the most retweets
* the most frequently occuring mentions within the trending tweets
* the trending tweets from users with the most followers
* trending tweets that originated from media organisations

To pull recent changes from twittter: require 'api_twit.rb', update = APITwitter.new, update.refresh_all_twitter_data

Following the Makeathon I decided to try to make the front-end design a little cleaner. I incorporated bootstrap and tried to give the page as clean a feel as possible - not an easy job for an app that has so much text. The design still needs work, but currently looks like this:

![Screenshot](/Screen Shot 2015-02-15 at 10.37.35.png?raw=true "ScreenShot")

##Future Intentions

Having revisited the code following the makeathon, I realised that the classes need rethinking. I would like to redesign the backend logic as well as refactor the code that speaks to the API.
