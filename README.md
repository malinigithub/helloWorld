# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1
with: who-to-greet: 'Mona the Octocat'

## Issues faced:

https://github.com/coreui/coreui-react/issues/55 - put the code in public directory - this was given when code was selected.
