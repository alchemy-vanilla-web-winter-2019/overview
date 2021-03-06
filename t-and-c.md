Techniques and Concepts List
===


## ESModules

1. `export default` and `import` default

## App Design

1. Two-stage logic checking (toss check, then broke check)
1. function as unit of work (`feedCaterpillar`)

## Built-ins

### Browser

1. global `document`

### JavaScript

1. `Math.random()` returns 0 to <1
1. Format number as currency with `.toLocaleString()`

## Variables

1. Declaring and assign `const` variable
1. Declare `let` variable with sensible default
1. Reassign `let` variable in conditional block
1. Declare module-level `let` variable as state
1. Assign variable from property of global object
1. Reassign module-level state variable

## Control Flow

1. `if` and `else` conditionality
1. for loop with `index`

## Functions

1. Calling a function
1. Using an anonymous function as a function argument
1. Define function parameter
1. Call a function with a variable
1. Call a function with two arguments

## Lists (Arrays)

1. access item by index: `array[index]`
1. array of strings

## Strings

1. concatenate string

## Tools

1. Use 3rd-party testing library

## Testing

1. TDD a pure function
1. Test assertions with `assert.equal`

## HTML 

### Elements

1. `<title>`, `<h1>`
1. `<button>`, `<section>`, `<img>`
1. `<h2>`, `<span>`


### Attributes

1. named radio inputs
1. `required` inputs
1. numeric type input
1. Disable button with `button.disabled = true`
1. Set form control value `button.value="apple"`

## CSS 

### Selectors

1. id (`#`), tag, and class (`.`)
1. make dynamic css selector with string concatenation

### Styling

1. Use `body` for global styling
1. `font-family`, `background`, `color`, `text-align`, `font-size`, `font-weight`
1. `visibility`, `margin`, `padding`, `margin: auto`, `min-height`
1. `padding`, `border-style`, `cursor`, `line-height`, `background`
1. `display: inline-block`, `height`, `width`
1. negative margins: `margin-left: -12px;`
1. `transform`, `transition`

## DOM 

### Node

1. remove class `element.classList.remove('class-to-remove')`
1. add class `element.classList.add('class-to-add')`
1. set text `element.textContent =`
1. set property `image.src =`
1. create new elements with `.createElement('tag')`
1. add new element to existing element with `.appendChild(node)`

### Events

1. subscribe to `click` event with `addEventListener`
1. subscribe to form `subscribe` event with `addEventListener`
1. use `event` callback argument to prevent default behavior

### Traversal

1. `document.getElementById('id')` matches HTML attribute `id="id"`
1. use css selector to get DOM elements via `document.querySelectorAll('.class')




