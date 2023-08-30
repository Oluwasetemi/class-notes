# class Note - 30th August 2023

## Review of JSX

- [check this tool out](https://transform.tools/html-to-jsx). Please convert your scissors project from HTML to react, use a PR approach to merge the react to the main branch.
- expression slots
- difference from HTML
  - className
  - htmlFor
  - lowercase HTML tags
  - closing of the self closing tags
  - lowercase attributes
- common mistakes of Gotchas
  - whitespace
  - image rendering

## Review of Last Class - Lifecycle methods

![Mount](https://files.slack.com/files-tmb/T04766DG6AK-F05PTP6KCCV-c394289b20/image_720.png)
![Trigger](https://files.slack.com/files-tmb/T04766DG6AK-F05PG4X7A5V-813ad6a2ad/image_720.png)
![Commit](https://files.slack.com/files-tmb/T04766DG6AK-F05PG4YM7TR-04b2583f01/image_720.png)
![Render](https://files.slack.com/files-tmb/T04766DG6AK-F05Q9A3536V-347acd9b40/image_720.png)

[Read More](https://react.dev/learn/render-and-commit)

![Explanation](https://files.slack.com/files-pri/T04766DG6AK-F05PWLZP50A/image.png)

Step 0: Mount with ReactDOM
Step 1: Trigger a render

- It’s the component’s initial render.
- The component’s (or one of its ancestors’) state has been updated.

Step 2: React renders your components
Step 3: React commits changes to the DOM

<!-- markdownlint-disable no-inline-html -->
<details>
  <summary>Summary</summary>
  <div>
    <p>
    Any screen update in a React app happens in three steps:
    </p>
    <ul>
      <li>Trigger</li>
      <li>Render</li>
      <li>Commit</li>
    </ul>
    <p>You can use Strict Mode to find mistakes in your components.</p>
    <p>React does not touch the DOM if the rendering result is the same as last time</p>
  </div>
</details>

## Components

1. Props
   - default values ??
   - Fragment
   - Children
   <!-- classwork: create a Button component (borderColor, color, Children) (themeColor, Children) (status, children) -->
2. Props drilling

## Iteration; Rendering a list; Understanding the need for a key on each list

> NB. Keys work with React.Fragment and not <>(shorthand)

## Conditional Rendering

1. if
2. &&
3. ternary
4. showing and hiding

## Styling

1. inline Styling
2. CSS Modules
3. Styled Components

## Class Take Home Project and Assignments

- Take Home Project ([Star](https://stackblitz.com/edit/vitejs-vite-3f4sce?file=src%2FStarRating.jsx), Grid). Solution Image ([Star](https://files.slack.com/files-tmb/T04766DG6AK-F05Q3827XRC-6f117352c7/image_360.png)).
- Assignments

  [Building this out](https://files.slack.com/files-tmb/T04766DG6AK-F05PQ2AU2S2-2b974088cf/image_360.png). Use this [image as a guide to each button](https://files.slack.com/files-pri/T04766DG6AK-F05PQ2CVBU6/image.png). (source the icons from `react-feather` npm package). Add an effect that allows the page title to be updated with the latest count. (Submit before next class)

## BONUS: [Converting an Old react project with classes to functions](https://stackblitz.com/edit/react-lifting-state-up-intro?file=index.js)

TODO: [Fix the errors in this project after migrating to the latest react and reactDOM version, change the class to function.](https://stackblitz.com/edit/react-egghead-stopwatch?file=index.js)

> *NEXT CLASS WILL FOCUS ON STATE AND HOOKS*
