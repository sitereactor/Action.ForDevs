# Hello world javascript action

This action prints "Hello ForDevs Community" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"ForDevs Community"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: sitereactor/Action.ForDevs@v1
with:
  who-to-greet: 'Sherry and Rasmus'