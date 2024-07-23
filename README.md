This repository contains style guidance for justtrack content.

Generally speaking, you can find documentation on style rules with vale [here](https://vale.sh/docs/topics/styles/).

## Our style guide

Here, are the rules we check with vale.sh.

### Contractions

Use contractions where possible because they sound more human and casual.

| Prefer this…                                    | Over this…                                        |
| ----------------------------------------------- | ------------------------------------------------- |
| Next, **you’ll** learn how to create a Network. | Next, **you will** learn how to create a Network. |
| **That’s** how you create a Network.            | **That is** how you create a Network.             |

[configuration](Justtrack/Contractions.yml)

### Identifiers

Use "ID" instead of "id" or "Id" when abbreviating "Identifier".

| Use this…                                              | Not this…                                              |
| ------------------------------------------------------ | ------------------------------------------------------ |
| This **ID** is unique to each user.                    | This **id** is unique to each user.                    |
| Copy these IDs, and paste them in the provided fields. | Copy these Ids, and paste them in the provided fields. |

[configuration](Justtrack/Identifier.yml)

### Headings

We enforce the following rules for headings:

Headings can't start with numbers.

| Use this…                          | Not this…                        |
| ---------------------------------- | -------------------------------- |
| Step 1: Find your API key          | 1. Find your API key             |
| Two easy ways to find your API key | 2 easy ways to find your API key |

[configuration](Justtrack/NumberedTitle.yml)

Headings should be in sentence case.

| Use this…         | Not this…         |
| ----------------- | ----------------- |
| Find your API key | Find Your API Key |
| Send a user event | Send A User Event |

[configuration](Justtrack/SentenceCase.yml)

### Oxford Comma

Always use an oxford comma.

| Use this…         | Not this…         |
| ----------------- | ----------------- |
| Input your first name, your last name, and your birthdate.  | Input your first name, your last name and your birthdate. |
| Adjoe, Google Ads, and Applovin  | Adjoe, Google Ads and Applovin |

[configuration](Justtrack/OxfordComma.yml)

### Spelling, phrases, and terms

Along with stylistic choices, we've also made choices on certain terminology and phrases.

For the most part, we use Vale's default dictionary for spell-checking. However, many industry-related words are not included there. If you want to include a new spelling, you must add the word to one of our ignore files:

- [ignore-general](Justtrack/ignore-general.txt)
- [ignore-industry-terms](Justtrack/ignore-industry-terms.txt)
- [ignore-technical-terms](Justtrack/ignore-technical-terms.txt)
- [ignore-platforms](Justtrack/ignore-platforms.txt)

For certain phrases and terms, we have rules for consistent usage:

- [Phrases](Justtrack/Phrases.yml)
- [Terms](Justtrack/Terms.yml)

## Releasing linter changes

Making changes to these files will not automatically be propagated to the repositories that use this configuration. To make your changes available to users of this style guide, we need to cut a [new release](https://github.com/justtrackio/content-style-guide/releases).
