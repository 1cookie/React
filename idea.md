## Using class components as opposed to function based.

```
class MyClass 
{
  render(){
    return (<div>Some JSX</div>);
  }
}

export default MyClass;
```

```
import React from 'react';

function MyComponent = (props) => {
  return (<div>Some JSX</div>);
}

export default MyComponent;
```

## Usage

    npm install && npm start
