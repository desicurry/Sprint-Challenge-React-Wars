# Answers

1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

ReactJS is a UI Component Library which deals with complex state. This library was created by engineers at FaceBook (originally); it's used to handle all the different components on a single page..(profile, friends post, newsfeed, new events etc) React was designed to manage all that without bogging down the actual DOM

2. What does it mean to think in react?

Thinking in React is how you approach your build. Instead of thinking of structuring in an HTML format, we break down our approach to 'components'(i.e. re-usable, independent blocks of code with their own structure, but work together to build your application).

3. Describe state.

State is what allows you to create dynamic, interactive components

4. Describe props.

Props are objects data we need will be injected as properties on this props object.

5. What are side effects, and how do you sync effects in a React component to state or prop changes?

Side effects are results (intended or unintended) from a function OUTSIDE scope of a function. Use `useEffect` for more control of side effects.
