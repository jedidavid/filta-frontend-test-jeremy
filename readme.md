# Front-end Asssessment

## Tech

- HTML
- Tailwind CSS
- Javascript
- Alpine.js

## Installation

You can check and view the html files in src folder. No need to run the server.

However, if you still want to run it which only has Tailwind CSS
Install the dependencies and start the server.

```sh
npm install
npm run start
```

## Exercise 1

- Go to src folder then view exercise-1.html

## Exercise 2

- Go to src folder then view exercise-1.html

### Bonus Points Explanation:

Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`

- `'b' + 'a'` results in the string `"ba"`.
- `"ba" + + 'a'`: The, `+ 'a'` converts `'a'` to `NaN`, `+a` is string that results into a NaN(NotaNumber) so the expression becomes `"ba" + NaN`.
- `"ba" + NaN` results in the string `"baNaN"`.
- `"baNaN" + 'a'` results in the string `"baNaNa"`.
- the `toLowerCase()` method converts `"baNaNa"` to `"banana"`.
