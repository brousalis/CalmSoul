# CalmSoul

Console logging wrapper to ease your development soul, for Node.js


## Installation

```bash
npm install calmsoul
```

```javascript
var calmsoul = require("calmsoul");
```


## Usage & Commands

### Set

Defaults:
* log: true
* debug: false
* info: true


**Turn a single method on or off**

```javascript
calmsoul.set("log", true);
```

**Change multiple settings at once**

```javascript
calmsoul.set({"log": true, "info": false, "debug": false});
```


### Log

```javascript
calmsoul.log("I am a log message!");
```

### Debug

```javascript
calmsoul.debug("I am a debug message!");
```

### Info

```javascript
calmsoul.info("I am an info message!");
```
