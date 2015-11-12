# babel-mocha-test

> Illustrate an issue with running mocha test written in ES2015 syntax with babel

When running with node 0.12, the following error is encountered:

```sh
:; npm test

> babel-mocha-test@1.0.0 test /Users/tnguyen/dev/babel-mocha-test
> mocha --compilers js:babel-core/register --ui tdd



  1) endsWith

  0 passing (107ms)
  1 failing

  1)  endsWith:
     TypeError: undefined is not a function
      at Context.<anonymous> (index.js:4:26)



npm ERR! Test failed.  See above for more details.
```
