# dash-sms
Send an SMS when an Amazon Dash button is pressed

## Setup

```
$ npm install
```

Copy config.json.sampl to config.json and update with your info.

Follow the [node-dash-button](https://github.com/hortinstein/node-dash-button) instructions to find your dash-button id.

Run it using:

```
$ sudo node index.js
```

Or install it globally and run

```
$ cd path/to/dashgong
$ sudo npm install . -g
$ sudo dashgong
```

Press your dash button and you should receive an SMS on the phone you set up.

