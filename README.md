# buildkite-sparse-checkout

Checks out the repo using partial / sparse checkouts

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - hivehr/buildkite-sparse-checkout#master:
          pattern: '*.md'
```
