jsfiddlelogger
=============

Show console.log output in the JSFIDDLE result pane.
![](./screen_shot.png)

Usage
=============

This is the entire code, so you can just add it to the top of your javascript
```
console.log = function(msg) { 
    document.body.innerHTML += msg + '<br>'; 
}
```

Alternatively, you can add http://seanewest.github.io/jsfiddlelogger/logger.js to External Resources (see screenshot).


