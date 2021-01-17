# React Workflow

## Step 1: Break The UI Into A Component Hierarchy

- Routes and components should be single-minded
- Each page/route of your application should be a child of the top level App component
- Each page/route of your application can then be broken down into its single-minded components

## Step 2: Build A Static Version in React

- Create import statements and function/class components stubs for your React components to start with
- If using fetch method, start with dummy data and make sure that props are passed correctly
- For large applications, build from the bottom level down
- For small applications, build from the top level down
- DO NOT USE STATE AT ALL
- Components should only have render methods

## Step 3: Identify The Minimal (but complete) Representation Of UI State

- DRY: figure out the absolute minimal representation of the state you application needs
- Make a list of each piece of data that could possibly be state
- Go through each piece of data and ask the following 3 questions: 1. If it's passed down from a parent via props, then it's probaby not state; 2. If it remains unchanged over time, then it probably isn't state. Remember that state changes; 3. Can it be calculated/computed from any other state data or props? If it can be, then it isn't state.

## Step 4: Identify Where Your State Should Live

## Step 5: Add Inverse Data Flow

## Step 6: Refactoring

- DRY code; if you use it twice abstract it
- Break your render into multiple renders if more components would be too granular
