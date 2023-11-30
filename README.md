# github-actions-docker-container
Creating a Docker container action

# Hello world docker action
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

```yml
  -
    uses: huy8895/github-actions-docker-container@v1
    with:
      who-to-greet: 'Trinh van huy'
```
