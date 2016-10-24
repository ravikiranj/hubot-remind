# hubot-remind

Script to remind users to do things after a time interval

See [`src/remind.coffee`](src/remind.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-remind --save`

Then add **hubot-remind** to your `external-scripts.json`:

```json
[
  "hubot-remind"
]
```

## Sample Interaction

```
user1>> hubot remind me in 2 seconds to bounce dev server
hubot>> I'll remind you to bounce dev server in a few seconds
hubot>> @Ravi you asked me to remind you to bounce dev server
```
