### React Challenge: Components and Props

#### Background

In React, components are the building blocks of an application. They allow you to split the UI into independent, reusable pieces. Props (short for "properties") are used to pass data from parent components to child components.

#### Example

Consider a simple application that displays a list of items with their names and prices. Each item in the list is a reusable component that receives its data through props.

#### Problem Statement

Create a React application that consists of three components: `App`, `ItemList`, and `Item`. The `App` component will serve as the root component for the application. The `ItemList` component will display a list of items, while the `Item` component will be used by the `ItemList` component to display individual items.

##### Requirements

1. Use functional components with hooks for all components.
2. Pass data between components using props.
3. The application should display a list of items with their names and prices.

#### Releases

**Release 0: Set up the project**

Create a new React project using Create React App or another preferred method.

**Release 1: Create the `ItemList` and `Item` components**

Create two functional components, `ItemList` and `Item`, that accept the necessary props to display the list of items and individual items.

**Release 2: Implement the `App` component**

Create a functional component, `App`, that includes the `ItemList` component and passes an array of item objects with names and prices as a prop.

**Release 3: Implement the `ItemList` component**

In the `ItemList` component, map through the array of item objects passed as a prop and render the `Item` component for each item. Pass the item name and price as props to the `Item` component.

**Release 4: Implement the `Item` component**

In the `Item` component, display the item name and price using the props passed from the `ItemList` component.

**Release 5: Test the application**

Ensure that the application displays the list of items with their names and prices correctly.

#### Hints (if necessary)

1. Use the `map()` function to iterate through the array of item objects and render the `Item` component for each object.
2. Remember to assign a unique `key` prop to each `Item` component when mapping through the array in the `ItemList` component.

#### Learning Outcomes

By completing this challenge, you will gain experience in:

1. Creating functional components in React.
2. Passing data between components using props.
3. Rendering a list of components based on an array of data.