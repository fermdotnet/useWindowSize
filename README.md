## A custom hook for react: useWindowSize

### Demo (Codepen)

https://codepen.io/ferdotnet/pen/gOKKRJE

### Install

```yarn add @ferdotnet/use-window-size```

### How to use it?

```
import React from 'react';
import useWindowSize from '@ferdotnet/use-window-size';

export default () => {
    const { width, height } = useWindowSize(); 

    return <div>width: {width} height: {height}</div>;
};
```
