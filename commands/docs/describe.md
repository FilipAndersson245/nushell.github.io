---
title: describe
categories: |
  core
version: 0.84.0
core: |
  Describe the type and structure of the value(s) piped in.
usage: |
  Describe the type and structure of the value(s) piped in.
---

# <code>{{ $frontmatter.title }}</code> for core

<div class='command-title'>{{ $frontmatter.core }}</div>

## Signature

```> describe --no-collect```

## Parameters

 -  `--no-collect` `(-n)`: do not collect streams of structured data


## Input/output types:

| input | output |
| ----- | ------ |
| any   | string |

## Examples

Describe the type of a string
```shell
> 'hello' | describe
string
```
