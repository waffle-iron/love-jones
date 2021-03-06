[![Stories in Ready](https://badge.waffle.io/wensontsai/love-jones.png?label=ready&title=Ready)](https://waffle.io/wensontsai/love-jones)
# Love Jones
Webpack, React/Redux, Node/Express.
User auth with JSON Web Tokens, and store-wide notifications system.

### DEVELOPMENT
Serves up on localhost:3000

#### Setup
1. Install Node Modules:  
```npm i```

2. Testing Environment:  
```npm i -g mocha```

#### Run 
1.  Client
  1. Run tests:  
```npm run test:watch```

  2. Run webpack to compile front-end in dev mode:  
```npm start```

2.  Server
  1.  Run tests:  
```cd server && npm run test:watch```

  2.  Run Babel to transpile Node/Express back-end for API routes:  
```cd server && npm run build-dev:watch```
