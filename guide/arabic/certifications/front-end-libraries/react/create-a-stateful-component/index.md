---
title: Create a Stateful Component
localeTitle: إنشاء مكون Stateful
---
## إنشاء مكون Stateful

#### تلميح 1:

```JSX
class StatefulComponent extends React.Component {
  constructor(props) {
    super(props);
    // initialize state here
        // "This" area may be a good place to use "dot" notation.
        // dont forget to describe "name" property inside the state and assign your name to a property of "name".
  }
  render() {
    return (
      <div>
        <h1>{this.state.name}</h1>
      </div>
    );
  }
};
``` 

## حل

 `class StatefulComponent extends React.Component { 
  constructor(props) { 
    super(props); 
    // initialize state here 
 
    this.state = { 
      name : "Name" 
    } 
 
  } 
  render() { 
    return ( 
      <div> 
        <h1>{this.state.name}</h1> 
      </div> 
    ); 
  } 
 }; 
`