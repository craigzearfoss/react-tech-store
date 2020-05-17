# Tech Store Porject

```
create-react-app tech-store
cd tech-store
npm install --save react-router-dom
npm install --save react-icons
npm install --save styled-components
npm install --save bootstrap
```

## Styled Components
- Example
```
import React { Component } from "react";
import styles from "styled-component";
class App extends Component {
  render() {
    return (
      <h1>
        <Button large>hello styled component</Button>
      <.h1>
    )
  }
}
const color = "#f15025";
const Button = style.button`
  color: white;
  background: ${color}
  font-size: ${(props) => props.large ? "3rem" : "1rem")};
`;
``` 