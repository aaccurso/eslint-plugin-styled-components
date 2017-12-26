# eslint-plugin-styled-components

Eslint plugin for React styled components.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-styled-components`:

```
$ npm install eslint-plugin-styled-components --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-styled-components` globally.

## Usage

Add `styled-components` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "styled-components"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "styled-components/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





