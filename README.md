# cssmap-spec

CSS map specification

## What

CSS map is a standard for mapping (aliasing) identifiers to CSS rules and CSS
declarations.

The current specification is limited to the JSON format.

## Draft 1

- Static rule mapping
- Static directive mapping

### Static rule mapping

The `rules` field allows you to define the mapping between identifiers and CSS
Style declarations.

The identifier can be any non-empty string.

```json
{
  "rules": {
    "h-1": {
      "height": "1px"
    }
  }
}
```
