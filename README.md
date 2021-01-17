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

-

## Step 4: Identify Where Your State Should Live

## Step 5: Add Inverse Data Flow

## Step 6: Refactoring

- DRY code; if you use it twice abstract it
- Break your render into multiple renders if more components would be too granular
