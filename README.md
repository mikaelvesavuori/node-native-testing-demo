# Node native testing demo

Basic demo of Node native testing and how to make it work with TypeScript.

## Prerequisites

You will need Node 19 or later.

## Install

Run `npm install`.

## Run

Run `npm test`.

It should show something similar to:

```text
ℹ (node:31562) ExperimentalWarning: Custom ESM Loaders is an experimental feature and might change at any time
ℹ (Use `node --trace-warnings ...` to show where the warning was created)
✔ Basic greet (0.246333ms)
▶ Greet
  ✔ Should greet (0.111875ms)
  ✔ Should fail (0.082334ms)
▶ Greet (0.301583ms)

▶ Greet async
  ✔ Should greet (0.050583ms)
  ✔ Should fail (0.405708ms)
▶ Greet async (0.505708ms)

ℹ tests 5
ℹ suites 2
ℹ pass 5
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 133.355084
```
