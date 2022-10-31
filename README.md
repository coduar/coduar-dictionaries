# Coduar Dictionaries 📖

Custom [cspell](https://cspell.org) dictionaries used at CODUAR

## Usage 🚀

Add the desired [dictionary definition](https://cspell.org/docs/dictionaries/#dictionary-definition) files to a cspell config:

```json
"dictionaryDefinitions": [
  {
    "name": "coduar_allowed",
    "path": "https://github.com/coduar/coduar-dictionaries/raw/master/allowed.txt",
    "description": "Allowed Coduar Dictionary"
  },
  {
    "name": "coduar_forbidden",
    "path": "https://github.com/coduar/coduar-dictionaries/raw/master/forbidden.txt",
    "description": "Forbidden Coduar Dictionary"
  }
]
```
