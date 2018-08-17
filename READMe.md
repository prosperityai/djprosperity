# DJProsperity

DJProsperity is a demo Google Home App that integrates PubNub functions into Google's Dialogflow API in order to perform functions on user speech input. DJProsperity will analyze a user's sentiment based off their one sentence response to the question "What's Up." Then it will play the right song according to their mood.


## Quickstart


Sign Up for PubNub and create a new Project

Sign Up for Dialogflow and create a new Agent and a Intent named Get_Emotion.

In Default Welcome Intent, add text response, "Hey What's up?"

In Get_Emotion intent, add training phrase @sys.any:any

Enable webhook calls for Get_Emotion intent and then set its webhook URL as playmusic function's URL.

Sign Up for Amazon Web Services

Create AWS Access Key and Secret Key. Enter these credentials into My Secrets key-value store with keys "AWS_access_key" and "AWS_secret_key."

Create functions module and two functions within it: playmusic and amazoncomprehend.

Enter code for each function into its respective code editor on PubNub functions page.

Ensure that functions module is running and test your app!
