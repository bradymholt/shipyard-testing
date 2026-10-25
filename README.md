# shipyard-testing

A simple Hello World app that runs in Node.js.

This repo is also used to test the pull request review workflow: opening PRs, requesting reviews, and responding to review comments.

## Run

Install Node.js (which includes npm), then run from the repository directory:

```sh
npm start
```

Output:

```text
Hello, world!
```

Pass a name after `--` (npm forwards everything after it to the script):

```sh
npm start -- Alice
```

Output:

```text
Hello, Alice!
```

No dependencies or build step are required.

Copyright 2026 Brady Holt
