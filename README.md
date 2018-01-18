
React-Router & Redux-Form
===================
> Following **StephenGrider**'s tutorial: *Modern React with Redux* on udemy, here's the [link](https://www.udemy.com/react-redux/).
> Bellow are a mix of notes from the tutorial, react documentation, and other sources.

Helpful Links
-------------
>  
> [Lodash](https://lodash.com/)
> [React Router](https://reacttraining.com/react-router/)
> [Redux Form](https://redux-form.com/7.2.0/)

----------

Lodash
-------------
>  
> **Lodash** is a modern Javascript utility library deliverying modularity, performance & extras.
>  
>

----------

React Router
-------------
>  
> **React Router** is a collection of *navigational components* that compose declaratively with your application.
>  
> ----------

>
>```<Switch>``` renders the first child ```<Route>``` or ```<Redirect>``` that matches the location.
>
>```<Switch>``` is unique in that it renders a route *exclusively. In contrast, every ```<Route>``` that matches the location renders *inclusively*.
>
>This is what happened when we were seeing both the ```PostsIndex``` and ```PostsNew``` components being rendered to the browser at the same time, even through we were at url ```http://localhost:8080/posts/new```
>
>Follow this link to [react router's documentation](https://reacttraining.com/react-router/web/api/Switch) for more information and examples of ```<Switch>```
>
>----------
> ```<Link>``` provides declarative, accessible navigation around your application.
>  Here is an example of its use:
```
import { Link } from 'react-router-dom'

<Link to="/about">About</Link>
```
>
>  [Link](https://reacttraining.com/react-router/web/api/Link) to react router's documentation on ```<Link>```.
>  
>  ----------

----------

Redux Form
-------------
>  
> **Redux Form** works with *React Redux* to enable an html form in *React* to use *Redux* to store all of its *state*.
>  
> *Redux Form*'s responsibility is to handle state and validation of the form. It is *not* responsible for taking data and saving it in some fashion, making a  *post* request, or anything of that nature.
>  
>

----------

es6
-------------
>  
> The **destructuring assignment** syntax is a JavaScript expression that makes it possible to unpack values from arrays, or properties from objects, into distinct variables.
>  For more information/examples about *destructuring* with **es6**, follow the link to [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
>
```
// Example of basic assignment with Object destructuring

var o = {p: 42, q: true};
var {p, q} = o;

console.log(p); // 42
console.log(q); // true

```

----------



Javascript
-------------
>  
> The **conditional (ternary) operator** is the only javaScript operator that takes three operands. This operator is frequently used as a shortcut for the ```if``` statement.
>  
```
// Syntax

condition ? expression1 : expression2

```
>
> **condition (or conditions)**
> An expression that evaluates to *true* or *false*.
>
> **expression1, expression2**
> Expressions with values of any type.
>  
> If *condition* is *true*, the operator returns the value of *expression1*; otherwise, it returns the value of *expression2*. For example, to display a different message based on the value of the ```isMember``` variable, you could use this statement:
>
```

'The fee is ' + (isMember ? '$2.00' : '$10.00);

```
>
> For more information, use-cases, and examples on the **ternary operator**, follow this link to the [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator).

----------
