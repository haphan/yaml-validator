###About
This is a YAML validator tool runs in console to validate yaml file  compiliant with YAML 1.2 spec.

This tool employs js-yaml as validator engine.

###Installation

```bash
$ git clone git@github.com:haphan/yaml-validator.git
$ cd yaml-validator
$ npm install
$ chmod +x yml-lint.js
```

###Usage

Single file validation

```bash
$ node yml-lint.js file.yml
```

For validate multiple file recursively in `src` directory

```bash
$ find src -name '*.yml' -exec js-yaml.js {} \
```



