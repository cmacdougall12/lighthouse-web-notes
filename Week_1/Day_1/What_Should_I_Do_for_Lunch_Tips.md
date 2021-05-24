### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    return console.log("Wait until you are hungry before you get lunch!");
  } else if (availableTime < 20) {
    return console.log("You should pick something up and eat in back in the Lab or in the kitchen, where you can get to know your fellow classmates.");
  } else if (availableTime < 30) {
    return console.log("You deserve a break, and should try a place in Gastown");
  } else {
    return console.log("You should reconsider how much time you have for lunch! Remember you are in a bootcamp.");
  }
};
```