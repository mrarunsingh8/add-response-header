# add-response-header-middleware



## Authors

- [@arunsingh](https://github.com/mrarunsingh8)




## Installation

Install add-response-header-middleware with npm

```bash
  npm i add-response-header-middleware
```



**2. How to use it**

```javascript
const addResponseHeaderMiddleware = require("add-response-header-middleware");

Route.get("/", addResponseHeaderMiddleware, (req, res)=>{

});

```