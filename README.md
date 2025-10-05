# Embedded Coding Challenges

This repository is a collection of problem statements and supporting infrastructure to help you practise your "Embedded Systems Programming" muscle.

We will keep adding new problems from time to time.

# Getting started

All problems need to be solved in the GitHub codespaces. Be sure to be logged into your GitHub account.

## Create Codespace
To create/start the codespace, follow these steps:
1. click on `<> Code` button.
1. click the `Create codespace on main` button

wait for the codespace to be setup.

## Reopen the codespace

In the `<> Code` button, you should see the name of the previous codespace that was created. Select `Open in Browser` from the dropdown menu next to it.

## The Warmup Challenge
> [!IMPORTANT]
> Be sure to complete this challenge before anything else. It is designed to confirm that the setup works as expected.

Once the codespace is setup. Open a terminal and change the working directory to `warmup`.

```bash
cd warmup
```

Open the `main.c` and following the challenge details there. Most likely, you'll need to edit the `// TODO` to print `Hello, World!`.

If you are new to C/Embedded Programming, simply replace `// TODO` with `printf("Hello, World!");`

Next, from the terminal, compile and run the tests.
1. Compile the changes
   ```bash
   gcc main.c
   ```
1. Run tests
   ```
   checkbrah
   ```
The automated code checker will run tests on the compiled code and present you with stats.

### Checker

`checkbrah` is a simple chacker we made that will feed inputs, capture the output and compare it to the expected ones. It uses the loacally saved `tests.yaml` to infer the inputs and expected outputs.

When you run it, you should see one of the following

**Fail**
```bash
$ checkbrah
PASS: 0/1
FAIL: 1/1
-------
Oh No!! Some tests failed 🥺
```

**Pass**
```
$ checkbrah
PASS: 1/1
FAIL: 0/1
-------
🎯 You Nailed it!!
Move on to the next challenge...

```

# Support

You can report issues by creating an issue on this repository. If you have questions, feedback or problem statements, reach us at [support@pyjamabrah.com](mailto:support@pyjamabrah.com)

----

Copyright © 2025, Typobrahe Education LLP (pyjamabrah.com), All Rights Reserved.