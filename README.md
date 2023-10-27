# Assignment: ASSIGNMENT NAME

Assignment description goes here...

## Getting started

1. Create a new repository using the template
2. Clone it to your local machine
3. Create a new topic branch (!!!DO NOT WORK IN MASTER DIRECTLY!!!)
4. Prepare the assignment instruction
5. Provide the solution in a separated document
6. Prepare a code boilerplate
7. Add unit tests (use `unittest` framework only)
8. Open a PR into master to merge assignment branch

### Make your boilerplate file invisible for Git

When a boilerplate code is ready, you may want to implement the actual logic
for the assignment. To make changes inside a file invisible for Git use:

```shell
git update-index --assume-unchanged <file>
```

To switch it back:

```shell
git update-index --no-assume-unchanged <file>
```

### Testing

Assignment follows TDD approach. This means all the tests should fail.
Decorate your test cases with `unittest.expectedFailure`.

[//]: # (TODO: assignment documents)


## Publication checklist

- [ ] Provide assignment name (README and pyproject files).
- [ ] Provide short assignment description (README and pyproject files).
- [ ] Provide assignment instructions, you "assets" directory for static files.
- [ ] Implement test cases within "tests" directory, use `unittest` framework.
