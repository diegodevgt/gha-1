# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `input-test`

**Required** The name of the person to greet. Default `"GE"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/gha-1@v2
with:
  who-to-greet: 'GEV2'