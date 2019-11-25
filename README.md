## Setup

* `npm install`

## Running

* `npm start` - run the development server
* `npm test` - run the tests
* `npm run test:watch` - run the tests in watch mode


## Tasks - Overview

In the interview we will ask you to walk through your solution for one of the tasks mentioned below. We can provide a MacBook with Atom or VS Code to work through in front of us or feel free to bring your solution in using your own dev environment.

### Part 1: Staying out of React

  1. Flesh out some test scenarios for clearCompleted in `todos-spec.js`.
  2. Implement clearCompleted in `todos.js`.
  3. Move the `.trim()` logic out of `Header.js` and `TodoItem.js` into the data layer in `todos.js` and expand test coverage in `todos-spec.js`.


### Part 2: Shallow Rendering

  1. Add the other scenarios for the filter toggling behaviour in `Footer-spec.js`.
  2. Try changing the component & tests so the action is not fired if the filter is already selected.
  3. Add tests for the `escape` behaviour described in the TodoMVC spec, and then implement it (`TodoItem-spec.js` and `TodoItem.js`).


### Part 3: Visual Feedback

  1. Open up the `/devboard` page and take a look at `AddTodo` and `TodoItem`.
  2. Experiment with changing the CSS or the React component implementations and seeing how the results impact the devboard pages.
  3. Try adding some more examples to `Footer.dev.js` that show the different scenarios. Does the component seem like it has too many responsibilities? Think about how would you address this?
