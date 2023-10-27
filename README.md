# React Documentation
1. Quick Start:
   - const [history, setHistory] = useState([Array(9).fill(null)]);
   - array.indexOf()
2. Describing the UI:
   - conditional rendering: {name} {isPacked && '✔'} : https://react.dev/learn/describing-the-ui.
   - Pure function.
3. Adding interactivity:
   - label tag(understand use of label): The <label> tag defines a label for several elements(E.g: `<input type="checkbox">` )
   - <label>First name:{' '} `<input value={firstName} onChange={handleFirstNameChange}/>`</label>
   - Updating objects in state: we use spread operator(...update), Updating arrays in state
   - If copying objects in code gets tedious, you can use a library like Immer to reduce repetitive code:
4. Managing State:
   - 1. Reacting to input with state(Disable/Enable button).
   - 2. Choosing the state structure(state shouldn’t contain redundant or duplicated information).
   - 3. Sharing state between components : “lifting state up”
   - 4. Preserving and resetting state(****)
   - 5. Extracting state logic into a reducer(*****Editing and deleting data*********)
   - 6. Passing data deeply with context
   - 7. Scaling up with reducer and context
5. Escape Hatches
   - 






# Nodejs
1. Node.js = Runtime Environment + JavaScript Library
2. REPL(Read Eval Print Loop) Terminal, REPL Commands
3. command: `npm ls -g` : check all the modules installed globally
4. NPM: https://www.tutorialspoint.com/nodejs/nodejs_npm.htm
5. Callback, Event Loop, Event Emitter, Streams
6. Buffers: Node provides Buffer class which provides instances to store raw data similar to an array of integers but corresponds to a raw memory allocation outside the V8 heap.
7. What is a Web Server? : https://www.tutorialspoint.com/nodejs/nodejs_web_module.htm
8. Extra:
   - array.sort()
   - array.includes("world")
