![Virtualizm UI](doc/virtualizm-ui-vm.png)

# Set up 

### Install dependencies
#### `yarn install`

### Add config

add `public/config.js` file like following:
```js
window.CONFIG = {
  apiUrl: 'http://localhost:4567/api',
  wsUrl: 'ws://localhost:4567/ws_events'
}
```

### Run into development mode
#### `yarn start`

### Run tests
#### `yarn test`

### Production build
#### `yarn build`
