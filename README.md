# Hello World Javascript Action

This action prints "Hello World" or "Hello" + the name of the person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default is `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example Usage

```yaml
uses: actions/hello-world-javascript-action@main
with:
  who-to-greet: 'Ranger the Malamute'
```