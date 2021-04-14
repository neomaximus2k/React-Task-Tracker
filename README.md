# React-Task-Tracker

Example react task tracker.  The tracker is split into 3 seperate commits:

1. Simple system with static data. **init**
2. Second stage is with a JSON server and routing. **Stage2**
3. Final stage is with a Laravel backend. **TBD**

## JSON Server
JSON server is installed using https://github.com/typicode/json-server
```
npm install json-server
```
Add the following to your `package.json` file in the scripts area
```
"server": "json-server --watch db.json --port 5000"
```
you can then run the JSON server using `npm run server`

## Routing
Routing is handled by react routing dom
```
npm install react-router-dom
```
