# Full Stack Developer Practice Question with Answer

> Topic 
- JavaScript
- React.js
- Next.js 
- Node.js 
- Express.js 

## React.js
### What is React.js?
React.js is an open-source JavaScript library for building user interfaces, developed by Facebook.

### Major Features of React.js
- **VDOM (Virtual Document Object Model)**
    - Copying the real DOM in memory is called the Virtual DOM.
    - React uses the Virtual DOM to achieve efficient updates.
    - It compares the real DOM with the new Virtual DOM and updates the changes in the real DOM, which increases the performance of React. This process is called **reconciliation**.

- **JSX (JavaScript XML)**
    - Allows you to write HTML code in React components.

- **Component**
- **High Performance**

### Components
There are 2 types of components in React:
1. **Class-based Components**

    ```javascript
    import { Component } from "react";

    class ClassComponent extends Component {
        render() {
            return <h1>Kamlesh</h1>;
        }
    }

    export default ClassComponent;
    ```

2. **Functional Components**

    ```javascript
    const FunctionalComponent = () => {
        return <h1>Kamlesh</h1>;
    }

    export default FunctionalComponent;
    ```

    or 

    ```javascript
    function FunctionalComponent() {
        return <h1>Kamlesh</h1>;
    }

    export default FunctionalComponent;
    ```

### State in React
- The state is an object that holds information about the component.
- When the state changes, it re-renders the component automatically to display the latest values.

  ```javascript
  const [count, setCount] = useState(0);

  // `count` is the state which holds the value 0, and `setCount` is the function used to set or change the new value in the state.

  // Example
  setCount(7); // This will re-render the component to display the new value, 7, instead of 0.
