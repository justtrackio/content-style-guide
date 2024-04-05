This repository contains style guidance for justtrack content.

Generally speaking, you can find documentation on style rules with vale [here](https://vale.sh/docs/topics/styles/).

## Ignore misspellings

Some words are not included in vale's default dictionary, but we may still want to allow them. To do this, you must add the word to one of our ignore files:

- `Justtrack/ignore-general.txt`
- `Justtrack/ignore-industry-terms`
- `Justtrack/ignore-technical-terms`
- `Justtrack/ignore-platforms.txt`

## Releasing linter changes

To make changes available to users of this style guide, we need to cut a [new release](https://github.com/justtrackio/content-style-guide/releases).
