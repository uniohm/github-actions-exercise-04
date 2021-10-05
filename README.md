# Hello World docker

This action prints "Hello World" or "Hello" + the name of person to greet

## Inpots

## `who-to-greet`
**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

the time we greeted you

## Example usage
uses: actions/hello-world-docker-action@v1
with:
    who-to0greet: 'Mona the Octocat'