# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'
```

# Memo

```
npm init -y
```

```
npm install @actions/core
npm install @actions/github
```

https://docs.github.com/ja/actions/using-workflows/events-that-trigger-workflows
