This is simply my eslint and prettier configuration files that i use in my projects

# Note:

to use this in your pc you need to have prettier and eslint extension in your vscode and both `prettier` and `eslint` along with `eslint-conig-prettier` installed as dev dependency in your codebase.

Also you need to turn on

1. format on save
2. Prettier config
   inside your vscode seting

And at last you need to have

```
"format": "prettier \"src/**/*.{js,html}\"--write",
"lint": "eslint \"src/**/*.{js,jsx}\" --quiet"

```

in your scripts tag inside `package.json` file
