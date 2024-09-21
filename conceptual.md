### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
  - React is a JavaScript library for building user interfaces, primarily for single-page applications. It’s used when building dynamic, responsive, and component-based web applications.

- What is Babel?
  - Babel is a JavaScript compiler that converts modern JavaScript into backward-compatible JavaScript for older browsers.

- What is JSX?
  - JSX is a syntax extension for JavaScript that allows you to write HTML-like code in React components, which is then transformed into React elements.

- How is a Component created in React?
  - A component can be created either as a function or a class that returns a React element.

- What are some difference between state and props?
  - State is internal, mutable data specific to a component, while props are external, immutable inputs passed from parent to child components.

- What does "downward data flow" refer to in React?
  - Downward data flow means that data in React flows from parent components to child components through props, ensuring a one-way data binding.

- What is a controlled component?
  - A controlled component is a form input element that is controlled by React state, with its value and updates managed via state.

- What is an uncontrolled component?
  - An uncontrolled component is a form input element that maintains its own internal state and is accessed using refs.

- What is the purpose of the `key` prop when rendering a list of components?
  - The `key` prop helps React efficiently identify and update individual components in a list when changes occur.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
  - Using an array index as a `key` can cause issues when the list is reordered, leading to unexpected behavior in state and rendering.

- Describe useEffect.  What use cases is it used for in React components?
  - useEffect is a hook that runs side effects in functional components, such as fetching data, setting up subscriptions, or manually updating the DOM.

- What does useRef do?  Does a change to a ref value cause a rerender of a component?
  - useRef creates a mutable object that persists across renders without causing re-renders when updated.

- When would you use a ref? When wouldn't you use one?
  - You use a ref to access DOM elements or persist values between renders without triggering re-renders. Avoid using refs to manage state or trigger component updates.

- What is a custom hook in React? When would you want to write one?
  - A custom hook is a reusable function that encapsulates logic using React hooks. You would write one to abstract and reuse complex logic across multiple components.
