###About
This is a console YAML validator tool validating compliant with YAML 1.2 spec.

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
$ node yml-lint.js wrong.yml
```

To validate multiple files recursively in `src` directory

```bash
$ find src -name '*.yml' -exec js-yaml.js {} \
```



