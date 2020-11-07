# event-bot

Creates an event in the  google calendar.

Example:

Birthday Remainder at 12 AM tomorrow.

Interview at 4 PM.


## Requirements

rasa

python3

google-api-python-client

google-auth-httplib2

google-auth-oauthlib

## Google-Calendar Oauth 

Refer this url https://developers.google.com/calendar/quickstart/python to make google calendar api requests.

The file token.pickle stores the user's access and refresh tokens, and is created automatically when the authorization flow completes for the first time.

## How to run 

Train a unified NLU and dialogue model by running the below command:

$ rasa train

Once the model is trained, you can load it and talk to your assistant by running:

$ rasa shell

The command above will load your assistant for you to test. If, for example, you want to test only the NLU model, you can use:

$ rasa shell nlu

Launch the Rasa X UI. In your project directory run the command below:

$ rasa x
