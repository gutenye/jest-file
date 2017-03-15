jest-file, file tranfrom for jest
=============================

# Usage

```
$ yarn add --dev jest-file

# package.json

  {
    "jest": {
      "transform": {
        "^(?!.*\\.(js|css|json)$)": "jest-file"
      }
    }
  }
```

# Related Projects

- [jest-css](https://github.com/gutenye/jest-css): css transform for jest
