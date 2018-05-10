# 2 Things I Learened in the Form of Quiz Questions

1. Is the following code synchronous or asynchronous?

```js
var food = fs.readfile('foot.txt', 'utf8', function(err, food){
  if (err) {
  console.log(err);
  }else {
    console.log(food);
    }}'
    ````
    
    ## Answer: asynchronous because it uses a callback function
