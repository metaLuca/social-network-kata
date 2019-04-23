# Social Network kata

<img src="http://kata-log.rocks/images/social_network.jpg" height="20px" width="20px" alt="cover"/>

## Your Backlog
**Posting:** Alice can publish messages to a personal timeline

**Reading:** Bob can view Alice’s timeline

**Following:** Charlie can subscribe to Alice’s and Bob’s timelines, and view an aggregated list of all subscriptions

**Mentions:** Bob can link to Charlie in a message using “@”

**Links:** Alice can link to a clickable web resource in a message

**Direct Messages:** Mallory can send a private message to Alice

# Mocha tests

## Installation

Go to the root directory (where the `package.json` is located) and run:

```bash
npm install
```

## Running tests

Run the tests once:

```bash
npm test
```

Run the test and re-run them once a file changes:

```bash
npm run test:watch
```

### What's included

* Support for ES-2015 and stage-0 using Babel presets
* [Sinon JS](http://sinonjs.org/) for all stub, spy and mocking needs
* Mocha to run tests
* [Assertions using Chai]((http://chaijs.com/api/bdd)), extended with the
  [`sinon-chai` plugin](https://github.com/domenic/sinon-chai).
  * The Expect style is used by default,
  you can change to use `Should` instead, in `test/test-setup.js`,
