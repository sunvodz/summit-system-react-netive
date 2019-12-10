# summit-system-react-netive


 ```
npm install expo-cli --global
npm install -g yarn
expo init summit-system-react-netive
:blank
:summit-system
use yarn :y
CD summit-system-react-netive
yarn add react-navigation
yarn add react-native-reanimated react-native-gesture-handler react-native-screens@^1.0.0-alpha.23 
yarn add react-navigation-tabs
yarn start
 ```
 
Metro Bundler process exited with code 1 Set EXPO_DEBUG=true in your env to view the stack trace.

\node_modules\metro-config\src\defaults\blacklist.js

change to:
 ```
var sharedBlacklist = [
  /node_modules[\/\\]react[\/\\]dist[\/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
 ```
