### Readings: React and Forms

Topic Summary: _text_

## Reading

[React Docs - Forms](https://reactjs.org/docs/forms.html)

- Questions: 

  1.  What is a ‘Controlled Component’?
  2.  Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  3.  How do we target what the user is entering if we have an event handler on an input field?

- Answers:

  1. A componenet whose input value is always driven by the react state which allows one to pass values to other UI elements, or reset it from event handlers. Acts as a "single source of truth".
  2. 
  3. asdf

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- Questions: 
  1.  Why would we use a ternary operator?
  2.  Rewrite the following statement using a ternary statement:

          if(x===y){
            console.log(true);
          } else {
            console.log(false);
          }
          
- Answers: 

  1. It's a more concise way to write a conditional statement. **condition ? value if true : value if false**
  2. ternary example: 
  
          const compare = (x === y) ? 'true' : 'false';
          console.log(compare); 


## Bookmark and Review

*   [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
*   [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

