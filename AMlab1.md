# 2 Things I Learened in the Form of Quiz Questions

1. Is the following code synchronous or asynchronous?

   ```js
   var food = fs.readFile('foot.txt', 'utf8', function(err, food) {
   if (err) {
   console.log(err);
   } else {
    console.log(food);
    }
   });
   ```
    
   ## Answer: asynchronous because it uses a callback function
  
1. If you change the 200 code while running your local server will it update?
  
   ```js
   const http = require('http');


   http
   .createServer((request, response) => {
        response.writeHead(200);
        response.end("Our first node page");
    })
    .listen(999);


   console.log('Server running on port 3000')
   ```
   
   ## Answer: It will NOT updated until you restart the server, it cannot update in this case while running.

# 2 Questions I still have are...

* 
