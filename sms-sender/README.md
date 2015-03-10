# Send an SMS easily

Send an SMS easily using [Webtask.io](https://webtask.io)

![Send SMS](//cdn.auth0.com/webtask/sendSms.gif)

## Important pieces



## Using the example

### 1. Install Webtaskify

First, you need to install `webtaskify` to create JS proxies to call Webtask.io.

```bash
npm install -g webtaskify
```

### 2. Configure the SMS sender with your Twilio account

Create a `.env` file with your Twilio configuration with the following format:

```properties
TWILIO_ACCOUNT_SID= #Twilio Account SID
TWILIO_AUTH_TOKEN= #Twilio Auth token
TWILIO_NUMBER= # From number for the SMS
```

### 3. Create the JS proxies to call Webtask.io

```bash
webtaskify create -f ./sendSms.js -t [yourAccountName] -n [yourWebtaskToken]
```

### 4. Run & Enjoy

It's time to run the app and see it working. Just serve the current directory with `serve` or any other tool



