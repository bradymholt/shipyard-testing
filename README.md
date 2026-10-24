# shipyard-testing

A simple hello world app that runs in Node.js.

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
