1.What is JSX, and why is it used?
 Ans:JSX (JavaScript XML) is a syntax extension that allows you to write HTML-like code inside JavaScript files. It is used because it makes writing and visualizing UI structures much easier and faster than useing pure Js.
 2.What is the difference between State and Props?
  Ans:Props: Short for "properties." They are used to pass data from a parent component to a child. They are read-only (cannot be changed by the child).
State: This is a component's private data storage. It can be changed within the component to update the ui dynamically.
3.What is the useState hook, and how does it work?
 Ans:useState is a React Hook used to manage data that changes over time. It returns two things:
The current value (state).
A function to update that value.
When the state updates, React re-renders the component to show the new data.
4.How can you share state between components in React?
 Ans:You can share state using:
Lifting State Up: Moving the state to the closest common parent component.
Context API: Passing data globally without manual prop drilling.
Props: Passing state down from parent to child.
5.How is event handling done in React?
Event handling is similar to HTML but uses camelCase (e.g., onClick instead of onclick). You pass a function directly to the event handler:
<button onClick={handleBtnClick}>Submit</button>
