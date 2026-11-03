Step-1
                  Npx create-react-app myapp
Step-2
         Cd myapp
         C:\myapp>code .
Step -3
   Change App.js
    
import React from 'react';

function App() {
  function showMessage() {
    alert("Welcome to ReactJS!");
  }

  return (
    <div>
      <h1>My First React Application</h1>
      <p>Hello Students!</p>
      <p>This is a simple ReactJS program.</p>

      <button onClick={showMessage}>
        Click Me
      </button>
    </div>
  );
}

export default App;
step-4
   run with npm start;
