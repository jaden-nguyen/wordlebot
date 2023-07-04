# Wordle Bot

Wordle Bot is an application that gives the user recommendations for each guess in solving a Wordle.
It uses natural language processing (NLP) techniques to categorize new responses based on the user's
suggestions. If you you aren't familiar with Wordle, you can play a game here:
https://nytimes.com/games/wordle/index.html. This application is deployed on
(https://wordlebot.z5.web.core.windows.net/).

## At a Glance

Let's say the word I'm thinking about is CRISP.

|  Suggesting hints  |      Loading       |      Winning       |
| :----------------: | :----------------: | :----------------: |
| ![](/images/1.png) | ![](/images/2.png) | ![](/images/3.png) |

## Built with

-   TypeScript
-   React
-   Material UI

## Features

-   Users can suggest clues to the bot by clicking individual letter boxes
-   Bot will send a new response based on the clues
-   Users should have responsive feedback when the app is interacting with the server

## License

This project is licensed under the [MIT License](LICENSE).
