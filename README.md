# react-easy-button

A simple react button component which can be use to add anywhere in react application without investing on styling.

## Installation and usage

To use this module, install it:

```bash
npm i @priyanka_pal/react-easybutton
```

Then use it in your app:

```js
import React from 'react';
import { EasyButton } from "@priyanka_pal/react-easybutton";

export default function App() {

  return (
      <EasyButton>Your button content</EasyButton>
  );
}
```

## Props

Props | Description | Value | Default value | Is required 
--- | --- | --- | --- | ---
type | type of button | submit or button | submit | false
color | color of the button | primary,secondary,success,warning,danger | primary | false
outlined | make outline button | true or false | false | false
flat | add button shadow | true or false | true | false