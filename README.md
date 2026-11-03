# Task Manager

A simple to-do app built with React. Add, complete, filter and delete tasks. Tasks are saved in the browser, so they are still there after a refresh.

**Live demo:** _https://tholla12.github.io/task-manager/_

## Features

- Add, complete and delete tasks
- Filter by All, Active and Completed
- Counter showing how many tasks are left
- "Clear completed" button
- Tasks saved with `localStorage`
- Keyboard accessible with labelled controls

## Built with

React 18 (components, props, `useState`, `useEffect`), HTML and CSS. React is loaded from a CDN, so there is no install or build step.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

## What I learned

- Splitting a UI into components (`App`, `TaskItem`, `FilterBar`) and passing data with props
- Managing state with `useState`
- Syncing state to `localStorage` with `useEffect`
- Rendering lists with keys and filtering data before display

## Possible improvements

- Edit an existing task
- Due dates and priorities
- Rebuild the project with Vite and split components into separate files
