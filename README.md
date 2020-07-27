# Generate Release Hashes - GitHub Action
a

## Inputs
### `hash-type`
The type of hash to generate for each file. Must be one of `md5`, `sha1`, `sha256`, or `sha512`. Defaults to `sha256`.

## Outputs
### `hashes`
A string with the list of files/hashes generated by the action.

## Example usage
```yml
uses: MCJack123/ghaction-generate-release-hashes
with:
  hash-type: sha1
```