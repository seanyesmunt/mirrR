# mirrR

mirrR is a smart mirror React/Node app that can run on a Raspberry Pi

## How to run

Open your terminal and copy and paste these commands:

`git clone https://github.com/seanyesmunt/mirrR && cd mirrR`

`npm i && npm start`

Then go to [http://localhost:3000](http://localhost:3000)


### News/Twitter/Weather

Out of the box, News, Twitter and Weather will not work. You will need to retrieve the API keys first. MirrR will work fine without the API keys, you will just see a message if you try to toggle a component that needs one.

[News (NY Times)](https://developer.nytimes.com/signup) Choose "Top Stories V1" from the dropdown.

[Twitter](https://apps.twitter.com/) You will need to signup and create a new app.

[Weather (forecast.io)](https://developer.forecast.io/)

### Other info

This works on a Raspberry Pi 3. The original Pi is too slow to run this page, I haven't tested this on a Pi 2.

If you need to install Node/NPM, checkout [this treehouse guide](http://treehouse.github.io/installation-guides/mac/node-mac.html).

Talk to me [@seanyesmunt](https://twitter.com/seanyesmunt) if you have any questions.
