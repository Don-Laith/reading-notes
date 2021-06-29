![react](https://miro.medium.com/max/2128/1*KN7zbaWkbm5E71zZWfTf7A.gif) 
# Forms 
<hr> <br>
  * It’s good to have a JavaScript function that handling with submission of the form and has access to the data (the user entered into the form), by a technique called “controlled components”.

What is a ‘Controlled Component’?

In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

No, because it runs as the user hits keystrokes.

How do we target what the user is entering if we have an event handler on an input field?
In HTML, an <input type="file"> lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API.
 [👁️ watch it](https://www.youtube.com/watch?v=t3r9xW-sxqs&t=168s)
 ### What is a ‘Controlled Component’?

 * We can combine the two by the React state. Then the React component that renders a form also controls what happens in that form on subsequent user input.
  * An input form element whose value is controlled by React in this way is called a **“controlled component”**.

 ### Should we wait to store the users responses from the form into state when they submit the form? **no** OR should we update the state with their responses as soon as they enter them? **yes**.

  * In React, mutable state is typically kept in the state property of components, and only updated with setState(). 
   * delling with State

 ### How do we target what the user is entering if we have an event handler on an input field?

 * event.**target**.name


 [♥️from](https://reactjs.org/docs/forms.html)

## Ternary Operator
  * Why would we use a ternary operator?
    > 📍 To simplify our if-else statements (code) that are used to assign values to variables. and make it easy to track.
  * Rewrite the following statement using a ternary statement:⬇️
    > 📍 (x===y) ?  console.log(true) :  console.log(false)

    * 🗺️ In general: condition ? exprIfTrue : exprIfFalse
  
 [♥️from](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
