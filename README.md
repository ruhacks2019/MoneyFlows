# MoneyFlows

Check out our [Devpost](https://devpost.com/software/moneyflows-cspl8k) as well! credit to @JenitaJohn

MoneyFlows consists of a web-based tool designed to facilate new grads to manage their student loans and a personalized investment advisor (chatbot) using the Messenger API and a cloud tool with Natural Language Processing (NLP), built with 
* [Node.js](https://nodejs.org/) - evented I/O for the backend
* Express - fast node.js network app framework
* [Dialogflow](https://dialogflow.com/) - a cloud platform that provides several NLP functions that parse user input and match them to the right response

## Demo - budget calculator
Here is a quick demo of the budget calculator:

![pic 1](/img/landpage.png)

![pic 2](/img/web1.png)

![pic 3](/img/web2.png)


## Demo - chatbot
Here is a quick demo of the investment advisor (chatbot):

![head](/img/head.png)

![example msg 1](/img/msg1.png)

![example msg 2](/img/msg2.png)

## How to run

MoneyFlows requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

### How to run
To get started, clone the repo into the local directory:
```sh
$ git clone https://github.com/ruhacks2019/MoneyFlows
$ cd MoneyFlows
```

Next, execute npm install to download dependencies:
```sh
$ npm install body-parser express
$ node src/index.js
```

Install [ngrok](https://ngrok.com/) inside local the directory, and start an HTTP tunnel on port 5000 by running the following command in a separate terminal session:
```sh
$ ./ngrok http 5000
```

Add corresponding webhook to the Facebook page in order to link to the chatbot.

Test the [chatbot](m.me/2229489643807919) on Messenger!
