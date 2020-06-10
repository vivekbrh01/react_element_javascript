# React Element - writeCode

1. Create a `div` HTML element with the `id` of `root`
2. Find out the tag name, properties and children according to React.createElement in `<span class="sub--heading" id="main">Hello React Element</span>`

Answer: Tag -> Span
Properties -> {className: "sub--heading", id: "main"}
Children -> Hello React Element

3. Create a `h1` React element with text `Hello React🔥` and class `heading`
4. Convert this React element `React.createElement('input', {type: "checkbox", placeholder: "What are you learning?"})` into HTML element

5. Using ReactDOM render the element created in step 4 into DOM. (`div` with id `root`).

6. Convert the following HTML element into React element using `React.createElement`
   ```html
   <div class="container">
   	<input type="checkbox" />
   	<p>Learing React</p>
   	<span>Delete</span>
   </div>
   ```

```js

React.createElement('div',{class:"Container"},
    React.createElement("input",{type:'Checkbox'}),
    React.createElement('p', null,"Learning react")},
    React.createElement('span', null,"Delete")
    )

```

7. Convert the following HTML element into React element using `React.createElement`
   ```html
   <div>
   	<ul>
   		<li>one</li>
   		<li>two</li>
   		<li>three</li>
   	</ul>
   </div>
   ```

```js
React.createElement('div',{class:"Container"},
    React.createElement("ul", null,
      React.createElement('li', null,"One")},
      React.createElement('li', null,"Two"),
      React.createElement('li', null,"Three")
      )
    )
```
