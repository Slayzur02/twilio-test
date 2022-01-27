## Overview

A simple twilio app which allows video calling 

## Setup Requirements

Before we begin, we need to collect all the config values we need to run the application:

- Get your account SID (your primary Twilio account identifier) [here](https://www.twilio.com/console).
- Get your API Key SID (for authentication) [here](https://www.twilio.com/console/runtime/api-keys).
- Get your API Key Secret (also auth) [here](https://www.twilio.com/console/runtime/api-keys).

## Run instructions

1. Create a configuration file for your application: `cp .env.template .env`

2. Edit `.env` with the configuration parameters we gathered from above.

3. Next, we need to install our dependencies from npm: `npm install`

4. Run the application: `npm start`