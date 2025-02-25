React
===
React is a JavaScript library for building user interfaces.
* __Declarative__: React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
* __Component-Based__: Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
* __Learn Once, Write Anywhere__: We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [Node](https://nodejs.org/en) and power mobile apps using [React Native](https://reactnative.dev/).
[Learn how to use React in your project.](https://react.dev/learn)
## Installation
React has been designed for gradual adoption from the start, and __you can use as little or as much React as you need:__

* Use [Quick Start](https://react.dev/learn) to get a taste of React.
* [Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project) to use as little or as much React as you need.
* [Create a New React App](https://react.dev/learn/creating-a-react-app) if you're looking for a powerful JavaScript toolchain.
## Documentation
You can find the ~~React~~ documentation [on the website](https://react.dev/).

Check out the [Getting](https://react.dev/learn) [Started](https://react.dev/learn) page for a quick overview.

The documentation is divided into several sections:
* Quick Start
* Tutorial
* Thinking in React
* Installation
* Describing the UI
* Adding Interactivity
* Managing State
* Advanced Guides
* API Reference
* Where to Get Support
* Contributing Guide

You can improve it by sending pull requests to this [repository](https://github.com/reactjs/react.dev).

``` javascript
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
    import { createRoot } from 'react-dom/client';

    function HelloMessage({ name }) {
      return <div>Hello {name}</div>;
    }

    const root = createRoot(document.getElementById('container'));
    root.render(<HelloMessage name="Taylor" />);



This *example* will ***render*** `"Hello Taylor" `into a container on the page.

> You'll notice that we used an HTML-like syntax; we call it JSX. JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.

![bing 图片](https://th.bing.com/th/id/OIP.oVSj3uFsJgyPwO3fBNMMfAHaHa?w=236&h=236&c=7&o=5&dpr=1.5&pid=1.20)

| a | b | c |
|-:|-|:-:|
|111111|2|333333|
|c|d|e|



