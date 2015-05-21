# node callbox

A simple NodeJS-based Twilio callbox for an apartment.

## To Use

This app is setup to deploy to a simple Heroku instance and only requires one environment variable to be set in it's config, as below:

`CALLBOX_NUMBER=123-456-7890`


Configure Twilio to send voice calls to the following endpoint:

`http://your-app-name.herokuapp.com/callbox`
