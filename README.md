# react-native-timeago

```jsx
import React, { Component } from 'react';
import TimeAgo from 'react-native-timeago';

// Timestamp can be any valid data type accepted in a Moment.js constructor
// Currently accepts string, number, array, or a Date instance
let timestamp = "2015-06-21T06:24:44.124Z";

class MyComponent extends Component {

  ...

  render() {
    return (
      <TimeAgo time={timestamp} />
    )
  }

  ...
};
```
To FR (exemple):
```jsx
import TimeAgo from "react-native-timeago";
import moment from "moment";
import fr from "moment/locale/fr";

moment.locale('fr');
...
```