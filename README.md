jsfiddlelogger
=============

Redirect console.log to write to document.body.
![](./screen_shot.png)

Usage
=============

This is the entire code, so add it at the top of some javascript
```
console.log = function(msg) { 
    document.body.innerHTML += msg + '<br>'; 
}
```

In JSFIDDLE, add http://seanewest.github.io/cabin/cabin.js to External Resources (as in the screenshot).


