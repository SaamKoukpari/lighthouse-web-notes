### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  
    if (hungry) {
      if (availableTime <= 20) {
      console.log("I'm hungry and I have 20 minutes for lunch.");
      } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("I have less than 30 minutes");
      } else {
          console.log("not enough time for that!");
      }
    } else {
      console.log(`I'm not hungry and I have ${availableTime} for lunch`)
    } 
  }
```
