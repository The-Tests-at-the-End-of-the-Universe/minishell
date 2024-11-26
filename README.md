# prerequisites

## TTY
Watch out that minishell does not have tty test which exit when stdin, stdout, and stderror are not tty
because then the tests will not work. it is recommended to comment this function out to run tester

## minishell location
Make sure that minishell is compiled in a repository above the tester folder to make sure the tester will run well

# How-to-use


1. clone tester in repository
clone the repo in the root folder, or at least on the same level where minishell will be compiled.

2. run e2e.sh

to see all options of tester.
```sh
bash e2e.sh -h
```

to run tests

```sh
bash e2e.sh
```

3. check logs for errors
in the logs folder, you can find more detail about the errors encountered
