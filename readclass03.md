# How do I pass an event handler (like onClick) to a component?

Pass event handlers and other functions as props to child components:

```js
<button onClick={this.handleClick}>
```

# How do I bind a function to a component instance?

There are several ways to make sure functions have access to component attributes like this.props and this.state, depending on which syntax and build steps you are usin

#### Bind in Constructor (ES2015)

```js
class Foo extends Component {
  constructor(props) {
    super(props);
    this.handleClick = this.handleClick.bind(this);
  }
  handleClick() {
    console.log("Click happened");
  }
  render() {
    return <button onClick={this.handleClick}>Click Me</button>;
  }
}
```

# Class Properties (Stage 3 Proposal)

```js
class Foo extends Component {
  // Note: this syntax is experimental and not standardized yet.
  handleClick = () => {
    console.log('Click happened');
  }
  render() {
    return <button onClick={this.handleClick}>Click Me</button>;
  }
}

```

# Bind in Render

```js
class Foo extends Component {
  handleClick() {
    console.log('Click happened');
  }
  render() {
    return <button onClick={this.handleClick.bind(this)}>Click Me</button>;
  }
}
```

# How can I prevent a function from being called too quickly or too many times in a row?

If you have an event handler such as onClick or onScroll and want to prevent the callback from being fired too quickly, then you can limit the rate at which callback is executed. This can be done by using:

- throttling: sample changes based on a time based frequency (eg _.throttle)
- debouncing: publish changes after a period of inactivity (eg _.debounce)
- requestAnimationFrame throttling: sample changes based on requestAnimationFrame (eg raf-schd)

