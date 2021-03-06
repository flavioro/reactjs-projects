# R E A C T - J S - projects ![](https://www.mundojs.com.br/wp-content/uploads/2020/09/jsxComponentsProps.png)
ReactJs Projects

### Mapped Select option in React
```js
import React from "react";

const options = [
  {
    label: "Apple",
    value: "apple",
  },
  {
    label: "Mango",
    value: "mango",
  },
  {
    label: "Banana",
    value: "banana",
  },
  {
    label: "Pineapple",
    value: "pineapple",
  },
];

class App extends React.Component {
  render() {
    return (
      <div id="App">
        <div className="select-container">
          <select>
            {options.map((option) => (
              <option value={option.value}>{option.label}</option>
            ))}
          </select>
        </div>
      </div>
    );
  }
}

export default App;
```


**Use ReactJs online**

- https://stackblitz.com/edit/react-ls1dwp?file=index.js

- https://codesandbox.io/s/8k2kvlnly0?file=/src/index.js

- https://codesandbox.io/s/github/the-road-to-learn-react/react-list-component/tree/master/?fontsize=14&file=/src/components/ListScrollToItem.js


**Examples**
 - https://github.com/drcmda/the-substance
 
 -Scroll a component-into-view (https://robinvdvleuten.nl/blog/scroll-a-react-component-into-view/)
 
 - Scroll to an element on click in React js - https://medium.com/how-to-react/scroll-to-an-element-on-click-in-react-js-8424e478bb9
 
 
 
 Next JS https://codesandbox.io/s/muddy-shadow-l3qtd?file=/pages/itens.js:9089-9094
 
 
 **API P H O T O S**
  - https://picsum.photos/
