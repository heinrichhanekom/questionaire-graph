# survey-graph
A graphQL schema to interact with a neo4j database containing a survey model

## Start Up the Service
Install all the packages
```
npm install
```

Start the apollo client
```
node index.js
```

Start the apollo client with debug logging
```
DEBUG=@neo4j/graphql:* node index.js
```