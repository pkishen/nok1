nok1
====



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/nok1.svg)](https://npmjs.org/package/nok1)
[![Downloads/week](https://img.shields.io/npm/dw/nok1.svg)](https://npmjs.org/package/nok1)
[![License](https://img.shields.io/npm/l/nok1.svg)](https://github.com/pkishen/nok1/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g nok1
$ nok1 COMMAND
running command...
$ nok1 (-v|--version|version)
nok1/0.0.1 darwin-x64 node-v12.19.0
$ nok1 --help [COMMAND]
USAGE
  $ nok1 COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`nok1 hello [FILE]`](#nok1-hello-file)
* [`nok1 help [COMMAND]`](#nok1-help-command)

## `nok1 hello [FILE]`

describe the command here

```
USAGE
  $ nok1 hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ nok1 hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/pkishen/nok1/blob/v0.0.1/src/commands/hello.ts)_

## `nok1 help [COMMAND]`

display help for nok1

```
USAGE
  $ nok1 help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
