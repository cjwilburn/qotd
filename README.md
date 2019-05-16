qotd
====

Question Of The Day

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/qotd.svg)](https://npmjs.org/package/qotd)
[![Downloads/week](https://img.shields.io/npm/dw/qotd.svg)](https://npmjs.org/package/qotd)
[![License](https://img.shields.io/npm/l/qotd.svg)](https://github.com/cjwilburn/qotd/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g qotd
$ qotd COMMAND
running command...
$ qotd (-v|--version|version)
qotd/1.0.0 darwin-x64 node-v8.10.0
$ qotd --help [COMMAND]
USAGE
  $ qotd COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`qotd hello [FILE]`](#qotd-hello-file)
* [`qotd help [COMMAND]`](#qotd-help-command)

## `qotd hello [FILE]`

describe the command here

```
USAGE
  $ qotd hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ qotd hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/cjwilburn/qotd/blob/v1.0.0/src/commands/hello.ts)_

## `qotd help [COMMAND]`

display help for qotd

```
USAGE
  $ qotd help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_
<!-- commandsstop -->
