# OpenAI Realtime API Websocket Server

This is a websocket server for connecting to the OpenAI Realtime API

Useful if you want to connect to the OpenAI API from a frontend application, but don't want to store your
API Key on the backend.

Code for this has been pulled out from the relay server code on the openai-realtime-console demo.

Can check out the source code from that repo for the relay server here

https://github.com/openai/openai-realtime-console/tree/main/relay-server

Can also check out their Readme which explains a bit more about how the relay server works

https://github.com/openai/openai-realtime-console

So this repo bascially pulls that out into an express app, giving you a quick starting point to help build out
your own applications that needs a websocket server for connecting to the OpenAI realtime API