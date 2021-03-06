# wr2conv

> Convert HTML/CSS/JS file(s) to WebRelease2 template valid code

## Install

`npm install -g wr2conv`

## Usage

### node.js module
```js
var wr2conv = require('wr2conv');

var converted_code = wr2conv(src);
```

### CLI
```
wr2conv [options] [source_file]
```

#### CLI Options
* `--output`,`-o` Output directory
* `--help`,`-h` Show this help
* `--version`,`-v` Show version
* `--dry`,`-d` Dry run
* `--check-resource`,`-c` Generate resources repetition report to `--output` directory
* `--ext`,`-e` Set target file extension (ex:html)
* `--basedir`,`-b` Set base path 

#### CLI Usage
Convert all files in the `./html`, and save to `./template`.

```
wr2conv -o ./template ./html
```

Convert and save `index.html`.

```
wr2conv index.html
```
