============================================================
        intro.js — Task README
  A beginner's guide to creating and running a
        JavaScript introduction script
============================================================

------------------------------------------------------------
📋 PROJECT OVERVIEW
------------------------------------------------------------
This task involves creating a JavaScript file called
intro.js that logs your name, age, and favorite programming
language to the console using Node.js.

------------------------------------------------------------
✅ PREREQUISITES
------------------------------------------------------------
- Node.js installed on your computer
- VS Code or any code editor installed
- Basic knowledge of opening a terminal

------------------------------------------------------------
📁 FILE STRUCTURE
------------------------------------------------------------
my-project/
  └── intro.js

------------------------------------------------------------
💻 THE CODE (intro.js)
------------------------------------------------------------
Create a file named intro.js and add the following code:

  // intro.js - Personal Introduction

  const name = "Your Name";
  const age = 25;
  const favoriteLanguage = "JavaScript";

  console.log("Name: " + name);
  console.log("Age: " + age);
  console.log("Favorite Programming Language: " + favoriteLanguage);

------------------------------------------------------------
🚀 STEP-BY-STEP EXECUTION GUIDE
------------------------------------------------------------

Step 1 — Open VS Code Terminal
  - Open VS Code
  - Press Ctrl + ` (backtick) to open the terminal
  - Or go to Terminal > New Terminal from the menu bar

Step 2 — Navigate to Your Project Folder
  cd C:\Users\admin\Documents\my-project

Step 3 — Run the File
  node intro.js

Step 4 — Expected Output
  Name: Your Name
  Age: 25
  Favorite Programming Language: JavaScript

------------------------------------------------------------
⚠️  COMMON ERRORS & FIXES
------------------------------------------------------------

ERROR: ERR_INVALID_ARG_TYPE
  Cause : Missing callback in fs.writeFile()
  Fix   : Add a callback or use writeFileSync()

ERROR: ReferenceError: promises is not defined
  Cause : Wrong import syntax
  Fix   : Use require('fs/promises') correctly

ERROR: EPERM: operation not permitted
  Cause : Writing to a protected system folder
  Fix   : Save file in Documents or Desktop instead

------------------------------------------------------------
💡 PRO TIPS
------------------------------------------------------------
- Use __dirname to always save files relative to your
  script location
- Use template literals for cleaner string formatting
- Run node with no arguments to open the interactive
  REPL for quick tests
- Use Ctrl + C to exit the Node.js REPL terminal

------------------------------------------------------------
🔄 ALTERNATIVE SYNTAX (Template Literals)
------------------------------------------------------------
Instead of using the + operator, you can use template
literals for cleaner code:

  console.log(`Name: ${name}`);
  console.log(`Age: ${age}`);
  console.log(`Favorite Programming Language: ${favoriteLanguage}`);

