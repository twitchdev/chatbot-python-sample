# Twitch Chatbot Python Sample
Here you will find a simple Python chatbot using IRC that can help demonstrate how to interact with chat on Twitch.

## Installation
After you have cloned this repository, use pip or easy_install to install the IRC library.

```sh
$ pip install irc
```

## Usage
To run the chatbot, you will need to provide an OAuth access token with the chat_login scope.  You can reference an authentication sample to accomplish this, or simply use the [Twitch Chat OAuth Password Generator](http://twitchapps.com/tmi/).

```sh
$ python chatbot.py <username> <client id> <token> <channel>
```
* Username - The username of the chatbot
* Client ID - Your registered application's Client ID to allow API calls by the bot
* Token - Your OAuth Token
* Channel - The channel your bot will connect to

## Next Steps
Feel free to augment the chatbot with your own new commands by adding them in the do_command() function. 
