# Changelog

## 1.2.0 (10-10-2016)
Added:
- `debounceRate` argument to `component-playground`
- Include of template compiler moved to addon `include` hook in `index.js`

## 1.1.3 (10-06-2016)

Changed:
- Updated README to provide more information about the component's purpose and how to use it

## 1.1.2 (10-06-2016)

Changed:
- Moved `ivy-codemirror` to `devDependencies` because that did NOT work AT ALL.

Removed:
- `ember-template-compiler` removed from package as it is being imported from `ember` in bower components

## 1.1.1 (10-05-2016)

Changed:
- Moved `ivy-codemirror` to `dependencies` so it is pulled down in including apps.

## 1.1.0 (10-05-2016)

Added:
- Documentation for playground components

Changed:
- Debounced re-renders within playground preview

## 1.0.0 (10-05-2016)

Added:
- Component playground with realtime rendering of text input from code mirror editor component
