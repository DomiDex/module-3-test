### Todo List with Redux 📝

#### Task:

Write a React application that manages a todo list using Redux. Users should be able to add todo items.

#### Instructions:

1. **Create a Redux Store:**

   - Define a Redux store with an initial state containing an array of `todos`.
   - Create an action for adding (`ADD_TODO`) todos.
   - Create a reducer function that handles the add action and updates the `todos` array in the state.
   - **Files to Create:** `store.js`, `todoSlice.js`

2. **TodoList Component:**

   - Create a `TodoList` component that displays the list of todos from the Redux store.
   - Add an input field and a button to add new todos.
   - When users add a todo, dispatch the appropriate action to update the Redux store.
   - **File to Create:** `TodoList.js`

3. **App Component:**
   - Wrap the `App` component with the `Provider` component from `react-redux`, passing the Redux store as a prop.
   - Render the `TodoList` component within the `App` component.
   - **File to Create:** `App.js`

#### Expected Interactions:

1. **Todo List Management:**
   - **Add Todo:** Users can type a todo in the input field and click "Add" to add it to the list.
