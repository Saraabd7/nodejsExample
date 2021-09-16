# nodejsExample

## Enter the cookbook description here.

## Main Chef Commands:

### New cookbook
- How to generate a cookbook

```
  $ chef generate cookbook <name>
```

### Running Kitchen
- create VM
```
  $ kitchen create
```
### Run provision from recipe
- runs all your recipes
```
kitchen converge
```
### Prepare for testing
 - run setup
```
kitchen setup
```
### Run tests:
```
kitchen verify
```
Destroy your machine
```
kitchen destroy
```
Run all above ?
kitchen create --> all the steps --> kitchen destroy?
```
kitchen test

```
