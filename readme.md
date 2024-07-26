# Front-end Asssessment

## Tech

- HTML
- Tailwind CSS
- Javascript
- Alpine.js

## Exercise 1

For Exercise 1 you can directly view the html file in your browser just go to src folder then view exercise-1.html

## Exercise 2

In Exercise 2 we need a server so we can fetch the json file otherwise we will run into CORS error.

Install the dependencies and start the server.

```sh
npm install
npm run start
go to http://localhost:5500/src/exercise-2.html
```

### Bonus Points Explanation:

Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`

- `'b' + 'a'` results in the string `"ba"`.
- `"ba" + + 'a'`: The, `+ 'a'` converts `'a'` to `NaN`, `+a` is string that results into a NaN(NotaNumber) so the expression becomes `"ba" + NaN`.
- `"ba" + NaN` results in the string `"baNaN"`.
- `"baNaN" + 'a'` results in the string `"baNaNa"`.
- the `toLowerCase()` method converts `"baNaNa"` to `"banana"`.
