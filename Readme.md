## Simple Twitch chatbot
![twitch chatbot screenshot](https://github.com/owlypixel/Twitch_chatbot/raw/master/public/images/screenshot.png)

## What is this
This is a really simple Twitch chatbot. Every time someone in chat types the word "owl", the bot shows a random owl gif and user nickname on the html page. 
## How it works
With the help of irc-framework we listen to a Twitch chat. Skateboard library creates the websocket connection between our NodeJS server and the webpage that accessing it. Also, Skateboard sets up a localhost to host your public assets and fires up engine.io websocket connection, so our frontend can use a client library to cennect to websocket. It's pretty easy to get things up and running quickly with this library.
## What you'll learn from this
- Creating a simple server with NodeJs
- Working with websocket connections
- Implementing a world's simplest message queue
- Using bot to match messages in the chat

## Copyright & License
Copyright (c) 2017 Owlypixel Foundation - Released under the MIT License.
