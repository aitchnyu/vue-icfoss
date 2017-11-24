# Vue.js for bug-free interactive web pages
A workshop I'm taking at ICFOSS, Cusat.

## Exercise 1
How to introduce in a page
Reactivity
Dev tools


Install Vue Devtools in Firefox or Chrome
Open Vue devtools for exercise_1_complete.html
Click root component

`$vm0.message = 'Hello icfoss!'`

Minified and dev version - size and speed, download
What happens without v-cloak?

### Resources
Two approaches: https://vuejs.org/v2/guide/installation.html

Reactivity: https://vuejs.org/v2/guide/reactivity.html

## Exercise 2

Binding data and inputs

Methods

Fetching data

`randomName(function(name){console.log("name is", name)})`

Text input - bind to model

Buttons - bind to method

`reverse` and `fetchName`

### Resources

Losing `this` binding https://stackoverflow.com/questions/20279484/how-to-access-the-correct-this-inside-a-callback?noredirect=1&lq=1

## Excercise 3

Bootstrap 4

Usage of components

Data binding with number

v-for and :key

computed

Display table entries - bind to numbers

Total, costliest

addNewItem - just push to array

total

costliest - sort by subtotal, just one value though

See the subtotal, total and costliest updating in real-time

### Resources

Start using Bootstrap in Vue: https://bootstrap-vue.js.org/docs/reference/starter-templates/

v-for: https://vuejs.org/v2/guide/list.html

Why use key: https://vuejs.org/v2/guide/list.html#key

Computed properties: https://vuejs.org/v2/guide/computed.html
