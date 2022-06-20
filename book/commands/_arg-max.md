---
title: arg-max
version: 0.64.0
usage: |
  Return index for max value in series
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> arg-max ```

## Examples

Returns index for max value
```shell
> [1 3 2] | to-df | arg-max
```