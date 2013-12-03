# Hubot: hubot-factoid

A hubot script to build a factoid library for common questions.

See [`src/hello-world.coffee`](src/hello-world.coffee) for full documentation.

## Installation

Add **hubot-factoid** to your `package.json` file:

```json
"dependencies": {
  "hubot": ">= 2.5.1",
  "hubot-scripts": ">= 2.4.2",
  "hubot-factoid": ">= 0.0.0",
  "hubot-hipchat": "~2.5.1-5",
}
```

Add **hubot-factoid** to your `external-scripts.json`:

```json
["hubot-factoid"]
```

Run `npm install`

## Sample Interaction

```
user1>> hubot hello
hubot>> hello!
```
