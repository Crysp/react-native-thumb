
# react-native-thumb
Get thumbnail from local media. Currently, it only supports for video.

## Getting started

`$ npm install react-native-thumb --save`

### Mostly automatic installation

`$ react-native link react-native-thumb`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-thumb` and add `RNThumb.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNThumb.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

## Usage
```javascript
import RNThumb from 'react-native-thumb';

RNThumb.get(filepath, 100).then((result) => {
  console.log(result.path); // thumbnail path
})
```
