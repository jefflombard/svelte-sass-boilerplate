# svelte-sass-boilerplate
This project is based off of [sveltejs/template](https://github.com/sveltejs/template).

## Getting Started

1. Click the `Use this template` button.
2. Clone your newly created repo using `git clone <repo_name>`
3. `cd <repo_name>`
4. `yarn` to install dependencies.

## Usage

1. Start a local dev server by running `yarn dev`.
2. Global/Common SASS can be added to `src/styles`.
3. On an individual component you can now add the `type="text/sass"` attribute.

### Example of Component Styling using Sass

```html
  <style type="text/sass">
  .main {
    p {
      color: blue;
    }
  }
  </style>
```

### The `src/` dir with styles

```
src
  ├── styles
  |     ├── globals.scss     <--  For Variables, etc.
  |     └── main.scss        <--  Main scss file that imports everything else in this folder
  ├── App.svelte
  └── main.js
```


## Notable differences to [sveltejs/template](https://github.com/sveltejs/template)

1. Use of server
2. Sass is preconfigured
