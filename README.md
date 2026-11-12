# Online Scratch paper.
A static, client-only whiteboard and notepad.

## Privacy / persistence model

The application intentionally does **not** use:

- localStorage
- sessionStorage
- IndexedDB
- cookies
- service workers
- analytics
- collaboration
- a backend
- a database

Whiteboard and notepad content exists only in JavaScript memory. Reloading the page or closing the tab destroys the working state.

The only persistent copy a student can create is an explicit download using the **Download Work** button.


