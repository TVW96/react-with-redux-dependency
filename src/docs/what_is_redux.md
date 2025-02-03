## What is Redux? 
**Pattern and library for managing and updating global application state.**

What does it do?
- Redux is a pattern and library for managing and updating global application state, where the UI triggers events called "actions" to describe what happened, and separate update logic called "reducers" updates the state in response. It serves as a centralized store for state that needs to be used across your entire application, with rules ensuring that the state can only be updated in a predictable fashion.

What problems does it help solve?
- 
Why would you want to use Redux?
- You would want to use Redux in your application if you need a centralized state management system to handle complex state interactions, especially in large-scale applications. 

When should you not use redux?
- If your application has minimal global state and local state (useState) is sufficient.
- If you're building a simple app that doesn't require complext state management. 
- If [React Context API](https://react.dev/learn/passing-data-deeply-with-context) is enough for your applications needs. 