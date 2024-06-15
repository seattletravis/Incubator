# WELCOME TO THE INCUBATOR!!!

## Put all your app ideas here, and someday just maybe I'll build it.

### If you build it they will get built!

### <u>Low hanging fruit</u>

(The best sort of project ideas, stuff that can get done in a few weeks!)

## Idea #1 (Penny Press Adventure APP)

(I love pressed pennies!) There's something about the nostegia, childhood curriosity, that idea that there's a treasure adventure waiting for you to take it on. That's where this full stack web application comes into play.

The existing pressed penny api is really, really outdated and lame. It gives a map with all the pressed penny machines, but this is an outdated model and frontend. The new frontends for address locations start with a list of address cards that are ranked from shortest distance to the mobile device, and if on a pc then prompt user for location then show address cards. this is the perfect frontend for your onthego penny press hunting adventure.

Front end -

1.  prompt for location or get location from device,
2.  show list of address cards ranked by dist to user,
3.  CLick on card to show more information, and other user notes
4.  Sign in to leave your account of your adventure, (is penny press out of order?, How much is costs, other details)

Back end -

1.  use existing API for penny presses -or- build new backend
2.  authenitcation, simple chat functionality, reviews, penny press status,
3.  Use Django for the project
4.  Spin up server at my house because the cloud is not cool for an app that will get no hits.
5.  use Docker and Kubernetes - becuase it's so easy.

JSON Penny Press Machines -

pennyPressMachines =
{
"key": "1",
"name": "nameOfStoreOrBusiness",
"address": {
"street": "123 front st",
"city": "Seattle",
"state": "WA"},  
"outOfOrder": False,
"costPerPress": 0.50,
"paymentMethods": ["cash", "credit", "coin"],
"numberOfImpressions": 4,
}
