# Contribution Guidelines

### Naming Conventions:
It is preferred to use [camel case](https://en.wikipedia.org/wiki/Camel_case) in the naming of directories, files, variables, function names etc.


## Directory and file structure

For an algorithm say `algoName`, which is a type of a *searching algorithm*, the directory structure would be like:
```
\
 |- sortingAlgo
 |- searchingAlgo
     |- algoName
         |- algoName.c
         |- algoName.js
         |- algoName.py
     |- someOtherAlgo
     |- someOtherOtherAlgo
 |-someOtherTypeOfAlgo
```

## Code

### Format of code:
Write the main code in a function with the name of the function being the algorithm name, and having parameters as required. The return value should be the answer required to be printed.

For example, for a searching algorithm, we can have the function as `someSearch(arr, x)`, and the return value as the index of `x` in `arr`.

### Test Case:
It is preferred to have at least one testcase within the code instead of getting the input, and its output being printed by calling the function like `print(funName(arr,x))` etc.

### Stylistic guidelines:
- Ensure that the code is properly intended
- Preferably have some (not oo many) comments to describe the logic
