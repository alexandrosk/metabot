# metabot

The idea behind this project is that we check the tweets from gate.io that contain the words "new listings" 
like this one: https://twitter.com/gate_io/status/1469923460667355142 

Then we need to save the new token to a mongodb and the time that this new listing will come live.

Another service will check if it's time that a listing will go live and at that moment will check if the retweet count is bigger than 50 - 100 retweets (we need to clarify this better)
If it is then by the time this goes live we send a BUY order from gateio API and when it hits 100% we sell. 

