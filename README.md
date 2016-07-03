# RNBugsnag

### Description
This is a react-native module supporting both **iOS** and **Android**, and allows you to monitor crashes using [Bugsnag](https://bugsnag.com/).


### Installation (TODO)

```bash
npm install -s react-native-bugsnag
```


### Usage

```js
import RNBugsnag from 'react-native-bugsnag'

RNBugsnag({ApiKey: "YOUR_API_KEY_FROM_BUGSNAG"})
```


### API

| method | parameters (body) | Description | Returns|
|---------------|-------------------------------------------------|--------------------------------------------------------------|-----|
| **setIdentifier** | {`userId`:string, `userEmail`: string, `userFullname`: string} |  This function sets the id of the user that we will be logging.| Promise |
